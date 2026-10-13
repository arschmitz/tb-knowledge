<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["third_party"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["fd26d0458a32e41c9a68e84b4120a63370ecf00a477452b17a3f2fe3953e119d"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/ba88e2a9-978f-42db-af23-c62d320d8761.md"}} -->
# firefox/third_party native and TypeScript syntax map 303

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmb_item.cc

Blob: `2eba31ef7d6d50e6e8c9bacfc076f8438355cd36`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @11
- include <cstdint> @13
- include "modules/rtp_rtcp/source/byte_io.h" @15
- include "rtc_base/checks.h" @16
- include "rtc_base/logging.h" @17
- function_definition TmmbItem @21-24
- function_definition Parse @33-52
- function_definition Create @54-66
- function_definition set_packet_overhead @68-71

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h

Blob: `6156ffa8e7b92a2d433fbc564114572d0b77d233`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @14
- include <stdint.h> @15
- class_specifier TmmbItem @22-49
- function_definition TmmbItem @26-26
- function_definition set_ssrc @32-32
- function_definition set_bitrate_bps @33-33
- function_definition ssrc @36-36
- function_definition bitrate_bps @37-37
- function_definition packet_overhead @38-38

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmbn.cc

Blob: `24aa3a3384546bb6613ff4962b11acb1d67c2d6b`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet/tmmbn.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @16
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @17
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @18
- include "rtc_base/checks.h" @19
- include "rtc_base/logging.h" @20
- function_definition Tmmbn @49-49
- function_definition ~Tmmbn @51-51
- function_definition Parse @53-79
- function_definition AddTmmbr @81-83
- function_definition BlockLength @85-88
- function_definition Create @90-111

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmbn.h

Blob: `6f9904af36cbd68b2ab9b90a9e1d4dcc72495457`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @14
- include <cstdint> @15
- include <vector> @16
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @18
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @19
- class_specifier CommonHeader @23-23
- class_specifier Tmmbn @27-54
- function_definition (anonymous) @39-39

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmbn_unittest.cc

Blob: `0343d4219832fb8735fae2e466c81f38bfd9b3b7`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet/tmmbn.h" @11
- include <cstdint> @13
- include <tuple> @14
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @16
- include "rtc_base/buffer.h" @17
- include "test/gmock.h" @18
- include "test/gtest.h" @19
- include "test/rtcp_packet_parser.h" @20
- function_definition TEST @38-47
- function_definition TEST @49-60
- function_definition TEST @62-72
- function_definition TEST @74-92
- function_definition TEST @94-99
- function_definition TEST @101-108

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmbr.cc

Blob: `9f2ad5cecf8f1cc13d2e3a791115a95173d074aa`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet/tmmbr.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @16
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @17
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @18
- include "rtc_base/checks.h" @19
- include "rtc_base/logging.h" @20
- function_definition Tmmbr @50-50
- function_definition ~Tmmbr @52-52
- function_definition Parse @54-80
- function_definition AddTmmbr @82-84
- function_definition BlockLength @86-89
- function_definition Create @91-113

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmbr.h

Blob: `c3d30561384ad9772022773c28dea269dcff2df3`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @14
- include <cstdint> @15
- include <vector> @16
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @18
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @19
- class_specifier CommonHeader @23-23
- class_specifier Tmmbr @27-53
- function_definition (anonymous) @39-39

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/tmmbr_unittest.cc

Blob: `cdd2624684c9dc9433f44aef74ab7ae4a52c4308`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet/tmmbr.h" @11
- include <cstdint> @13
- include <tuple> @14
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @16
- include "rtc_base/buffer.h" @17
- include "test/gmock.h" @18
- include "test/gtest.h" @19
- include "test/rtcp_packet_parser.h" @20
- function_definition TEST @37-46
- function_definition TEST @48-58
- function_definition TEST @60-75
- function_definition TEST @77-83
- function_definition TEST @85-92

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/transport_feedback.cc

Blob: `e8c94119f131f838aa8c1b771467cb840a6cebd4`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <utility> @17
- include <vector> @18
- include "absl/algorithm/container.h" @20
- include "api/function_view.h" @21
- include "api/units/time_delta.h" @22
- include "api/units/timestamp.h" @23
- include "modules/include/module_common_types_public.h" @24
- include "modules/rtp_rtcp/source/byte_io.h" @25
- include "modules/rtp_rtcp/source/rtcp_packet.h" @26
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @27
- include "rtc_base/checks.h" @28
- include "rtc_base/logging.h" @29
- include "rtc_base/trace_event.h" @30
- function_definition LastChunk::LastChunk @83-85
- function_definition LastChunk::Empty @87-89
- function_definition LastChunk::Clear @91-95
- function_definition LastChunk::CanAdd @97-107
- function_definition LastChunk::Add @109-116
- function_definition LastChunk::AddMissingPackets @118-125
- function_definition LastChunk::Emit @127-154
- function_definition LastChunk::EncodeLast @156-163
- function_definition LastChunk::AppendTo @166-174
- function_definition LastChunk::Decode @176-184
- function_definition LastChunk::EncodeOneBit @197-204
- function_definition LastChunk::DecodeOneBit @206-214
- function_definition LastChunk::EncodeTwoBit @227-233
- function_definition LastChunk::DecodeTwoBit @235-243
- function_definition LastChunk::EncodeRunLength @256-260
- function_definition LastChunk::DecodeRunLength @262-272
- function_definition TransportFeedback @274-275
- function_definition TransportFeedback @277-284
- function_definition TransportFeedback @286-286
- function_definition TransportFeedback @288-301
- function_definition ~TransportFeedback @303-303
- function_definition SetBase @305-312
- function_definition SetFeedbackSequenceNumber @314-316
- function_definition AddReceivedPacket @318-367
- function_definition (anonymous) @369-372
- function_definition ForAllPackets @374-390
- function_definition GetBaseSequence @392-394
- function_definition BaseTime @396-402
- function_definition GetBaseDelta @404-413
- function_definition Parse @416-514
- function_definition ParseFrom @516-528
- function_definition IsConsistent @530-594
- function_definition BlockLength @596-599
- function_definition PaddingLength @601-603
- function_definition Create @606-666
- function_definition Clear @668-676
- function_definition AddDeltaSize @678-699
- function_definition AddMissingPackets @701-733

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h

Blob: `6132a7bd5afbe23136bbffa562262bb5ed5021f1`. Grammar: cpp. Status: syntax-clean.

- include <array> @14
- include <cstddef> @15
- include <cstdint> @16
- include <memory> @17
- include <vector> @18
- include "api/function_view.h" @20
- include "api/units/time_delta.h" @21
- include "api/units/timestamp.h" @22
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @23
- class_specifier CommonHeader @27-27
- class_specifier TransportFeedback @29-182
- class_specifier ReceivedPacket @31-45
- function_definition ReceivedPacket @33-34
- function_definition ReceivedPacket @35-35
- function_definition (anonymous) @36-36
- function_definition sequence_number @38-38
- function_definition delta_ticks @39-39
- function_definition delta @40-40
- function_definition GetPacketStatusCount @82-82
- function_definition IncludeTimestamps @91-91
- class_specifier LastChunk @113-160

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet/transport_feedback_unittest.cc

Blob: `2894aab98ec055ca2b3e2b864a34576d9d87334b`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <limits> @16
- include <memory> @17
- include <optional> @18
- include <span> @19
- include <utility> @20
- include <vector> @21
- include "api/units/time_delta.h" @23
- include "api/units/timestamp.h" @24
- include "modules/rtp_rtcp/source/byte_io.h" @25
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @26
- include "rtc_base/buffer.h" @27
- include "rtc_base/checks.h" @28
- include "test/gmock.h" @29
- include "test/gtest.h" @30
- include "test/near_matcher.h" @31
- function_definition Parse @65-73
- class_specifier FeedbackTester @75-179
- function_definition FeedbackTester @77-77
- function_definition FeedbackTester @78-81
- function_definition WithExpectedSize @83-85
- function_definition WithDefaultDelta @87-87
- function_definition WithInput @89-119
- function_definition VerifyPacket @121-130
- function_definition VerifyInternal @135-153
- function_definition GenerateReceiveTimestamps @155-170
- function_definition TEST @189-199
- function_definition TEST @201-209
- function_definition TEST @211-221
- function_definition TEST @223-234
- function_definition TEST @236-247
- function_definition TEST @249-260
- function_definition TEST @262-273
- function_definition TEST @275-282
- function_definition TEST @284-297
- function_definition TEST @299-317
- function_definition TEST @319-336
- function_definition TEST @338-351
- function_definition TEST @353-366
- function_definition TEST @368-395
- function_definition TEST @397-419
- function_definition TEST @421-465
- function_definition TEST @467-484
- function_definition TEST @486-513
- function_definition TEST @515-552
- function_definition TEST @554-584
- function_definition TEST @586-603
- function_definition TEST @605-629
- function_definition TEST @631-650
- function_definition TEST @652-669

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_packet_unittest.cc

Blob: `149a739db6b1ce13bdfc0f09f41db771b1c0da8e`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_packet.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <span> @15
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @17
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @18
- include "test/gmock.h" @19
- include "test/gtest.h" @20
- function_definition TEST @33-47

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_receiver.cc

Blob: `58eb0d767ee496289a2ed9ef49d3ee78b5a3ed75`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtcp_receiver.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <cstring> @16
- include <iterator> @17
- include <limits> @18
- include <memory> @19
- include <optional> @20
- include <span> @21
- include <utility> @22
- include <vector> @23
- include "absl/algorithm/container.h" @25
- include "api/environment/environment.h" @26
- include "api/field_trials_view.h" @27
- include "api/sequence_checker.h" @28
- include "api/transport/network_types.h" @29
- include "api/units/data_rate.h" @30
- include "api/units/time_delta.h" @31
- include "api/units/timestamp.h" @32
- include "api/video/video_codec_constants.h" @33
- include "modules/rtp_rtcp/include/report_block_data.h" @34
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @35
- include "modules/rtp_rtcp/source/ntp_time_util.h" @36
- include "modules/rtp_rtcp/source/rtcp_packet/app.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet/bye.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @39
- include "modules/rtp_rtcp/source/rtcp_packet/congestion_control_feedback.h" @40
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @41
- include "modules/rtp_rtcp/source/rtcp_packet/extended_reports.h" @42
- include "modules/rtp_rtcp/source/rtcp_packet/fir.h" @43
- include "modules/rtp_rtcp/source/rtcp_packet/loss_notification.h" @44
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @45
- include "modules/rtp_rtcp/source/rtcp_packet/pli.h" @46
- include "modules/rtp_rtcp/source/rtcp_packet/psfb.h" @47
- include "modules/rtp_rtcp/source/rtcp_packet/rapid_resync_request.h" @48
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @49
- include "modules/rtp_rtcp/source/rtcp_packet/remb.h" @50
- include "modules/rtp_rtcp/source/rtcp_packet/remote_estimate.h" @51
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @52
- include "modules/rtp_rtcp/source/rtcp_packet/sdes.h" @53
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @54
- include "modules/rtp_rtcp/source/rtcp_packet/tmmbn.h" @55
- include "modules/rtp_rtcp/source/rtcp_packet/tmmbr.h" @56
- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @57
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @58
- include "modules/rtp_rtcp/source/tmmbr_help.h" @59
- include "rtc_base/checks.h" @60
- include "rtc_base/containers/flat_map.h" @61
- include "rtc_base/logging.h" @62
- include "rtc_base/synchronization/mutex.h" @63
- include "rtc_base/trace_event.h" @64
- include "system_wrappers/include/clock.h" @65
- include "system_wrappers/include/ntp_time.h" @66
- function_definition ResetTimestampIfExpired @90-100
- function_definition RegisteredSsrcs::RegisteredSsrcs @104-119
- function_definition RegisteredSsrcs::contains @121-124
- function_definition RegisteredSsrcs::media_ssrc @126-129
- function_definition RegisteredSsrcs::set_media_ssrc @131-134
- struct_specifier RTCPReceiver::PacketInformation @136-148
- function_definition RTCPReceiver @150-177
- function_definition ~RTCPReceiver @179-179
- function_definition IncomingPacket @181-191
- function_definition SetRemoteSSRC @193-202
- function_definition set_local_media_ssrc @204-206
- function_definition local_media_ssrc @208-210
- function_definition RttStats::AddRtt @212-216
- function_definition RttStats::average_rtt @218-223
- function_definition RttStats::last_rtt @225-230
- function_definition AverageRtt @232-235
- function_definition LastRtt @237-240
- function_definition GetNonSenderRTT @242-245
- function_definition SetNonSenderRttMeasurement @247-250
- function_definition GetAndResetXrRrRtt @252-257
- function_definition OnPeriodicRttUpdate @260-287
- function_definition GetSenderReportStats @289-297
- function_definition ConsumeReceivedXrReferenceTimeInfo @299-319
- function_definition RemoteRTCPSenderInfo @321-330
- function_definition GetLatestReportBlockData @332-339
- function_definition ParseCompoundPacket @341-474
- struct_specifier RtcpReceivedBlock @349-352
- function_definition HandleSenderReport @476-510
- function_definition HandleReceiverReport @512-529
- function_definition HandleReportBlock @531-587
- function_definition BoundingSet @589-593
- function_definition HandleSdes @595-609
- function_definition HandleNack @611-635
- function_definition HandleApp @637-655
- function_definition HandleBye @657-681
- function_definition HandleXr @683-701
- function_definition HandleXrReceiveReferenceTime @703-723
- function_definition HandleXrDlrrReportBlock @725-755
- function_definition HandlePli @757-777
- function_definition HandleTmmbr @779-810
- function_definition HandleTmmbn @812-825
- function_definition HandleSrReq @827-836
- function_definition HandlePsfbApp @838-863
- function_definition HandleFir @865-899
- function_definition HandleTransportFeedback @901-919
- function_definition HandleCongestionControlFeedback @921-935
- function_definition NotifyTmmbrUpdated @937-953
- function_definition TriggerCallbacksFromRtcpPacket @956-1054
- function_definition TmmbrReceived @1056-1071
- function_definition RtcpRrTimeoutLocked @1073-1080
- function_definition RtcpRrSequenceNumberTimeoutLocked @1082-1089

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_receiver.h

Blob: `e7519d210f29419d49a07bdd7900d73ff887c7dc`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <list> @16
- include <optional> @17
- include <span> @18
- include <vector> @19
- include "absl/container/inlined_vector.h" @21
- include "api/environment/environment.h" @22
- include "api/sequence_checker.h" @23
- include "api/units/time_delta.h" @24
- include "api/units/timestamp.h" @25
- include "api/video/video_codec_constants.h" @26
- include "modules/rtp_rtcp/include/report_block_data.h" @27
- include "modules/rtp_rtcp/include/rtcp_statistics.h" @28
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @29
- include "modules/rtp_rtcp/source/rtcp_nack_stats.h" @30
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @31
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @32
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @33
- include "rtc_base/containers/flat_map.h" @34
- include "rtc_base/synchronization/mutex.h" @35
- include "rtc_base/system/no_unique_address.h" @36
- include "rtc_base/thread_annotations.h" @37
- class_specifier CommonHeader @41-41
- class_specifier ReportBlock @42-42
- class_specifier Rrtr @43-43
- class_specifier TmmbItem @44-44
- class_specifier RTCPReceiver @47-360
- class_specifier ModuleRtpRtcp @49-60
- function_definition ~ModuleRtpRtcp @59-59
- class_specifier NonSenderRttStats @62-89
- function_definition NonSenderRttStats @64-64
- function_definition NonSenderRttStats @65-65
- function_definition (anonymous) @66-66
- function_definition ~NonSenderRttStats @67-67
- function_definition Update @68-72
- function_definition Invalidate @73-73
- function_definition round_trip_time @75-77
- function_definition total_round_trip_time @79-79
- function_definition round_trip_time_measurements @81-83
- class_specifier RegisteredSsrcs @142-158
- struct_specifier PacketInformation @160-160
- struct_specifier TimedTmmbrItem @163-166
- struct_specifier RrtrInformation @169-182
- function_definition RrtrInformation @170-175
- struct_specifier LastFir @184-189
- class_specifier RttStats @191-206
- function_definition RttStats @193-193
- function_definition RttStats @194-194
- function_definition (anonymous) @195-195

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_receiver_unittest.cc

Blob: `40d9150d31de3831736fbc7b48a0bd75434d88da`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtcp_receiver.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <memory> @15
- include <optional> @16
- include <set> @17
- include <span> @18
- include <string> @19
- include <utility> @20
- include <vector> @21
- include "absl/strings/string_view.h" @23
- include "api/environment/environment_factory.h" @24
- include "api/transport/network_types.h" @25
- include "api/units/data_rate.h" @26
- include "api/units/time_delta.h" @27
- include "api/units/timestamp.h" @28
- include "modules/rtp_rtcp/include/report_block_data.h" @29
- include "modules/rtp_rtcp/include/rtcp_statistics.h" @30
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @31
- include "modules/rtp_rtcp/mocks/mock_network_link_rtcp_observer.h" @32
- include "modules/rtp_rtcp/mocks/mock_network_state_estimator_observer.h" @33
- include "modules/rtp_rtcp/source/byte_io.h" @34
- include "modules/rtp_rtcp/source/ntp_time_util.h" @35
- include "modules/rtp_rtcp/source/rtcp_packet/app.h" @36
- include "modules/rtp_rtcp/source/rtcp_packet/bye.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet/compound_packet.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/congestion_control_feedback.h" @39
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @40
- include "modules/rtp_rtcp/source/rtcp_packet/extended_reports.h" @41
- include "modules/rtp_rtcp/source/rtcp_packet/fir.h" @42
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @43
- include "modules/rtp_rtcp/source/rtcp_packet/pli.h" @44
- include "modules/rtp_rtcp/source/rtcp_packet/rapid_resync_request.h" @45
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @46
- include "modules/rtp_rtcp/source/rtcp_packet/remb.h" @47
- include "modules/rtp_rtcp/source/rtcp_packet/remote_estimate.h" @48
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @49
- include "modules/rtp_rtcp/source/rtcp_packet/sdes.h" @50
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @51
- include "modules/rtp_rtcp/source/rtcp_packet/tmmbr.h" @52
- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @53
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @54
- include "rtc_base/buffer.h" @55
- include "rtc_base/random.h" @56
- include "system_wrappers/include/clock.h" @57
- include "system_wrappers/include/ntp_time.h" @58
- include "test/create_test_field_trials.h" @59
- include "test/gmock.h" @60
- include "test/gtest.h" @61
- include "test/near_matcher.h" @62
- class_specifier MockRtcpPacketTypeCounterObserver @84-90
- class_specifier MockRtcpIntraFrameObserver @92-95
- class_specifier MockRtcpLossNotificationObserver @97-107
- function_definition ~MockRtcpLossNotificationObserver @99-99
- class_specifier MockCnameCallbackImpl @109-112
- class_specifier MockReportBlockDataObserverImpl @114-117
- class_specifier MockModuleRtpRtcp @119-128
- struct_specifier ReceiverMocks @144-166
- function_definition Create @168-172
- function_definition TEST @174-182
- function_definition TEST @184-194
- function_definition TEST @196-210
- function_definition TEST @212-227
- function_definition TEST @229-256
- function_definition TEST @258-286
- function_definition TEST @288-314
- function_definition TEST @316-328
- function_definition TEST @330-346
- function_definition TEST @348-366
- function_definition TEST @368-386
- function_definition TEST @388-461
- function_definition TEST @463-514
- function_definition TEST @516-546
- function_definition TEST @548-577
- function_definition TEST @580-592
- function_definition TEST @594-607
- function_definition TEST @609-641
- function_definition TEST @643-660
- function_definition TEST @662-677
- function_definition TEST @679-693
- function_definition TEST @695-710
- function_definition TEST @712-722
- function_definition TEST @724-733
- function_definition TEST @735-758
- function_definition TEST @760-779
- function_definition TEST @781-806
- function_definition TEST @808-834
- function_definition TEST @836-854
- function_definition TEST @856-885
- function_definition TEST @887-899
- function_definition TEST @901-928
- function_definition TEST @932-960
- function_definition TEST @964-992
- function_definition TEST @994-1021
- function_definition TEST @1024-1073
- function_definition TEST @1078-1116
- function_definition TEST @1121-1156
- function_definition TEST @1159-1210
- function_definition TEST @1212-1218
- function_definition TEST @1220-1244
- function_definition TEST @1246-1275
- function_definition TEST @1277-1307
- function_definition TEST @1309-1315
- function_definition TEST @1317-1343
- function_definition TEST @1345-1367
- function_definition TEST @1369-1389
- function_definition TEST @1391-1429
- function_definition TEST @1431-1470
- function_definition TEST @1472-1516
- function_definition TEST @1518-1540
- function_definition TEST @1542-1578
- function_definition TEST @1580-1618
- function_definition TEST @1620-1640
- function_definition TEST @1642-1661
- function_definition TEST @1663-1688
- function_definition TEST @1690-1710
- function_definition TEST @1712-1738
- function_definition TEST @1740-1761
- function_definition TEST @1763-1777
- function_definition TEST @1779-1793
- function_definition TEST @1795-1808
- function_definition TEST @1810-1842
- function_definition TEST @1844-1897
- function_definition TEST @1899-1916
- function_definition TEST @1918-1929
- function_definition TEST @1931-1966

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_sender.cc

Blob: `87da809b57041a23655e50834c69d1b0c064c274`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtcp_sender.h" @11
- include <algorithm> @13
- include <cstdint> @14
- include <cstring> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <string> @19
- include <utility> @20
- include <vector> @21
- include "absl/strings/string_view.h" @23
- include "api/call/transport.h" @24
- include "api/environment/environment.h" @25
- include "api/rtc_event_log/rtc_event_log.h" @26
- include "api/rtp_headers.h" @27
- include "api/units/data_rate.h" @28
- include "api/units/time_delta.h" @29
- include "api/units/timestamp.h" @30
- include "logging/rtc_event_log/events/rtc_event_rtcp_packet_outgoing.h" @31
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @32
- include "modules/rtp_rtcp/source/ntp_time_util.h" @33
- include "modules/rtp_rtcp/source/rtcp_packet.h" @34
- include "modules/rtp_rtcp/source/rtcp_packet/app.h" @35
- include "modules/rtp_rtcp/source/rtcp_packet/bye.h" @36
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet/extended_reports.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/fir.h" @39
- include "modules/rtp_rtcp/source/rtcp_packet/loss_notification.h" @40
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @41
- include "modules/rtp_rtcp/source/rtcp_packet/pli.h" @42
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @43
- include "modules/rtp_rtcp/source/rtcp_packet/remb.h" @44
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @45
- include "modules/rtp_rtcp/source/rtcp_packet/rrtr.h" @46
- include "modules/rtp_rtcp/source/rtcp_packet/sdes.h" @47
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @48
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @49
- include "modules/rtp_rtcp/source/rtcp_packet/tmmbn.h" @50
- include "modules/rtp_rtcp/source/rtcp_packet/tmmbr.h" @51
- include "modules/rtp_rtcp/source/rtp_rtcp_config.h" @52
- include "modules/rtp_rtcp/source/tmmbr_help.h" @53
- include "rtc_base/checks.h" @54
- include "rtc_base/logging.h" @55
- include "rtc_base/numerics/safe_conversions.h" @56
- include "rtc_base/synchronization/mutex.h" @57
- include "rtc_base/trace_event.h" @58
- class_specifier RTCPSender::PacketSender @69-97
- function_definition PacketSender @71-75
- function_definition ~PacketSender @76-76
- function_definition AppendPacket @80-82
- function_definition Send @85-90
- function_definition FeedbackState::FeedbackState @99-104
- function_definition FeedbackState::FeedbackState @106-106
- function_definition FeedbackState::FeedbackState @108-108
- function_definition FeedbackState::~FeedbackState @110-110
- class_specifier RTCPSender::RtcpContext @112-122
- function_definition RtcpContext @114-117
- function_definition RTCPSender @124-173
- function_definition ~RTCPSender @175-175
- function_definition Status @177-180
- function_definition SetRTCPStatus @182-192
- function_definition Sending @194-197
- function_definition SetSendingStatus @199-220
- function_definition SetNonSenderRttMeasurement @222-225
- function_definition SendLossNotification @227-265
- function_definition SetRemb @267-281
- function_definition UnsetRemb @283-287
- function_definition TMMBR @289-292
- function_definition SetMaxRtpPacketSize @294-297
- function_definition SetTimestampOffset @299-302
- function_definition SetLastRtpTime @304-320
- function_definition SetRtpClockRate @322-325
- function_definition SSRC @327-330
- function_definition SetRemoteSSRC @332-335
- function_definition SetCNAME @337-342
- function_definition TimeToSendRTCPReport @344-361
- function_definition BuildSR @363-391
- function_definition BuildSDES @393-400
- function_definition BuildRR @402-409
- function_definition BuildPLI @411-418
- function_definition BuildFIR @420-429
- function_definition BuildREMB @431-437
- function_definition SetTargetBitrate @439-442
- function_definition BuildTMMBR @444-496
- function_definition BuildTMMBN @498-508
- function_definition BuildAPP @510-514
- function_definition BuildLossNotification @516-521
- function_definition BuildNACK @523-538
- function_definition BuildBYE @540-545
- function_definition BuildExtendedReports @547-563
- function_definition SendRTCP @565-589
- function_definition ComputeSsrc @591-598
- function_definition ComputeCompoundRTCPPacket @600-674
- function_definition ComputeTimeUntilNextReport @676-712
- function_definition PrepareReport @714-744
- function_definition CreateReportBlocks @746-766
- function_definition SetCsrcs @768-772
- function_definition SetTmmbn @774-778
- function_definition SetFlag @780-786
- function_definition IsFlagPresent @788-790
- function_definition ConsumeFlag @792-799
- function_definition AllVolatileFlagsConsumed @801-807
- function_definition SendCombinedRtcpPacket @809-836
- function_definition SetNextRtcpSendEvaluationDuration @838-841

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_sender.h

Blob: `b2aa20243814c745df2709ead9f48726eeac8109`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <map> @16
- include <memory> @17
- include <optional> @18
- include <set> @19
- include <span> @20
- include <string> @21
- include <vector> @22
- include "absl/functional/any_invocable.h" @24
- include "absl/strings/string_view.h" @25
- include "api/call/transport.h" @26
- include "api/environment/environment.h" @27
- include "api/rtp_headers.h" @28
- include "api/units/data_rate.h" @29
- include "api/units/time_delta.h" @30
- include "api/units/timestamp.h" @31
- include "modules/rtp_rtcp/include/receive_statistics.h" @32
- include "modules/rtp_rtcp/include/rtcp_statistics.h" @33
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @34
- include "modules/rtp_rtcp/source/rtcp_nack_stats.h" @35
- include "modules/rtp_rtcp/source/rtcp_packet.h" @36
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet/loss_notification.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @39
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @40
- include "modules/rtp_rtcp/source/rtcp_receiver.h" @41
- include "rtc_base/random.h" @42
- include "rtc_base/synchronization/mutex.h" @43
- include "rtc_base/thread_annotations.h" @44
- include "system_wrappers/include/ntp_time.h" @45
- class_specifier RTCPSender @49-318
- struct_specifier Configuration @51-83
- struct_specifier FeedbackState @84-102
- function_definition RTCPSender @106-106
- function_definition RTCPSender @107-107
- function_definition (anonymous) @108-108
- class_specifier RtcpContext @179-179
- class_specifier PacketSender @180-180
- struct_specifier ReportFlag @304-311
- function_definition ReportFlag @305-306
- function_definition operator< @307-307
- function_definition operator== @308-308

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_sender_unittest.cc

Blob: `b10159a3e0a36462e791d4f45bc5fd96550674db`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_sender.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <memory> @15
- include <optional> @16
- include <span> @17
- include <utility> @18
- include <vector> @19
- include "api/call/transport.h" @21
- include "api/environment/environment.h" @22
- include "api/rtp_headers.h" @23
- include "api/units/time_delta.h" @24
- include "api/units/timestamp.h" @25
- include "modules/rtp_rtcp/include/receive_statistics.h" @26
- include "modules/rtp_rtcp/include/rtcp_statistics.h" @27
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @28
- include "modules/rtp_rtcp/source/rtcp_packet.h" @29
- include "modules/rtp_rtcp/source/rtcp_packet/bye.h" @30
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @31
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @32
- include "modules/rtp_rtcp/source/rtcp_packet/remote_estimate.h" @33
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @34
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @35
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @36
- include "modules/rtp_rtcp/source/rtp_rtcp_impl2.h" @37
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @38
- include "rtc_base/rate_limiter.h" @39
- include "system_wrappers/include/clock.h" @40
- include "system_wrappers/include/ntp_time.h" @41
- include "test/create_test_environment.h" @42
- include "test/gmock.h" @43
- include "test/gtest.h" @44
- include "test/mock_transport.h" @45
- include "test/rtcp_packet_parser.h" @46
- include "test/run_loop.h" @47
- class_specifier RtcpPacketTypeCounterObserverImpl @58-70
- function_definition RtcpPacketTypeCounterObserverImpl @60-60
- function_definition ~RtcpPacketTypeCounterObserverImpl @61-61
- function_definition RtcpPacketTypesCounterUpdated @62-67
- class_specifier TestTransport @72-87
- function_definition TestTransport @74-74
- function_definition SendRtp @76-79
- function_definition SendRtcp @80-85
- class_specifier RtcpSenderTest @94-159
- function_definition RtcpSenderTest @96-102
- function_definition GetDefaultConfig @104-113
- function_definition GetDefaultRtpRtcpConfig @115-124
- function_definition CreateRtcpSender @126-136
- function_definition InsertIncomingPacket @138-145
- function_definition parser @147-147
- function_definition feedback_state @149-151
- function_definition TEST_F @161-166
- function_definition TEST_F @168-173
- function_definition TEST_F @175-179
- function_definition TEST_F @181-200
- function_definition TEST_F @202-234
- function_definition TEST_F @236-250
- function_definition TEST_F @252-262
- function_definition TEST_F @264-271
- function_definition TEST_F @273-278
- function_definition TEST_F @280-294
- function_definition TEST_F @296-310
- function_definition TEST_F @312-321
- function_definition TEST_F @323-331
- function_definition TEST_F @333-339
- function_definition TEST_F @341-348
- function_definition TEST_F @350-362
- function_definition TEST_F @364-371
- function_definition TEST_F @373-382
- function_definition TEST_F @384-399
- function_definition TEST_F @401-429
- function_definition TEST_F @431-439
- function_definition TEST_F @441-456
- function_definition TEST_F @458-472
- function_definition TEST_F @474-486
- function_definition TEST_F @488-505
- function_definition TEST_F @507-532
- function_definition TEST_F @534-547
- function_definition TEST_F @550-564
- function_definition TEST_F @567-576
- function_definition TEST_F @578-586
- function_definition TEST_F @588-596
- function_definition TEST_F @598-608
- function_definition TEST_F @610-621
- function_definition TEST_F @623-643
- function_definition TEST_F @651-662
- function_definition TEST_F @668-703
- function_definition TEST_F @705-712
- function_definition TEST_F @714-730

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver.cc

Blob: `9b0ed57d3c23f6e63c1ad117343f273a8f71bf91`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_transceiver.h" @11
- include <cstdint> @13
- include <memory> @14
- include <utility> @15
- include <vector> @16
- include "absl/cleanup/cleanup.h" @18
- include "absl/functional/any_invocable.h" @19
- include "api/units/timestamp.h" @20
- include "modules/rtp_rtcp/source/rtcp_packet.h" @21
- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @22
- include "modules/rtp_rtcp/source/rtcp_transceiver_impl.h" @23
- include "rtc_base/checks.h" @24
- include "rtc_base/copy_on_write_buffer.h" @25
- include "system_wrappers/include/clock.h" @26
- function_definition RtcpTransceiver @30-35
- function_definition ~RtcpTransceiver @37-45
- function_definition Stop @47-55
- function_definition AddMediaReceiverRtcpObserver @57-65
- function_definition RemoveMediaReceiverRtcpObserver @67-78
- function_definition SetReadyToSend @80-84
- function_definition ReceivePacket @86-92
- function_definition SendCompoundPacket @94-98
- function_definition SetRemb @100-107
- function_definition UnsetRemb @109-113
- function_definition SendCombinedRtcpPacket @115-123
- function_definition SendNack @125-133
- function_definition SendPictureLossIndication @135-139
- function_definition SendFullIntraRequest @141-143
- function_definition SendFullIntraRequest @145-152

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver.h

Blob: `c1ff78bac623ab0e08a20161162a59c8981b2451`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @14
- include <memory> @15
- include <vector> @16
- include "absl/functional/any_invocable.h" @18
- include "api/task_queue/task_queue_base.h" @19
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @20
- include "modules/rtp_rtcp/source/rtcp_packet.h" @21
- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @22
- include "modules/rtp_rtcp/source/rtcp_transceiver_impl.h" @23
- include "rtc_base/copy_on_write_buffer.h" @24
- include "system_wrappers/include/clock.h" @25
- class_specifier RtcpTransceiver @32-103
- function_definition RtcpTransceiver @35-35
- function_definition (anonymous) @36-36

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver_config.cc

Blob: `806dfe4eee8e37fc040f283ff47d9d23e3641c01`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @11
- include "api/rtp_headers.h" @13
- include "api/units/time_delta.h" @14
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @15
- include "rtc_base/logging.h" @16
- function_definition RtcpTransceiverConfig @20-20
- function_definition RtcpTransceiverConfig @21-22
- function_definition ~RtcpTransceiverConfig @25-25
- function_definition Validate @27-76

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver_config.h

Blob: `8fc7d6374a0bf5a0c407ffab5907d839aaa69aa3`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @14
- include <cstdint> @15
- include <functional> @16
- include <span> @17
- include <string> @18
- include "api/rtp_headers.h" @20
- include "api/task_queue/task_queue_base.h" @21
- include "api/units/time_delta.h" @22
- include "api/units/timestamp.h" @23
- include "api/video/video_bitrate_allocation.h" @24
- include "modules/rtp_rtcp/include/report_block_data.h" @25
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @26
- include "system_wrappers/include/clock.h" @27
- include "system_wrappers/include/ntp_time.h" @28
- class_specifier ReceiveStatisticsProvider @31-31
- class_specifier MediaReceiverRtcpObserver @36-47
- function_definition ~MediaReceiverRtcpObserver @38-38
- function_definition OnSenderReport @40-42
- function_definition OnBye @43-43
- function_definition OnBitrateAllocation @44-46
- class_specifier RtpStreamRtcpHandler @50-91
- function_definition ~RtpStreamRtcpHandler @52-52
- class_specifier RtpStats @55-80
- function_definition RtpStats @57-57
- function_definition RtpStats @58-58
- function_definition (anonymous) @59-59
- function_definition ~RtpStats @60-60
- function_definition num_sent_packets @62-62
- function_definition num_sent_bytes @63-63
- function_definition last_capture_time @64-64
- function_definition last_rtp_timestamp @65-65
- function_definition last_clock_rate @66-66
- function_definition set_num_sent_packets @68-68
- function_definition set_num_sent_bytes @69-69
- function_definition set_last_capture_time @70-70
- function_definition set_last_rtp_timestamp @71-71
- function_definition set_last_clock_rate @72-72
- function_definition OnNack @83-84
- function_definition OnFir @85-85
- function_definition OnPli @86-86
- function_definition OnReport @90-90
- struct_specifier RtcpTransceiverConfig @93-172

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver_impl.cc

Blob: `41144156a68b1965bc5e99bab05e5605dbffab57`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtcp_transceiver_impl.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <functional> @16
- include <iterator> @17
- include <memory> @18
- include <optional> @19
- include <span> @20
- include <string> @21
- include <utility> @22
- include <vector> @23
- include "absl/algorithm/container.h" @25
- include "api/rtp_headers.h" @26
- include "api/task_queue/task_queue_base.h" @27
- include "api/units/data_rate.h" @28
- include "api/units/time_delta.h" @29
- include "api/units/timestamp.h" @30
- include "api/video/video_bitrate_allocation.h" @31
- include "api/video/video_codec_constants.h" @32
- include "modules/rtp_rtcp/include/receive_statistics.h" @33
- include "modules/rtp_rtcp/include/report_block_data.h" @34
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @35
- include "modules/rtp_rtcp/source/ntp_time_util.h" @36
- include "modules/rtp_rtcp/source/rtcp_packet.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet/bye.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @39
- include "modules/rtp_rtcp/source/rtcp_packet/congestion_control_feedback.h" @40
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @41
- include "modules/rtp_rtcp/source/rtcp_packet/extended_reports.h" @42
- include "modules/rtp_rtcp/source/rtcp_packet/fir.h" @43
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @44
- include "modules/rtp_rtcp/source/rtcp_packet/pli.h" @45
- include "modules/rtp_rtcp/source/rtcp_packet/psfb.h" @46
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @47
- include "modules/rtp_rtcp/source/rtcp_packet/remb.h" @48
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @49
- include "modules/rtp_rtcp/source/rtcp_packet/rrtr.h" @50
- include "modules/rtp_rtcp/source/rtcp_packet/rtpfb.h" @51
- include "modules/rtp_rtcp/source/rtcp_packet/sdes.h" @52
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @53
- include "modules/rtp_rtcp/source/rtcp_packet/target_bitrate.h" @54
- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @55
- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @56
- include "rtc_base/checks.h" @57
- include "rtc_base/containers/flat_map.h" @58
- include "rtc_base/logging.h" @59
- include "rtc_base/numerics/divide_round.h" @60
- include "rtc_base/task_utils/repeating_task.h" @61
- include "system_wrappers/include/clock.h" @62
- include "system_wrappers/include/ntp_time.h" @63
- struct_specifier SenderReportTimes @68-71
- function_definition GetRtcpTransport @73-87
- struct_specifier RtcpTransceiverImpl::RemoteSenderState @91-95
- struct_specifier RtcpTransceiverImpl::LocalSenderState @97-104
- class_specifier RtcpTransceiverImpl::PacketSender @111-141
- function_definition PacketSender @113-117
- function_definition ~PacketSender @118-118
- function_definition AppendPacket @122-124
- function_definition Send @127-132
- function_definition IsEmpty @134-134
- function_definition RtcpTransceiverImpl @143-151
- function_definition ~RtcpTransceiverImpl @153-153
- function_definition AddMediaReceiverRtcpObserver @155-166
- function_definition RemoveMediaReceiverRtcpObserver @168-179
- function_definition AddMediaSender @181-195
- function_definition RemoveMediaSender @197-205
- function_definition SetReadyToSend @207-216
- function_definition ReceivePacket @218-236
- function_definition SendCompoundPacket @238-243
- function_definition SetRemb @245-264
- function_definition UnsetRemb @266-268
- function_definition SendNack @270-280
- function_definition SendPictureLossIndication @282-289
- function_definition SendFullIntraRequest @291-305
- function_definition HandleReceivedPacket @307-331
- function_definition HandleBye @333-343
- function_definition HandleSenderReport @345-363
- function_definition HandleReceiverReport @365-375
- function_definition HandleReportBlocks @377-416
- function_definition HandlePayloadSpecificFeedback @418-432
- function_definition HandleFir @434-452
- function_definition HandlePli @454-464
- function_definition HandleRemb @466-476
- function_definition HandleRtpFeedback @478-492
- function_definition HandleNack @494-504
- function_definition HandleTransportFeedback @506-518
- function_definition HandleCongestionControlFeedback @520-532
- function_definition HandleExtendedReports @534-555
- function_definition HandleDlrr @557-574
- function_definition ProcessReportBlocks @576-598
- function_definition HandleTargetBitrate @600-626
- function_definition ReschedulePeriodicCompoundPackets @628-634
- function_definition SchedulePeriodicCompoundPackets @636-646
- function_definition FillReports @648-770
- function_definition CreateCompoundPacket @772-851
- function_definition SendPeriodicCompoundPacket @853-858
- function_definition SendCombinedRtcpPacket @860-869
- function_definition SendImmediateFeedback @871-888
- function_definition CreateReportBlocks @890-914

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver_impl.h

Blob: `c7249d30c5cdcf98b4c3f2d422f8916c7392c1f0`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @14
- include <cstdint> @15
- include <functional> @16
- include <list> @17
- include <memory> @18
- include <optional> @19
- include <span> @20
- include <vector> @21
- include "api/units/time_delta.h" @23
- include "api/units/timestamp.h" @24
- include "modules/rtp_rtcp/include/report_block_data.h" @25
- include "modules/rtp_rtcp/source/rtcp_packet.h" @26
- include "modules/rtp_rtcp/source/rtcp_packet/common_header.h" @27
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @28
- include "modules/rtp_rtcp/source/rtcp_packet/remb.h" @29
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @30
- include "modules/rtp_rtcp/source/rtcp_packet/target_bitrate.h" @31
- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @32
- include "rtc_base/containers/flat_map.h" @33
- include "rtc_base/task_utils/repeating_task.h" @34
- class_specifier RtcpTransceiverImpl @41-171
- function_definition RtcpTransceiverImpl @44-44
- function_definition (anonymous) @45-45
- function_definition StopPeriodicTask @48-48
- class_specifier PacketSender @82-82
- struct_specifier RemoteSenderState @83-83
- struct_specifier LocalSenderState @84-84
- struct_specifier RrtrTimes @85-91
- struct_specifier ReservedBytes @137-140

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver_impl_unittest.cc

Blob: `4f108781f875ab20f68bfc0e9087ccde1ac19c3a`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtcp_transceiver_impl.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <functional> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include <vector> @20
- include "api/rtp_headers.h" @22
- include "api/task_queue/task_queue_base.h" @23
- include "api/task_queue/task_queue_factory.h" @24
- include "api/test/create_time_controller.h" @25
- include "api/test/time_controller.h" @26
- include "api/units/data_rate.h" @27
- include "api/units/time_delta.h" @28
- include "api/units/timestamp.h" @29
- include "api/video/video_bitrate_allocation.h" @30
- include "api/video/video_codec_constants.h" @31
- include "modules/rtp_rtcp/include/receive_statistics.h" @32
- include "modules/rtp_rtcp/include/report_block_data.h" @33
- include "modules/rtp_rtcp/mocks/mock_network_link_rtcp_observer.h" @34
- include "modules/rtp_rtcp/source/ntp_time_util.h" @35
- include "modules/rtp_rtcp/source/rtcp_packet/app.h" @36
- include "modules/rtp_rtcp/source/rtcp_packet/bye.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet/compound_packet.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/congestion_control_feedback.h" @39
- include "modules/rtp_rtcp/source/rtcp_packet/dlrr.h" @40
- include "modules/rtp_rtcp/source/rtcp_packet/extended_reports.h" @41
- include "modules/rtp_rtcp/source/rtcp_packet/fir.h" @42
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @43
- include "modules/rtp_rtcp/source/rtcp_packet/pli.h" @44
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @45
- include "modules/rtp_rtcp/source/rtcp_packet/remb.h" @46
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @47
- include "modules/rtp_rtcp/source/rtcp_packet/rrtr.h" @48
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @49
- include "modules/rtp_rtcp/source/rtcp_packet/target_bitrate.h" @50
- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @51
- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @52
- include "system_wrappers/include/clock.h" @53
- include "system_wrappers/include/ntp_time.h" @54
- include "test/gmock.h" @55
- include "test/gtest.h" @56
- include "test/rtcp_packet_parser.h" @57
- class_specifier MockReceiveStatisticsProvider @80-83
- class_specifier MockMediaReceiverRtcpObserver @85-93
- class_specifier MockRtpStreamRtcpHandler @95-116
- function_definition MockRtpStreamRtcpHandler @97-106
- class_specifier FakeRtcpTransport @127-146
- function_definition FakeRtcpTransport @129-129
- function_definition AsStdFunction @131-133
- function_definition WaitPacket @136-141
- function_definition RtcpParserTransport @148-153
- class_specifier RtcpTransceiverImplTest @155-179
- function_definition DefaultTestConfig @157-167
- function_definition (anonymous) @169-169
- function_definition CurrentTime @170-170
- function_definition AdvanceTime @171-171
- function_definition CreateTaskQueue @172-175
- function_definition TEST_F @181-199
- function_definition TEST_F @201-216
- function_definition TEST_F @218-232
- function_definition TEST_F @234-258
- function_definition TEST_F @260-293
- function_definition TEST_F @295-340
- function_definition TEST_F @342-357
- function_definition TEST_F @359-376
- function_definition TEST_F @378-401
- function_definition TEST_F @403-423
- function_definition TEST_F @425-437
- function_definition TEST_F @439-457
- function_definition TEST_F @459-472
- function_definition TEST_F @474-490
- function_definition TEST_F @492-514
- function_definition TEST_F @516-538
- function_definition TEST_F @540-556
- function_definition TEST_F @558-573
- function_definition TEST_F @575-594
- function_definition TEST_F @596-621
- function_definition TEST_F @623-643
- function_definition TEST_F @645-663
- function_definition TEST_F @665-686
- function_definition TEST_F @688-705
- function_definition TEST_F @707-735
- function_definition TEST_F @737-758
- function_definition TEST_F @760-779
- function_definition TEST_F @781-799
- function_definition TEST_F @801-842
- function_definition TEST_F @844-891
- function_definition TEST_F @893-916
- function_definition TEST_F @918-940
- function_definition TEST_F @942-959
- function_definition TEST_F @961-983
- function_definition TEST_F @985-1001
- function_definition TEST_F @1003-1022
- function_definition TEST_F @1024-1040
- function_definition TEST_F @1042-1069
- function_definition TEST_F @1071-1093
- function_definition TEST_F @1095-1115
- function_definition TEST_F @1117-1145
- function_definition TEST_F @1147-1170
- function_definition TEST_F @1172-1188
- function_definition TEST_F @1190-1206
- function_definition TEST_F @1208-1225
- function_definition TEST_F @1227-1259
- function_definition TEST_F @1261-1287
- function_definition TEST_F @1289-1315
- function_definition TEST_F @1317-1331
- function_definition TEST_F @1333-1354
- function_definition TEST_F @1356-1379
- function_definition TEST_F @1381-1402
- function_definition TEST_F @1404-1422
- function_definition TEST_F @1424-1447
- function_definition TEST_F @1449-1463
- function_definition TEST_F @1465-1489
- function_definition TEST_F @1491-1539
- function_definition TEST_F @1541-1552
- function_definition TEST_F @1554-1583
- function_definition TEST_F @1585-1610
- function_definition TEST_F @1612-1654
- function_definition TEST_F @1656-1704

### third_party/libwebrtc/modules/rtp_rtcp/source/rtcp_transceiver_unittest.cc

Blob: `3f0baf20d921f9acc5aa762ae1cb9df6737b890b`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtcp_transceiver.h" @11
- include <cstdint> @13
- include <memory> @14
- include <span> @15
- include <utility> @16
- include <vector> @17
- include "api/units/time_delta.h" @19
- include "api/units/timestamp.h" @20
- include "modules/rtp_rtcp/source/rtcp_packet.h" @21
- include "modules/rtp_rtcp/source/rtcp_packet/remote_estimate.h" @22
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @23
- include "modules/rtp_rtcp/source/rtcp_packet/transport_feedback.h" @24
- include "modules/rtp_rtcp/source/rtcp_transceiver_config.h" @25
- include "rtc_base/buffer.h" @26
- include "rtc_base/copy_on_write_buffer.h" @27
- include "rtc_base/event.h" @28
- include "rtc_base/task_queue_for_test.h" @29
- include "system_wrappers/include/clock.h" @30
- include "system_wrappers/include/ntp_time.h" @31
- include "test/gmock.h" @32
- include "test/gtest.h" @33
- include "test/rtcp_packet_parser.h" @34
- class_specifier MockMediaReceiverRtcpObserver @50-53
- function_definition WaitPostedTasks @57-61
- function_definition TEST @63-78
- function_definition TEST @80-98
- function_definition TEST @100-116
- function_definition TEST @118-137
- function_definition TEST @139-159
- function_definition CreateSenderReport @162-170
- function_definition TEST @172-197
- function_definition TEST @199-222
- function_definition TEST @224-250
- function_definition TEST @252-271
- function_definition TEST @273-310
- function_definition TEST @312-351

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_depacketizer_sframe.cc

Blob: `10d40a9c97195749022f8ef9e888c188c692cb88`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_depacketizer_sframe.h" @11
- include <bitset> @13
- include <cstddef> @14
- include <memory> @15
- include <utility> @16
- include "api/rtc_error.h" @18
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @19
- include "modules/rtp_rtcp/source/sframe_descriptor.h" @20
- include "modules/rtp_rtcp/source/sframe_rtp_packet_received.h" @21
- function_definition ParseSframeRtpPacketOrError @25-48

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_depacketizer_sframe.h

Blob: `8f040ba54a07e20c77e9061ddcaef9504477281b`. Grammar: cpp. Status: syntax-clean.

- include <memory> @14
- include "api/rtc_error.h" @16
- include "modules/rtp_rtcp/source/sframe_rtp_packet_received.h" @17
- class_specifier RtpPacketReceived @21-21

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_depacketizer_sframe_unittest.cc

Blob: `0bb2421d72e6b77f5544582000c531bd4b29d7b1`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_depacketizer_sframe.h" @11
- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <vector> @17
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @19
- include "modules/rtp_rtcp/source/sframe_descriptor.h" @20
- include "modules/rtp_rtcp/source/sframe_rtp_packet_received.h" @21
- include "test/gmock.h" @22
- include "test/gtest.h" @23
- function_definition MakeDescriptorByte @32-38
- function_definition MakeReceivedPacket @40-52
- function_definition TEST @54-61
- function_definition TEST @63-73
- function_definition TEST @75-83
- function_definition TEST @85-94
- function_definition TEST @96-108
- function_definition TEST @110-119
- function_definition TEST @121-139
- function_definition TEST @141-152
- function_definition TEST @154-165
- function_definition TEST @167-175
- function_definition TEST @177-188
- function_definition TEST @190-205

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.cc

Blob: `5b92c6466ea1407b89f40674e652f95219776405`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h" @11
- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <span> @16
- include "api/transport/rtp/dependency_descriptor.h" @18
- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_reader.h" @19
- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_writer.h" @20
- include "rtc_base/numerics/divide_round.h" @21
- function_definition Parse @25-31
- function_definition ValueSize @33-40
- function_definition Write @42-50
- function_definition Parse @52-63

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h

Blob: `c757e40d64beea4cb698c22607c3d218f8376adc`. Grammar: cpp. Status: syntax-clean.

- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <span> @16
- include "absl/strings/string_view.h" @18
- include "api/rtp_parameters.h" @19
- include "api/transport/rtp/dependency_descriptor.h" @20
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @21
- class_specifier RtpDependencyDescriptorExtension @26-61
- function_definition Uri @29-31
- function_definition ValueSize @42-45
- function_definition Write @49-53

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_extension_unittest.cc

Blob: `9b054e7dc615c54dcb980a87c0a6ba82473c3c65`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h" @11
- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <cstring> @16
- include <span> @17
- include "api/transport/rtp/dependency_descriptor.h" @19
- include "test/gmock.h" @20
- include "test/gtest.h" @21
- function_definition TEST @28-42
- function_definition TEST @44-68
- function_definition TEST @72-94
- function_definition TEST @96-120
- function_definition TEST @122-138
- function_definition TEST @140-159
- function_definition TEST @161-181

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_reader.cc

Blob: `ad20ce321ecbf7947be4bdd164b4b095a1c8db12`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_reader.h" @10
- include <cstddef> @12
- include <cstdint> @13
- include <memory> @14
- include <optional> @15
- include <span> @16
- include <utility> @17
- include <vector> @18
- include "api/transport/rtp/dependency_descriptor.h" @20
- include "rtc_base/bitstream_reader.h" @21
- include "rtc_base/checks.h" @22
- function_definition RtpDependencyDescriptorReader @26-50
- function_definition ReadTemplateDependencyStructure @52-65
- function_definition ReadTemplateLayers @67-107
- enum_specifier NextLayerIdc @68-73
- function_definition ReadTemplateDtis @109-119
- function_definition ReadTemplateFdiffs @121-130
- function_definition ReadTemplateChains @132-148
- function_definition ReadResolutions @150-160
- function_definition ReadMandatoryFields @162-167
- function_definition ReadExtendedFields @169-182
- function_definition ReadFrameDependencyDefinition @184-215
- function_definition ReadFrameDtis @217-224
- function_definition ReadFrameFdiffs @226-233
- function_definition ReadFrameChains @235-241

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_reader.h

Blob: `b493fb666024c474594140d441daaf53e5562b4d`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @13
- include <span> @14
- include "api/transport/rtp/dependency_descriptor.h" @16
- include "rtc_base/bitstream_reader.h" @17
- class_specifier RtpDependencyDescriptorReader @21-63
- function_definition RtpDependencyDescriptorReader @27-27
- function_definition (anonymous) @28-29
- function_definition ParseSuccessful @32-32

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_writer.cc

Blob: `3d126050044d1baa438f0ea87e873fc80df39597`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_writer.h" @10
- include <algorithm> @12
- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <iterator> @16
- include <span> @17
- include <vector> @18
- include "absl/algorithm/container.h" @20
- include "api/transport/rtp/dependency_descriptor.h" @21
- include "api/video/render_resolution.h" @22
- include "rtc_base/bit_buffer.h" @23
- include "rtc_base/checks.h" @24
- include "rtc_base/numerics/safe_compare.h" @25
- enum_specifier NextLayerIdc @30-36
- function_definition GetNextLayerIdc @38-55
- function_definition RtpDependencyDescriptorWriter @59-79
- function_definition Write @81-93
- function_definition ValueSizeBits @95-109
- function_definition StructureSizeBits @111-135
- function_definition CalculateMatch @137-176
- function_definition FindBestTemplate @178-201
- function_definition ShouldWriteActiveDecodeTargetsBitmask @203-213
- function_definition HasExtendedFields @215-218
- function_definition TemplateId @220-224
- function_definition WriteBits @226-229
- function_definition WriteNonSymmetric @231-235
- function_definition WriteTemplateDependencyStructure @237-254
- function_definition WriteTemplateLayers @256-270
- function_definition WriteTemplateDtis @272-281
- function_definition WriteTemplateFdiffs @283-293
- function_definition WriteTemplateChains @295-318
- function_definition WriteResolutions @320-332
- function_definition WriteMandatoryFields @334-339
- function_definition WriteExtendedFields @341-356
- function_definition WriteFrameDependencyDefinition @358-365
- function_definition WriteFrameDtis @367-374
- function_definition WriteFrameFdiffs @376-389
- function_definition WriteFrameChains @391-401

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_dependency_descriptor_writer.h

Blob: `1feb21ec6143bd7d24c7342650161dac1452f775`. Grammar: cpp. Status: syntax-clean.

- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <span> @16
- include <vector> @17
- include "api/transport/rtp/dependency_descriptor.h" @19
- include "rtc_base/bit_buffer.h" @20
- class_specifier RtpDependencyDescriptorWriter @23-85
- struct_specifier TemplateMatch @43-51

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_descriptor_authentication.cc

Blob: `f4525f0db10f05a3c301c6a303e613c4ee9194fe`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_descriptor_authentication.h" @11
- include <cstdint> @13
- include <vector> @14
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @16
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @17
- include "modules/rtp_rtcp/source/rtp_video_header.h" @18
- function_definition RtpDescriptorAuthentication @22-56

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_descriptor_authentication.h

Blob: `1791abecd8b41f7ae391c255904dfe6f6d4ba4f5`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @14
- include <vector> @15
- include "modules/rtp_rtcp/source/rtp_video_header.h" @17

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_fec_unittest.cc

Blob: `8548dd5ba1f6a4ddc81b3960c8d459fb0f0b72a2`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @11
- include <cstdint> @12
- include <cstring> @13
- include <list> @14
- include <memory> @15
- include <utility> @16
- include <vector> @17
- include "absl/algorithm/container.h" @19
- include "modules/include/module_fec_types.h" @20
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @21
- include "modules/rtp_rtcp/source/byte_io.h" @22
- include "modules/rtp_rtcp/source/fec_test_helper.h" @23
- include "modules/rtp_rtcp/source/flexfec_03_header_reader_writer.h" @24
- include "modules/rtp_rtcp/source/forward_error_correction.h" @25
- include "modules/rtp_rtcp/source/forward_error_correction_internal.h" @26
- include "modules/rtp_rtcp/source/ulpfec_header_reader_writer.h" @27
- include "rtc_base/checks.h" @28
- include "rtc_base/random.h" @29
- include "test/gtest.h" @30
- function_definition DeepCopyEveryNthPacket @45-56
- class_specifier RtpFecTest @63-105
- function_definition RtpFecTest @65-72
- function_definition NetworkReceivedPackets @108-115
- function_definition ReceivedPackets @119-155
- function_definition IsRecoveryComplete @158-176
- class_specifier FlexfecForwardErrorCorrection @183-200
- function_definition FlexfecForwardErrorCorrection @187-192
- function_definition GetFirstFecSeqNum @196-199
- class_specifier UlpfecForwardErrorCorrection @202-218
- function_definition UlpfecForwardErrorCorrection @206-211
- function_definition GetFirstFecSeqNum @215-217
- function_definition TYPED_TEST @224-244
- function_definition TYPED_TEST @246-268
- function_definition TYPED_TEST @270-298
- function_definition TYPED_TEST @300-344
- function_definition TYPED_TEST @347-411
- function_definition TYPED_TEST @415-451
- function_definition TEST_F @465-505
- function_definition TEST_F @516-563
- function_definition TYPED_TEST @566-604
- function_definition TYPED_TEST @607-643
- function_definition TYPED_TEST @648-707
- function_definition TYPED_TEST @712-788
- function_definition TYPED_TEST @790-818
- function_definition TYPED_TEST @820-864
- function_definition TYPED_TEST @867-927
- function_definition TYPED_TEST @929-992
- function_definition TYPED_TEST @994-1064
- function_definition TYPED_TEST @1066-1136

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format.cc

Blob: `3c5a2282bc0abc82c4cc95ec6b15e78e758e3a64`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtp_format.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <memory> @15
- include <span> @16
- include <vector> @17
- include "absl/base/nullability.h" @19
- include "modules/rtp_rtcp/source/rtp_format_h264.h" @20
- include "modules/rtp_rtcp/source/rtp_format_video_generic.h" @21
- include "modules/rtp_rtcp/source/rtp_format_vp8.h" @22
- include "modules/rtp_rtcp/source/rtp_format_vp9.h" @23
- include "modules/rtp_rtcp/source/rtp_packetizer_av1.h" @24
- include "modules/video_coding/codecs/h264/include/h264_globals.h" @25
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @26
- include "modules/video_coding/codecs/vp9/include/vp9_globals.h" @27
- include "rtc_base/checks.h" @28
- include "rtc_base/numerics/safe_compare.h" @29
- include "modules/rtp_rtcp/source/rtp_packetizer_h265.h" @32
- class_specifier EmptyRtpPacketizer @37-41
- function_definition NumPackets @39-39
- function_definition NextPacket @40-40
- function_definition unique_ptr<RtpPacketizer> RtpPacketizer::Create @44-96
- function_definition SplitAboutEqually @98-174

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format.h

Blob: `fe908fc5da06f1fd2769249eaa53f820deccb3c1`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @14
- include <algorithm> @16
- include <cstddef> @17
- include <memory> @18
- include <span> @19
- include <vector> @20
- include "absl/base/nullability.h" @22
- include "modules/rtp_rtcp/source/rtp_video_header.h" @23
- class_specifier RtpPacketToSend @27-27
- class_specifier RtpPacketizer @29-81
- struct_specifier PayloadSizeLimits @31-49
- function_definition Sanitize @38-48
- enum_specifier PacketizationFormat @51-59
- function_definition ~RtpPacketizer @67-67

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_h264.cc

Blob: `5152f915c0cc89ca2c2f9c90219ccc9f428b0768`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_h264.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <span> @16
- include <vector> @17
- include "absl/algorithm/container.h" @19
- include "common_video/h264/h264_common.h" @20
- include "modules/rtp_rtcp/source/byte_io.h" @21
- include "modules/rtp_rtcp/source/rtp_format.h" @22
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @23
- include "modules/video_coding/codecs/h264/include/h264_globals.h" @24
- include "rtc_base/checks.h" @25
- include "rtc_base/logging.h" @26
- function_definition RtpPacketizerH264 @37-61
- function_definition ~RtpPacketizerH264 @63-63
- function_definition NumPackets @65-67
- function_definition GeneratePackets @69-100
- function_definition PacketizeFuA @102-152
- function_definition PacketizeStapA @154-202
- function_definition PacketizeSingleNalu @204-227
- function_definition NextPacket @229-249
- function_definition NextAggregatePacket @251-282
- function_definition NextFragmentPacket @284-307

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_h264.h

Blob: `0af5ba51cb30f832386fe2cc0d4e84933195aca6`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @14
- include <stdint.h> @15
- include <deque> @17
- include <queue> @18
- include <span> @19
- include "modules/rtp_rtcp/source/rtp_format.h" @21
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @22
- include "modules/video_coding/codecs/h264/include/h264_globals.h" @23
- class_specifier RtpPacketizerH264 @37-95
- function_definition RtpPacketizerH264 @47-47
- function_definition (anonymous) @48-48
- struct_specifier PacketUnit @64-81
- function_definition PacketUnit @65-74

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_h264_unittest.cc

Blob: `fb02b9b4c21011cbb6ec8cceca8ee9f6f2e471a1`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_h264.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <initializer_list> @16
- include <span> @17
- include <vector> @18
- include "absl/algorithm/container.h" @20
- include "modules/rtp_rtcp/source/rtp_format.h" @21
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @22
- include "modules/video_coding/codecs/h264/include/h264_globals.h" @23
- include "rtc_base/buffer.h" @24
- include "rtc_base/checks.h" @25
- include "test/gmock.h" @26
- include "test/gtest.h" @27
- enum_specifier Nalu @44-52
- function_definition GenerateNalUnit @58-73
- function_definition CreateFrame @76-101
- function_definition CreateFrame @104-125
- function_definition FetchAllPackets @127-138
- class_specifier RtpPacketizerH264ModeTest @142-143
- function_definition TEST_P @145-153
- function_definition TEST_P @155-167
- function_definition TEST_P @169-186
- function_definition TEST_P @188-205
- function_definition TEST_P @207-219
- function_definition TEST @228-260
- function_definition TEST @262-275
- function_definition TEST @277-299
- function_definition TEST @301-335
- function_definition TEST @337-359
- function_definition TEST @361-382
- function_definition TEST @385-426
- function_definition TEST @428-446
- function_definition TestFua @450-478
- function_definition TEST @481-485
- function_definition TEST @487-493
- function_definition TEST @495-501
- function_definition TEST @503-508
- function_definition TEST @510-514
- function_definition TEST @516-521
- function_definition TEST @523-530
- function_definition TEST @532-541
- function_definition TEST @543-552
- function_definition TEST @554-725
- function_definition TEST @727-734
- function_definition TEST @736-743

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_unittest.cc

Blob: `0c1a842551a3b9c247dc69f3481c82008f03c709`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format.h" @11
- include <cstdint> @13
- include <memory> @14
- include <vector> @15
- include "absl/algorithm/container.h" @17
- include "api/video/video_frame_type.h" @18
- include "modules/rtp_rtcp/source/rtp_video_header.h" @19
- include "test/gmock.h" @20
- include "test/gtest.h" @21
- function_definition EffectivePacketsSizeDifference @38-47
- function_definition Sum @49-51
- function_definition TEST @53-61
- function_definition TEST @63-71
- function_definition TEST @73-84
- function_definition TEST @86-97
- function_definition TEST @99-107
- function_definition TEST @109-119
- function_definition TEST @121-129
- function_definition TEST @131-140
- function_definition TEST @142-152
- function_definition TEST @154-164
- function_definition TEST @166-175
- function_definition TEST @177-188
- function_definition TEST @190-204
- function_definition TEST @206-215
- function_definition TEST @217-224
- function_definition TEST @226-237
- function_definition TEST @239-251
- function_definition TEST @253-266
- function_definition TEST @268-273
- function_definition TEST @275-281
- function_definition TEST @283-289
- function_definition TEST @291-297
- function_definition TEST @299-305
- function_definition TEST @307-313
- function_definition TEST @315-327
- function_definition TEST @329-341

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_video_generic.cc

Blob: `c44d7ca636cd9c03c15204b1f00fef72a7025c77`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_video_generic.h" @11
- include <cstdint> @13
- include <cstring> @14
- include <span> @15
- include <variant> @16
- include "api/video/video_frame_type.h" @18
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @19
- include "modules/rtp_rtcp/source/rtp_video_header.h" @20
- include "rtc_base/checks.h" @21
- function_definition RtpPacketizerGeneric @31-41
- function_definition RtpPacketizerGeneric @43-48
- function_definition ~RtpPacketizerGeneric @50-50
- function_definition NumPackets @52-54
- function_definition NextPacket @56-86
- function_definition BuildHeader @88-104

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_video_generic.h

Blob: `cc9a6fb058b1b6d094474fdb619bf3c03f6746fb`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @13
- include <cstddef> @15
- include <span> @16
- include <vector> @17
- include "modules/rtp_rtcp/source/rtp_format.h" @19
- class_specifier RtpPacketToSend @23-23
- struct_specifier RTPVideoHeader @24-24
- class_specifier RtpPacketizerGeneric @34-70
- function_definition RtpPacketizerGeneric @51-51
- function_definition (anonymous) @52-52

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_video_generic_unittest.cc

Blob: `2a200dd434bdfa5788f05a1426b46a7621415a28`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_video_generic.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <span> @15
- include <vector> @16
- include "api/video/video_frame_type.h" @18
- include "modules/rtp_rtcp/source/rtp_format.h" @19
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @20
- include "modules/rtp_rtcp/source/rtp_video_header.h" @21
- include "test/gmock.h" @22
- include "test/gtest.h" @23
- function_definition NextPacketFillPayloadSizes @35-42
- function_definition TEST @44-55
- function_definition TEST @57-70
- function_definition TEST @72-91
- function_definition TEST @93-107
- function_definition TEST @109-124
- function_definition TEST @126-144
- function_definition TEST @146-157
- function_definition TEST @159-169

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp8.cc

Blob: `7727438b0dd82a2e7e01ebd8c45982e838f4e7e3`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_vp8.h" @11
- include <cstdint> @13
- include <cstring> @14
- include <span> @15
- include <vector> @16
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @18
- include "modules/video_coding/codecs/interface/common_constants.h" @19
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @20
- include "rtc_base/checks.h" @21
- function_definition ValidateHeader @36-56
- function_definition RtpPacketizerVp8 @60-69
- function_definition ~RtpPacketizerVp8 @71-71
- function_definition NumPackets @73-75
- function_definition NextPacket @77-96
- function_definition BuildHeader @98-168

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp8.h

Blob: `034ad449a509d5c7fb3381e37711d1dec2689113`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @28
- include <cstdint> @30
- include <span> @31
- include <vector> @32
- include "absl/container/inlined_vector.h" @34
- include "modules/rtp_rtcp/source/rtp_format.h" @35
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @36
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @37
- class_specifier RtpPacketizerVp8 @42-71
- function_definition RtpPacketizerVp8 @52-52
- function_definition (anonymous) @53-53

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp8_test_helper.cc

Blob: `f55bbfb2dd091c99e094d9e17fd03462a3a9ecde`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_vp8_test_helper.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <iterator> @15
- include <span> @16
- include "modules/rtp_rtcp/source/rtp_format_vp8.h" @18
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @19
- include "modules/video_coding/codecs/interface/common_constants.h" @20
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @21
- include "rtc_base/buffer.h" @22
- include "test/gmock.h" @23
- include "test/gtest.h" @24
- function_definition Bit @51-53
- function_definition RtpFormatVp8TestHelper @57-66
- function_definition ~RtpFormatVp8TestHelper @68-68
- function_definition GetAllPacketsAndCheck @70-92
- function_definition CheckHeader @94-117
- function_definition CheckPictureID @121-134
- function_definition CheckTl0PicIdx @138-148
- function_definition CheckTIDAndKeyIdx @153-183

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp8_test_helper.h

Blob: `3e744d9b2055b594c67bf395736e8b216ab990b4`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @20
- include <cstdint> @21
- include <span> @22
- include "modules/rtp_rtcp/source/rtp_format_vp8.h" @24
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @25
- include "rtc_base/buffer.h" @26
- class_specifier RtpFormatVp8TestHelper @30-54
- function_definition RtpFormatVp8TestHelper @35-35
- function_definition (anonymous) @36-36
- function_definition payload @41-41
- function_definition payload_size @42-42

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp8_unittest.cc

Blob: `304369ba49262f07b68666272e2f80d421cb209f`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_vp8.h" @11
- include <cstddef> @13
- include "modules/rtp_rtcp/source/rtp_format.h" @15
- include "modules/rtp_rtcp/source/rtp_format_vp8_test_helper.h" @16
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @17
- include "test/gtest.h" @18
- function_definition TEST @25-35
- function_definition TEST @37-49
- function_definition TEST @51-69
- function_definition TEST @72-84
- function_definition TEST @87-99
- function_definition TEST @101-111
- function_definition TEST @114-125

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp9.cc

Blob: `77935f9f05e646f4afc0408fbf0d4304514e98cc`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_vp9.h" @11
- include <cstdint> @13
- include <cstring> @14
- include <span> @15
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @17
- include "modules/video_coding/codecs/interface/common_constants.h" @18
- include "modules/video_coding/codecs/vp9/include/vp9_globals.h" @19
- include "rtc_base/bit_buffer.h" @20
- include "rtc_base/checks.h" @21
- include "rtc_base/logging.h" @22
- function_definition TemporalIdxField @36-38
- function_definition SpatialIdxField @40-42
- function_definition Tl0PicIdxField @44-46
- function_definition PictureIdLength @56-60
- function_definition PictureIdPresent @62-64
- function_definition LayerInfoLength @76-81
- function_definition LayerInfoPresent @83-85
- function_definition RefIndicesLength @94-101
- function_definition SsDataLength @123-144
- function_definition PayloadDescriptorLengthMinusSsData @146-149
- function_definition WritePictureId @159-164
- function_definition WriteLayerInfoCommon @174-182
- function_definition WriteLayerInfoNonFlexibleMode @192-196
- function_definition WriteLayerInfo @198-206
- function_definition WriteRefIndices @215-226
- function_definition WriteSsData @248-280
- function_definition RemoveInactiveSpatialLayers @287-307
- function_definition RtpPacketizerVp9 @310-326
- function_definition ~RtpPacketizerVp9 @328-328
- function_definition NumPackets @330-332
- function_definition NextPacket @334-365
- function_definition WriteHeader @402-449

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp9.h

Blob: `59af6383c40bef1c755ac27a6cb2710819d3b247`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @24
- include <stdint.h> @25
- include <span> @27
- include <vector> @28
- include "modules/rtp_rtcp/source/rtp_format.h" @30
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @31
- include "modules/video_coding/codecs/vp9/include/vp9_globals.h" @32
- class_specifier RtpPacketizerVp9 @36-69
- function_definition RtpPacketizerVp9 @45-45
- function_definition (anonymous) @46-46

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_format_vp9_unittest.cc

Blob: `9c59ef788f102d5f6c6f39f045b63245d526c886`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_format_vp9.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <memory> @15
- include <span> @16
- include <vector> @17
- include "api/video/video_codec_type.h" @19
- include "modules/rtp_rtcp/source/rtp_format.h" @20
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @21
- include "modules/rtp_rtcp/source/rtp_video_header.h" @22
- include "modules/rtp_rtcp/source/video_rtp_depacketizer_vp9.h" @23
- include "modules/video_coding/codecs/vp9/include/vp9_globals.h" @24
- include "test/gtest.h" @25
- function_definition VerifyHeader @29-73
- function_definition ParseAndCheckPacket @75-87
- class_specifier RtpPacketizerVp9Test @123-191
- function_definition RtpPacketizerVp9Test @128-128
- function_definition SetUp @129-129
- function_definition Init @138-145
- function_definition CheckPayload @147-155
- function_definition CreateParseAndCheckPackets @157-175
- function_definition CreateParseAndCheckPacketsLayers @177-190
- function_definition TEST_F @193-196
- function_definition TEST_F @198-208
- function_definition TEST_F @210-221
- function_definition TEST_F @223-229
- function_definition TEST_F @231-246
- function_definition TEST_F @248-263
- function_definition TEST_F @265-285
- function_definition TEST_F @287-305
- function_definition TEST_F @307-334
- function_definition TEST_F @336-347
- function_definition TEST_F @349-371
- function_definition TEST_F @373-389
- function_definition TEST_F @391-433
- function_definition TEST_F @435-478
- function_definition TEST_F @480-506
- function_definition TEST_F @508-529
- function_definition TEST_F @531-558
- function_definition TEST_F @560-571
- function_definition TEST_F @573-614

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_generic_frame_descriptor.cc

Blob: `44124f3b469e472031a7d9dc49cd31dd9f0d9267`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @11
- include <cstdint> @13
- include <span> @14
- include "rtc_base/checks.h" @16
- function_definition RtpGenericFrameDescriptor @20-20
- function_definition RtpGenericFrameDescriptor @21-22
- function_definition ~RtpGenericFrameDescriptor @23-23
- function_definition TemporalLayer @25-28
- function_definition SetTemporalLayer @30-34
- function_definition SpatialLayer @36-45
- function_definition SpatialLayersBitmask @47-50
- function_definition SetSpatialLayersBitmask @52-56
- function_definition SetResolution @58-66
- function_definition FrameId @68-71
- function_definition SetFrameId @73-76
- function_definition FrameDependenciesDiffs @78-82
- function_definition AddFrameDependencyDiff @84-95

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h

Blob: `4075bfef0e25bbbd5cc33a58c982ac5e7ad2b23f`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @13
- include <stdint.h> @14
- include <span> @16
- class_specifier RtpGenericFrameDescriptorExtension @20-20
- class_specifier RtpGenericFrameDescriptor @23-72
- function_definition FirstPacketInSubFrame @33-33
- function_definition SetFirstPacketInSubFrame @34-34
- function_definition LastPacketInSubFrame @35-35
- function_definition SetLastPacketInSubFrame @36-36
- function_definition Width @49-49
- function_definition Height @50-50
- function_definition ClearFrameDependencies @57-57

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.cc

Blob: `511b93e591ba459429daf9109a0e3240fd74b4e6`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <span> @15
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @17
- include "rtc_base/checks.h" @18
- function_definition Parse @65-114
- function_definition ValueSize @116-131
- function_definition Write @133-175

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h

Blob: `c213f52310a971390cc37d1ea0c8c0c6ea08bc8a`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @13
- include <stdint.h> @14
- include <span> @16
- include "absl/strings/string_view.h" @18
- include "api/rtp_parameters.h" @19
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @20
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @21
- class_specifier RtpGenericFrameDescriptorExtension00 @28-42
- function_definition Uri @32-34

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension_unittest.cc

Blob: `4e3ac9be1226ac8f45172ecb19240ba8bbb7a491`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @10
- include <cstdint> @12
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @14
- include "test/gmock.h" @15
- include "test/gtest.h" @16
- function_definition TEST @27-42
- function_definition TEST @44-61
- function_definition TEST @63-71
- function_definition TEST @73-84
- function_definition TEST @86-94
- function_definition TEST @96-108
- function_definition TEST @110-118
- function_definition TEST @120-132
- function_definition TEST @134-142
- function_definition TEST @144-156
- function_definition TEST @158-167
- function_definition TEST @169-183
- function_definition TEST @185-193
- function_definition TEST @195-207
- function_definition TEST @209-219
- function_definition TEST @221-236
- function_definition TEST @238-248
- function_definition TEST @250-265

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extension_map.cc

Blob: `8ae5fb8f853967320d6220407c83333421d91a69`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @11
- include <iterator> @13
- include <span> @14
- include "absl/strings/string_view.h" @16
- include "api/rtp_header_extension_id.h" @17
- include "api/rtp_parameters.h" @18
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @19
- include "modules/rtp_rtcp/source/corruption_detection_extension.h" @20
- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h" @21
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @22
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @23
- include "modules/rtp_rtcp/source/rtp_video_layers_allocation_extension.h" @24
- include "rtc_base/checks.h" @25
- include "rtc_base/logging.h" @26
- struct_specifier ExtensionInfo @31-34
- function_definition CreateExtensionInfo @37-39
- function_definition RtpHeaderExtensionMap @73-73
- function_definition RtpHeaderExtensionMap @75-79
- function_definition RtpHeaderExtensionMap @81-86
- function_definition Reset @88-93
- function_definition RegisterByType @95-102
- function_definition RegisterByUri @104-112
- function_definition GetType @114-123
- function_definition Deregister @125-132
- function_definition Register @134-170

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extension_map_unittest.cc

Blob: `a27e120731d842678462d27966480698f07bd863`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @10
- include <vector> @12
- include "api/rtp_header_extension_id.h" @14
- include "api/rtp_parameters.h" @15
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @16
- include "test/gtest.h" @17
- function_definition TEST @21-31
- function_definition TEST @33-42
- function_definition TEST @44-52
- function_definition TEST @54-62
- function_definition TEST @64-69
- function_definition TEST @71-75
- function_definition TEST @77-85
- function_definition TEST @87-93
- function_definition TEST @95-102
- function_definition TEST @104-111
- function_definition TEST @113-117

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extension_size.cc

Blob: `4e074cb9cabfa35f8c31c216d84d4afc60ecfa28`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @11
- include <span> @13
- include "api/rtp_header_extension_id.h" @15
- include "api/rtp_parameters.h" @16
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @17
- function_definition RtpHeaderExtensionSize @21-50

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extension_size.h

Blob: `48a180812ed84f8fd43f19b736a20dc35ef3e888`. Grammar: cpp. Status: syntax-clean.

- include <span> @13
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @15
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @16
- struct_specifier RtpExtensionSize @20-23

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extension_size_unittest.cc

Blob: `640c19f98a3c7551aabafcca99d5509e3d70f79e`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @10
- include "api/rtp_header_extension_id.h" @12
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @13
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @14
- include "test/gtest.h" @15
- function_definition TEST @26-34
- function_definition TEST @36-45
- function_definition TEST @47-55
- function_definition TEST @57-68
- function_definition TEST @70-81
- function_definition TEST @83-94

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extensions.cc

Blob: `6c30b519f8ff876a531dd35f685f0ae0730c4d12`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @11
- include <string.h> @13
- include <cmath> @15
- include <cstddef> @16
- include <cstdint> @17
- include <cstring> @18
- include <limits> @19
- include <optional> @20
- include <span> @21
- include <string> @22
- include <vector> @23
- include "absl/strings/string_view.h" @25
- include "api/rtp_headers.h" @26
- include "api/units/time_delta.h" @27
- include "api/video/color_space.h" @28
- include "api/video/hdr_metadata.h" @29
- include "api/video/video_content_type.h" @30
- include "api/video/video_rotation.h" @31
- include "api/video/video_timing.h" @32
- include "modules/rtp_rtcp/include/rtp_cvo.h" @33
- include "modules/rtp_rtcp/source/byte_io.h" @34
- include "rtc_base/checks.h" @35
- function_definition Parse @53-59
- function_definition Write @61-66
- function_definition Parse @103-119
- function_definition ValueSize @121-128
- function_definition Write @130-143
- function_definition Parse @164-173
- function_definition Write @175-183
- function_definition Parse @207-217
- function_definition ValueSize @219-221
- function_definition Write @223-233
- function_definition Parse @252-258
- function_definition Write @260-265
- function_definition Parse @274-280
- function_definition Write @282-287
- function_definition Parse @306-331
- function_definition Write @333-351
- function_definition Parse @364-370
- function_definition Write @372-376
- function_definition Parse @378-383
- function_definition Write @385-389
- function_definition Parse @396-405
- function_definition Write @407-425
- function_definition Parse @441-451
- function_definition ValueSize @453-455
- function_definition Write @457-465
- function_definition Parse @477-489
- function_definition Write @491-496
- function_definition Parse @519-549
- function_definition Write @551-571
- function_definition Write @573-580
- function_definition Parse @617-655
- function_definition Write @657-676
- function_definition CombineRangeAndChromaSiting @683-693
- function_definition ParseHdrMetadata @695-721
- function_definition ParseChromaticity @723-732
- function_definition ParseLuminance @734-740
- function_definition WriteHdrMetadata @742-770
- function_definition WriteChromaticity @772-784
- function_definition WriteLuminance @786-794
- function_definition Parse @796-806
- function_definition Write @808-817
- function_definition Parse @836-844
- function_definition Write @846-857
- function_definition Parse @866-873
- function_definition Write @875-880

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_header_extensions.h

Blob: `b5148dff8c888304d0a3a7400176557299eaca7d`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @13
- include <stdint.h> @14
- include <cstdint> @16
- include <optional> @17
- include <span> @18
- include <string> @19
- include <vector> @20
- include "absl/strings/string_view.h" @22
- include "api/rtp_headers.h" @23
- include "api/rtp_parameters.h" @24
- include "api/units/time_delta.h" @25
- include "api/units/timestamp.h" @26
- include "api/video/color_space.h" @27
- include "api/video/hdr_metadata.h" @28
- include "api/video/video_content_type.h" @29
- include "api/video/video_rotation.h" @30
- include "api/video/video_timing.h" @31
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @32
- include "rtc_base/checks.h" @33
- include "system_wrappers/include/ntp_time.h" @34
- class_specifier AbsoluteSendTime @45-77
- function_definition Uri @50-52
- function_definition ValueSize @55-57
- function_definition To24Bits @60-66
- function_definition To24Bits @68-71
- function_definition ToTimestamp @73-76
- class_specifier AbsoluteCaptureTimeExtension @79-95
- function_definition Uri @86-88
- class_specifier AudioLevelExtension @97-111
- function_definition Uri @102-104
- function_definition ValueSize @107-109
- class_specifier CsrcAudioLevel @114-127
- function_definition Uri @118-120
- class_specifier TransmissionOffset @130-142
- function_definition Uri @135-137
- function_definition ValueSize @140-140
- class_specifier TransportSequenceNumber @144-160
- function_definition Uri @149-151
- function_definition ValueSize @155-157
- class_specifier TransportSequenceNumberV2 @162-187
- function_definition Uri @168-170
- function_definition ValueSize @175-180
- class_specifier VideoOrientation @189-204
- function_definition Uri @194-196
- function_definition ValueSize @199-199
- function_definition ValueSize @202-202
- class_specifier PlayoutDelayLimits @206-227
- function_definition Uri @211-213
- function_definition ValueSize @224-224
- class_specifier VideoContentTypeExtension @229-242
- function_definition Uri @234-236
- function_definition ValueSize @240-240
- class_specifier VideoTimingExtension @244-274
- function_definition Uri @249-251
- function_definition ValueSize @264-264
- function_definition ValueSize @267-269
- class_specifier ColorSpaceExtension @276-312
- function_definition Uri @282-284
- function_definition ValueSize @287-290
- class_specifier CsrcAudioLevel @315-329
- function_definition Uri @318-320
- class_specifier BaseRtpStringExtension @334-344
- function_definition ValueSize @342-342
- class_specifier RtpStreamId @346-350
- function_definition Uri @349-349
- class_specifier RepairedRtpStreamId @352-358
- function_definition Uri @355-357
- class_specifier RtpMid @360-364
- function_definition Uri @363-363
- class_specifier InbandComfortNoiseExtension @366-382
- function_definition Uri @374-374
- function_definition ValueSize @378-380
- class_specifier VideoFrameTrackingIdExtension @384-399
- function_definition Uri @389-391
- function_definition ValueSize @395-397

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet.cc

Blob: `ef78a45945ceab61dbbed1f6ebfe264530898a29`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packet.h" @11
- include <cstdint> @13
- include <cstring> @14
- include <span> @15
- include <string> @16
- include <utility> @17
- include <vector> @18
- include "api/rtp_header_extension_id.h" @20
- include "api/rtp_parameters.h" @21
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @22
- include "modules/rtp_rtcp/source/byte_io.h" @23
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @24
- include "rtc_base/checks.h" @25
- include "rtc_base/copy_on_write_buffer.h" @26
- include "rtc_base/logging.h" @27
- include "rtc_base/numerics/safe_conversions.h" @28
- include "rtc_base/strings/string_builder.h" @29
- function_definition RtpPacket @65-65
- function_definition RtpPacket @67-68
- function_definition RtpPacket @70-75
- function_definition RtpPacket @77-77
- function_definition RtpPacket @78-78
- function_definition ~RtpPacket @81-81
- function_definition IdentifyExtensions @83-85
- function_definition Parse @87-95
- function_definition Parse @97-99
- function_definition Parse @101-110
- function_definition Csrcs @112-121
- function_definition CopyHeaderFrom @123-137
- function_definition SetMarker @139-146
- function_definition SetPayloadType @148-152
- function_definition SetSequenceNumber @154-157
- function_definition SetTimestamp @159-162
- function_definition SetSsrc @164-167
- function_definition ZeroMutableExtensions @169-226
- function_definition SetCsrcs @228-248
- function_definition AllocateRawExtension @250-361
- function_definition PromoteToTwoByteHeaderExtension @363-397
- function_definition SetExtensionLengthMaybeAddZeroPadding @399-411
- function_definition AllocatePayload @413-418
- function_definition SetPayload @420-426
- function_definition SetPayloadSize @428-433
- function_definition SetPadding @435-455
- function_definition Clear @457-472
- function_definition ParseBuffer @474-592
- function_definition FindExtensionInfo @594-602
- function_definition (anonymous) @604-613
- function_definition FindExtension @615-626
- function_definition AllocateExtension @628-647
- function_definition HasExtension @649-656
- function_definition RemoveExtension @658-718
- function_definition ToString @720-730

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet.h

Blob: `48525922dfc4faffa089ffbd136d10504661dd22`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <optional> @16
- include <span> @17
- include <string> @18
- include <utility> @19
- include <vector> @20
- include "api/rtp_header_extension_id.h" @22
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @23
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @24
- include "rtc_base/copy_on_write_buffer.h" @25
- class_specifier RtpPacket @29-237
- function_definition (anonymous) @71-71
- function_definition Marker @74-74
- function_definition PayloadType @75-75
- function_definition SequenceNumber @76-76
- function_definition Timestamp @77-77
- function_definition Ssrc @78-78
- function_definition headers_size @81-81
- function_definition payload_size @84-84
- function_definition has_padding @85-85
- function_definition padding_size @86-86
- function_definition payload @87-89
- function_definition PayloadBuffer @90-92
- function_definition Buffer @95-95
- function_definition capacity @96-96
- function_definition size @97-99
- function_definition data @100-100
- function_definition buffer @101-101
- function_definition FreeCapacity @102-102
- function_definition MaxPayloadSize @103-103
- struct_specifier ExtensionInfo @185-192
- function_definition ExtensionInfo @186-186
- function_definition ExtensionInfo @187-188
- function_definition WriteAt @217-217
- function_definition WriteAt @218-220
- function_definition ReadAt @221-221
- function_definition HasExtension @240-242
- function_definition IsRegistered @245-247
- function_definition GetExtension @250-256
- function_definition GetExtension @259-265
- function_definition GetRawExtension @268-270
- function_definition SetExtension @273-279
- function_definition SetRawExtension @282-289
- function_definition ReserveExtension @292-298

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_h265_common.h

Blob: `904e1d235b7c08714230309d74bba59a7ba283c6`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @13
- include <cstdint> @14
- enum_specifier NalHdrMasks @35-43
- enum_specifier FuBitmasks @46-50

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_history.cc

Blob: `f2154240fdf4d5662aca95b9e1ce9b6a9a8c60ca`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packet_history.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <limits> @16
- include <memory> @17
- include <optional> @18
- include <span> @19
- include <utility> @20
- include "api/environment/environment.h" @22
- include "api/function_view.h" @23
- include "api/units/time_delta.h" @24
- include "api/units/timestamp.h" @25
- include "modules/include/module_common_types_public.h" @26
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @27
- include "rtc_base/checks.h" @28
- include "rtc_base/logging.h" @29
- include "rtc_base/synchronization/mutex.h" @30
- include "system_wrappers/include/clock.h" @31
- function_definition StoredPacket::StoredPacket @42-50
- function_definition StoredPacket::StoredPacket @52-52
- function_definition StoredPacket::~StoredPacket @55-55
- function_definition StoredPacket::IncrementTimesRetransmitted @57-59
- function_definition RtpPacketHistory @61-68
- function_definition ~RtpPacketHistory @70-70
- function_definition SetStorePacketsStatus @72-82
- function_definition GetStorageMode @84-87
- function_definition SetRtt @89-99
- function_definition PutRtpPacket @101-150
- function_definition GetPacketAndMarkAsPending @152-158
- function_definition GetPacketAndMarkAsPending @160-192
- function_definition MarkPacketAsSent @194-210
- function_definition GetPacketState @212-233
- function_definition VerifyRtt @235-246
- function_definition GetPayloadPaddingPacket @248-253
- function_definition GetPayloadPaddingPacket @255-299
- function_definition CullAcknowledgedPackets @301-312
- function_definition Clear @314-317
- function_definition Reset @319-322
- function_definition CullOldPackets @324-361
- function_definition RemovePacket @363-376
- function_definition GetPacketIndex @378-403
- function_definition GetStoredPacket @405-413

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_history.h

Blob: `9a8c8825fd3a7b808ce223d4ad94ee788999c6a4`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <deque> @16
- include <memory> @17
- include <optional> @18
- include <span> @19
- include "api/environment/environment.h" @21
- include "api/function_view.h" @22
- include "api/units/time_delta.h" @23
- include "api/units/timestamp.h" @24
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @25
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @26
- include "rtc_base/synchronization/mutex.h" @27
- include "rtc_base/thread_annotations.h" @28
- class_specifier Clock @32-32
- class_specifier RtpPacketHistory @34-194
- enum_specifier StorageMode @36-40
- enum_specifier PaddingMode @42-47
- function_definition RtpPacketHistory @61-61
- function_definition RtpPacketHistory @62-62
- function_definition (anonymous) @63-63
- class_specifier StoredPacket @126-159
- function_definition StoredPacket @128-128
- function_definition insert_order @136-136
- function_definition times_retransmitted @137-137
- function_definition send_time @141-141
- function_definition set_send_time @142-142

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_history_unittest.cc

Blob: `a2654836523c2d72ec3fb613cefb68e176b1ad82`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packet_history.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <limits> @15
- include <memory> @16
- include <utility> @17
- include <vector> @18
- include "api/environment/environment.h" @20
- include "api/units/time_delta.h" @21
- include "api/units/timestamp.h" @22
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @23
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @24
- include "rtc_base/copy_on_write_buffer.h" @25
- include "system_wrappers/include/clock.h" @26
- include "test/create_test_environment.h" @27
- include "test/gmock.h" @28
- include "test/gtest.h" @29
- function_definition To16u @37-39
- function_definition CreatePacket @47-56
- class_specifier RtpPacketHistoryTest @60-75
- function_definition RtpPacketHistoryTest @63-66
- function_definition CreateRtpPacket @72-74
- function_definition TEST_P @77-85
- function_definition TEST_P @87-96
- function_definition TEST_P @98-124
- function_definition TEST_P @126-133
- function_definition TEST_P @135-138
- function_definition TEST_P @140-148
- function_definition TEST_P @150-164
- function_definition TEST_P @166-191
- function_definition TEST_P @193-222
- function_definition TEST_P @224-252
- function_definition TEST_P @254-276
- function_definition TEST_P @278-304
- function_definition TEST_P @306-326
- function_definition TEST_P @328-351
- function_definition TEST_P @353-405
- function_definition TEST_P @407-431
- function_definition TEST_P @433-458
- function_definition TEST_P @460-474
- function_definition TEST_P @476-502
- function_definition TEST_P @504-524
- function_definition TEST_P @526-545
- function_definition TEST_P @547-558
- function_definition TEST_P @560-583
- function_definition TEST_P @585-625
- function_definition TEST @633-652
- function_definition TEST @654-674
- function_definition TEST @676-696
- function_definition TEST @698-724

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_received.cc

Blob: `22b1c510fb3193eb9a3e80eaa200ca8150174853`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packet_received.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <vector> @15
- include "api/rtp_headers.h" @17
- include "api/units/timestamp.h" @18
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @19
- include "modules/rtp_rtcp/source/rtp_packet.h" @20
- include "rtc_base/numerics/safe_conversions.h" @21
- function_definition RtpPacketReceived @25-25
- function_definition RtpPacketReceived @26-29
- class_specifier Timestamp @28-28
- function_definition RtpPacketReceived @30-30
- function_definition RtpPacketReceived @31-31
- function_definition ~RtpPacketReceived @38-38
- function_definition GetHeader @40-79

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_received.h

Blob: `77ed8c74c2ef1fe6a1ef937b1969d7bbc97451f5`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @13
- include <utility> @15
- include "api/ref_counted_base.h" @17
- include "api/rtp_headers.h" @18
- include "api/scoped_refptr.h" @19
- include "api/transport/ecn_marking.h" @20
- include "api/units/timestamp.h" @21
- include "modules/rtp_rtcp/source/rtp_packet.h" @22
- class_specifier RtpPacketReceived @28-80
- function_definition arrival_time @48-48
- function_definition set_arrival_time @49-49
- function_definition ecn @53-53
- function_definition set_ecn @54-54
- function_definition recovered @57-57
- function_definition set_recovered @58-58
- function_definition payload_type_frequency @60-60
- function_definition set_payload_type_frequency @61-63
- function_definition additional_data @67-69
- function_definition set_additional_data @70-72

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_to_send.cc

Blob: `014de42f07e019445e4065f0bc4467e960160cc7`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @11
- include <cstddef> @13
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @15
- function_definition RtpPacketToSend @19-20
- function_definition RtpPacketToSend @21-23
- function_definition RtpPacketToSend @24-24
- function_definition RtpPacketToSend @25-25
- function_definition ~RtpPacketToSend @31-31
- function_definition set_packet_type @33-40

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_to_send.h

Blob: `405fe6d74d052ce271fd96407830ba5acd830cb5`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @13
- include <stdint.h> @14
- include <optional> @16
- include <utility> @17
- include "api/ref_counted_base.h" @19
- include "api/scoped_refptr.h" @20
- include "api/units/time_delta.h" @21
- include "api/units/timestamp.h" @22
- include "api/video/video_timing.h" @23
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @24
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @25
- include "modules/rtp_rtcp/source/rtp_packet.h" @26
- class_specifier RtpPacketToSend @32-184
- function_definition capture_time @48-48
- class_specifier Timestamp @48-48
- function_definition set_capture_time @49-49
- class_specifier Timestamp @49-49
- function_definition packet_type @53-53
- enum_specifier OriginalType @55-55
- function_definition original_packet_type @57-59
- function_definition set_retransmitted_sequence_number @64-66
- function_definition retransmitted_sequence_number @67-69
- function_definition set_original_ssrc @73-73
- function_definition original_ssrc @74-74
- function_definition set_allow_retransmission @76-78
- function_definition allow_retransmission @79-79
- function_definition set_allow_sending @84-84
- function_definition allow_sending @85-85
- function_definition additional_data @89-91
- function_definition set_additional_data @92-94
- function_definition set_packetization_finish_time @96-100
- class_specifier Timestamp @96-96
- function_definition set_pacer_exit_time @102-106
- class_specifier Timestamp @102-102
- function_definition set_network_time @108-112
- class_specifier Timestamp @108-108
- function_definition set_network2_time @114-118
- class_specifier Timestamp @114-114
- function_definition set_first_packet_of_frame @121-123
- function_definition is_first_packet_of_frame @124-124
- function_definition set_last_packet_of_frame @127-129
- function_definition is_last_packet_of_frame @130-130
- function_definition set_is_key_frame @133-133
- function_definition is_key_frame @134-134
- function_definition set_fec_protect_packet @137-137
- function_definition fec_protect_packet @138-138
- function_definition set_is_red @142-142
- function_definition is_red @143-143
- function_definition set_time_in_send_queue @147-149
- function_definition time_in_send_queue @150-152
- function_definition transport_sequence_number @155-157
- function_definition set_transport_sequence_number @158-160
- function_definition send_as_ect1 @164-164
- function_definition set_send_as_ect1 @165-165
- class_specifier Timestamp @168-168

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packet_unittest.cc

Blob: `74a2decc4bd424740bde8d298d465070342db1c1`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packet.h" @10
- include <cstddef> @12
- include <cstdint> @13
- include <cstring> @14
- include <optional> @15
- include <span> @16
- include <string> @17
- include <type_traits> @18
- include <utility> @19
- include <vector> @20
- include "absl/strings/string_view.h" @22
- include "api/rtp_header_extension_id.h" @23
- include "api/rtp_headers.h" @24
- include "api/units/time_delta.h" @25
- include "api/video/color_space.h" @26
- include "api/video/video_timing.h" @27
- include "common_video/test/utilities.h" @28
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @29
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @30
- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h" @31
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @32
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @33
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @34
- include "rtc_base/copy_on_write_buffer.h" @35
- include "test/gmock.h" @36
- include "test/gtest.h" @37
- function_definition TestCreateAndParseColorSpaceExtension @225-240
- function_definition TEST @242-249
- function_definition TEST @251-261
- function_definition TEST @263-277
- function_definition TEST @279-298
- function_definition TEST @300-322
- function_definition TEST @324-334
- function_definition TEST @336-341
- function_definition TEST @343-350
- function_definition TEST @352-357
- function_definition TEST @359-366
- function_definition TEST @368-375
- function_definition TEST @377-384
- function_definition TEST @386-407
- function_definition TEST @409-422
- function_definition TEST @424-436
- function_definition TEST @438-454
- function_definition TEST @456-470
- function_definition TEST @472-478
- function_definition TEST @480-490
- function_definition TEST @492-498
- function_definition TEST @500-512
- function_definition TEST @514-526
- function_definition TEST @528-534
- function_definition TEST @536-542
- function_definition TEST @544-553
- function_definition TEST @555-561
- function_definition TEST @563-572
- function_definition TEST @574-586
- function_definition TEST @588-603
- function_definition TEST @605-623
- function_definition TEST @625-639
- function_definition TEST @641-658
- function_definition TEST @660-673
- function_definition TEST @675-690
- function_definition TEST @692-706
- function_definition TEST @708-722
- function_definition TEST @724-738
- function_definition TEST @740-761
- function_definition TEST @763-776
- function_definition TEST @778-791
- function_definition TEST @793-805
- function_definition TEST @807-819
- function_definition TEST @821-835
- function_definition TEST @837-846
- function_definition TEST @848-857
- function_definition TEST @859-874
- function_definition TEST @876-894
- function_definition TEST @896-933
- function_definition TEST @935-944
- struct_specifier UncopyableValue @946-950
- function_definition UncopyableValue @947-947
- function_definition UncopyableValue @948-948
- function_definition (anonymous) @949-949
- struct_specifier UncopyableExtension @951-964
- function_definition Uri @953-953
- function_definition ValueSize @955-955
- function_definition Write @956-959
- function_definition Parse @960-963
- function_definition TEST @966-973
- function_definition TEST @975-984
- struct_specifier ParseByReferenceExtension @986-1005
- function_definition Uri @988-988
- function_definition ValueSize @990-992
- function_definition Write @993-997
- function_definition Parse @998-1004
- function_definition TEST @1007-1019
- function_definition TEST @1021-1056
- function_definition TEST @1058-1072
- function_definition TEST @1074-1076
- function_definition TEST @1078-1080
- function_definition TEST @1082-1109
- function_definition TEST @1111-1139
- function_definition TEST @1141-1163
- function_definition TEST @1165-1194
- function_definition TEST @1196-1229
- function_definition TEST @1231-1264
- function_definition TEST @1266-1284
- function_definition TEST @1287-1312
- function_definition TEST @1316-1344
- function_definition TEST @1348-1370
- function_definition TEST @1372-1381
- function_definition TEST @1383-1403
- function_definition TEST @1405-1409
- function_definition TEST @1411-1418
- function_definition TEST @1420-1424

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_av1.cc

Blob: `e9c61a8972e63b731326bee794260218169653ee`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_av1.h" @10
- include <algorithm> @12
- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <span> @16
- include <vector> @17
- include "api/video/video_frame_type.h" @19
- include "modules/rtp_rtcp/source/leb128.h" @20
- include "modules/rtp_rtcp/source/rtp_format.h" @21
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @22
- include "rtc_base/byte_buffer.h" @23
- include "rtc_base/checks.h" @24
- include "rtc_base/logging.h" @25
- function_definition ObuHasExtension @45-47
- function_definition ObuHasSize @49-51
- function_definition ObuType @53-55
- function_definition MaxFragmentSize @60-69
- function_definition RtpPacketizerAv1 @73-80
- function_definition ParseObus @82-128
- function_definition AdditionalBytesForPreviousObuElement @130-147
- function_definition PacketizeInternal @149-300
- function_definition Packetize @302-348
- function_definition AggregationHeader @350-381
- function_definition NextPacket @383-455

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_av1.h

Blob: `c121877ff8ff78947472919a34018ec96d0aa007`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @14
- include <stdint.h> @15
- include <span> @17
- include <vector> @18
- include "api/video/video_frame_type.h" @20
- include "modules/rtp_rtcp/source/rtp_format.h" @21
- class_specifier RtpPacketizerAv1 @25-73
- function_definition ~RtpPacketizerAv1 @31-31
- function_definition NumPackets @33-33
- struct_specifier Obu @37-42
- struct_specifier Packet @43-53
- function_definition Packet @44-44

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_av1_test_helper.cc

Blob: `80bf92fdaf1b11cf4bfe711c5317f81e24b1c37a`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_av1_test_helper.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <initializer_list> @15
- include <utility> @16
- include <vector> @17
- function_definition Av1Obu @21-21
- function_definition (anonymous) @23-27
- function_definition (anonymous) @28-31
- function_definition (anonymous) @32-35
- function_definition BuildAv1Frame @37-56

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_av1_test_helper.h

Blob: `7b0a0410c45697820e24d38f613537e2aeef01fe`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @14
- include <initializer_list> @16
- include <vector> @17
- class_specifier Av1Obu @32-45

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_av1_unittest.cc

Blob: `2a5a8cadc476a9130ee4dad6a6a05b35680c307e`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_av1.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <initializer_list> @15
- include <span> @16
- include <utility> @17
- include <vector> @18
- include "api/scoped_refptr.h" @20
- include "api/video/encoded_image.h" @21
- include "api/video/video_frame_type.h" @22
- include "modules/rtp_rtcp/source/rtp_format.h" @23
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @24
- include "modules/rtp_rtcp/source/rtp_packetizer_av1_test_helper.h" @25
- include "modules/rtp_rtcp/source/video_rtp_depacketizer_av1.h" @26
- include "test/gmock.h" @27
- include "test/gtest.h" @28
- struct_specifier RtpPayload @42-58
- function_definition RtpPayload @46-46
- function_definition (anonymous) @47-47
- function_definition RtpPayload @48-48
- function_definition begin @50-50
- function_definition end @51-51
- function_definition data @52-52
- function_definition size @53-53
- function_definition aggregation_header @55-55
- class_specifier Av1Frame @62-77
- function_definition Av1Frame @67-68
- function_definition begin @70-70
- function_definition end @71-73
- function_definition Packetize @79-93
- function_definition ReassembleFrame @95-101
- function_definition TEST @103-107
- function_definition TEST @109-116
- function_definition TEST @118-128
- function_definition TEST @130-137
- function_definition TEST @139-148
- function_definition TEST @150-161
- function_definition TEST @163-176
- function_definition TEST @178-193
- function_definition TEST @195-219
- function_definition TEST @221-231
- function_definition TEST @233-243
- function_definition TEST @245-255
- function_definition TEST @262-274
- function_definition TEST @276-288
- function_definition TEST @290-302
- function_definition TEST @304-316
- function_definition TEST @318-332
- function_definition TEST @334-346
- function_definition TEST @348-356

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_h265.cc

Blob: `fe8fcfd565301fc765313737eb7b7b5c52693a08`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_h265.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <cstring> @16
- include <span> @17
- include <vector> @18
- include "common_video/h264/h264_common.h" @20
- include "common_video/h265/h265_common.h" @21
- include "modules/rtp_rtcp/source/byte_io.h" @22
- include "modules/rtp_rtcp/source/rtp_format.h" @23
- include "modules/rtp_rtcp/source/rtp_packet_h265_common.h" @24
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @25
- include "rtc_base/checks.h" @26
- function_definition RtpPacketizerH265 @30-52
- function_definition ~RtpPacketizerH265 @54-54
- function_definition NumPackets @56-58
- function_definition GeneratePackets @60-83
- function_definition PacketizeFu @85-146
- function_definition PacketizeAp @148-203
- function_definition NextPacket @205-228
- function_definition NextAggregatePacket @230-284
- function_definition NextFragmentPacket @286-337

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_h265.h

Blob: `d3fca2e584e040f4ddd46744e999ab295cdfb5e4`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @14
- include <cstdint> @15
- include <deque> @16
- include <queue> @17
- include <span> @18
- include "modules/rtp_rtcp/source/rtp_format.h" @20
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @21
- class_specifier RtpPacketizerH265 @25-64
- function_definition RtpPacketizerH265 @32-32
- function_definition (anonymous) @33-33
- struct_specifier PacketUnit @45-51

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_h265_unittest.cc

Blob: `20634a977db9c3fd953ad3149dee95577b9a2e38`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_h265.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <initializer_list> @16
- include <span> @17
- include <vector> @18
- include "absl/algorithm/container.h" @20
- include "common_video/h265/h265_common.h" @21
- include "modules/rtp_rtcp/source/rtp_format.h" @22
- include "modules/rtp_rtcp/source/rtp_packet_h265_common.h" @23
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @24
- include "rtc_base/buffer.h" @25
- include "rtc_base/checks.h" @26
- include "test/gmock.h" @27
- include "test/gtest.h" @28
- struct_specifier NalUnitHeader @47-52
- function_definition GenerateNalUnit @55-70
- function_definition CreateFrame @73-97
- function_definition CreateFrame @100-121
- function_definition FetchAllPackets @123-133
- function_definition TEST @136-144
- function_definition TEST @146-165
- function_definition TEST @167-193
- function_definition TEST @195-221
- function_definition TEST @223-234
- function_definition TEST @236-247
- function_definition TEST @250-293
- function_definition TEST @295-347
- function_definition TEST @349-360
- function_definition TEST @362-397
- function_definition TEST @399-438
- function_definition TEST @440-463
- function_definition TEST @465-495
- function_definition TEST @497-514
- function_definition TestFu @518-551
- function_definition TEST @554-558
- function_definition TEST @560-566
- function_definition TEST @568-574
- function_definition TEST @576-581
- function_definition TEST @583-587
- function_definition TEST @589-594
- function_definition TEST @596-603
- function_definition TEST @606-611
- struct_specifier PacketInfo @613-621
- struct_specifier MixedApFuTestParams @623-627
- class_specifier RtpPacketizerH265ParametrizedTest @629-630
- function_definition TEST_P @633-684
- function_definition TEST @730-736
- function_definition TEST @738-744

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_sframe.cc

Blob: `9c5aa8ae69827f474c0cd1b44f89bc796a8deb90`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_sframe.h" @11
- include <algorithm> @13
- include <bitset> @14
- include <cstddef> @15
- include <cstdint> @16
- include <span> @17
- include <utility> @18
- include "api/media_types.h" @20
- include "api/rtc_error.h" @21
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @22
- include "modules/rtp_rtcp/source/sframe_descriptor.h" @23
- include "rtc_base/checks.h" @24
- function_definition GetSframeStartAndEndBits @32-39
- function_definition BuildDescriptorByte @41-50
- function_definition PacketizeSframeRtpPacketOrError @54-91

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_sframe.h

Blob: `560ebf7d35ab5c86ec8eb35aa09f5c507a1ffea1`. Grammar: cpp. Status: syntax-clean.

- include "api/media_types.h" @14
- include "api/rtc_error.h" @15
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @16
- include "modules/rtp_rtcp/source/sframe_descriptor.h" @17

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_packetizer_sframe_unittest.cc

Blob: `41039d179c1b57e8461bc31e7e2e839aa9b5239a`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_packetizer_sframe.h" @11
- include <bitset> @13
- include <cstddef> @14
- include <cstdint> @15
- include <vector> @16
- include "api/media_types.h" @18
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @19
- include "modules/rtp_rtcp/source/sframe_descriptor.h" @20
- include "test/gmock.h" @21
- include "test/gtest.h" @22
- function_definition MakeDescriptorByte @29-35
- function_definition MakeSendPacket @37-44
- function_definition TEST @46-58
- function_definition TEST @60-69
- function_definition TEST @71-81
- function_definition TEST @83-93
- function_definition TEST @95-107
- function_definition TEST @109-118
- function_definition TEST @120-136
- function_definition TEST @138-148
- function_definition TEST @150-161
- function_definition TEST @163-178
- function_definition TEST @180-189

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_rtcp_config.h

Blob: `d69ae9420b9a3e3a91adff4c4f73c40aabcbe9de`. Grammar: cpp. Status: syntax-clean.

- include "api/units/time_delta.h" @14

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_rtcp_impl2.cc

Blob: `6da9a18f8ec84b2d6f5c6edadd6215383ed374e6`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_rtcp_impl2.h" @11
- include <cstdint> @13
- include <cstring> @14
- include <memory> @15
- include <optional> @16
- include <span> @17
- include <utility> @18
- include <vector> @19
- include "absl/functional/any_invocable.h" @21
- include "absl/strings/string_view.h" @22
- include "api/environment/environment.h" @23
- include "api/rtp_header_extension_id.h" @24
- include "api/rtp_headers.h" @25
- include "api/sequence_checker.h" @26
- include "api/task_queue/pending_task_safety_flag.h" @27
- include "api/task_queue/task_queue_base.h" @28
- include "api/units/time_delta.h" @29
- include "api/units/timestamp.h" @30
- include "modules/include/module_fec_types.h" @31
- include "modules/rtp_rtcp/include/report_block_data.h" @32
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @33
- include "modules/rtp_rtcp/source/ntp_time_util.h" @34
- include "modules/rtp_rtcp/source/rtcp_packet.h" @35
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @36
- include "modules/rtp_rtcp/source/rtcp_receiver.h" @37
- include "modules/rtp_rtcp/source/rtcp_sender.h" @38
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @39
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @40
- include "modules/rtp_rtcp/source/rtp_rtcp_config.h" @41
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @42
- include "modules/rtp_rtcp/source/rtp_sender.h" @43
- include "modules/rtp_rtcp/source/rtp_sequence_number_map.h" @44
- include "rtc_base/checks.h" @45
- include "rtc_base/logging.h" @46
- include "rtc_base/synchronization/mutex.h" @47
- include "rtc_base/task_utils/repeating_task.h" @48
- include "system_wrappers/include/ntp_time.h" @49
- function_definition RtpSenderContext::RtpSenderContext @62-77
- function_definition ModuleRtpRtcpImpl2 @79-147
- function_definition ~ModuleRtpRtcpImpl2 @149-152
- function_definition SetRtxSendStatus @154-156
- function_definition RtxSendStatus @158-160
- function_definition SetRtxSendPayloadType @162-166
- function_definition RtxSsrc @168-170
- function_definition FlexfecSsrc @172-177
- function_definition IncomingRtcpPacket @179-183
- function_definition RegisterSendPayloadFrequency @185-188
- function_definition DeRegisterSendPayload @190-193
- function_definition StartTimestamp @195-197
- function_definition SetStartTimestamp @200-204
- function_definition SequenceNumber @206-209
- function_definition SetSequenceNumber @212-218
- function_definition SetRtpState @220-226
- function_definition SetRtxState @228-232
- function_definition GetRtpState @234-239
- function_definition GetRtxState @241-246
- function_definition SetNonSenderRttMeasurement @248-251
- function_definition local_media_ssrc @253-257
- function_definition SetMid @259-265
- function_definition GetFeedbackState @269-301
- function_definition SetSendingStatus @303-309
- function_definition Sending @311-313
- function_definition SetSendingMediaStatus @315-317
- function_definition SendingMedia @319-321
- function_definition IsAudioConfigured @323-326
- function_definition SetAsPartOfAllocation @328-332
- function_definition OnSendingRtpFrame @334-365
- function_definition CanSendPacket @367-380
- function_definition AssignSequenceNumber @382-390
- function_definition SendPacket @392-397
- function_definition TrySendPacket @399-407
- function_definition OnBatchComplete @409-412
- function_definition SetFecProtectionParams @414-420
- function_definition FetchFecPackets @422-427
- function_definition OnAbortedRetransmissions @429-434
- function_definition OnPacketsAcknowledged @436-440
- function_definition SupportsPadding @442-445
- function_definition SupportsRtxPayloadPadding @447-450
- function_definition GeneratePadding @452-460
- function_definition GetSentRtpPacketInfos @462-467
- function_definition ExpectedPerPacketOverhead @469-474
- function_definition OnPacketSendingThreadSwitched @476-479
- function_definition MaxRtpPacketSize @481-484
- function_definition SetMaxRtpPacketSize @486-497
- function_definition RTCP @499-501
- function_definition SetRTCPStatus @504-506
- function_definition SetCNAME @508-510
- function_definition LastRtt @512-521
- function_definition ExpectedRetransmissionTime @523-534
- function_definition SendRTCP @538-540
- function_definition GetSendStreamDataCounters @542-546
- function_definition RemoteRTCPSenderInfo @549-554
- function_definition GetLatestReportBlockData @556-559
- function_definition GetSenderReportStats @561-564
- function_definition GetNonSenderRttStats @566-576
- function_definition SetRemb @579-582
- function_definition UnsetRemb @584-586
- function_definition SetExtmapAllowMixed @588-590
- function_definition RegisterRtpHeaderExtension @592-603
- function_definition DeregisterSendRtpHeaderExtension @605-608
- function_definition SetTmmbn @610-612
- function_definition SendNACK @615-648
- function_definition SendNack @650-653
- function_definition TimeToSendFullNackList @655-673
- function_definition SetStorePacketsStatus @676-682
- function_definition StorePackets @684-687
- function_definition SendCombinedRtcpPacket @689-692
- function_definition SendLossNotification @694-701
- function_definition SetRemoteSSRC @703-707
- function_definition GetSendRates @709-712
- function_definition OnRequestSendReport @714-716
- function_definition OnReceivedNack @718-734
- function_definition OnReceivedRtcpReportBlocks @736-755
- function_definition set_rtt_ms @757-766
- function_definition rtt_ms @768-771
- function_definition RtpSender @773-775
- function_definition RtpSender @777-779
- function_definition PeriodicUpdate @781-793
- function_definition MaybeSendRtcp @795-799
- function_definition MaybeSendRtcpAtOrAfterTimestamp @803-820
- function_definition ScheduleRtcpSendEvaluation @822-837
- function_definition ScheduleMaybeSendRtcpAtOrAfterTimestamp @839-853
- function_definition RtcpSenderSourceSsrc @855-861

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_rtcp_impl2.h

Blob: `aa8df0310fceb3c91d338496121a7096d5e4af2a`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @14
- include <stdint.h> @15
- include <memory> @17
- include <optional> @18
- include <span> @19
- include <utility> @20
- include <vector> @21
- include "absl/functional/any_invocable.h" @23
- include "absl/memory/memory.h" @24
- include "absl/strings/string_view.h" @25
- include "api/environment/environment.h" @26
- include "api/rtp_header_extension_id.h" @27
- include "api/rtp_headers.h" @28
- include "api/sequence_checker.h" @29
- include "api/task_queue/pending_task_safety_flag.h" @30
- include "api/task_queue/task_queue_base.h" @31
- include "api/units/time_delta.h" @32
- include "api/units/timestamp.h" @33
- include "modules/include/module_fec_types.h" @34
- include "modules/rtp_rtcp/include/report_block_data.h" @35
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @36
- include "modules/rtp_rtcp/source/packet_sequencer.h" @37
- include "modules/rtp_rtcp/source/rtcp_packet.h" @38
- include "modules/rtp_rtcp/source/rtcp_packet/tmmb_item.h" @39
- include "modules/rtp_rtcp/source/rtcp_receiver.h" @40
- include "modules/rtp_rtcp/source/rtcp_sender.h" @41
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @42
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @43
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @44
- include "modules/rtp_rtcp/source/rtp_sender.h" @45
- include "modules/rtp_rtcp/source/rtp_sender_egress.h" @46
- include "modules/rtp_rtcp/source/rtp_sequence_number_map.h" @47
- include "rtc_base/checks.h" @48
- include "rtc_base/gtest_prod_util.h" @49
- include "rtc_base/synchronization/mutex.h" @50
- include "rtc_base/system/no_unique_address.h" @51
- include "rtc_base/task_utils/repeating_task.h" @52
- include "rtc_base/thread_annotations.h" @53
- struct_specifier PacedPacketInfo @57-57
- struct_specifier RTPVideoHeader @58-58
- class_specifier ModuleRtpRtcpImpl2 @76-382
- function_definition CreateSendModule @79-85
- function_definition CreateReceiveModule @86-94
- function_definition SSRC @138-138
- struct_specifier RtpSenderContext @293-309

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_rtcp_impl2_unittest.cc

Blob: `77d0ece9a3a5df4087d8b85fdf67a62ffb4c9521`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_rtcp_impl2.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <map> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include <vector> @20
- include "absl/strings/string_view.h" @22
- include "api/call/transport.h" @23
- include "api/environment/environment.h" @24
- include "api/frame_transformer_interface.h" @25
- include "api/rtp_header_extension_id.h" @26
- include "api/rtp_headers.h" @27
- include "api/rtp_parameters.h" @28
- include "api/task_queue/task_queue_base.h" @29
- include "api/task_queue/task_queue_factory.h" @30
- include "api/units/time_delta.h" @31
- include "api/units/timestamp.h" @32
- include "api/video/video_codec_type.h" @33
- include "api/video/video_content_type.h" @34
- include "api/video/video_frame_type.h" @35
- include "api/video/video_rotation.h" @36
- include "modules/include/module_fec_types.h" @37
- include "modules/rtp_rtcp/include/flexfec_sender.h" @38
- include "modules/rtp_rtcp/include/receive_statistics.h" @39
- include "modules/rtp_rtcp/include/remote_ntp_time_estimator.h" @40
- include "modules/rtp_rtcp/include/report_block_data.h" @41
- include "modules/rtp_rtcp/include/rtcp_statistics.h" @42
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @43
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @44
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @45
- include "modules/rtp_rtcp/source/rtcp_packet/sender_report.h" @46
- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @47
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @48
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @49
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @50
- include "modules/rtp_rtcp/source/rtp_sender_video.h" @51
- include "modules/rtp_rtcp/source/rtp_sequence_number_map.h" @52
- include "modules/rtp_rtcp/source/ulpfec_generator.h" @53
- include "modules/rtp_rtcp/source/video_fec_generator.h" @54
- include "modules/video_coding/codecs/interface/common_constants.h" @55
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @56
- include "rtc_base/buffer.h" @57
- include "rtc_base/rate_limiter.h" @58
- include "system_wrappers/include/ntp_time.h" @59
- include "test/create_test_environment.h" @60
- include "test/gmock.h" @61
- include "test/gtest.h" @62
- include "test/near_matcher.h" @63
- include "test/rtcp_packet_parser.h" @64
- include "test/time_controller/simulated_time_controller.h" @65
- class_specifier RtcpRttStatsTestImpl @95-105
- function_definition RtcpRttStatsTestImpl @97-97
- function_definition ~RtcpRttStatsTestImpl @98-98
- function_definition OnRttUpdate @100-100
- function_definition LastProcessedRtt @101-101
- class_specifier SendTransport @107-161
- function_definition SendTransport @109-117
- function_definition ~SendTransport @119-119
- function_definition SetRtpRtcpModule @121-121
- function_definition SimulateNetworkDelay @122-122
- function_definition SendRtp @123-128
- function_definition SendRtcp @129-149
- function_definition NumRtcpSent @151-151
- class_specifier RtpRtcpModule @163-275
- struct_specifier SentPacket @167-173
- function_definition SentPacket @168-169
- function_definition RtpRtcpModule @175-181
- function_definition RtcpPacketTypesCounterUpdated @192-196
- function_definition OnSendPacket @198-204
- function_definition GetDataCounters @206-209
- function_definition DataCountersUpdated @210-213
- function_definition last_sent_packet @215-217
- function_definition RtcpSent @219-222
- function_definition RtcpReceived @224-227
- function_definition RtpSent @228-228
- function_definition LastRtpSequenceNumber @229-229
- function_definition LastNackListSent @230-232
- function_definition SetRtcpReportIntervalAndReset @233-236
- function_definition (anonymous) @237-237
- function_definition RegisterHeaderExtension @238-242
- function_definition ReinintWithFec @243-246
- function_definition CreateModuleImpl @248-267
- class_specifier RtpRtcpImpl2Test @278-394
- function_definition RtpRtcpImpl2Test @280-284
- function_definition SetUp @286-305
- function_definition AdvanceTime @307-309
- function_definition ReinitWithFec @311-328
- function_definition SendFrame @336-343
- function_definition SendFrame @345-380
- function_definition IncomingRtcpNack @382-393
- function_definition TEST_F @396-423
- function_definition TEST_F @425-454
- function_definition TEST_F @456-473
- function_definition TEST_F @475-490
- function_definition TEST_F @492-505
- function_definition TEST_F @507-547
- function_definition TEST_F @549-559
- function_definition TEST_F @561-583
- function_definition TEST_F @585-608
- function_definition TEST_F @610-648
- function_definition TEST_F @650-686
- function_definition TEST_F @688-716
- function_definition TEST_F @718-778
- function_definition TEST_F @781-783
- function_definition TEST_F @786-793
- function_definition TEST_F @797-810
- function_definition TEST_F @813-833
- function_definition TEST_F @836-850
- function_definition TEST_F @854-863
- function_definition TEST_F @867-881
- function_definition TEST_F @883-888
- function_definition TEST_F @890-896
- function_definition TEST_F @898-931
- function_definition TEST_F @933-952
- function_definition TEST_F @954-969
- function_definition TEST_F @971-977
- function_definition TEST_F @979-993
- function_definition TEST_F @995-1007
- function_definition TEST_F @1009-1040
- function_definition TEST_F @1042-1067
- function_definition TEST_F @1069-1115
- function_definition TEST_F @1117-1160
- function_definition TEST_F @1162-1170
- function_definition TEST_F @1172-1181
- function_definition TEST_F @1183-1192
- function_definition TEST_F @1194-1204
- function_definition TEST_F @1206-1215
- function_definition TEST_F @1217-1269

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_rtcp_interface.h

Blob: `f12d039c1a2feacd1f54eeffdb318a8a40fb1cc9`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <string> @19
- include <vector> @20
- include "absl/strings/string_view.h" @22
- include "api/frame_transformer_interface.h" @23
- include "api/rtp_header_extension_id.h" @24
- include "api/rtp_headers.h" @25
- include "api/rtp_packet_sender.h" @26
- include "api/scoped_refptr.h" @27
- include "api/transport/network_types.h" @28
- include "api/units/time_delta.h" @29
- include "api/units/timestamp.h" @30
- include "modules/include/module_fec_types.h" @31
- include "modules/rtp_rtcp/include/receive_statistics.h" @32
- include "modules/rtp_rtcp/include/report_block_data.h" @33
- include "modules/rtp_rtcp/include/rtcp_statistics.h" @34
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @35
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @36
- include "modules/rtp_rtcp/source/rtp_sequence_number_map.h" @37
- include "modules/rtp_rtcp/source/video_fec_generator.h" @38
- include "system_wrappers/include/ntp_time.h" @39
- class_specifier FrameEncryptorInterface @44-44
- class_specifier RateLimiter @45-45
- class_specifier RTPSender @46-46
- class_specifier Transport @47-47
- class_specifier RtpRtcpInterface @49-461
- struct_specifier Configuration @51-147
- struct_specifier SenderReportStats @151-174
- struct_specifier NonSenderRttStats @177-184
- function_definition SendPictureLossIndication @451-451
- function_definition SendFullIntraRequest @453-453

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender.cc

Blob: `5de673c2589456f816dc0708b70e035ec8d7a723`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <cstring> @16
- include <memory> @17
- include <optional> @18
- include <span> @19
- include <string> @20
- include <utility> @21
- include <vector> @22
- include "absl/strings/string_view.h" @24
- include "api/environment/environment.h" @25
- include "api/rtp_header_extension_id.h" @26
- include "api/rtp_headers.h" @27
- include "api/rtp_packet_sender.h" @28
- include "api/units/time_delta.h" @29
- include "api/units/timestamp.h" @30
- include "logging/rtc_event_log/events/rtc_event_rtp_packet_outgoing.h" @31
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @32
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @33
- include "modules/rtp_rtcp/source/byte_io.h" @34
- include "modules/rtp_rtcp/source/corruption_detection_extension.h" @35
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @36
- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @37
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @38
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @39
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @40
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @41
- include "rtc_base/checks.h" @42
- include "rtc_base/logging.h" @43
- include "rtc_base/numerics/safe_minmax.h" @44
- include "rtc_base/rate_limiter.h" @45
- include "rtc_base/synchronization/mutex.h" @46
- function_definition CreateExtensionSize @62-64
- function_definition CreateMaxExtensionSize @67-69
- function_definition IsNonVolatile @114-153
- function_definition HasBweExtension @155-160
- function_definition RTPSender @164-196
- function_definition ~RTPSender @198-208
- function_definition FecExtensionSizes @210-212
- function_definition VideoExtensionSizes @214-216
- function_definition AudioExtensionSizes @218-220
- function_definition SetExtmapAllowMixed @222-225
- function_definition RegisterRtpHeaderExtension @227-234
- function_definition IsRtpHeaderExtensionRegistered @236-239
- function_definition DeregisterRtpHeaderExtension @241-246
- function_definition SetMaxRtpPacketSize @248-253
- function_definition MaxRtpPacketSize @255-257
- function_definition SetRtxStatus @259-268
- function_definition RtxStatus @270-273
- function_definition SetRtxPayloadType @275-286
- function_definition ReSendPacket @288-334
- function_definition OnReceivedAckOnSsrc @336-344
- function_definition OnReceivedAckOnRtxSsrc @346-354
- function_definition OnReceivedNack @356-369
- function_definition SupportsPadding @371-374
- function_definition SupportsRtxPayloadPadding @376-380
- function_definition GeneratePadding @382-497
- function_definition EnqueuePackets @499-513
- function_definition FecOrPaddingPacketMaxRtpHeaderLength @515-518
- function_definition ExpectedPerPacketOverhead @520-523
- function_definition AllocatePacket @525-565
- function_definition RtxPacketOverhead @567-598
- function_definition SetSendingMediaStatus @600-603
- function_definition SendingMedia @605-608
- function_definition IsAudioConfigured @610-612
- function_definition SetTimestampOffset @614-617
- function_definition TimestampOffset @619-622
- function_definition SetMid @624-630
- function_definition CopyHeaderAndExtensionsToRtxPacket @632-677
- function_definition BuildRtxPacket @679-746
- function_definition SetRtpState @748-754
- function_definition GetRtpState @756-763
- function_definition SetRtxRtpState @765-768
- function_definition GetRtxRtpState @770-778
- function_definition UpdateHeaderSizes @780-830

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender.h

Blob: `cc2ab5e9c7f51596cdcce811511a68008c389c97`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <map> @16
- include <memory> @17
- include <optional> @18
- include <span> @19
- include <string> @20
- include <vector> @21
- include "absl/strings/string_view.h" @23
- include "api/environment/environment.h" @24
- include "api/rtp_header_extension_id.h" @25
- include "api/rtp_packet_sender.h" @26
- include "modules/rtp_rtcp/include/flexfec_sender.h" @27
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @28
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @29
- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @30
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @31
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @32
- include "rtc_base/random.h" @33
- include "rtc_base/synchronization/mutex.h" @34
- include "rtc_base/thread_annotations.h" @35
- class_specifier FrameEncryptorInterface @39-39
- class_specifier RateLimiter @40-40
- class_specifier RtpPacketToSend @41-41
- class_specifier RTPSender @46-214
- function_definition RTPSender @53-53
- function_definition (anonymous) @54-54
- function_definition RTC_LOCKS_EXCLUDED @108-110
- function_definition RTC_LOCKS_EXCLUDED @143-143
- function_definition RTC_LOCKS_EXCLUDED @145-145
- function_definition RTC_LOCKS_EXCLUDED @147-149
- function_definition RTC_GUARDED_BY @207-207

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_audio.cc

Blob: `2b829a4efeb380e8b90dea1a29f31ae03f464303`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender_audio.h" @11
- include <cstdint> @13
- include <cstring> @14
- include <memory> @15
- include <optional> @16
- include <utility> @17
- include <vector> @18
- include "absl/strings/match.h" @20
- include "absl/strings/string_view.h" @21
- include "api/rtp_headers.h" @22
- include "modules/audio_coding/include/audio_coding_module_typedefs.h" @23
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @24
- include "modules/rtp_rtcp/source/absolute_capture_time_sender.h" @25
- include "modules/rtp_rtcp/source/byte_io.h" @26
- include "modules/rtp_rtcp/source/dtmf_queue.h" @27
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @28
- include "modules/rtp_rtcp/source/rtp_packet.h" @29
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @30
- include "modules/rtp_rtcp/source/rtp_sender.h" @31
- include "rtc_base/checks.h" @32
- include "rtc_base/logging.h" @33
- include "rtc_base/numerics/safe_conversions.h" @34
- include "rtc_base/synchronization/mutex.h" @35
- include "system_wrappers/include/clock.h" @36
- function_definition RTPSenderAudio @40-45
- function_definition ~RTPSenderAudio @47-47
- function_definition RegisterAudioPayload @49-86
- function_definition MarkerBit @88-129
- function_definition SendAudio @131-273
- function_definition SendTelephoneEvent @276-292
- function_definition SendTelephoneEventPacket @294-342

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_audio.h

Blob: `b206ff2f5aabb3ca0242d726e990bb79da945f66`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @14
- include <stdint.h> @15
- include <optional> @17
- include <span> @18
- include "absl/strings/string_view.h" @20
- include "api/units/timestamp.h" @21
- include "modules/audio_coding/include/audio_coding_module_typedefs.h" @22
- include "modules/rtp_rtcp/source/absolute_capture_time_sender.h" @23
- include "modules/rtp_rtcp/source/dtmf_queue.h" @24
- include "modules/rtp_rtcp/source/rtp_sender.h" @25
- include "rtc_base/one_time_event.h" @26
- include "rtc_base/synchronization/mutex.h" @27
- include "rtc_base/thread_annotations.h" @28
- include "system_wrappers/include/clock.h" @29
- class_specifier RTPSenderAudio @33-117
- function_definition RTPSenderAudio @37-37
- function_definition RTPSenderAudio @38-38
- function_definition (anonymous) @39-39
- struct_specifier RtpAudioFrame @49-69

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_audio_unittest.cc

Blob: `5c4d4e5ae598d7f73566af5656d17f6190c83bfb`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender_audio.h" @11
- include <cstdint> @13
- include <memory> @14
- include <span> @15
- include <vector> @16
- include "api/call/transport.h" @18
- include "api/environment/environment.h" @19
- include "api/rtp_header_extension_id.h" @20
- include "api/rtp_headers.h" @21
- include "api/units/timestamp.h" @22
- include "modules/audio_coding/include/audio_coding_module_typedefs.h" @23
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @24
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @25
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @26
- include "modules/rtp_rtcp/source/rtp_rtcp_impl2.h" @27
- include "system_wrappers/include/clock.h" @28
- include "system_wrappers/include/ntp_time.h" @29
- include "test/create_test_environment.h" @30
- include "test/gmock.h" @31
- include "test/gtest.h" @32
- include "test/run_loop.h" @33
- class_specifier LoopbackTransportTest @47-71
- function_definition LoopbackTransportTest @49-53
- function_definition SendRtp @55-60
- function_definition SendRtcp @61-64
- function_definition (anonymous) @65-65
- function_definition packets_sent @66-66
- class_specifier RtpSenderAudioTest @75-97
- function_definition RtpSenderAudioTest @77-89
- function_definition TEST_F @99-111
- function_definition TEST_F @113-139
- function_definition TEST_F @141-157
- function_definition TEST_F @159-182
- function_definition TEST_F @190-232
- function_definition TEST_F @234-247

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_egress.cc

Blob: `d4d39c2bddae498114562741527838f141170daa`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender_egress.h" @11
- include <algorithm> @13
- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include <vector> @20
- include "api/call/transport.h" @22
- include "api/environment/environment.h" @23
- include "api/rtc_event_log/rtc_event_log.h" @24
- include "api/sequence_checker.h" @25
- include "api/task_queue/pending_task_safety_flag.h" @26
- include "api/task_queue/task_queue_base.h" @27
- include "api/transport/network_types.h" @28
- include "api/units/data_rate.h" @29
- include "api/units/time_delta.h" @30
- include "api/units/timestamp.h" @31
- include "logging/rtc_event_log/events/rtc_event_rtp_packet_outgoing.h" @32
- include "modules/include/module_fec_types.h" @33
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @34
- include "modules/rtp_rtcp/source/packet_sequencer.h" @35
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @36
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @37
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @38
- include "modules/rtp_rtcp/source/rtp_sequence_number_map.h" @39
- include "rtc_base/bitrate_tracker.h" @40
- include "rtc_base/checks.h" @41
- include "rtc_base/copy_on_write_buffer.h" @42
- include "rtc_base/logging.h" @43
- include "rtc_base/task_utils/repeating_task.h" @44
- function_definition NonPacedPacketSender::NonPacedPacketSender @54-63
- function_definition NonPacedPacketSender::~NonPacedPacketSender @64-66
- function_definition NonPacedPacketSender::EnqueuePackets @68-86
- function_definition NonPacedPacketSender::PrepareForSend @88-102
- function_definition RtpSenderEgress @104-139
- function_definition ~RtpSenderEgress @141-144
- function_definition SendPacket @146-253
- function_definition OnBatchComplete @255-261
- function_definition CompleteSendPacket @263-325
- function_definition GetSendRates @327-335
- function_definition GetDataCounters @337-349
- function_definition ForceIncludeSendPacketsInAllocation @351-355
- function_definition MediaHasBeenSent @357-360
- function_definition SetMediaHasBeenSent @362-365
- function_definition SetTimestampOffset @367-370
- function_definition GetSentRtpPacketInfos @372-394
- function_definition SetFecProtectionParameters @396-401
- function_definition FetchFecPackets @403-410
- function_definition OnAbortedRetransmissions @412-421
- function_definition HasCorrectSsrc @423-438
- function_definition SendPacketToNetwork @440-452
- function_definition UpdateRtpStats @454-498
- function_definition PeriodicUpdate @500-507

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_egress.h

Blob: `35779a4bbd62c35e00646b1d23fcf7b425b7ec1b`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include <vector> @20
- include "api/call/transport.h" @22
- include "api/environment/environment.h" @23
- include "api/rtp_packet_sender.h" @24
- include "api/task_queue/pending_task_safety_flag.h" @25
- include "api/task_queue/task_queue_base.h" @26
- include "api/transport/network_types.h" @27
- include "api/units/timestamp.h" @28
- include "modules/include/module_fec_types.h" @29
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @30
- include "modules/rtp_rtcp/source/packet_sequencer.h" @31
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @32
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @33
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @34
- include "modules/rtp_rtcp/source/rtp_sequence_number_map.h" @35
- include "modules/rtp_rtcp/source/video_fec_generator.h" @36
- include "rtc_base/bitrate_tracker.h" @37
- include "rtc_base/task_utils/repeating_task.h" @38
- include "rtc_base/thread_annotations.h" @39
- class_specifier RtpSenderEgress @43-168
- class_specifier NonPacedPacketSender @47-66
- function_definition RemovePacketsForSsrc @57-57
- function_definition Ssrc @76-76
- function_definition RtxSsrc @77-77
- function_definition FlexFecSsrc @78-78
- struct_specifier Packet @106-110

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_egress_unittest.cc

Blob: `68476ca7a2d31c3a179493cc67468bd7d9f10671`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtp_sender_egress.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <map> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include "api/call/transport.h" @21
- include "api/environment/environment.h" @22
- include "api/rtp_header_extension_id.h" @23
- include "api/transport/network_types.h" @24
- include "api/units/data_size.h" @25
- include "api/units/time_delta.h" @26
- include "api/units/timestamp.h" @27
- include "api/video/video_timing.h" @28
- include "modules/rtp_rtcp/include/flexfec_sender.h" @29
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @30
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @31
- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @32
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @33
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @34
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @35
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @36
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @37
- include "rtc_base/checks.h" @38
- include "test/create_test_environment.h" @39
- include "test/gmock.h" @40
- include "test/gtest.h" @41
- include "test/time_controller/simulated_time_controller.h" @42
- class_specifier MockSendPacketObserver @66-72
- class_specifier MockStreamDataCountersCallback @74-91
- function_definition GetDataCounters @80-83
- function_definition DataCountersUpdated @84-88
- struct_specifier TransmittedPacket @93-102
- function_definition TransmittedPacket @94-99
- class_specifier TestTransport @104-128
- function_definition TestTransport @106-107
- function_definition SendRtp @109-115
- function_definition SendRtcp @117-120
- function_definition last_packet @122-122
- class_specifier RtpSenderEgressTest @132-189
- function_definition RtpSenderEgressTest @134-140
- function_definition CreateRtpSenderEgress @142-145
- function_definition DefaultConfig @147-158
- function_definition BuildRtpPacket @160-175
- function_definition BuildRtpPacket @177-179
- function_definition TEST_F @191-197
- function_definition TEST_F @199-211
- function_definition TEST_F @213-227
- function_definition TEST_F @229-243
- function_definition TEST_F @245-252
- function_definition TEST_F @254-264
- function_definition TEST_F @266-277
- function_definition TEST_F @279-288
- function_definition TEST_F @290-308
- function_definition TEST_F @310-328
- function_definition TEST_F @330-354
- function_definition TEST_F @356-371
- function_definition TEST_F @373-385
- function_definition TEST_F @387-394
- function_definition TEST_F @396-409
- function_definition TEST_F @411-440
- function_definition TEST_F @442-487
- class_specifier MockBitrateStaticsObserver @443-446
- function_definition TEST_F @489-499
- function_definition TEST_F @501-511
- function_definition TEST_F @513-542
- function_definition TEST_F @544-567
- function_definition TEST_F @569-651
- function_definition TEST_F @653-701
- function_definition TEST_F @703-749
- function_definition TEST_F @751-778
- function_definition TEST_F @780-809
- function_definition TEST_F @811-831
- function_definition TEST_F @833-849
- function_definition TEST_F @851-914
- function_definition TEST_F @916-941

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_unittest.cc

Blob: `ab678609db6af117768eb32563439b5a8f91e4fd`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtp_sender.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <memory> @15
- include <optional> @16
- include <string> @17
- include <utility> @18
- include <vector> @19
- include "absl/strings/string_view.h" @21
- include "api/environment/environment.h" @22
- include "api/frame_transformer_interface.h" @23
- include "api/rtp_header_extension_id.h" @24
- include "api/rtp_packet_sender.h" @25
- include "api/rtp_parameters.h" @26
- include "api/units/frequency.h" @27
- include "api/units/time_delta.h" @28
- include "api/units/timestamp.h" @29
- include "api/video/video_codec_type.h" @30
- include "api/video/video_frame_type.h" @31
- include "modules/rtp_rtcp/include/flexfec_sender.h" @32
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @33
- include "modules/rtp_rtcp/source/packet_sequencer.h" @34
- include "modules/rtp_rtcp/source/rtp_format_video_generic.h" @35
- include "modules/rtp_rtcp/source/rtp_header_extension_size.h" @36
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @37
- include "modules/rtp_rtcp/source/rtp_packet_history.h" @38
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @39
- include "modules/rtp_rtcp/source/rtp_rtcp_interface.h" @40
- include "modules/rtp_rtcp/source/rtp_sender_video.h" @41
- include "modules/rtp_rtcp/source/video_fec_generator.h" @42
- include "rtc_base/rate_limiter.h" @43
- include "test/create_test_environment.h" @44
- include "test/gmock.h" @45
- include "test/gtest.h" @46
- include "test/time_controller/simulated_time_controller.h" @47
- class_specifier MockRtpPacketPacer @90-100
- function_definition MockRtpPacketPacer @92-92
- function_definition ~MockRtpPacketPacer @93-93
- function_definition ToRtpTimestamp @102-105
- class_specifier RtpSenderTest @109-262
- function_definition RtpSenderTest @111-122
- function_definition SetUp @124-124
- function_definition SetUpRtpSender @126-134
- function_definition GetDefaultConfig @136-146
- function_definition CreateSender @148-158
- function_definition BuildRtpPacket @170-181
- function_definition SendPacket @183-196
- function_definition SendGenericPacket @198-205
- function_definition GeneratePadding @207-212
- function_definition Sequence @214-220
- function_definition GenerateAndSendPadding @222-231
- function_definition EnableRtx @237-245
- function_definition EnableMidSending @249-252
- function_definition EnableRidSending @256-261
- function_definition TEST_F @264-273
- function_definition TEST_F @275-298
- function_definition TEST_F @300-330
- function_definition TEST_F @332-344
- function_definition TEST_F @346-363
- function_definition TEST_F @367-406
- function_definition TEST_F @408-422
- function_definition TEST_F @424-434
- function_definition TEST_F @436-445
- function_definition TEST_F @447-458
- function_definition TEST_F @460-479
- function_definition TEST_F @481-500
- function_definition TEST_F @502-531
- function_definition TEST_F @533-566
- function_definition TEST_F @570-580
- function_definition TEST_F @582-589
- function_definition TEST_F @591-613
- function_definition TEST_F @615-635
- function_definition TEST_F @637-653
- function_definition TEST_F @659-685
- function_definition TEST_F @690-728
- function_definition TEST_F @730-771
- function_definition TEST_F @775-790
- function_definition TEST_F @795-818
- function_definition TEST_F @820-863
- function_definition TEST_F @865-877
- function_definition TEST_F @879-893
- function_definition TEST_F @895-915
- function_definition TEST_F @917-948
- function_definition TEST_F @950-977
- function_definition TEST_F @979-1007
- function_definition TEST_F @1009-1034
- function_definition TEST_F @1036-1076
- function_definition TEST_F @1078-1100
- function_definition TEST_F @1102-1113
- function_definition TEST_F @1115-1161
- function_definition TEST_F @1163-1202
- function_definition TEST_F @1204-1250
- function_definition TEST_F @1252-1288
- function_definition TEST_F @1290-1310
- function_definition TEST_F @1312-1330
- function_definition TEST_F @1332-1359
- function_definition TEST_F @1361-1408

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_video.cc

Blob: `940496c1d010e24ab48b09c754faf29e24852451`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender_video.h" @11
- include <cstdint> @13
- include <cstdlib> @14
- include <cstring> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include <variant> @20
- include <vector> @21
- include "absl/algorithm/container.h" @23
- include "absl/memory/memory.h" @24
- include "api/crypto/frame_encryptor_interface.h" @25
- include "api/field_trials_view.h" @26
- include "api/frame_transformer_interface.h" @27
- include "api/make_ref_counted.h" @28
- include "api/media_types.h" @29
- include "api/task_queue/task_queue_factory.h" @30
- include "api/transport/rtp/corruption_detection_message.h" @31
- include "api/transport/rtp/dependency_descriptor.h" @32
- include "api/units/data_rate.h" @33
- include "api/units/frequency.h" @34
- include "api/units/time_delta.h" @35
- include "api/units/timestamp.h" @36
- include "api/video/encoded_image.h" @37
- include "api/video/video_codec_type.h" @38
- include "api/video/video_content_type.h" @39
- include "api/video/video_frame_type.h" @40
- include "api/video/video_layers_allocation.h" @41
- include "api/video/video_rotation.h" @42
- include "api/video/video_timing.h" @43
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @44
- include "modules/rtp_rtcp/source/absolute_capture_time_sender.h" @45
- include "modules/rtp_rtcp/source/corruption_detection_extension.h" @46
- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h" @47
- include "modules/rtp_rtcp/source/rtp_descriptor_authentication.h" @48
- include "modules/rtp_rtcp/source/rtp_format.h" @49
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @50
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @51
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @52
- include "modules/rtp_rtcp/source/rtp_packet_to_send.h" @53
- include "modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate.h" @54
- include "modules/rtp_rtcp/source/rtp_video_header.h" @55
- include "modules/rtp_rtcp/source/rtp_video_layers_allocation_extension.h" @56
- include "modules/rtp_rtcp/source/video_fec_generator.h" @57
- include "modules/video_coding/codecs/h264/include/h264_globals.h" @58
- include "modules/video_coding/codecs/interface/common_constants.h" @59
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @60
- include "modules/video_coding/codecs/vp9/include/vp9_globals.h" @61
- include "rtc_base/buffer.h" @62
- include "rtc_base/checks.h" @63
- include "rtc_base/experiments/field_trial_parser.h" @64
- include "rtc_base/logging.h" @65
- include "rtc_base/race_checker.h" @66
- include "rtc_base/synchronization/mutex.h" @67
- include "system_wrappers/include/ntp_time.h" @68
- function_definition BuildRedPayload @79-89
- function_definition MinimizeDescriptor @91-102
- function_definition IsBaseLayer @104-134
- function_definition LoadVideoPlayoutDelayOverride @136-148
- function_definition PacketWillLikelyBeRequestedForRestransmissionIfLost @152-160
- function_definition GetPacketizationFormat @162-182
- function_definition RTPSenderVideo @186-223
- function_definition ~RTPSenderVideo @225-228
- function_definition LogAndSendToNetwork @230-250
- function_definition FecPacketOverhead @252-270
- function_definition SetRetransmissionSetting @272-275
- function_definition SetVideoStructure @277-284
- function_definition SetVideoStructureAfterTransformation @286-289
- function_definition SetVideoStructureInternal @291-319
- function_definition SetVideoLayersAllocation @321-329
- function_definition SetVideoLayersAllocationAfterTransformation @331-334
- function_definition SetVideoLayersAllocationInternal @336-360
- function_definition AddRtpHeaderExtensions @362-520
- function_definition SendVideo @522-535
- function_definition SendVideoFrame @537-846
- function_definition SendEncodedImage @848-866
- function_definition PostEncodeOverhead @868-872
- function_definition AllowRetransmission @874-898
- function_definition GetTemporalId @900-913
- struct_specifier TemporalIdGetter @901-911
- function_definition operator() @902-902
- function_definition operator() @903-905
- function_definition operator() @906-906
- function_definition operator() @907-909
- function_definition operator() @910-910
- function_definition UpdateConditionalRetransmit @915-957
- function_definition MaybeUpdateCurrentPlayoutDelay @959-971

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_video.h

Blob: `0bba6be56b567897697964ab082aa7a62b08c5f0`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <map> @16
- include <memory> @17
- include <optional> @18
- include <span> @19
- include <vector> @20
- include "api/field_trials_view.h" @22
- include "api/frame_transformer_interface.h" @23
- include "api/scoped_refptr.h" @24
- include "api/task_queue/task_queue_factory.h" @25
- include "api/transport/rtp/dependency_descriptor.h" @26
- include "api/units/data_rate.h" @27
- include "api/units/time_delta.h" @28
- include "api/units/timestamp.h" @29
- include "api/video/color_space.h" @30
- include "api/video/encoded_image.h" @31
- include "api/video/video_codec_type.h" @32
- include "api/video/video_layers_allocation.h" @33
- include "api/video/video_rotation.h" @34
- include "api/video/video_timing.h" @35
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @36
- include "modules/rtp_rtcp/source/absolute_capture_time_sender.h" @37
- include "modules/rtp_rtcp/source/active_decode_targets_helper.h" @38
- include "modules/rtp_rtcp/source/rtp_sender.h" @39
- include "modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate.h" @40
- include "modules/rtp_rtcp/source/rtp_video_header.h" @41
- include "modules/rtp_rtcp/source/video_fec_generator.h" @42
- include "rtc_base/bitrate_tracker.h" @43
- include "rtc_base/frequency_tracker.h" @44
- include "rtc_base/one_time_event.h" @45
- include "rtc_base/race_checker.h" @46
- include "rtc_base/synchronization/mutex.h" @47
- include "rtc_base/thread_annotations.h" @48
- include "system_wrappers/include/clock.h" @49
- class_specifier FrameEncryptorInterface @53-53
- class_specifier RtpPacketizer @54-54
- class_specifier RtpPacketToSend @55-55
- enum_specifier RetransmissionMode @61-67
- class_specifier RTPSenderVideo @69-275
- struct_specifier Config @73-94
- function_definition Config @74-74
- function_definition Config @75-75
- function_definition Config @76-76
- struct_specifier TemporalLayerStats @174-177
- enum_specifier SendVideoLayersAllocation @179-183
- function_definition red_enabled @201-201

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate.cc

Blob: `fd068e7f659befda2f93ffca7d8b51809f000f00`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate.h" @11
- include <cstddef> @13
- include <cstdint> @14
- include <memory> @15
- include <optional> @16
- include <span> @17
- include <string> @18
- include <utility> @19
- include <variant> @20
- include <vector> @21
- include "api/frame_transformer_interface.h" @23
- include "api/scoped_refptr.h" @24
- include "api/sequence_checker.h" @25
- include "api/task_queue/task_queue_factory.h" @26
- include "api/transport/rtp/dependency_descriptor.h" @27
- include "api/units/time_delta.h" @28
- include "api/units/timestamp.h" @29
- include "api/video/encoded_image.h" @30
- include "api/video/video_codec_type.h" @31
- include "api/video/video_frame_metadata.h" @32
- include "api/video/video_frame_type.h" @33
- include "api/video/video_layers_allocation.h" @34
- include "api/video_codecs/video_codec.h" @35
- include "modules/rtp_rtcp/source/rtp_video_header.h" @36
- include "rtc_base/checks.h" @37
- include "rtc_base/event.h" @38
- include "rtc_base/synchronization/mutex.h" @39
- class_specifier TransformableVideoSenderFrame @51-192
- function_definition TransformableVideoSenderFrame @53-71
- function_definition TransformableVideoSenderFrame @73-98
- function_definition ~TransformableVideoSenderFrame @100-100
- function_definition GetData @103-103
- function_definition SetData @105-107
- function_definition GetPreTransformPayloadSize @109-111
- function_definition GetTimestamp @113-118
- function_definition GetRtpTimestampInfo @119-121
- function_definition SetRTPTimestamp @122-124
- function_definition GetSsrc @126-126
- function_definition IsKeyFrame @128-130
- function_definition Rid @132-132
- function_definition Metadata @134-139
- function_definition SetMetadata @141-145
- function_definition (anonymous) @147-147
- function_definition GetPayloadType @148-148
- function_definition GetCodecType @149-149
- function_definition GetCaptureTimeIdentifier @150-152
- function_definition GetPresentationTimestamp @153-155
- function_definition GetExpectedRetransmissionTime @157-159
- function_definition GetDirection @161-161
- function_definition GetMimeType @162-165
- function_definition ReceiveTime @167-167
- function_definition CaptureTime @169-171
- function_definition SenderCaptureTimeOffset @173-175
- function_definition RTPSenderVideoFrameTransformerDelegate @194-207
- function_definition Init @209-212
- function_definition TransformFrame @214-237
- function_definition OnTransformedFrame @239-252
- function_definition StartShortCircuiting @254-257
- function_definition SendVideo @259-296
- function_definition SetVideoStructureUnderLock @298-303
- function_definition SetVideoLayersAllocationUnderLock @305-310
- function_definition Reset @312-327
- function_definition CloneSenderVideoFrame @329-349
- function_definition CreateSenderVideoFrame @351-361

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate.h

Blob: `5cf5e4532d8ac6b61060e29846760c9845e4b7d6`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <span> @17
- include <string> @18
- include <vector> @19
- include "api/frame_transformer_interface.h" @21
- include "api/scoped_refptr.h" @22
- include "api/sequence_checker.h" @23
- include "api/task_queue/task_queue_base.h" @24
- include "api/task_queue/task_queue_factory.h" @25
- include "api/transport/rtp/dependency_descriptor.h" @26
- include "api/units/time_delta.h" @27
- include "api/units/timestamp.h" @28
- include "api/video/encoded_image.h" @29
- include "api/video/video_codec_type.h" @30
- include "api/video/video_layers_allocation.h" @31
- include "modules/rtp_rtcp/source/rtp_video_header.h" @32
- include "rtc_base/synchronization/mutex.h" @33
- include "rtc_base/thread_annotations.h" @34
- class_specifier RTPVideoFrameSenderInterface @40-68
- function_definition ~RTPVideoFrameSenderInterface @67-67
- class_specifier RTPSenderVideoFrameTransformerDelegate @73-136
- function_definition ~RTPSenderVideoFrameTransformerDelegate @122-122

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate_unittest.cc

Blob: `ead7075ff972ba8db5d5e3a8f0a2aae6b1e94f6d`. Grammar: cpp. Status: contains-errors.

- include "modules/rtp_rtcp/source/rtp_sender_video_frame_transformer_delegate.h" @11
- include <array> @13
- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <string> @19
- include <utility> @20
- include <variant> @21
- include <vector> @22
- include "api/frame_transformer_interface.h" @24
- include "api/make_ref_counted.h" @25
- include "api/scoped_refptr.h" @26
- include "api/test/mock_frame_transformer.h" @27
- include "api/test/mock_transformable_video_frame.h" @28
- include "api/transport/rtp/dependency_descriptor.h" @29
- include "api/units/time_delta.h" @30
- include "api/units/timestamp.h" @31
- include "api/video/encoded_image.h" @32
- include "api/video/video_codec_type.h" @33
- include "api/video/video_frame_metadata.h" @34
- include "api/video/video_frame_type.h" @35
- include "api/video/video_layers_allocation.h" @36
- include "modules/rtp_rtcp/source/rtp_video_header.h" @37
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @38
- include "rtc_base/event.h" @39
- include "test/gmock.h" @40
- include "test/gtest.h" @41
- include "test/time_controller/simulated_time_controller.h" @42
- class_specifier MockRTPVideoFrameSenderInterface @54-90
- class_specifier RtpSenderVideoFrameTransformerDelegateTest @92-129
- function_definition RtpSenderVideoFrameTransformerDelegateTest @94-96
- function_definition ~RtpSenderVideoFrameTransformerDelegateTest @98-98
- function_definition GetTransformableFrame @100-124
- function_definition TEST_F @131-140
- function_definition TEST_F @142-151
- function_definition TEST_F @153-179
- function_definition TEST_F @181-208
- function_definition TEST_F @210-237
- function_definition TEST_F @239-266
- function_definition TEST_F @268-294
- function_definition TEST_F @296-345
- function_definition TEST_F @347-369
- function_definition TEST_F @371-396
- function_definition TEST_F @398-432

### third_party/libwebrtc/modules/rtp_rtcp/source/rtp_sender_video_unittest.cc

Blob: `ed2aafc2ec52f260b6e62a018ef0864aedba7da4`. Grammar: cpp. Status: syntax-clean.

- include "modules/rtp_rtcp/source/rtp_sender_video.h" @11
- include <array> @13
- include <cstddef> @14
- include <cstdint> @15
- include <memory> @16
- include <optional> @17
- include <span> @18
- include <utility> @19
- include <vector> @20
- include "absl/memory/memory.h" @22
- include "api/call/transport.h" @23
- include "api/environment/environment.h" @24
- include "api/field_trials_view.h" @25
- include "api/frame_transformer_factory.h" @26
- include "api/frame_transformer_interface.h" @27
- include "api/make_ref_counted.h" @28
- include "api/rtp_header_extension_id.h" @29
- include "api/rtp_headers.h" @30
- include "api/scoped_refptr.h" @31
- include "api/task_queue/task_queue_base.h" @32
- include "api/task_queue/task_queue_factory.h" @33
- include "api/test/mock_frame_encryptor.h" @34
- include "api/test/mock_frame_transformer.h" @35
- include "api/transport/rtp/corruption_detection_message.h" @36
- include "api/transport/rtp/dependency_descriptor.h" @37
- include "api/units/data_rate.h" @38
- include "api/units/time_delta.h" @39
- include "api/units/timestamp.h" @40
- include "api/video/corruption_detection/frame_instrumentation_data.h" @41
- include "api/video/encoded_image.h" @42
- include "api/video/video_codec_constants.h" @43
- include "api/video/video_codec_type.h" @44
- include "api/video/video_frame_type.h" @45
- include "api/video/video_layers_allocation.h" @46
- include "api/video/video_rotation.h" @47
- include "api/video/video_timing.h" @48
- include "modules/rtp_rtcp/include/rtp_cvo.h" @49
- include "modules/rtp_rtcp/include/rtp_header_extension_map.h" @50
- include "modules/rtp_rtcp/include/rtp_rtcp_defines.h" @51
- include "modules/rtp_rtcp/source/corruption_detection_extension.h" @52
- include "modules/rtp_rtcp/source/rtcp_packet/nack.h" @53
- include "modules/rtp_rtcp/source/rtcp_packet/receiver_report.h" @54
- include "modules/rtp_rtcp/source/rtcp_packet/report_block.h" @55
- include "modules/rtp_rtcp/source/rtp_dependency_descriptor_extension.h" @56
- include "modules/rtp_rtcp/source/rtp_format_video_generic.h" @57
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor.h" @58
- include "modules/rtp_rtcp/source/rtp_generic_frame_descriptor_extension.h" @59
- include "modules/rtp_rtcp/source/rtp_header_extensions.h" @60
- include "modules/rtp_rtcp/source/rtp_packet.h" @61
- include "modules/rtp_rtcp/source/rtp_packet_received.h" @62
- include "modules/rtp_rtcp/source/rtp_rtcp_impl2.h" @63
- include "modules/rtp_rtcp/source/rtp_sender.h" @64
- include "modules/rtp_rtcp/source/rtp_video_layers_allocation_extension.h" @65
- include "modules/video_coding/codecs/h264/include/h264_globals.h" @66
- include "modules/video_coding/codecs/vp8/include/vp8_globals.h" @67
- include "modules/video_coding/codecs/vp9/include/vp9_globals.h" @68
- include "rtc_base/checks.h" @69
- include "rtc_base/rate_limiter.h" @70
- include "system_wrappers/include/clock.h" @71
- include "system_wrappers/include/ntp_time.h" @72
- include "test/create_test_environment.h" @73
- include "test/gmock.h" @74
- include "test/gtest.h" @75
- include "test/run_loop.h" @76
- include "test/time_controller/simulated_time_controller.h" @77
- class_specifier LoopbackTransportTest @122-167
- function_definition LoopbackTransportTest @124-146
- function_definition SendRtp @148-153
- function_definition SendRtcp @154-157
- function_definition (anonymous) @158-158
- function_definition packets_sent @159-159
- function_definition (anonymous) @160-162
- class_specifier TestRtpSenderVideo @169-192
- function_definition TestRtpSenderVideo @171-182
- function_definition ~TestRtpSenderVideo @183-183
- function_definition AllowRetransmission @185-191
- class_specifier RtpSenderVideoTest @194-227
- function_definition RtpSenderVideoTest @196-214
- function_definition TEST_F @229-245
- function_definition TEST_F @247-273
- function_definition TEST_F @275-311
- function_definition TEST_F @313-344
- function_definition TEST_F @346-368
- function_definition TEST_F @370-391
- function_definition TEST_F @395-412
- function_definition TEST_F @414-427
- function_definition TEST_F @429-444
- function_definition TEST_F @446-467
- function_definition TEST_F @469-487
- function_definition TEST_F @489-507
- function_definition TEST_F @509-558
- function_definition TEST_F @560-589
- function_definition TEST_F @591-657
- function_definition TEST_F @659-727
- function_definition TEST_F @729-783
- function_definition TEST_F @785-817
- function_definition TEST_F @819-852
- function_definition TEST_F @854-929
- function_definition TEST_F @931-973
- function_definition TEST_F @975-1002
- function_definition UsesMinimalVp8DescriptorWhenGenericFrameDescriptorExtensionIsUsed @1004-1032
- function_definition TEST_F @1034-1037
- function_definition TEST_F @1039-1042
- function_definition TEST_F @1044-1080
- function_definition TEST_F @1082-1131
- function_definition TEST_F @1133-1179
- function_definition TEST_F @1181-1223
- function_definition TEST_F @1225-1266
- function_definition TEST_F @1268-1311
- function_definition TEST_F @1313-1349
- function_definition TEST_F @1351-1368
- function_definition TEST_F @1370-1406
- function_definition TEST_F @1408-1440
- function_definition TEST_F @1442-1503
- function_definition TEST_F @1505-1538
- function_definition TEST_F @1540-1556
- class_specifier RtpSenderVideoRawPacketizationTest @1558-1561
- function_definition RtpSenderVideoRawPacketizationTest @1560-1560
- function_definition TEST_F @1563-1578
- function_definition TEST_F @1580-1596
- class_specifier RtpSenderVideoWithFrameTransformerTest @1598-1631
- function_definition RtpSenderVideoWithFrameTransformerTest @1600-1612
- function_definition CreateSenderWithFrameTransformer @1614-1623
- function_definition CreateDefaultEncodedImage @1633-1638
- function_definition TEST_F @1640-1648
- function_definition TEST_F @1650-1659
- function_definition TEST_F @1661-1674
- function_definition TEST_F @1676-1689
- function_definition TEST_F @1691-1723
- function_definition TEST_F @1726-1748
- function_definition TEST_F @1751-1785
- function_definition TEST_F @1787-1822
- function_definition TEST_F @1824-1865
- function_definition TEST_F @1867-1889
- function_definition TEST_F @1891-1929

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [ba88e2a9-978f-42db-af23-c62d320d8761.md](ba88e2a9-978f-42db-af23-c62d320d8761.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `fd26d0458a32e41c9a68e84b4120a63370ecf00a477452b17a3f2fe3953e119d`.
