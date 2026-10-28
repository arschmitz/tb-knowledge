<!-- knowledge: {"repository":"thunderbird","at":"2026-10-28T23:48:02.353Z","paths":["mailnews/protocols/ews/src/IEwsClient.idl","mailnews/protocols/ews/src/EwsFetchMsgToOffline.cpp","mailnews/protocols/exchange/src/ExchangeFetchMsgsToOffline.cpp","rust/protocol_shared/src/safe_xpcom/message_fetch_listener.rs"],"source":{"reference":"knowledge-record:d4dd536fe3aaed622f5a2d62678fc96ec59bbf1ec2db753fc4a7285abafd1edf","recordId":"d4dd536fe3aaed622f5a2d62678fc96ec59bbf1ec2db753fc4a7285abafd1edf","status":"supported","publicationKey":"704566ec3901c130e37ea760495e16edf27091af1510bf9b870de7aa7066d39c"}} -->
# The fetch callback gives its native consumer a complete stream rather than a separate byte count

The early proposal removes the separate callback count and changes offline storage from a count-limited copy to reading the supplied complete stream to EOF. The copy helper reports actual bytes written; the offline consumer adds those bytes to its stored size. The historical channel already copied to EOF, so its change removes the unused count parameter. Backout3515 reverses the proposal. Accepted current code uses the no-count Exchange callback, but retains the Rust i32::MAX payload check and copied native string data. This is a scoped callback contract, not permission to supply arbitrary chunks or a claim that every stream size is supported. No stream or payload test ran.

Scope: Exchange fetch callback and native stream-copy contract.

## Evidence

[Lesson record](../records/d4dd536fe3aaed622f5a2d62678fc96ec59bbf1ec2db753fc4a7285abafd1edf.json).

- [Supporting record](../records/242e48dca49e0a06e9af1a4a9ce1660d3cda1559d851b78ee7ec5511f221fc74.json)
- [Supporting record](../records/42bf2c3d17f74632545a90ae09e5cb81854f11bacf22cb4e59d0abc737866878.json)
- [Supporting record](../records/671f86ddd110a56cf790a401c995c2639c467b10b516e93630d6646e665d446e.json)
- [Supporting record](../records/e236388e1d078f4f98ce36240a3e28e4adaba31e61b2f4a64d3af54866c56fe2.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
