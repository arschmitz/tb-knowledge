<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:14:46.642314+00:00","paths":["third_party/rust/nix/test/sys/test_socket.rs","third_party/rust/nix/test/sys/test_sockopt.rs","third_party/rust/nix/test/sys/test_stat.rs","third_party/rust/nix/test/sys/test_statfs.rs","third_party/rust/nix/test/sys/test_statvfs.rs","third_party/rust/nix/test/sys/test_sysinfo.rs","third_party/rust/nix/test/sys/test_termios.rs","third_party/rust/nix/test/sys/test_time.rs","third_party/rust/nix/test/sys/test_timer.rs","third_party/rust/nix/test/sys/test_timerfd.rs","third_party/rust/nix/test/sys/test_uio.rs","third_party/rust/nix/test/sys/test_utsname.rs","third_party/rust/nix/test/sys/test_wait.rs","third_party/rust/nix/test/test.rs","third_party/rust/nix/test/test_clearenv.rs","third_party/rust/nix/test/test_dir.rs","third_party/rust/nix/test/test_errno.rs","third_party/rust/nix/test/test_fcntl.rs","third_party/rust/nix/test/test_kmod/hello_mod/Makefile","third_party/rust/nix/test/test_kmod/hello_mod/hello.c","third_party/rust/nix/test/test_kmod/mod.rs","third_party/rust/nix/test/test_mq.rs","third_party/rust/nix/test/test_net.rs","third_party/rust/nix/test/test_nix_path.rs","third_party/rust/nix/test/test_poll.rs","third_party/rust/nix/test/test_pty.rs","third_party/rust/nix/test/test_sched.rs","third_party/rust/nix/test/test_sendfile.rs","third_party/rust/nix/test/test_spawn.rs","third_party/rust/nix/test/test_syslog.rs","third_party/rust/nix/test/test_time.rs","third_party/rust/nix/test/test_unistd.rs","third_party/rust/nom/.cargo-checksum.json","third_party/rust/nom/.cargo_vcs_info.json","third_party/rust/nom/CHANGELOG.md","third_party/rust/nom/Cargo.lock","third_party/rust/nom/Cargo.toml","third_party/rust/nom/Cargo.toml.orig","third_party/rust/nom/LICENSE","third_party/rust/nom/README.md","third_party/rust/nom/doc/nom_recipes.md","third_party/rust/nom/src/bits/complete.rs","third_party/rust/nom/src/bits/mod.rs","third_party/rust/nom/src/bits/streaming.rs","third_party/rust/nom/src/branch/mod.rs","third_party/rust/nom/src/branch/tests.rs","third_party/rust/nom/src/bytes/complete.rs","third_party/rust/nom/src/bytes/mod.rs","third_party/rust/nom/src/bytes/streaming.rs","third_party/rust/nom/src/bytes/tests.rs","third_party/rust/nom/src/character/complete.rs","third_party/rust/nom/src/character/mod.rs","third_party/rust/nom/src/character/streaming.rs","third_party/rust/nom/src/character/tests.rs","third_party/rust/nom/src/combinator/mod.rs","third_party/rust/nom/src/combinator/tests.rs","third_party/rust/nom/src/error.rs","third_party/rust/nom/src/internal.rs","third_party/rust/nom/src/lib.rs","third_party/rust/nom/src/macros.rs","third_party/rust/nom/src/multi/mod.rs","third_party/rust/nom/src/multi/tests.rs","third_party/rust/nom/src/number/complete.rs","third_party/rust/nom/src/number/mod.rs","third_party/rust/nom/src/number/streaming.rs","third_party/rust/nom/src/sequence/mod.rs","third_party/rust/nom/src/sequence/tests.rs","third_party/rust/nom/src/str.rs","third_party/rust/nom/src/traits.rs","third_party/rust/nom/tests/arithmetic.rs","third_party/rust/nom/tests/arithmetic_ast.rs","third_party/rust/nom/tests/css.rs","third_party/rust/nom/tests/custom_errors.rs","third_party/rust/nom/tests/escaped.rs","third_party/rust/nom/tests/float.rs","third_party/rust/nom/tests/fnmut.rs","third_party/rust/nom/tests/ini.rs","third_party/rust/nom/tests/ini_str.rs","third_party/rust/nom/tests/issues.rs","third_party/rust/nom/tests/json.rs","third_party/rust/nom/tests/mp4.rs","third_party/rust/nom/tests/multiline.rs","third_party/rust/nom/tests/overflow.rs","third_party/rust/nom/tests/reborrow_fold.rs","third_party/rust/nss-rs/.cargo-checksum.json","third_party/rust/nss-rs/.clippy.toml","third_party/rust/nss-rs/.rustfmt.toml","third_party/rust/nss-rs/Cargo.lock","third_party/rust/nss-rs/Cargo.toml","third_party/rust/nss-rs/LICENSE-APACHE","third_party/rust/nss-rs/LICENSE-MIT","third_party/rust/nss-rs/README.md","third_party/rust/nss-rs/SECURITY.md","third_party/rust/nss-rs/bindings/bindings.toml","third_party/rust/nss-rs/bindings/nspr_err.h","third_party/rust/nss-rs/bindings/nspr_error.h","third_party/rust/nss-rs/bindings/nspr_io.h","third_party/rust/nss-rs/bindings/nspr_lib.h","third_party/rust/nss-rs/bindings/nspr_time.h","third_party/rust/nss-rs/bindings/nss_ciphers.h","third_party/rust/nss-rs/bindings/nss_init.h","third_party/rust/nss-rs/bindings/nss_p11.h","third_party/rust/nss-rs/bindings/nss_prelude.h","third_party/rust/nss-rs/bindings/nss_secerr.h","third_party/rust/nss-rs/bindings/nss_ssl.h","third_party/rust/nss-rs/bindings/nss_sslerr.h","third_party/rust/nss-rs/bindings/nss_sslopt.h","third_party/rust/nss-rs/build.rs","third_party/rust/nss-rs/install-nss/action.yml","third_party/rust/nss-rs/src/aead/mod.rs","third_party/rust/nss-rs/src/aead/recprot.rs","third_party/rust/nss-rs/src/aead/recprot_blapi.rs","third_party/rust/nss-rs/src/aead/recprot_null.rs","third_party/rust/nss-rs/src/agent.rs","third_party/rust/nss-rs/src/agentio.rs","third_party/rust/nss-rs/src/auth.rs","third_party/rust/nss-rs/src/cert.rs","third_party/rust/nss-rs/src/constants.rs","third_party/rust/nss-rs/src/der.rs","third_party/rust/nss-rs/src/ec.rs","third_party/rust/nss-rs/src/ech.rs","third_party/rust/nss-rs/src/err.rs","third_party/rust/nss-rs/src/exp.rs","third_party/rust/nss-rs/src/ext.rs","third_party/rust/nss-rs/src/freebl/bindgen.h","third_party/rust/nss-rs/src/freebl/mod.rs","third_party/rust/nss-rs/src/freebl/vector.rs","third_party/rust/nss-rs/src/hash.rs","third_party/rust/nss-rs/src/hkdf.rs","third_party/rust/nss-rs/src/hmac.rs","third_party/rust/nss-rs/src/hp/header_protection.rs","third_party/rust/nss-rs/src/hp/header_protection_blapi.rs","third_party/rust/nss-rs/src/hp/mod.rs","third_party/rust/nss-rs/src/hpke.rs","third_party/rust/nss-rs/src/lib.rs","third_party/rust/nss-rs/src/p11.rs","third_party/rust/nss-rs/src/pbkdf2.rs","third_party/rust/nss-rs/src/pk11_utils.rs","third_party/rust/nss-rs/src/prio.rs","third_party/rust/nss-rs/src/replay.rs","third_party/rust/nss-rs/src/result.rs","third_party/rust/nss-rs/src/secrets.rs","third_party/rust/nss-rs/src/selfencrypt.rs","third_party/rust/nss-rs/src/sig.rs","third_party/rust/nss-rs/src/ssl.rs","third_party/rust/nss-rs/src/time.rs","third_party/rust/nss-rs/src/util.rs","third_party/rust/nss-rs/tests/aead.rs","third_party/rust/nss-rs/tests/aead_fips.rs","third_party/rust/nss-rs/tests/agent.rs","third_party/rust/nss-rs/tests/common/mod.rs","third_party/rust/nss-rs/tests/ec.rs","third_party/rust/nss-rs/tests/ext.rs","third_party/rust/nss-rs/tests/handshake.rs","third_party/rust/nss-rs/tests/hkdf.rs","third_party/rust/nss-rs/tests/hp.rs","third_party/rust/nss-rs/tests/init.rs","third_party/rust/nss-rs/tests/selfencrypt.rs","third_party/rust/num-bigint/.cargo-checksum.json","third_party/rust/num-bigint/.cargo_vcs_info.json","third_party/rust/num-bigint/Cargo.toml","third_party/rust/num-bigint/Cargo.toml.orig","third_party/rust/num-bigint/LICENSE-APACHE","third_party/rust/num-bigint/LICENSE-MIT","third_party/rust/num-bigint/README.md","third_party/rust/num-bigint/RELEASES.md","third_party/rust/num-bigint/benches/bigint.rs","third_party/rust/num-bigint/benches/factorial.rs","third_party/rust/num-bigint/benches/gcd.rs","third_party/rust/num-bigint/benches/rng/mod.rs","third_party/rust/num-bigint/benches/roots.rs","third_party/rust/num-bigint/benches/shootout-pidigits.rs","third_party/rust/num-bigint/src/bigint.rs","third_party/rust/num-bigint/src/bigint/addition.rs","third_party/rust/num-bigint/src/bigint/arbitrary.rs","third_party/rust/num-bigint/src/bigint/bits.rs","third_party/rust/num-bigint/src/bigint/convert.rs","third_party/rust/num-bigint/src/bigint/division.rs","third_party/rust/num-bigint/src/bigint/multiplication.rs","third_party/rust/num-bigint/src/bigint/power.rs","third_party/rust/num-bigint/src/bigint/serde.rs","third_party/rust/num-bigint/src/bigint/shift.rs","third_party/rust/num-bigint/src/bigint/subtraction.rs","third_party/rust/num-bigint/src/bigrand.rs","third_party/rust/num-bigint/src/biguint.rs","third_party/rust/num-bigint/src/biguint/addition.rs","third_party/rust/num-bigint/src/biguint/arbitrary.rs","third_party/rust/num-bigint/src/biguint/bits.rs","third_party/rust/num-bigint/src/biguint/convert.rs","third_party/rust/num-bigint/src/biguint/division.rs","third_party/rust/num-bigint/src/biguint/iter.rs","third_party/rust/num-bigint/src/biguint/monty.rs","third_party/rust/num-bigint/src/biguint/multiplication.rs","third_party/rust/num-bigint/src/biguint/power.rs","third_party/rust/num-bigint/src/biguint/serde.rs","third_party/rust/num-bigint/src/biguint/shift.rs","third_party/rust/num-bigint/src/biguint/subtraction.rs","third_party/rust/num-bigint/src/lib.rs","third_party/rust/num-bigint/src/macros.rs","third_party/rust/num-bigint/tests/bigint.rs","third_party/rust/num-bigint/tests/bigint_bitwise.rs","third_party/rust/num-bigint/tests/bigint_scalar.rs","third_party/rust/num-bigint/tests/biguint.rs","third_party/rust/num-bigint/tests/biguint_scalar.rs","third_party/rust/num-bigint/tests/consts/mod.rs","third_party/rust/num-bigint/tests/fuzzed.rs","third_party/rust/num-bigint/tests/macros/mod.rs","third_party/rust/num-bigint/tests/modpow.rs","third_party/rust/num-bigint/tests/roots.rs","third_party/rust/num-complex/.cargo-checksum.json","third_party/rust/num-complex/.cargo_vcs_info.json","third_party/rust/num-complex/Cargo.toml","third_party/rust/num-complex/Cargo.toml.orig","third_party/rust/num-complex/LICENSE-APACHE","third_party/rust/num-complex/LICENSE-MIT","third_party/rust/num-complex/README.md","third_party/rust/num-complex/RELEASES.md","third_party/rust/num-complex/src/cast.rs","third_party/rust/num-complex/src/complex_float.rs","third_party/rust/num-complex/src/crand.rs","third_party/rust/num-complex/src/lib.rs","third_party/rust/num-complex/src/pow.rs","third_party/rust/num-conv/.cargo-checksum.json","third_party/rust/num-conv/.cargo_vcs_info.json","third_party/rust/num-conv/Cargo.lock","third_party/rust/num-conv/Cargo.toml","third_party/rust/num-conv/Cargo.toml.orig","third_party/rust/num-conv/LICENSE-Apache","third_party/rust/num-conv/LICENSE-MIT","third_party/rust/num-conv/README.md","third_party/rust/num-conv/src/lib.rs","third_party/rust/num-derive/.cargo-checksum.json","third_party/rust/num-derive/.cargo_vcs_info.json","third_party/rust/num-derive/Cargo.toml","third_party/rust/num-derive/Cargo.toml.orig","third_party/rust/num-derive/LICENSE-APACHE","third_party/rust/num-derive/LICENSE-MIT","third_party/rust/num-derive/README.md","third_party/rust/num-derive/RELEASES.md","third_party/rust/num-derive/src/lib.rs","third_party/rust/num-derive/tests/empty_enum.rs","third_party/rust/num-derive/tests/issue-16.rs","third_party/rust/num-derive/tests/issue-6.rs","third_party/rust/num-derive/tests/issue-9.rs","third_party/rust/num-derive/tests/newtype-2015.rs","third_party/rust/num-derive/tests/newtype-2018.rs","third_party/rust/num-derive/tests/newtype.rs","third_party/rust/num-derive/tests/no_implicit_prelude.rs","third_party/rust/num-derive/tests/num_derive_without_num.rs","third_party/rust/num-derive/tests/trivial-2015.rs","third_party/rust/num-derive/tests/trivial-2018.rs","third_party/rust/num-derive/tests/trivial.rs","third_party/rust/num-derive/tests/with_custom_values.rs","third_party/rust/num-integer/.cargo-checksum.json","third_party/rust/num-integer/.cargo_vcs_info.json","third_party/rust/num-integer/Cargo.toml","third_party/rust/num-integer/Cargo.toml.orig","third_party/rust/num-integer/LICENSE-APACHE","third_party/rust/num-integer/LICENSE-MIT","third_party/rust/num-integer/README.md","third_party/rust/num-integer/RELEASES.md","third_party/rust/num-integer/benches/average.rs","third_party/rust/num-integer/benches/gcd.rs","third_party/rust/num-integer/benches/roots.rs","third_party/rust/num-integer/src/average.rs","third_party/rust/num-integer/src/lib.rs","third_party/rust/num-integer/src/roots.rs","third_party/rust/num-integer/tests/average.rs","third_party/rust/num-integer/tests/roots.rs","third_party/rust/num-iter/.cargo-checksum.json","third_party/rust/num-iter/.cargo_vcs_info.json","third_party/rust/num-iter/Cargo.toml","third_party/rust/num-iter/Cargo.toml.orig","third_party/rust/num-iter/LICENSE-APACHE","third_party/rust/num-iter/LICENSE-MIT","third_party/rust/num-iter/README.md","third_party/rust/num-iter/RELEASES.md","third_party/rust/num-iter/src/lib.rs","third_party/rust/num-rational/.cargo-checksum.json","third_party/rust/num-rational/.cargo_vcs_info.json","third_party/rust/num-rational/Cargo.toml","third_party/rust/num-rational/Cargo.toml.orig","third_party/rust/num-rational/LICENSE-APACHE","third_party/rust/num-rational/LICENSE-MIT","third_party/rust/num-rational/README.md","third_party/rust/num-rational/RELEASES.md","third_party/rust/num-rational/src/lib.rs","third_party/rust/num-rational/src/pow.rs","third_party/rust/num-traits/.cargo-checksum.json","third_party/rust/num-traits/.cargo_vcs_info.json","third_party/rust/num-traits/Cargo.toml","third_party/rust/num-traits/Cargo.toml.orig","third_party/rust/num-traits/LICENSE-APACHE","third_party/rust/num-traits/LICENSE-MIT","third_party/rust/num-traits/README.md","third_party/rust/num-traits/RELEASES.md","third_party/rust/num-traits/build.rs","third_party/rust/num-traits/src/bounds.rs","third_party/rust/num-traits/src/cast.rs","third_party/rust/num-traits/src/float.rs","third_party/rust/num-traits/src/identities.rs","third_party/rust/num-traits/src/int.rs","third_party/rust/num-traits/src/lib.rs","third_party/rust/num-traits/src/macros.rs","third_party/rust/num-traits/src/ops/bytes.rs","third_party/rust/num-traits/src/ops/checked.rs","third_party/rust/num-traits/src/ops/euclid.rs","third_party/rust/num-traits/src/ops/inv.rs","third_party/rust/num-traits/src/ops/mod.rs","third_party/rust/num-traits/src/ops/mul_add.rs","third_party/rust/num-traits/src/ops/overflowing.rs","third_party/rust/num-traits/src/ops/saturating.rs","third_party/rust/num-traits/src/ops/wrapping.rs","third_party/rust/num-traits/src/pow.rs","third_party/rust/num-traits/src/real.rs","third_party/rust/num-traits/src/sign.rs","third_party/rust/num-traits/tests/cast.rs","third_party/rust/num/.cargo-checksum.json","third_party/rust/num/.cargo_vcs_info.json","third_party/rust/num/Cargo.toml","third_party/rust/num/Cargo.toml.orig","third_party/rust/num/LICENSE-APACHE","third_party/rust/num/LICENSE-MIT","third_party/rust/num/README.md","third_party/rust/num/RELEASES.md","third_party/rust/num/src/lib.rs","third_party/rust/num_cpus/.cargo-checksum.json","third_party/rust/num_cpus/.cargo_vcs_info.json","third_party/rust/num_cpus/.github/FUNDING.yml","third_party/rust/num_cpus/.github/workflows/ci.yml","third_party/rust/num_cpus/CHANGELOG.md","third_party/rust/num_cpus/CONTRIBUTING.md","third_party/rust/num_cpus/Cargo.lock","third_party/rust/num_cpus/Cargo.toml","third_party/rust/num_cpus/Cargo.toml.orig","third_party/rust/num_cpus/LICENSE-APACHE","third_party/rust/num_cpus/LICENSE-MIT","third_party/rust/num_cpus/README.md","third_party/rust/num_cpus/ci/cgroups/Dockerfile","third_party/rust/num_cpus/examples/values.rs","third_party/rust/num_cpus/fixtures/cgroups/cgroups/ceil/cpu.cfs_period_us","third_party/rust/num_cpus/fixtures/cgroups/cgroups/ceil/cpu.cfs_quota_us","third_party/rust/num_cpus/fixtures/cgroups/cgroups/good/cpu.cfs_period_us","third_party/rust/num_cpus/fixtures/cgroups/cgroups/good/cpu.cfs_quota_us","third_party/rust/num_cpus/fixtures/cgroups/cgroups/zero-period/cpu.cfs_period_us","third_party/rust/num_cpus/fixtures/cgroups/cgroups/zero-period/cpu.cfs_quota_us","third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/cgroup","third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/mountinfo","third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/mountinfo_multi_opt","third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/mountinfo_zero_opt","third_party/rust/num_cpus/fixtures/cgroups2/cgroups/ceil/cpu.max","third_party/rust/num_cpus/fixtures/cgroups2/cgroups/good/cpu.max","third_party/rust/num_cpus/fixtures/cgroups2/cgroups/zero-period/cpu.max","third_party/rust/num_cpus/fixtures/cgroups2/proc/cgroups/cgroup","third_party/rust/num_cpus/fixtures/cgroups2/proc/cgroups/cgroup_multi","third_party/rust/num_cpus/fixtures/cgroups2/proc/cgroups/mountinfo","third_party/rust/num_cpus/src/lib.rs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/third_party structural source map 1019

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. This is an automated navigation map, not a behavior review.
Each row gives the repository-relative path, Git blob ID, byte size, role inferred from the path, declaration candidates, and literal dependency candidates. `@N` is the source line.
Candidates come from line-based patterns. They can miss multiline, anonymous, macro-generated, and language-specific declarations or match comments and fixture text. Dependencies are not resolved imports, runtime calls, or a complete graph. No candidates does not mean no functions or dependencies.
Imported code and tests are included. Binary and non-UTF-8 files have a census entry but no declaration extraction. Symlink contents are scanned as text, not followed. No uncommitted changes, build products, ignored files, or untracked files are studied.

## File map

`third_party/rust/nix/test/sys/test_socket.rs` | `42906a65e240747f9ee8a8a14df02764e950aff8` | 98739 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_timestamping@16; test_timestamping_realtime@77; test_timestamping_monotonic@139; test_path_to_sock_addr@196; calculate_hash@208; test_addr_equality_path@215; test_abstract_sun_path_too_long@229; test_addr_equality_abstract@237; test_abstract_uds_addr@253; test_unnamed_uds_addr@275; test_getsockname@289; test_socketpair@311; test_recvmsg_sockaddr_un@331; test_std_conversions@371; recvfrom@383; sendrecv@391; stream@424; udp@437; udp_offload@466; gso@475; gro@541; udp_sendmmsg@562; udp_recvmmsg@624; udp_recvmmsg_dontwait_short_read@700; udp_inet6@780; bind@795; Err@796; Err@800; Ok@801; test_recvmsg_ebadf@827; test_scm_rights@846; test_af_alg_cipher@932; test_af_alg_aead@1028; test_sendmsg_ipv4packetinfo@1171; test_sendmsg_ipv6packetinfo@1236; test_sendmsg_ipv4sendsrcaddr@1290; test_scm_rights_single_cmsg_multiple_fds@1333; Some@1361; test_sendmsg_empty_cmsgs@1391; test_scm_credentials@1440; ControlMessageOwned::ScmCredentials@1498; ControlMessageOwned::ScmCreds@1500; test_scm_credentials_and_rights@1524; test_too_large_cmsgspace@1536; test_too_small_cmsgspace@1543; test_impl_scm_credentials_and_rights@1552; ControlMessageOwned::ScmRights@1618; ControlMessageOwned::ScmCredentials@1623; test_named_unixdomain@1657; test_listen_maxbacklog@1703; test_listen_wrongbacklog@1710; test_unnamed_unixdomain@1721; test_unnamed_unixdomain_autobind@1741; test_syscontrol@1769; loopback_address@1794; Ok@1804; Err@1805; test_recv_ipv4pktinfo@1836; Some@1846; test_recvif@1927; Some@1937; ControlMessageOwned::Ipv4RecvIf@1993; ControlMessageOwned::Ipv4RecvDstAddr@2003; test_recvif_ipv4@2028; Some@2037; ControlMessageOwned::Ipv4OrigDstAddr@2090; test_recvif_ipv6@2114; Some@2123; ControlMessageOwned::Ipv6OrigDstAddr@2176; test_recv_ipv6pktinfo@2213; Some@2223; test_vsock@2290; test_vsock@2330; test_recvmsg_timestampns@2376; Some@2416; Some@2417; test_recvmmsg_timestampns@2435; Some@2477; Some@2478; test_recvmsg_rxq_ovfl@2496; Ok@2565; Some@2567; Some@2570; Err@2574; test_ip_tos_udp@2604; test_ipv6_tclass_udp@2685; bind@2704; linux_errqueue@2774; test_recverr_v4@2785; IcmpTypes@2787; IcmpUnreachCodes@2791; test_recverr_v6@2833; IcmpV6Types@2835; IcmpV6UnreachCodes@2839; test_recverr_impl@2878; Some@2931; test_txtime@2954; test_icmp_protocol@3015; test_recvmm2@3050; can_use_cmsg_space@3155; can_open_routing_socket@3166
Dependencies: crate::@2; libc::c_char@3; nix::sys::socket::@4; std::collections::hash_map::DefaultHasher@5; std::hash::@6; std::net::@7; std::os::unix::io::@8; std::path::Path@9; std::slice@10; std::str::FromStr@11; nix::sys::socket::@17; std::io::@22; nix::sys::socket::@78; std::io::@83; nix::sys::socket::@140; std::io::@145; crate::nix::sys::socket::SockaddrLike@276; nix::sys::socket::bind@290; nix::sys::socket::@291; nix::sys::socket::@312; nix::unistd::@313; nix::sys::socket::@332; nix::sys::socket::@372; super::@384; nix::sys::socket::@385; nix::@386; std::thread@387; super::@467; nix::sys::socket::sockopt::@468; std::io::IoSlice@469; std::io::IoSlice@563; nix::sys::socket::@625; std::io::IoSliceMut@626; nix::sys::socket::@701; std::io::IoSliceMut@702; nix::errno::Errno@828; nix::sys::socket::@829; std::io::IoSliceMut@830; nix::sys::socket::@847; nix::unistd::@851; std::io::@852; nix::sys::socket::sockopt::AlgSetKey@933; nix::sys::socket::@934; nix::unistd::read@938; std::io::IoSlice@939; libc::@1029; nix::fcntl::@1030; nix::sys::socket::sockopt::@1031; nix::sys::socket::@1032; nix::unistd::read@1036; std::io::IoSlice@1037; cfg_if::cfg_if@1172; nix::sys::socket::@1173; std::io::IoSlice@1177; nix::errno::Errno@1237; nix::sys::socket::@1238; std::io::IoSlice@1242; nix::sys::socket::@1291; std::io::IoSlice@1295; nix::sys::socket::@1334; std::io::@1337; std::os::unix::io::@1338; std::os::unix::net::UnixDatagram@1339; std::thread@1340; nix::sys::socket::@1392; std::io::@1396; nix::sys::socket::@1441; nix::sys::socket::@1446; nix::unistd::@1447; std::io::@1448; libc::ucred@1555; nix::sys::socket::sockopt::PassCred@1556; nix::sys::socket::@1557; nix::unistd::@1561; std::io::@1562; nix::sys::socket::@1658; nix::sys::socket::@1661; nix::unistd::@1662; std::thread@1663; nix::sys::socket::Backlog@1704; nix::sys::socket::Backlog@1711; nix::sys::socket::@1722; nix::sys::socket::@1723; nix::sys::socket::@1742; nix::sys::socket::@1743; nix::errno::Errno@1770; nix::sys::socket::@1771; nix::ifaddrs::getifaddrs@1797; nix::net::if_::@1798; nix::sys::socket::SockaddrLike@1799; std::io@1800; std::io::Write@1801; nix::net::if_::@1837; nix::sys::socket::sockopt::Ipv4PacketInfo@1838; nix::sys::socket::@1839; nix::sys::socket::@1840; nix::sys::socket::@1841; std::io::@1842; nix::net::if_::@1928; nix::sys::socket::sockopt::@1929; nix::sys::socket::@1930; nix::sys::socket::@1931; nix::sys::socket::@1932; std::io::@1933; nix::sys::socket::sockopt::Ipv4OrigDstAddr@2029; nix::sys::socket::@2030; nix::sys::socket::@2031; nix::sys::socket::@2032; std::io::@2033; nix::sys::socket::sockopt::Ipv6OrigDstAddr@2115; nix::sys::socket::@2116; nix::sys::socket::@2117; nix::sys::socket::@2118; std::io::@2119; nix::net::if_::@2214; nix::sys::socket::sockopt::Ipv6RecvPacketInfo@2215; nix::sys::socket::@2216; nix::sys::socket::@2217; nix::sys::socket::@2218; std::io::@2219; nix::sys::socket::SockaddrLike@2291; nix::sys::socket::@2292; std::mem@2293; nix::sys::socket::SockaddrLike@2331; nix::sys::socket::@2332; std::mem@2333; nix::sys::socket::@2377; nix::sys::time::@2378; std::io::@2379; std::time::@2380; nix::sys::socket::@2436; nix::sys::time::@2437; std::io::@2438; std::time::@2439; nix::sys::socket::sockopt::@2497; nix::sys::socket::@2498; nix::Error@2499; std::io::@2500; nix::sys::socket::ControlMessageOwned@2605; nix::sys::socket::@2606; nix::sys::socket::ControlMessageOwned@2686; nix::sys::socket::@2687; super::FromStr@2775; nix::sys::socket::@2776; std::os::unix::io::AsRawFd@2777; nix::errno::Errno@2890; std::io::IoSliceMut@2891; nix::sys::socket::@2955; nix::sys::time::TimeValLike@2959; nix::time::@2960; nix::sys::socket::@3016; nix::sys::@3051; std::io::@3059; std::os::unix::io::AsRawFd@3060; std::str::FromStr@3061; nix::sys::socket::@3167

`third_party/rust/nix/test/sys/test_sockopt.rs` | `87ad72a953442e1423065e869f18dbcb744e7357` | 37844 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_local_peercred_seqpacket@13; test_local_peercred_stream@34; test_local_peer_pid@55; test_local_peer_token@71; audit_token_to_pid@82; is_so_mark_functional@101; test_so_buf@119; test_so_listen_q_limit@138; test_so_tcp_maxseg@163; test_so_type@240; test_so_type_unknown@256; test_tcp_congestion@277; test_tcp_function_blk_alias@308; test_bindtodevice@337; test_so_tcp_keepalive@355; test_get_mtu@385; test_ttl_opts@411; test_multicast_ttl_opts_ipv4@434; test_multicast_ttl_opts_ipv6@448; test_ipv6_multicast_hops@461; test_dontfrag_opts@475; test_v6dontfrag_opts@508; test_so_priority@539; test_ip_tos@554; test_ipv6_tclass@572; test_receive_timestamp@587; test_ts_clock_realtime_micro@601; test_ts_clock_bintime@629; test_ts_clock_realtime@652; test_ts_clock_monotonic@676; test_ip_bind_address_no_port@703; test_tcp_fast_open_connect@727; can_get_peercred_on_unix_socket@751; pid_from_pidfd@768; can_get_peerpidfd_on_unix_socket@779; is_socket_type_unix@808; is_socket_type_dgram@823; can_get_listen_on_tcp_socket@841; test_ktls@876; setsockopt@908; Ok@909; Err@912; Err@914; setsockopt@943; Ok@944; Err@945; Err@949; test_utun_ifname@955; test_reuseport_lb@988; test_ipv4_recv_ttl_opts@1004; test_ipv6_recv_hop_limit_opts@1032; test_ipv4_recv_tos_opts@1063; test_ipv6_recv_traffic_class_opts@1091; test_linger_sec@1122; sockopt_impl@1142; test_so_tcp_keepalive@1151; test_linger@1171; test_exclbind@1193; test_solfilter@1228; test_so_attach_reuseport_cbpf@1251
Dependencies: crate::@2; nix::sys::socket::@3; rand::@7; std::os::unix::io::@8; nix::@14; nix::@35; nix::sys::socket::socketpair@56; nix::sys::socket::@72; nix::sys::socket::sockopt@102; nix::sys::socket::@139; std::net::SocketAddrV4@140; std::str::FromStr@141; nix::sys::socket::@164; std::net::SocketAddrV4@167; std::str::FromStr@168; nix::unistd::write@222; nix::errno::Errno@257; std::ffi::OsString@278; std::os::unix::ffi::OsStrExt@279; std::ffi::CStr@309; nix::sys::socket::@386; std::net::SocketAddrV4@387; std::str::FromStr@388; nix::sys::socket::SocketTimestamp@602; nix::sys::socket::SocketTimestamp@630; nix::sys::socket::SocketTimestamp@653; nix::sys::socket::SocketTimestamp@677; nix::sys::socket::@752; std::fs::read_to_string@769; nix::sys::socket::@780; nix::sys::socket::@809; nix::sys::socket::@824; nix::sys::socket::@842; nix::sys::socket::@877; std::net::SocketAddrV4@880; std::str::FromStr@881; nix::sys::socket::connect@958; nix::sys::socket::SysControlAddr@959; nix::sys::socket::@1143; nix::errno::Errno@1194; nix::sys::socket::@1195; std::net::SocketAddrV4@1198; std::str::FromStr@1199; nix::errno::Errno@1229

`third_party/rust/nix/test/sys/test_stat.rs` | `fed517cf76b672753f597b29958f90cbd5edc95b` | 16252 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: assert_stat_results@55; assert_lstat_results@70; test_stat_and_fstat@94; test_fstatat@110; test_stat_fstat_lstat@124; test_fchmod@148; test_fchmodat@171; assert_times_eq@211; test_utimes@228; test_lutimes@245; test_futimens@272; test_utimensat@286; test_mkdirat_success_path@322; test_mkdirat_success_mode@334; test_mkdirat_fail@352; test_mknod@374; test_mknodat@394; test_futimens_unchanged@413; test_utimensat_unchanged@445; test_chflags@487
Dependencies: std::fs@2; std::fs::File@3; std::os::unix::fs::symlink@5; std::os::unix::fs::PermissionsExt@7; std::path::Path@9; std::time::@11; libc::mode_t@13; libc::@15; nix::errno::Errno@18; nix::fcntl@20; nix::sys::stat::lutimes@27; nix::sys::stat::utimensat@29; nix::sys::stat::FchmodatFlags@31; nix::sys::stat::Mode@32; nix::sys::stat::UtimensatFlags@34; nix::sys::stat::@36; nix::sys::stat::@37; nix::sys::stat::@39; nix::sys::stat::@41; nix::sys::stat::FileStat@44; nix::sys::time::@47; nix::unistd::chdir@49; nix::Result@52; nix::sys::stat::fstat@95; nix::sys::stat::@125; stat::@375; fcntl::@395; nix::dir::Dir@396; stat::@397; nix::@488; tempfile::NamedTempFile@492

`third_party/rust/nix/test/sys/test_statfs.rs` | `ca7934e6eddd2c16293bf7be32d32fffaabad423` | 2693 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: check_fstatfs@6; check_statfs@16; check_fstatfs_strict@25; check_statfs_strict@35; assert_fs_equals@46; statfs_call@52; fstatfs_call@60; statfs_call_strict@71; fstatfs_call_strict@82; assert_fs_equals_strict@91
Dependencies: nix::sys::statfs::@1; nix::sys::statvfs::@2; std::fs::File@3; std::path::Path@4

`third_party/rust/nix/test/sys/test_statvfs.rs` | `5c80965253de592a1642ac615a472f84fb72ac09` | 212 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: statvfs_call@5; fstatvfs_call@10
Dependencies: nix::sys::statvfs::@1; std::fs::File@2

`third_party/rust/nix/test/sys/test_sysinfo.rs` | `2897366effc905dde51ca2fc686d55f73233f026` | 455 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: sysinfo_works@4
Dependencies: nix::sys::sysinfo::@1

`third_party/rust/nix/test/sys/test_termios.rs` | `98de86bc7481624c6f1cf84cc13ef79600a46ede` | 3718 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: write_all@11; test_baudrate_try_from@19; test_tcgetattr_pty@29; test_tcgetattr_enotty@39; test_output_flags@46; test_local_flags@84
Dependencies: std::os::unix::io::AsFd@1; tempfile::tempfile@2; nix::errno::Errno@4; nix::fcntl@5; nix::pty::openpty@6; nix::sys::termios::@7; nix::unistd::@8

`third_party/rust/nix/test/sys/test_time.rs` | `0510225a9271a9ce57bbd49fc539cf71b2548bc3` | 3034 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_timespec@5; test_timespec_from@18; test_timespec_neg@27; test_timespec_ord@35; test_timespec_fmt@44; test_timeval@54; test_timeval_ord@67; test_timeval_neg@76; test_timeval_fmt@84
Dependencies: nix::sys::time::@1; std::time::Duration@2

`third_party/rust/nix/test/sys/test_timer.rs` | `ffd146867bd1d119c32918830c5d9a2995b8e8aa` | 3659 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: alarm_fires@23; Ok@68
Dependencies: nix::sys::signal::@1; nix::sys::timer::@5; nix::time::ClockId@6; std::convert::TryFrom@7; std::sync::atomic::@8; std::thread@9; std::time::@10

`third_party/rust/nix/test/sys/test_timerfd.rs` | `08e292106cccb94ed774e29acaabe1181283d8f5` | 1574 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_timerfd_oneshot@8; test_timerfd_interval@28; test_timerfd_unset@55
Dependencies: nix::sys::time::@1; nix::sys::timerfd::@2; std::time::Instant@5

`third_party/rust/nix/test/sys/test_uio.rs` | `38f35fa5d9c1df37f73084ab42935e81760ce870` | 7879 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_writev@19; test_readv@63; test_pwrite@107; test_pread@121; test_pwritev@150; test_preadv@190; test_process_vm_readv@229
Dependencies: nix::sys::uio::@1; nix::unistd::@2; rand::distr::Alphanumeric@3; rand::@4; std::fs::OpenOptions@5; std::io::IoSlice@6; std::@7; std::io::IoSliceMut@10; tempfile::tempdir@12; tempfile::tempfile@14; std::io::Read@108; std::io::Write@122; std::io::Read@151; std::io::Write@191; crate::@230; nix::sys::signal::@231; nix::sys::wait::@232; nix::unistd::ForkResult::@233

`third_party/rust/nix/test/sys/test_utsname.rs` | `8f84ac074f550e41acbb007479866b1adee1c10d` | 418 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_uname_linux@3; test_uname_darwin@9; test_uname_freebsd@15

`third_party/rust/nix/test/sys/test_wait.rs` | `365b0165f85027280fc6906ac36b6fe364e25d57` | 8041 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_wait_signal@10; test_waitid_signal@42; test_wait_exit@62; test_waitid_exit@90; test_waitstatus_from_raw@108; test_waitstatus_pid@122; test_waitid_pid@141; ptrace@156; ptrace_child@165; ptrace_wait_parent@173; ptrace_waitid_parent@205; test_wait_ptrace@246; test_waitid_ptrace@258
Dependencies: libc::_exit@1; nix::errno::Errno@2; nix::sys::signal::@3; nix::sys::wait::@4; nix::unistd::ForkResult::@5; nix::unistd::@6; crate::@157; libc::_exit@158; nix::sys::ptrace::@159; nix::sys::signal::@160; nix::sys::wait::@161; nix::unistd::ForkResult::@162; nix::unistd::@163

`third_party/rust/nix/test/test.rs` | `71a42a64441832d37756bd56534d6bc5b1c2ab46` | 2993 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: common@7; mount@8; sys@9; test_dir@11; test_errno@12; test_fcntl@13; test_kmod@15; test_mq@21; test_net@23; test_nix_path@24; test_poll@25; test_pty@31; test_sched@37; test_sendfile@39; test_spawn@47; test_syslog@49; test_time@51; test_unistd@52; read_exact@60; DirRestore@89; new@95; drop@105; std::thread::panicking@107
Dependencies: nix::unistd::@54; parking_lot::@55; std::os::unix::io::AsFd@56; std::path::PathBuf@57

`third_party/rust/nix/test/test_clearenv.rs` | `28a77680498ca5cafc041aa011b20cc6216963ee` | 232 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: clearenv@4
Dependencies: std::env@1

`third_party/rust/nix/test/test_dir.rs` | `c9713c6455dbff5dfe45e7943c8edfa0bbcbe2eb` | 1990 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: flags@8; read@19; rewind@41
Dependencies: nix::dir::@1; nix::fcntl::OFlag@2; nix::sys::stat::Mode@3; std::fs::File@4; tempfile::tempdir@5

`third_party/rust/nix/test/test_errno.rs` | `750fc924ff87ac1cd4881e71b16e38b604ba42d0` | 312 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: errno_set_and_read@4; errno_set_and_clear@10
Dependencies: nix::errno::Errno@1

`third_party/rust/nix/test/test_fcntl.rs` | `76c3b9f2dcbfe38e5f0a4dc167a657c59bafc422` | 25003 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_openat@39; test_openat2@65; test_openat2_forbidden@94; test_renameat@117; test_renameat2_behaves_like_renameat_with_no_flags@144; test_renameat2_exchange@173; test_renameat2_noreplace@218; test_readlink@246; test_copy_file_range@276; linux_android@299; test_splice@314; test_tee@334; test_vmsplice@356; test_fallocate@375; test_ofd_write_lock@393; test_ofd_read_lock@431; lock_info@467; test_posix_fadvise@496; test_success@503; test_errno@510; test_posix_fallocate@525; success@534; Ok@539; Err@544; errno@557; test_f_get_path@569; test_f_preallocate@586; test_f_get_path_nofirmlink@604; test_f_kinfo@635; test_flock@655; lock_and_drop@661; Ok@672; Err@673; Flock::lock@680; downgrade@687; unlock@710; Flock::lock@723; upgrade@730; test_f_rdadvise@756; test_f_log2phys@776; test_f_transferextents@798; test_f_readahead@811
Dependencies: nix::errno::@2; nix::fcntl::@4; nix::fcntl::@6; nix::fcntl::@9; nix::fcntl::@20; nix::sys::stat::Mode@22; nix::unistd::read@24; std::fs::File@26; std::io::prelude::@28; std::os::unix::fs@30; tempfile::NamedTempFile@32; nix::fcntl::copy_file_range@277; libc::loff_t@300; std::io::prelude::@301; std::io::IoSlice@302; nix::fcntl::@304; nix::unistd::@305; tempfile::tempfile@307; tempfile::NamedTempFile@309; crate::@311; nix::sys::stat::fstat@394; std::mem@395; nix::sys::stat::fstat@432; std::mem@433; std::@468; nix::errno::Errno@497; nix::fcntl::@498; nix::unistd::pipe@499; tempfile::NamedTempFile@500; nix::errno::Errno@527; nix::fcntl::@528; nix::unistd::pipe@529; std::io::Read@530; tempfile::NamedTempFile@531; nix::fcntl::@570; std::path::PathBuf@571; nix::fcntl::@587; nix::fcntl::@605; std::path::PathBuf@606; nix::fcntl::@636; std::path::PathBuf@637; nix::fcntl::@656; tempfile::NamedTempFile@657; nix::fcntl::@757; nix::fcntl::@777; nix::fcntl::@799; std::os::fd::AsRawFd@800; nix::fcntl::@812

`third_party/rust/nix/test/test_kmod/hello_mod/Makefile` | `74c99b77e96e1434c00eee89f44b0baa07951760` | 167 bytes | imported-path,test-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nix/test/test_kmod/hello_mod/hello.c` | `1c34987d2ac399af2a498233967a425119036f71` | 547 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: init_module@15; cleanup_module@21
Dependencies: linux/module.h@4; linux/kernel.h@5

`third_party/rust/nix/test/test_kmod/mod.rs` | `6f9aaa897f1ded10bdcb85754a298cb8feb97b9d` | 5648 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: compile_kernel_module@7; test_finit_and_delete_module@43; test_finit_and_delete_module_with_params@62; test_init_and_delete_module@88; test_init_and_delete_module_with_params@110; test_finit_module_invalid@135; test_finit_module_twice_and_delete_module@150; test_delete_module_not_loaded@177
Dependencies: crate::@1; std::fs::copy@2; std::path::PathBuf@3; std::process::Command@4; tempfile::@5; nix::errno::Errno@35; nix::kmod::@36; nix::kmod::@37; std::ffi::CString@38; std::fs::File@39; std::io::Read@40

`third_party/rust/nix/test/test_mq.rs` | `874a72b44deec3cd24c4484958c77a8d7050138c` | 8457 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_mq_send_and_receive@33; test_mq_timedreceive@62; test_mq_getattr@93; test_mq_setattr@126; test_mq_set_nonblocking@184; test_mq_unlink@208
Dependencies: cfg_if::cfg_if@1; std::str@2; nix::errno::Errno@4; nix::mqueue::@5; nix::mqueue::@8; nix::sys::stat::Mode@9; nix::sys::time::@10; nix::time::@11; nix::mqueue::mq_getattr@94; nix::mqueue::@127; nix::mqueue::@185; nix::mqueue::mq_unlink@209

`third_party/rust/nix/test/test_net.rs` | `be86b65d305ea8d2538abdd51c28c1367cd46657` | 663 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_if_nametoindex@14; test_if_indextoname@20
Dependencies: nix::net::if_::@1

`third_party/rust/nix/test/test_nix_path.rs` | `8b137891791fe96927ad78e64b0aad7bded08bdc` | 1 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/nix/test/test_poll.rs` | `fcb325494e825a4b0545d16b89e188d2e23784b3` | 2289 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Ok@12; Err@13; Err@14; test_poll@21; test_ppoll@43; test_pollfd_events@67
Dependencies: nix::@1; std::os::unix::io::@6; nix::poll::ppoll@44; nix::sys::signal::SigSet@45; nix::sys::time::@46

`third_party/rust/nix/test/test_pty.rs` | `a5808327052da1fdf97a9f0d2deae56e1c4374e9` | 8675 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_ptsname_equivalence@17; test_ptsname_copy@35; test_ptsname_r_copy@53; test_ptsname_unique@67; open_ptty_pair@83; test_open_ptty_pair@138; make_raw@143; test_read_ptty_pair@152; test_write_ptty_pair@169; test_openpty@185; test_openpty_with_termios@215; test_forkpty@253
Dependencies: std::fs::File@1; std::io::@2; std::os::unix::prelude::@3; std::path::Path@4; libc::_exit@6; nix::fcntl::@7; nix::pty::@8; nix::sys::stat@9; nix::sys::termios::@10; nix::sys::wait::WaitStatus@11; nix::unistd::@12; libc::@105; nix::sys::signal::@254; nix::sys::wait::wait@255

`third_party/rust/nix/test/test_sched.rs` | `c52616b8bb34c77065dfc0d8ae39cfa4f0d221b0` | 1399 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_sched_affinity@5
Dependencies: nix::sched::@1; nix::unistd::Pid@2

`third_party/rust/nix/test/test_sendfile.rs` | `ab50a1d04004ee50569fb2030f11b912305a5e85` | 7974 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_sendfile_linux@21; test_sendfile64_linux@40; test_sendfile_freebsd@59; test_sendfile_dragonfly@110; test_sendfile_darwin@159; test_sendfilev@208
Dependencies: std::io::prelude::@1; libc::off_t@3; nix::sys::sendfile::@4; tempfile::tempfile@5; nix::unistd::@9; std::net::Shutdown@11; std::os::unix::net::UnixStream@12; std::net::Shutdown@14; std::net::@15; std::os::fd::AsFd@209

`third_party/rust/nix/test/test_spawn.rs` | `a5e69b97f350039f1ec62e78c89795ae5bcab56c` | 5600 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: which@9; spawn_true@25; WaitStatus::Exited@43; spawn_sleep@54; WaitStatus::Signaled@80; spawn_cmd_does_not_exist@95; spawnp_true@110; WaitStatus::Exited@127; spawnp_sleep@138; WaitStatus::Signaled@163; spawnp_cmd_does_not_exist@178
Dependencies: super::FORK_MTX@1; nix::errno::Errno@2; nix::spawn::@3; nix::sys::signal@4; nix::sys::wait::@5; std::ffi::@6

`third_party/rust/nix/test/test_syslog.rs` | `fc8f9080709fdde6aa55f9fdc3a2aa0b05dbc3f8` | 1112 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_syslog_hello_world@4; test_openlog_with_ident@19; test_openlog_with_ident@33
Dependencies: nix::syslog::@1; std::ffi::CStr@20

`third_party/rust/nix/test/test_time.rs` | `64c8161dbf9d4fe8b765a91cdbb163103096f44e` | 1636 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_clock_getres@7; test_clock_gettime@12; test_clock_getcpuclockid@18; test_clock_id_res@25; test_clock_id_now@30; test_clock_id_pid_cpu_clock_id@36; test_clock_nanosleep@52
Dependencies: nix::time::clock_getcpuclockid@2; nix::time::@3; nix::@53

`third_party/rust/nix/test/test_unistd.rs` | `6037bb7a02d9cd4a5bf0e2ed2729d769832d73ee` | 42188 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: test_fork_and_waitpid@41; Ok@54; Err@62; test_rfork_and_waitpid@70; Ok@85; Err@93; test_wait@100; test_mkstemp@117; Ok@123; Err@126; test_mkstemp_directory@131; test_mkfifo@138; test_mkfifo_directory@151; test_mkfifoat_none@163; test_mkfifoat@185; test_mkfifoat_directory_none@207; test_mkfifoat_directory@224; test_getpid@236; test_getsid@245; linux_android@253; test_gettid@257; test_setgroups@271; test_initgroups@300; $test_name@337; syscall_cstr_ref@347; syscall_cstring@359; common_test@371; test_cstr_ref@417; test_cstring@425; test_fchdir@481; test_getcwd@494; test_chown@519; test_fchown@539; test_fchownat@553; test_lseek@580; test_lseek64@595; test_acct@637; test_fpathconf_limited@663; test_pathconf_limited@677; test_sysconf_limited@690; test_sysconf_unsupported@703; test_getresuid@713; test_getresgid@722; test_pipe@732; test_pipe2@756; test_truncate@770; test_ftruncate@787; test_alarm@815; test_canceling_alarm@860; test_symlinkat@871; test_linkat_file@901; test_linkat_pathtypes@935; test_linkat_olddirfd_none@967; test_linkat_newdirfd_none@1007; test_linkat_no_follow_symlink@1047; test_linkat_follow_symlink@1093; test_unlinkat_dir_noremovedir@1145; test_unlinkat_dir_removedir@1166; test_unlinkat_file@1186; test_access_not_existing@1205; test_access_file_exists@1215; test_user_into_passwd@1225; test_setfsuid@1245; test_ttyname@1286; test_ttyname_not_pty@1310; test_getpeereid@1317; test_faccessat_none_not_existing@1335; test_faccessat_not_existing@1351; test_faccessat_none_file_exists@1367; test_faccessat_file_exists@1385; test_eaccess_not_existing@1404; test_eaccess_file_exists@1415; test_group_from@1425
Dependencies: libc::@1; nix::errno::Errno@2; nix::fcntl::readlink@4; nix::fcntl::OFlag@5; nix::fcntl::@7; nix::pty::@13; nix::sys::signal::@15; nix::sys::stat::@18; nix::sys::wait::@19; nix::unistd::ForkResult::@20; nix::unistd::@21; std::env@22; std::ffi::CString@24; std::fs::DirBuilder@26; std::fs::@27; std::io::Write@28; std::path::Path@34; tempfile::@35; crate::@37; nix::fcntl::AT_FDCWD@164; nix::fcntl@186; nix::fcntl::AT_FDCWD@208; nix::unistd::gettid@254; std::ffi::CStr@338; super::@339; nix::fcntl::AtFlags@458; nix::fcntl::AtFlags@469; nix::fcntl::AtFlags@554; nix::fcntl::AT_FDCWD@555; std::process::Command@638; std::@639; tempfile::NamedTempFile@640; nix::fcntl::@757; std::@816; nix::fcntl::AT_FDCWD@872; nix::fcntl::AtFlags@902; nix::fcntl::AtFlags@936; nix::fcntl::AtFlags@968; nix::fcntl::AT_FDCWD@969; nix::fcntl::AtFlags@1008; nix::fcntl::AT_FDCWD@1009; nix::fcntl::AtFlags@1048; nix::fcntl::AT_FDCWD@1049; nix::fcntl::AtFlags@1094; nix::fcntl::AT_FDCWD@1095; std::os::unix::fs::PermissionsExt@1246; std::@1247; std::os::fd::AsRawFd@1287; std::os::unix::net::UnixStream@1318; nix::fcntl::AtFlags@1336; nix::fcntl::AT_FDCWD@1337; nix::fcntl::AtFlags@1352; nix::fcntl::AtFlags@1368; nix::fcntl::AT_FDCWD@1369; nix::fcntl::AtFlags@1386

`third_party/rust/nom/.cargo-checksum.json` | `89ee5e722e5fd98a5e4d0f92315b4cf2c963ac50` | 4519 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nom/.cargo_vcs_info.json` | `c356c323b4ecf57c23f9e69574cff55e45d98e33` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nom/CHANGELOG.md` | `a8f4c02c27dac714232b4662a4e3bf8381f904bd` | 60291 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/nom/Cargo.lock` | `c7168342e7d5cdfd5cece84f3baf7b07d7694594` | 7532 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nom/Cargo.toml` | `2388b4ceea350c37fa54ea270824daa6342a94b8` | 2915 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/nom/Cargo.toml.orig` | `c01eeba88bc2c9a2620f071b19f833fc000176fc` | 2465 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nom/LICENSE` | `88557e44e34e2469f83d9c87701821c14386ba6b` | 1065 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nom/README.md` | `f2c1b0528637147021dcdfda20ec00f98930acf3` | 14405 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/nom/doc/nom_recipes.md` | `e8626344a7fcf3db6af36203d77ea329359732ec` | 9280 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/nom/src/bits/complete.rs` | `bf36dcc2aae007f8cdc887fb6dc8c720a0ffc897` | 5617 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: take@33; tag@85; bool@123; test@132; test_take_0@136; test_take_eof@148; test_take_span_over_multiple_bytes@163; test_bool_0@175; test_bool_eof@184
Dependencies: crate::error::@4; crate::internal::@5; crate::lib::std::ops::@6; crate::traits::@7; super::@133

`third_party/rust/nom/src/bits/mod.rs` | `0d3f73db25d1a83049ffbc895832441876b4cb5f` | 6094 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: complete@4; streaming@5; bits@40; Ok@48; Err@55; Err@56; Err@57; bytes@86; Ok@101; Err@102; Err@103; Some@104; Err@107; Err@108; test@114; test_complete_byte_consumption_bits@123; test_partial_byte_consumption_bits@148; test_incomplete_bits@168
Dependencies: crate::error::@7; crate::internal::@8; crate::lib::std::ops::RangeFrom@9; crate::traits::@10; super::@115; crate::bits::streaming::take@116; crate::error::Error@117; crate::sequence::tuple@118

`third_party/rust/nom/src/bits/streaming.rs` | `a7c8d0a67b9f26d9a4c9823f29321317998b1219` | 4614 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: take@10; tag@59; bool@97; test@106; test_take_0@110; test_tag_ok@122; test_tag_err@135; test_bool_0@154; test_bool_eof@163
Dependencies: crate::error::@4; crate::internal::@5; crate::lib::std::ops::@6; crate::traits::@7; super::@107

`third_party/rust/nom/src/branch/mod.rs` | `e03622cb0c833db7ca3b32304eb3594bf90c5155` | 8157 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tests@4; Alt@13; choice@15; alt@47; Permutation@56; permutation@58; permutation@106; choice@134; Err@136; Err@147; choice@165; permutation@197; Ok@226; Err@231; Some@233; Err@237
Dependencies: crate::error::ErrorKind@6; crate::error::ParseError@7; crate::internal::@8

`third_party/rust/nom/src/branch/tests.rs` | `ecd44407e93f92e50cea893991aa5abb17991f54` | 3764 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ErrorStr@16; from@20; from@27; from_error_kind@34; append@38; alt_test@48; work@49; dont_work@54; work2@58; alt1@62; alt2@65; alt3@68; alt4@87; alt_incomplete@96; alt1@97; permutation_test@116; perm@117
Dependencies: crate::branch::@1; crate::bytes::streaming::tag@2; crate::error::ErrorKind@3; crate::internal::@4; crate::@6

`third_party/rust/nom/src/bytes/complete.rs` | `a5442b53f7428ba2702dfbfb3d455c61f6e18e79` | 25004 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tag@32; tag_no_case@74; is_not@117; is_a@151; take_while@183; take_while1@213; take_while_m_n@249; Some@262; Ok@294; Err@295; take_till@330; take_till1@361; take@403; Err@412; Ok@413; take_until@435; Some@446; take_until1@471; Some@482; Some@483; escaped@509; Ok@536; Err@548; Ok@559; Err@566; Err@580; escaped_transform@623; Ok@656; Err@666; Ok@679; Err@687; Err@700; tests@708; complete_take_while_m_n_utf8_all_matching@712; complete_take_while_m_n_utf8_all_matching_substring@719; escaped_string@726; escaped_hang@733; unquote@739; escaped_hang_1118@753
Dependencies: crate::error::ErrorKind@3; crate::error::ParseError@4; crate::internal::@5; crate::lib::std::ops::RangeFrom@6; crate::lib::std::result::Result::@7; crate::traits::@8; crate::traits::AsChar@527; crate::traits::AsChar@644; super::@709; crate::character::complete::@727; crate::bytes::complete::@740; crate::character::complete::@741; crate::combinator::opt@742; crate::sequence::delimited@743

`third_party/rust/nom/src/bytes/mod.rs` | `7bc2d15a79cb991d825323c5cad564481ab9bfaa` | 100 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: complete@3; streaming@4; tests@6

`third_party/rust/nom/src/bytes/streaming.rs` | `e972760e21e47ee7ae6c12bbc149305e3588faa0` | 23434 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tag@31; tag_no_case@73; is_not@117; is_a@153; take_while@188; take_while1@222; take_while_m_n@260; Some@273; Ok@305; Err@306; take_till@343; take_till1@375; take@411; Err@420; Ok@421; take_until@446; Some@458; take_until1@486; Some@498; Some@499; escaped@525; Ok@552; Err@562; Ok@570; Err@577; Err@585; escaped_transform@627; Ok@660; Err@670; Ok@680; Err@688; Err@695
Dependencies: crate::error::ErrorKind@3; crate::error::ParseError@4; crate::internal::@5; crate::lib::std::ops::RangeFrom@6; crate::lib::std::result::Result::@7; crate::traits::@8; crate::traits::AsChar@543; crate::traits::AsChar@648

`third_party/rust/nom/src/bytes/tests.rs` | `159c4b4ffcc6937967ab1aeb94ce51ba8b17b526` | 16930 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: is_a@18; a_or_b@21; is_not@42; a_or_b@45; escaping@71; esc@74; esc2@98; escaping_str@106; esc@109; esc2@130; esc3@135; to_s@142; escape_transform@148; esc@149; esc2@194; escape_transform_str@219; esc@220; esc2@253; esc3@266; take_until_incomplete@277; y@279; take_until_incomplete_s@288; ys@290; recognize@297; x@302; ya@310; yd@316; yhd@322; yod@328; yan@334; ys@340; yms@346; take_while@354; f@357; take_while1@372; f@375; take_while_m_n@393; x@396; take_till@418; f@421; take_till1@436; f@439; take_while_utf8@457; f@460; g@469; take_till_utf8@479; f@482; g@491; take_utf8@501; f@504; g@515; take_while_m_n_utf8@525; parser@528; take_while_m_n_utf8_full_match@536; parser@539; recognize_take_while@547; x@552; y@555; length_bytes@564; x@567; y@575; case_insensitive@587; test@590; test2@606; tag_fixed_size_array@624; test@627; test2@630
Dependencies: crate::character::is_alphabetic@1; crate::character::streaming::@2; crate::error::ErrorKind@6; crate::internal::@7; crate::@9; crate::bytes::streaming::is_a@19; crate::bytes::streaming::is_not@43; crate::character::streaming::one_of@72; crate::character::streaming::one_of@107; crate::bytes::streaming::take_until@278; crate::bytes::streaming::take_until@289; crate::bytes::streaming::@298; crate::combinator::recognize@299; crate::sequence::delimited@300; crate::bytes::streaming::take_while@355; crate::bytes::streaming::take_while1@373; crate::bytes::streaming::take_while_m_n@394; crate::bytes::streaming::take_till@419; crate::bytes::streaming::take_till1@437; crate::bytes::streaming::take_while@458; crate::bytes::streaming::take_till@480; crate::bytes::streaming::@502; crate::bytes::streaming::take_while_m_n@526; crate::bytes::streaming::take_while_m_n@537; crate::bytes::streaming::take_while@548; crate::character::is_alphanumeric@549; crate::combinator::recognize@550; crate::@565; crate::bytes::streaming::tag_no_case@588; crate::bytes::streaming::tag@625

`third_party/rust/nom/src/character/complete.rs` | `7cb760a68361bcbc0adf903c6118f5c0aa20ed20` | 41254 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: char@32; Some@41; satisfy@61; Some@72; one_of@89; Some@96; none_of@113; Some@120; crlf@141; not_line_ending@177; Some@190; line_ending@227; newline@262; tab@286; anychar@309; Some@317; Some@319; alpha0@341; alpha1@366; digit0@392; digit1@435; hex_digit0@459; hex_digit1@483; oct_digit0@508; oct_digit1@533; alphanumeric0@558; alphanumeric1@583; space0@608; space1@636; multispace0@667; multispace1@695; sign@709; $t@733; Some@756; Some@758; Some@772; Some@774; $t@795; Some@816; Some@818; tests@832; character@846; character_s@891; offset@924; Ok@933; Ok@939; Ok@945; Ok@951; Ok@957; Ok@963; Ok@969; is_not_line_ending_bytes@977; is_not_line_ending_str@1004; hex_digit_test@1030; oct_digit_test@1061; full_line_windows@1084; take_full_line@1086; full_line_unix@1095; take_full_line@1097; check_windows_lineending@1106; check_unix_lineending@1113; cr_lf@1120; end_of_line@1143; digit_to_i16@1167; Some@1171; Some@1172; let@1176; Ok@1177; Err@1178; Some@1187; digit_to_u32@1201; Some@1204; ints@1214; uints@1221
Dependencies: crate::branch::alt@5; crate::combinator::opt@6; crate::error::ErrorKind@7; crate::error::ParseError@8; crate::internal::@9; crate::lib::std::ops::@10; crate::traits::@11; crate::traits::@14; crate::bytes::complete::tag@714; crate::combinator::value@715; super::@833; crate::internal::Err@834; crate::traits::ParseTo@835; proptest::prelude::@836; crate::traits::Offset@922; crate::sequence::pair@1085; crate::sequence::pair@1096

`third_party/rust/nom/src/character/mod.rs` | `2c5d3bc4ad833e461e6eb48b2b55923dbf4f89e6` | 2638 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tests@6; complete@8; streaming@9; is_alphabetic@21; is_digit@35; is_hex_digit@51; is_oct_digit@66; is_alphanumeric@82; is_space@98; is_newline@114

`third_party/rust/nom/src/character/streaming.rs` | `88aabba3560596fa2b2db4a9f12261e793bf68fb` | 41796 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: char@31; Some@41; Some@42; satisfy@61; Some@73; Some@74; one_of@90; Some@98; Some@99; none_of@115; Some@123; Some@124; crlf@140; not_line_ending@171; Some@184; line_ending@218; newline@250; tab@270; anychar@289; Some@297; Some@299; alpha0@317; alpha1@338; digit0@359; digit1@380; hex_digit0@401; hex_digit1@422; oct_digit0@443; oct_digit1@464; alphanumeric0@485; alphanumeric1@506; space0@527; space1@550; multispace0@577; multispace1@601; sign@615; $t@639; Some@662; Some@664; Some@678; Some@680; $t@701; Some@722; Some@724; tests@738; anychar_str@754; character@760; character_s@828; offset@887; Ok@896; Ok@902; Ok@908; Ok@914; Ok@920; Ok@926; Ok@932; is_not_line_ending_bytes@940; is_not_line_ending_str@967; hex_digit_test@996; oct_digit_test@1027; full_line_windows@1050; take_full_line@1051; full_line_unix@1060; take_full_line@1061; check_windows_lineending@1070; check_unix_lineending@1077; cr_lf@1084; end_of_line@1101; digit_to_i16@1122; Some@1126; Some@1127; let@1131; Ok@1132; Err@1133; Err@1134; Some@1142; digit_to_u32@1156; Some@1159; ints@1169; uints@1176
Dependencies: crate::branch::alt@5; crate::combinator::opt@6; crate::error::ErrorKind@7; crate::error::ParseError@8; crate::internal::@9; crate::lib::std::ops::@10; crate::traits::@11; crate::traits::@14; crate::bytes::streaming::tag@620; crate::combinator::value@621; super::@739; crate::error::ErrorKind@740; crate::internal::@741; crate::sequence::pair@742; crate::traits::ParseTo@743; proptest::prelude::@744; super::anychar@755; crate::traits::Offset@885

`third_party/rust/nom/src/character/tests.rs` | `64c2a1c8a7c8c4efbb38dad0ebe896bff093b3cd` | 1282 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: one_of_test@6; f@7; utf8@17; none_of_test@26; f@27; char_byteslice@39; f@40; char_str@52; f@53
Dependencies: super::streaming::@1; crate::error::ErrorKind@2; crate::internal::@3

`third_party/rust/nom/src/combinator/mod.rs` | `fe08d4a1050b480d2070c3865eaf4d978b9074ae` | 22846 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tests@20; rest@31; rest_len@48; map@73; map_res@104; f@115; Ok@116; Err@117; map_opt@142; f@153; Some@154; map_parser@176; flat_map@206; opt@239; Ok@246; Err@247; Err@248; cond@271; Ok@281; Err@282; peek@304; Ok@311; Err@312; eof@333; complete@356; Err@363; all_consuming@384; verify@417; second@431; value@453; not@477; Ok@484; Err@485; Err@486; recognize@506; Ok@515; Err@519; consumed@561; Ok@570; Err@575; cut@631; Err@636; into@663; Ok@673; Err@674; Err@675; Err@676; iterator@700; ParserIterator@713; finish@721; State::Failure@724; State::Incomplete@725; Item@735; next@737; Ok@742; Err@747; Err@751; Err@755; State@766; success@794; fail@807
Dependencies: crate::lib::std::boxed::Box@6; crate::error::@8; crate::internal::@9; crate::lib::std::borrow::Borrow@10; crate::lib::std::convert::Into@11; crate::lib::std::fmt::Debug@13; crate::lib::std::mem::transmute@14; crate::lib::std::ops::@15; crate::traits::@16; crate::traits::@17

`third_party/rust/nom/src/combinator/tests.rs` | `15d32b8aae3322834dadf8383ef3390e82cf5534` | 6536 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: t1@19; eof_on_slices@28; eof_on_strs@43; end_of_input@59; rest_on_slices@73; rest_on_strs@80; rest_len_on_slices@87; from@94; from_error_kind@100; append@104; CustomError@109; custom_error@111; test_flat_map@117; test_map_opt@126; test_map_parser@139; test_all_consuming@148; test_verify_ref@162; parser2@173; test_verify_alloc@180; test_into@195; opt_test@209; opt_abcd@210; peek_test@223; peek_tag@224; not_test@237; not_aaa@238; verify_test@251; test@254; fail_test@269
Dependencies: super::@1; crate::bytes::complete::take@2; crate::bytes::streaming::tag@3; crate::error::ErrorKind@4; crate::error::ParseError@5; crate::internal::@6; crate::lib::std::boxed::Box@8; crate::number::complete::u8@9; crate::lib::std::convert::From@92; crate::bytes::complete::take@163; crate::bytes::complete::take@181; crate::bytes::complete::take@196; crate::@197; crate::bytes::streaming::take@252

`third_party/rust/nom/src/error.rs` | `498b5e135a0973239978f2578314c320eaeccea6` | 25672 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ParseError@16; from_error_kind@18; append@23; from_char@26; or@32; ContextError@39; add_context@43; FromExternalError@50; from_external_error@53; Error@58; new@67; from_error_kind@73; append@77; from_external_error@86; fmt@93; from_error_kind@104; append@108; from_external_error@116; from_error_kind@122; append@124; from_external_error@130; make_error@134; append_error@141; VerboseError@151; VerboseErrorKind@161; from_error_kind@173; append@179; from_char@184; add_context@194; from_external_error@204; fmt@211; VerboseErrorKind::Nom@215; VerboseErrorKind::Char@216; VerboseErrorKind::Context@217; context@233; Ok@241; Err@242; Err@243; Err@244; convert_error@251; VerboseErrorKind::Char@265; VerboseErrorKind::Context@268; VerboseErrorKind::Nom@269; VerboseErrorKind::Char@297; VerboseErrorKind::Context@329; VerboseErrorKind::Nom@341; ErrorKind@366; error_to_u32@425; description@487; dbg_dmp@590; Err@599; tests@609; convert_error_panic@614; add_error_pattern@629; slice_to_offsets@638; prepare_errors@646; print_error@659; generate_colors@670; code_from_offset@682; reset_color@704; write_color@712; print_codes@725; print_offsets@747
Dependencies: crate::internal::Parser@6; crate::lib::std::fmt@7; crate::internal::@228; crate::lib::std::fmt::Write@255; crate::traits::Offset@256; crate::HexDisplay@597; super::@610; crate::character::complete::char@611; lib::std::@623; lib::std::hash::Hash@626

`third_party/rust/nom/src/internal.rs` | `b7572fbd0a942984626c36f46d6ce6b3afb1cbce` | 13958 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: IResult@18; Finish@21; finish@32; finish@36; Ok@38; Err@39; Err@40; Needed@50; new@59; NonZeroUsize::new@60; Some@61; is_known@67; map@73; Size@76; Err@97; is_incomplete@110; map@119; Err::Incomplete@124; Err::Failure@125; Err::Error@126; convert@131; map_input@141; Err::Incomplete@146; Err::Failure@147; Err::Error@148; map_input@155; Err::Incomplete@160; Err::Failure@161; Err::Error@165; to_owned@179; to_owned@188; to_owned@197; to_owned@206; fmt@217; Err::Incomplete@219; Err::Incomplete@220; Err::Failure@221; Err::Error@222; source@235; Parser@241; parse@244; map@247; flat_map@260; and_then@274; and@287; or@296; into@306; parse@324; parse@334; Map@341; parse@348; Err@350; Ok@351; FlatMap@358; parse@367; AndThen@375; parse@384; And@393; parse@401; Or@410; parse@418; Err@420; Err@421; Into@431; parse@449; Ok@451; Err@452; Err@453; Err@454; tests@460; size_test@474; err_map_test@485
Dependencies: self::Needed::@3; crate::error::@4; crate::lib::std::fmt@5; core::num::NonZeroUsize@6; crate::lib::std::@174; std::error::Error@228; alloc::boxed::Box@330; super::@461; crate::error::ErrorKind@462

`third_party/rust/nom/src/lib.rs` | `3beb2f4179d48973b5dee9215811d22dbd139863` | 15735 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: lib@392; std@398; prelude@412; std@420; prelude@429; macros@442; error@444; branch@446; combinator@447; internal@448; multi@449; sequence@450; traits@451; bits@453; bytes@454; character@456; str@458; number@460; recipes@464

`third_party/rust/nom/src/macros.rs` | `980d2d90ed28a5777aa1cd4f345a642f0ca631ea` | 1453 bytes | imported-path,source | UTF-8 | mode 100644

`third_party/rust/nom/src/multi/mod.rs` | `73129084e2a9034b8210907b083b5b23340d96c4` | 31256 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tests@4; many0@53; Err@64; Err@65; Ok@66; many1@108; Err@115; Err@116; Ok@117; Err@125; Err@126; Ok@127; many_till@165; Ok@180; Err@181; Err@183; Err@184; Ok@185; Err@196; separated_list0@228; Err@242; Err@243; Ok@244; Err@253; Err@254; Ok@255; Err@262; Err@263; Ok@264; separated_list1@302; Err@317; Ok@318; Err@327; Err@328; Ok@329; Err@336; Err@337; Ok@338; many_m_n@380; Ok@401; Err@410; Err@417; many0_count@452; Ok@466; Err@476; Err@478; many1_count@510; Err@519; Err@520; Ok@521; Err@529; Err@530; Ok@531; count@569; Ok@584; Err@588; Err@591; fill@625; f@636; Ok@637; Err@641; Err@644; fold_many0@689; Ok@709; Err@718; Err@721; fold_many1@765; Err@781; Err@782; Ok@783; Err@791; Err@794; Ok@795; fold_many_m_n@854; Ok@877; Err@887; Err@894; length_data@921; length_value@966; Err@987; Err@988; Ok@989; length_count@1018; Ok@1034; Err@1038; Err@1041
Dependencies: crate::error::ErrorKind@6; crate::error::ParseError@7; crate::internal::@8; crate::lib::std::vec::Vec@10; crate::traits::@11; core::num::NonZeroUsize@12

`third_party/rust/nom/src/multi/tests.rs` | `96a65181764e7fd604d292dd8367a0939484d288` | 14739 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: separated_list0_test@22; multi@23; multi_empty@26; empty_sep@29; multi_longsep@32; separated_list1_test@71; multi@72; multi_longsep@75; many0_test@106; multi@107; multi_empty@110; many1_test@134; multi@135; many_till_test@157; multi@158; infinite_many@182; tst@183; multi0@189; multi1@195; many_m_n_test@207; multi@208; count_test@233; cnt_2@235; count_zero@267; counter_2@269; NilError@305; from@308; from_error_kind@314; append@317; number@322; length_count_test@330; cnt@331; length_data_test@352; take@353; length_value_test@370; length_value_1@371; length_value_2@374; fold_many0_test@409; fold_into_vec@410; multi@414; multi_empty@417; fold_many1_test@441; fold_into_vec@442; multi@446; fold_many_m_n_test@468; fold_into_vec@469; multi@473; many0_count_test@497; count0_nums@498; many1_count_test@515; count1_nums@516
Dependencies: super::@1; crate::@2; crate::@12; crate::combinator::map_res@323

`third_party/rust/nom/src/number/complete.rs` | `98b8b3abf836c9ce1e6b8aabdbba2b61388721e8` | 65110 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: be_u8@32; be_u16@62; be_u24@95; be_u32@128; be_u64@161; be_u128@194; be_i8@227; be_i16@250; be_i24@273; be_i32@305; be_i64@328; be_i128@351; le_u8@374; le_u16@404; le_u24@437; le_u32@470; le_u64@503; le_u128@536; le_i8@569; le_i16@592; le_i24@615; le_i32@647; le_i64@670; le_i128@693; u8@717; u16@757; u24@796; u32@835; u64@874; u128@913; i8@944; i16@976; i24@1015; i32@1054; i64@1093; i128@1132; be_f32@1162; be_u32@1166; Err@1167; Ok@1168; be_f64@1188; be_u64@1192; Err@1193; Ok@1194; le_f32@1214; le_u32@1218; Err@1219; Ok@1220; le_f64@1240; le_u64@1244; Err@1245; Ok@1246; f32@1275; f64@1314; hex_u32@1345; recognize_float@1386; recognize_float_or_exceptions@1413; crate::Err::Error@1425; crate::Err::Failure@1426; crate::Err::Incomplete@1427; recognize_float_parts@1452; let@1466; Some@1467; Some@1476; let@1486; let@1524; Some@1525; Some@1526; float@1558; Some@1586; double@1611; Some@1639; tests@1648; i8_tests@1662; be_i8_tests@1670; be_i16_tests@1678; be_u24_tests@1686; be_i24_tests@1696; be_i32_tests@1706; be_i64_tests@1720; be_i128_tests@1740; le_i8_tests@1786; le_i16_tests@1794; le_u24_tests@1802; le_i24_tests@1812; le_i32_tests@1822; le_i64_tests@1836; le_i128_tests@1856; be_f32_tests@1902; be_f64_tests@1911; le_f32_tests@1923; le_f64_tests@1932; hex_u32_tests@1944; float_test@1965; configurable_endianness@2018; be_tst16@2021; le_tst16@2024; be_tst32@2030; le_tst32@2033; be_tst64@2045; le_tst64@2048; be_tsti16@2060; le_tsti16@2063; be_tsti32@2069; le_tsti32@2072; be_tsti64@2084; le_tsti64@2087; parse_f64@2101; recognize_float_or_exceptions@2102; Err@2103; Ok@2104; Some@2109; floats@2119
Dependencies: crate::branch::alt@3; crate::bytes::complete::tag@4; crate::character::complete::@5; crate::combinator::@6; crate::error::ParseError@7; crate::error::@8; crate::internal::@9; crate::lib::std::ops::@10; crate::sequence::@11; crate::traits::@12; crate::traits::ParseTo@1539; super::@1649; crate::error::ErrorKind@1650; crate::internal::Err@1651; proptest::prelude::@1652; crate::number::Endianness@2019

`third_party/rust/nom/src/number/mod.rs` | `58c3d51b0bdb6afa4f90c592dd98394fafbc9765` | 271 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: complete@3; streaming@4; Endianness@8

`third_party/rust/nom/src/number/streaming.rs` | `b4e856d29844243ebd5ca93e5e61f777d8c1d9f2` | 69767 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: be_u8@30; be_u16@60; be_u24@93; be_u32@126; be_u64@159; be_u128@191; be_i8@221; be_i16@241; be_i24@261; be_i32@290; be_i64@311; be_i128@331; le_u8@351; le_u16@381; le_u24@414; le_u32@447; le_u64@480; le_u128@513; le_i8@543; le_i16@566; le_i24@589; le_i32@621; le_i64@644; le_i128@667; u8@691; u16@731; u24@770; u32@809; u64@848; u128@887; i8@918; i16@950; i24@989; i32@1028; i64@1067; i128@1106; be_f32@1135; be_u32@1139; Err@1140; Ok@1141; be_f64@1160; be_u64@1164; Err@1165; Ok@1166; le_f32@1185; le_u32@1189; Err@1190; Ok@1191; le_f64@1210; le_u64@1214; Err@1215; Ok@1216; f32@1245; f64@1284; hex_u32@1314; recognize_float@1355; recognize_float_or_exceptions@1382; crate::Err::Error@1394; crate::Err::Failure@1395; crate::Err::Incomplete@1396; recognize_float_parts@1421; let@1435; Some@1436; Some@1446; let@1456; Some@1477; let@1497; Some@1498; Some@1499; float@1530; Some@1558; double@1584; Some@1612; tests@1621; i8_tests@1635; i16_tests@1644; u24_tests@1654; i24_tests@1670; i32_tests@1686; i64_tests@1710; i128_tests@1756; le_i8_tests@1865; le_i16_tests@1873; le_u24_tests@1881; le_i24_tests@1891; le_i32_tests@1901; le_i64_tests@1915; le_i128_tests@1935; be_f32_tests@1981; be_f64_tests@1990; le_f32_tests@2002; le_f64_tests@2011; hex_u32_tests@2023; float_test@2044; configurable_endianness@2097; be_tst16@2100; le_tst16@2103; be_tst32@2109; le_tst32@2112; be_tst64@2124; le_tst64@2127; be_tsti16@2139; le_tsti16@2142; be_tsti32@2148; le_tsti32@2151; be_tsti64@2163; le_tsti64@2166; parse_f64@2180; recognize_float_or_exceptions@2182; Err@2183; Ok@2184; Some@2189; floats@2199
Dependencies: crate::branch::alt@3; crate::bytes::streaming::tag@4; crate::character::streaming::@5; crate::combinator::@6; crate::error::@7; crate::internal::@8; crate::lib::std::ops::@9; crate::sequence::@10; crate::traits::@11; super::@1622; crate::error::ErrorKind@1623; crate::internal::@1624; proptest::prelude::@1625; crate::number::Endianness@2098; crate::traits::ParseTo@2181

`third_party/rust/nom/src/sequence/mod.rs` | `735ab45cc73485392ceb862200cf8a5e71bbdea0` | 8773 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: tests@4; pair@29; preceded@63; terminated@97; separated_pair@133; delimited@172; Tuple@192; parse@194; parse@200; parse@226; parse@259; tuple@275
Dependencies: crate::error::ParseError@6; crate::internal::@7

`third_party/rust/nom/src/sequence/tests.rs` | `30ad0d67833d81cb7c2a368e876ab04281e50e97` | 7785 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: single_element_tuples@8; B@21; C@27; error_to_string@37; complete@72; err_test@74; pair_test@88; pair_abc_def@89; separated_pair_test@120; sep_pair_abc_def@121; preceded_test@152; preceded_abcd_efgh@153; terminated_test@184; terminated_abcd_efgh@185; delimited_test@216; delimited_abc_def_ghi@217; tuple_test@259; tuple_3@260; unit_type@277
Dependencies: super::@1; crate::bytes::streaming::@2; crate::error::@3; crate::internal::@4; crate::number::streaming::be_u16@5; crate::character::complete::alpha1@9; crate::@10; util::@33; crate::bytes::complete::tag@73

`third_party/rust/nom/src/str.rs` | `1a8b8ba2d4952cb7611aec88f3e896764f9898d9` | 13621 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: test@2; tagtr_succeed@12; test@15; test@19; Ok@20; tagtr_incomplete@39; Err@47; tagtr_error@59; Err@65; take_s_succeed@76; Ok@83; take_until_succeed@105; Ok@113; take_s_incomplete@137; Err@144; is_alphabetic@155; take_while@160; f@163; take_while1@178; f@181; take_till_s_succeed@199; till_s@203; test@206; test@209; Ok@210; take_while_succeed_none@232; while_s@238; test@241; test@244; Ok@245; is_not_succeed@267; test@272; test@275; Ok@276; take_while_succeed_some@298; while_s@304; test@315; test@318; Ok@319; is_not_fail@341; test@344; test@347; Err@348; take_while1_succeed@357; while1_s@363; test@374; test@377; Ok@378; take_until_incomplete@400; Err@408; is_a_succeed@418; test@423; test@426; Ok@427; take_while1_fail@449; while1_s@453; test@456; test@459; Err@460; is_a_fail@470; test@473; test@476; Err@477; take_until_error@486; Err@494; recognize_is_a@505; f@509; utf8_indexing@518; dot@519; case_insensitive@528; test@529
Dependencies: crate::@4; crate::@5; crate::bytes::streaming::tag@40; crate::bytes::streaming::take@138; crate::internal::Needed@153; crate::bytes::streaming::take_while@161; crate::bytes::streaming::take_while1@179; crate::bytes::complete::take_while@233; crate::bytes::complete::take_while@299; crate::bytes::complete::take_while1@358; crate::bytes::streaming::take_until@401; crate::bytes::complete::take_while1@450; crate::bytes::streaming::take_until@487

`third_party/rust/nom/src/traits.rs` | `394e5bc3a59e045b2684e8e88a2758d2c088b7cd` | 35275 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: InputLength@18; input_len@21; input_len@26; input_len@33; input_len@40; Offset@48; offset@50; offset@54; offset@63; offset@72; offset@81; AsBytes@90; as_bytes@92; as_bytes@97; as_bytes@104; as_bytes@111; as_bytes@118; as_bytes@128; as_bytes@135; AsChar@151; as_char@153; is_alpha@159; is_alphanum@163; is_dec_digit@165; is_hex_digit@167; is_oct_digit@169; len@171; as_char@176; is_alpha@180; is_alphanum@184; is_dec_digit@188; is_hex_digit@192; is_oct_digit@198; len@202; as_char@208; is_alpha@212; is_alphanum@216; is_dec_digit@220; is_hex_digit@224; is_oct_digit@230; len@234; as_char@241; is_alpha@245; is_alphanum@249; is_dec_digit@253; is_hex_digit@257; is_oct_digit@261; len@265; as_char@272; is_alpha@276; is_alphanum@280; is_dec_digit@284; is_hex_digit@288; is_oct_digit@292; len@296; InputIter@302; Item@306; Iter@310; IterElem@313; iter_indices@316; iter_elements@318; position@320; slice_index@324; InputTake@328; take@330; take_split@332; Item@336; Iter@337; IterElem@338; iter_indices@341; iter_elements@345; position@349; slice_index@356; take@367; take_split@371; Item@378; Iter@379; IterElem@380; iter_indices@382; iter_elements@386; position@389; predicate@394; slice_index@401; take@418; take_split@424; UnspecializedInput@439; InputTakeAtPosition@444; Item@448; split_at_position@454; split_at_position1@464; split_at_position_complete@476; split_at_position1_complete@489; Item@501; split_at_position@503; Some@508; split_at_position1@513; Some@522; Some@523; split_at_position_complete@528; Err@536; split_at_position1_complete@541; Err@550; Item@563; split_at_position@565; Some@570; split_at_position1@575; Some@584; Some@585; split_at_position_complete@590; Some@598; split_at_position1_complete@603; Some@612; Some@613; Item@626; split_at_position@628; Some@634; split_at_position1@639; Some@648; Some@650; split_at_position_complete@655; Some@664; split_at_position1_complete@675; Some@684; Some@686; CompareResult@707; Compare@717; compare@719; compare_no_case@727; lowercase_byte@730; compare@739; Some@743; compare_no_case@771; compare@792; Some@799; compare_no_case@811; compare@828; compare_no_case@832; compare@839; compare_no_case@845; Some@852; compare@866; compare_no_case@870; FindToken@876; find_token@878; find_token@882; find_token@888; find_token@894; find_token@900; find_token@906; find_token@912; find_token@918; find_token@924; FindSubstring@930; find_substring@932; find_substring@936; let@941; Some@942; find_substring@970; find_substring@977; ParseTo@983; parse_to@986; parse_to@990; parse_to@996; Slice@1006; slice@1008; slice@1013; input_len@1055; input_len@1062; Item@1068; Iter@1069; IterElem@1070; iter_indices@1072; iter_elements@1076; position@1080; slice_index@1085; compare@1092; compare_no_case@1097; compare@1104; compare_no_case@1109; find_token@1115; find_token@1121; ExtendInto@1138; Item@1142; Extender@1145; new_builder@1148; extend_into@1150; Item@1155; Extender@1156; new_builder@1159; extend_into@1163; Item@1170; Extender@1171; new_builder@1174; extend_into@1178; Item@1185; Extender@1186; new_builder@1189; extend_into@1193; Item@1200; Extender@1201; new_builder@1204; extend_into@1208; Item@1215; Extender@1216; new_builder@1219; extend_into@1223; ToUsize@1234; to_usize@1236; to_usize@1241; to_usize@1248; to_usize@1255; to_usize@1263; to_usize@1271; ErrorConvert@1277; convert@1279; convert@1283; convert@1289; convert@1296; convert@1305; convert@1316; convert@1326; convert@1334; HexDisplay@1340; to_hex@1343; to_hex_from@1347; to_hex@1356; to_hex_from@1361; to_hex@1404; to_hex_from@1409; tests@1415; test_offset_u8@1419; test_offset_str@1431
Dependencies: crate::error::@2; crate::internal::@3; crate::lib::std::iter::@4; crate::lib::std::ops::@5; crate::lib::std::slice::Iter@6; crate::lib::std::str::from_utf8@7; crate::lib::std::str::CharIndices@8; crate::lib::std::str::Chars@9; crate::lib::std::str::FromStr@10; crate::lib::std::string::String@13; crate::lib::std::vec::Vec@15; crate::error@1294; super::@1416

`third_party/rust/nom/tests/arithmetic.rs` | `5b627a97a5c47c12ef2b9275bf6c4b3c20f05da9` | 2292 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: parens@17; factor@25; term@35; expr@51; factor_test@68; term_test@76; expr_test@83; parens_test@90
Dependencies: nom::@1; std::str::FromStr@14

`third_party/rust/nom/tests/arithmetic_ast.rs` | `ca1511096099a7d66dff1659d3a8146d26525d15` | 4029 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Expr@16; Oper@26; fmt@34; Value@37; Add@38; Sub@39; Mul@40; Div@41; Paren@42; fmt@48; Value@51; Add@52; Sub@53; Mul@54; Div@55; Paren@56; parens@61; factor@69; fold_exprs@79; term@91; expr@107; factor_test@124; term_test@132; expr_test@140; parens_test@156
Dependencies: std::fmt@1; std::fmt::@2; std::str::FromStr@4; nom::@6; self::Expr::@35; self::Expr::@49

`third_party/rust/nom/tests/css.rs` | `ad3d72b8fae22aeb9cfb2ffe3d658a1c79ca9890` | 899 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Color@7; from_hex@13; is_hex_digit@17; hex_primary@21; hex_color@25; parse_color@33
Dependencies: nom::bytes::complete::@1; nom::combinator::map_res@2; nom::sequence::tuple@3; nom::IResult@4

`third_party/rust/nom/tests/custom_errors.rs` | `2021713341a205e7ab563abb3ae4df526758b397` | 1329 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: CustomError@13; from@16; from_error_kind@22; append@26; test1@31; test2@36; test3@41; test4@46
Dependencies: nom::bytes::streaming::tag@3; nom::character::streaming::digit1@4; nom::combinator::verify@5; nom::error::@6; nom::multi::count@8; nom::sequence::terminated@9; nom::IResult@10

`third_party/rust/nom/tests/escaped.rs` | `47c6a71e52613b47d19350a177613726f1e76454` | 732 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: esc@6; esc_trans@11; test_escaped@17; test_escaped_transform@23
Dependencies: nom::bytes::complete::escaped@1; nom::character::complete::digit1@2; nom::character::complete::one_of@3; nom::@4; nom::bytes::complete::@12

`third_party/rust/nom/tests/float.rs` | `634b189899bfbadbdb5ee0ae857eefaa9fa567c1` | 1420 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: unsigned_float@11; float@20; unsigned_float_test@33; float_test@42
Dependencies: nom::branch::alt@1; nom::bytes::complete::tag@2; nom::character::streaming::digit1@3; nom::combinator::@4; nom::sequence::@5; nom::IResult@6; std::str@8; std::str::FromStr@9

`third_party/rust/nom/tests/fnmut.rs` | `b1486cbe636c62df09d0adc6bd47772bfc48eaa0` | 653 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: parse@7; accumulate@24
Dependencies: nom::@1

`third_party/rust/nom/tests/ini.rs` | `e556f44a3c073df15ea4724b2c1b472b99dd2fdc` | 5368 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: category@15; key_value@22; keys_and_values@30; category_and_keys@36; categories@42; parse_category_test@57; Ok@69; parse_key_value_test@77; Ok@86; parse_key_value_with_space_test@94; Ok@103; parse_key_value_with_comment_test@111; Ok@120; parse_multiple_keys_and_values_test@128; Ok@140; parse_category_then_multiple_keys_and_values_test@151; Ok@165; parse_multiple_categories_test@176; Ok@193
Dependencies: nom::@1; std::collections::HashMap@12; std::str@13

`third_party/rust/nom/tests/ini_str.rs` | `3702303527615e1304688f75338bb04053fb130b` | 5366 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: is_line_ending_or_comment@12; not_line_ending@16; space_or_line_ending@20; category@24; key_value@31; keys_and_values_aggregator@42; keys_and_values@46; keys_and_values_aggregator@47; Ok@48; Err@49; category_and_keys@53; categories_aggregator@57; categories@61; categories_aggregator@62; Ok@63; Err@64; parse_category_test@69; Ok@81; parse_key_value_test@89; Ok@98; parse_key_value_with_space_test@106; Ok@115; parse_key_value_with_comment_test@123; Ok@132; parse_multiple_keys_and_values_test@140; Ok@152; parse_category_then_multiple_keys_and_values_test@163; Ok@177; parse_multiple_categories_test@188; Ok@203
Dependencies: nom::@1; std::collections::HashMap@10

`third_party/rust/nom/tests/issues.rs` | `7985702f6785309a724cd1ca132dd2e3180df6ae` | 6476 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Range@8; take_char@13; parse_int@22; parse_ints@32; spaces_or_int@36; Ok@45; Err@46; issue_142@54; usize_length_bytes_issue@66; take_till_issue@73; nothing@76; issue_655@85; twolines@87; issue_717@103; issue_647@110; Input@115; Data@118; list@123; data@130; issue_848_overflow_incomplete_bits_to_bytes@139; take@140; parser@144; issue_942@159; parser@161; issue_many_m_n_with_zeros@171; issue_1027_convert_error_panic_nonempty@179; Err::Error@188; issue_1231_bits_expect_fn_closure@200; example@204; issue_1282_findtoken_char@211; issue_1459_clamp_capacity@219; issue_1617_count_parser_returning_zero_size@234
Dependencies: nom::@5; nom::HexDisplay@23; nom::@24; std::str@30; nom::multi::length_data@67; nom::number::streaming::be_u16@68; nom::bytes::streaming::take_till@74; nom::character::streaming::@86; nom::bytes::complete::@104; nom::multi::separated_list0@105; nom::bytes::streaming::tag@111; nom::combinator::complete@112; nom::multi::separated_list0@113; nom::@114; nom::bytes::streaming::take@141; nom::bits::@145; nom::error::@160; nom::@164; nom::character::complete::char@172; nom::multi::many_m_n@173; nom::character::complete::char@180; nom::error::@181; nom::sequence::pair@182; nom::bits::@201; nom::error::Error@202; nom::sequence::tuple@203; nom::character::complete::one_of@212; nom::error::Error@213; nom::character::complete::char@220; nom::multi::many_m_n@223; nom::multi::count@228; nom::@235

`third_party/rust/nom/tests/json.rs` | `e8a06fd778a1370f8916263117d47cf17aa99add` | 5656 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: JsonValue@18; boolean@27; u16_hex@31; unicode_escape@35; character@60; string@82; ws@93; array@97; object@105; json_value@119; json@132; json_string@137; json_object@156; json_array@174; json_whitespace@185
Dependencies: nom::@3; std::collections::HashMap@15; JsonValue::@120; JsonValue::@157; JsonValue::@175; JsonValue::@186

`third_party/rust/nom/tests/mp4.rs` | `852bf29555f6eac1a4e21215a799e5323cb3b782` | 7771 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: mp4_box@15; be_u32@16; Ok@17; Err@25; FileType@31; Mvhd32@40; Mvhd64@70; mvhd32@98; mvhd64@150; MvhdBox@202; MoovBox@208; MP4BoxType@221; MP4BoxHeader@241; brand_name@246; filetype_parser@250; mvhd_box@263; unknown_box_type@277; box_type@281; moov_type@296; box_header@310; moov_header@316
Dependencies: nom::@3; std::str@13

`third_party/rust/nom/tests/multiline.rs` | `7378b9e3b4ddf447009e6859263a1db04a60f4f5` | 684 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: end_of_line@8; read_line@16; read_lines@20; read_lines_test@26
Dependencies: nom::@1

`third_party/rust/nom/tests/overflow.rs` | `ea513bb395bffe921f5164b74d22c6e441031028` | 3817 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: parser02@15; overflow_incomplete_tuple@20; overflow_incomplete_length_bytes@29; multi@30; overflow_incomplete_many0@43; multi@44; overflow_incomplete_many1@57; multi@60; overflow_incomplete_many_till@73; multi@76; overflow_incomplete_many_m_n@89; multi@92; overflow_incomplete_count@105; counter@108; overflow_incomplete_length_count@120; multi@124; overflow_incomplete_length_data@136; multi@137
Dependencies: nom::bytes::streaming::take@4; nom::multi::@6; nom::number::streaming::be_u64@8; nom::sequence::tuple@9; nom::@10; nom::multi::many1@58; nom::@74; nom::multi::many_m_n@90; nom::multi::count@106; nom::multi::length_count@121; nom::number::streaming::be_u8@122

`third_party/rust/nom/tests/reborrow_fold.rs` | `486617e427268d0b9110ef4d2dab77c1eb2d252e` | 771 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: atom@13; list@23
Dependencies: std::str@4; nom::bytes::complete::is_not@6; nom::character::complete::char@7; nom::combinator::@8; nom::multi::fold_many0@9; nom::sequence::delimited@10; nom::IResult@11

`third_party/rust/nss-rs/.cargo-checksum.json` | `f21782bb94901f49cecf112e0a45ac28d7b2020a` | 6240 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/.clippy.toml` | `5394331555196b6d72e6c87e130cf14d4001acdd` | 486 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/.rustfmt.toml` | `232030382d0db6ebe4c6896a6d756d8a536f4f4e` | 143 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/Cargo.lock` | `8f8194e5e82ba37db8a93cdcd172a4ee3a552082` | 15704 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/Cargo.toml` | `cd727e1a775c988826f5860311215d81eda96a61` | 9186 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/nss-rs/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/LICENSE-MIT` | `b4850c9520045155c4c3650841d02871375154c8` | 1062 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/README.md` | `530993fbaecdc1effa0b7207e48f281e90b032a2` | 1580 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/nss-rs/SECURITY.md` | `25413ad316d628d57536367dd1354f5261653aa4` | 924 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/nss-rs/bindings/bindings.toml` | `54aef246fd2d393f686ca749ec4f40f311e2649d` | 7703 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/bindings/nspr_err.h` | `204e771c49a3fcb5537f4e32c575411e3bda1967` | 320 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: prerr.h@7

`third_party/rust/nss-rs/bindings/nspr_error.h` | `8ff8ce202db0f2995bbac6531f7638b1a5f2009c` | 322 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: prerror.h@7

`third_party/rust/nss-rs/bindings/nspr_io.h` | `9997fb812e12179773e6f0793271a6b365febd1a` | 319 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: prio.h@7

`third_party/rust/nss-rs/bindings/nspr_lib.h` | `711cbf05c025dd09bb0e2900b9d13122a79390dc` | 321 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: prlink.h@7

`third_party/rust/nss-rs/bindings/nspr_time.h` | `f5596577fad4a5b1e75861472b8cf792120afe0a` | 321 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: prtime.h@7

`third_party/rust/nss-rs/bindings/nss_ciphers.h` | `f064f39c5d34e5b8c9b53236adb1c07495e61773` | 373 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: sslproto.h@8

`third_party/rust/nss-rs/bindings/nss_init.h` | `ae111bac2b313e47393b505a99b23928a698d52f` | 364 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: nss.h@7; ssl.h@8

`third_party/rust/nss-rs/bindings/nss_p11.h` | `6c5f106bb26a7f64d2b5ec42c45154e05795ccf7` | 419 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: cert.h@7; hasht.h@8; keyhi.h@9; pk11pub.h@10; pkcs11t.h@11; secoid.h@12

`third_party/rust/nss-rs/bindings/nss_prelude.h` | `72af8f03c92344a09b0a4ce37bc3f6f4813fcd9c` | 344 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: seccomon.h@7; secitem.h@8

`third_party/rust/nss-rs/bindings/nss_secerr.h` | `c2b2d4020c9a224a36303ee836819cf5cc6e065a` | 321 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: secerr.h@7

`third_party/rust/nss-rs/bindings/nss_ssl.h` | `1cde112cf23ef4adbd59ab094823a2efb6908d57` | 360 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: sslproto.h@7; ssl.h@8; sslexp.h@9

`third_party/rust/nss-rs/bindings/nss_sslerr.h` | `74a836f1e881d2a9ea6c9ffdcc9e84571f7e722a` | 321 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: sslerr.h@7

`third_party/rust/nss-rs/bindings/nss_sslopt.h` | `a14e1e69d1844cce39b48f437609db33229762ce` | 318 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: ssl.h@7

`third_party/rust/nss-rs/build.rs` | `198037c94569830ac9084cd749544685e7ad0e3a` | 24355 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: min_nss_version@30; Bindings@42; check_sorted@73; setup_clang@99; env::var@103; env::var@106; nss_dir@163; get_bash@206; build_nss@220; lib_stem@245; rerun_if_libs_changed@256; link_search@277; dynamic_link@282; maybe_link_freebl3@305; env::var@306; static_link@313; get_includes@389; include_flags@395; Pkcs11Types@405; int_macro@408; build_bindings@427; setup_pkg_config@490; Ok@502; Err@503; setup_standalone@548; setup_for_gecko@580; setup_for_gecko@637; process_config@641; main@675
Dependencies: std::@13; bindgen::@20; serde_derive::Deserialize@24; mozbuild::@581

`third_party/rust/nss-rs/install-nss/action.yml` | `1de31daf54ec38d2a3fd214c4e0c7664f548ac26` | 1352 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/nss-rs/src/aead/mod.rs` | `210935db0f04ab85511d84562db278b725e41894` | 19979 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: RecordProtectionOps@46; expansion@49; encrypt@56; encrypt_in_place@69; decrypt@76; decrypt_in_place@89; recprot@94; expand_label@97; expand_hkdf_label@124; expand_label_buf@138; xor_nonce@154; split_tag@171; SequenceNumber@181; c_int_len@184; Mode@193; AeadAlgorithms@209; Error@234; try_from@235; Aead@245; import_key@252; new@271; encrypt@294; encrypt_with_seq@333; decrypt@371; test@410; check0@417; decrypt@445; quic_retry@463; quic_server_initial@484; quic_chacha@528; roundtrip_encrypt_with_seq@554; encrypt_with_seq_aes128gcm@572; encrypt_with_seq_aes256gcm@578; encrypt_with_seq_chacha20poly1305@584
Dependencies: std::os::raw::c_char@8; std::ptr::null@10; std::@11; crate::@20; crate::@32; test_fixture::fixture_init@411; crate::aead::@413

`third_party/rust/nss-rs/src/aead/recprot.rs` | `5453cf38db2b8bdfb2a8d8ffb54879ec4d026749` | 6755 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: cipher_mech_and_key_len@25; make_ctx@30; aead_op@59; RecordProtection@93; new@104; expansion@128; encrypt@132; encrypt_in_place@167; decrypt@192; decrypt_in_place@219; fmt@243
Dependencies: std::@7; super::@12; crate::@16

`third_party/rust/nss-rs/src/aead/recprot_blapi.rs` | `4b8566e0d7550c5a0831d858aa782df0aa98c265` | 10293 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: RecordCipher@66; aead_op@86; RecordCipher::Aes@99; RecordCipher::ChaCha@123; RecordProtection@147; new@159; expansion@208; encrypt@212; encrypt_in_place@248; decrypt@274; decrypt_in_place@302; fmt@327
Dependencies: std::@13; zeroize::@18; super::@20; crate::@24

`third_party/rust/nss-rs/src/aead/recprot_null.rs` | `4d3190c88d12cfc6ef9fd13d544000c83cb3e8c3` | 6053 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: RecordProtection@14; decrypt_check@17; expansion@53; encrypt@57; encrypt_in_place@76; decrypt@85; decrypt_in_place@98; fmt@104; tests@111; aead@114; expansion@119; debug@124; encrypt_decrypt_roundtrip@129; encrypt_in_place_roundtrip@144; decrypt_empty_plaintext@159; decrypt_fails_too_short@170; decrypt_fails_bad_tag@177; decrypt_rejects_all_zero_data_bytes@189
Dependencies: std::fmt@7; super::@9; crate::@10; super::@112

`third_party/rust/nss-rs/src/agent.rs` | `af5bde06ccbd6a0281378adbdfcceab8999f3a47` | 50817 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: hex_snip_middle@55; HandshakeState@75; get_alpn@108; Some@130; Ok@131; Err@132; SecretAgentPreInfo@141; $v@149; new@163; max_early_data@195; ech_public_name@221; alpn@231; SecretAgentInfo@237; new@249; alpn@295; SecretAgent@307; new@329; create_fd@356; ready@411; configure@438; set_version_range@459; set_ciphers@469; set_groups@497; send_additional_key_shares@515; set_option@526; enable_0rtt@535; disable_end_of_early_data@544; set_alpn@561; set_certificate_compression@606; extension_handler@630; set_raw@642; HandshakeState::Complete@663; preinfo@676; peer_certificate@682; export_keying_material@697; alert@722; authenticated@731; capture_error@737; update_state@748; handshake@780; HandshakeState::Authenticated@788; setup_raw@812; handshake_raw@827; close@855; has_secret@889; read_secret@895; write_secret@901; ech_config@907; drop@913; fmt@919; ResumptionToken@925; fmt@932; Client@957; new@975; server_name@1031; ready@1035; resumption_token@1048; has_resumption_token@1054; enable_resumption@1064; enable_ech@1087; fmt@1114; ZeroRttCheckResult@1121; ZeroRttChecker@1134; check@1135; AllowZeroRtt@1142; check@1144; ZeroRttCheckState@1151; new@1156; Server@1164; load_cert_and_key@1172; new@1189; new_with_ocsp_and_scts@1212; ZeroRttCheckResult::HelloRetryRequest@1278; enable_0rtt@1299; send_ticket@1327; enable_ech@1343; fmt@1367; Agent@1374; Target@1380; deref@1381; Self::Client@1383; Self::Server@1384; deref_mut@1390; Self::Client@1392; Self::Server@1393; tests@1400; resumption_token_debug_impl@1404
Dependencies: std::@12; log::@26; crate::@29; crate::ResumptionToken@1401

`third_party/rust/nss-rs/src/agentio.rs` | `1903afb20965bbb0387ce3b74117bc3f77310a68` | 11911 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: PrFd@36; PrStatus@37; as_c_void@42; Record@48; new@56; write@65; fmt@79; RecordList@92; append@98; setup@125; AgentIoInputContext@134; drop@139; AgentIoInput@145; wrap@153; read_input@162; reset@184; fmt@192; AgentIo@198; borrow@207; wrap@211; save_output@217; take_output@223; fmt@230; Ok@251; Err@252; tests@383; ingest_errors@389; formatting@424
Dependencies: std::@12; log::trace@22; crate::@24; std::ptr::addr_of_mut@384; super::@386

`third_party/rust/nss-rs/src/auth.rs` | `7e0ff2e7bfdebb4f9308d737524bec466360649a` | 2846 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: AuthenticationStatus@14; from@40; from@48; tests@55; authentication_status_from_error_code@59
Dependencies: strum::FromRepr@7; crate::err::@9; super::@56

`third_party/rust/nss-rs/src/cert.rs` | `8d44ee160fc7577527d113b3d972fa158b8fa18c` | 8346 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: CertificateInfo@30; peer_certificate_chain@39; stapled_ocsp_responses@51; signed_cert_timestamp@68; IntoIter@81; Item@82; into_iter@83; new@89; iter@98; stapled_ocsp_responses@103; signed_cert_timestamp@108; UnsafeCertCompression@115; CertificateCompressor@128; encode@147; decode@159; T::decode@181
Dependencies: std::@7; log::error@13; crate::@15

`third_party/rust/nss-rs/src/constants.rs` | `61da3c562d14957df2e256e625fab715e756492c` | 6965 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Alert@15; Epoch@19; Error@31; try_from@33; from@39; $t@48; ciphers@67; tests@174; epoch_into_usize@178
Dependencies: enum_map::Enum@7; strum::FromRepr@8; crate::@10; super::Epoch@175

`third_party/rust/nss-rs/src/der.rs` | `eb92565f46b3260703865109de0b0abbe8b0a639` | 4347 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: write_tag_and_length@34; integer@49; bit_string@70; null@78; object_id@84; sequence@91; octet_string@101; context_specific_explicit_tag@108
Dependencies: crate::Error@7

`third_party/rust/nss-rs/src/ec.rs` | `3d64ac912f4e11fbaa43b70636fbff44ca1d9197` | 9052 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: EcCurve@32; EcdhPublicKey@40; EcdhPrivateKey@41; EcdhKeypair@44; Ecdh@50; generate_keypair@58; object_id@91; ec_curve_to_oid@95; ecdh_keygen@117; export_ec_private_key_pkcs8@159; import_ec_public_key_from_spki@168; import_ec_private_key_pkcs8@188; export_ec_private_key_from_raw@217; ecdh@226; convert_to_public@250; sign@258; sign_ecdsa@282; sign_eddsa@286; verify@290; verify_ecdsa@317; verify_eddsa@321
Dependencies: std::ptr@7; crate::@11

`third_party/rust/nss-rs/src/ech.rs` | `b005d17a19408f76381c5fe1f05dc8e6e6b59b0e` | 6137 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: convert_ech_error@67; generate_keys@96; encode_config@153
Dependencies: std::@7; log::trace@13; crate::@15

`third_party/rust/nss-rs/src/err.rs` | `7e042dde806b660af8815fea4a3d2601264fe7b1` | 11024 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: codes@13; nspr@21; mozpkix@26; mozilla_pkix_ErrorCode@32; Res@53; Error@56; last_nss_error@114; from@120; from@125; from@130; from@135; wrap_str_fn@147; Err@162; IntoResult@167; Ok@169; into_result@174; into_result@177; Ok@190; into_result@192; Ok@200; into_result@202; secstatus_to_res@211; tests@217; set_error_code@225; error_code@234; is_ok@242; is_err@247; is_err_zero_code@265; blocked@281; error_from_std_errors@298; mozpkix_error_codes_are_negative@311
Dependencies: std::@7; crate::nss_prelude::@9; thiserror::Error@18; std::ffi::CStr@145; test_fixture::fixture_init@218; crate::@220; std::ffi::CString@299; crate::err::mozpkix::@312

`third_party/rust/nss-rs/src/exp.rs` | `1963b0cf76a44606885f4bc0ef71deeef277e139` | 2447 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: $n@16; ExperimentalAPI@17; test@41; nonexistent_fn@52
Dependencies: crate::err::Error@42

`third_party/rust/nss-rs/src/ext.rs` | `06027c8b515d7352454c930ffbcdf373ce3b4977` | 7666 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ExtensionWriterResult@49; ExtensionHandlerResult@54; ExtensionHandler@59; write@71; handle@83; BoxedExtensionHandler@91; ExtensionTracker@93; wrap_handler_call@101; Self::wrap_handler_call@130; ExtensionWriterResult::Write@131; ExtensionHandlerResult::Alert@161; new@181; fmt@216
Dependencies: std::@12; crate::@20

`third_party/rust/nss-rs/src/freebl/bindgen.h` | `35e83b9c6d3ec5135737b8ff6512c7f5c8cd8c67` | 2557 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: CK_ULONG@17; CK_ULONG@18; struct@19; struct@20; struct@21; struct@22; struct@23; struct@24; struct@25; struct@26; struct@27; struct@28; struct@29; struct@30; struct@31; struct@32; struct@33; struct@34; struct@35; struct@36; struct@37; struct@38; struct@39; struct@40; struct@41; struct@42; struct@43; struct@44; struct@45; struct@46; struct@47; struct@48; struct@49; struct@50; struct@51; struct@52; struct@53; struct@54; struct@55; struct@56; unsigned@57
Dependencies: blapit.h@12; prtypes.h@13; loader.h@59

`third_party/rust/nss-rs/src/freebl/mod.rs` | `7462df29eab3884906b2e8ed5c8d10251a30dac1` | 11298 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: AESContext@32; ChaCha20Poly1305Context@37; ChaChaOpFn@43; generated@67; PLArenaPool@73; KyberParams@76; AesCreateFn@83; AesDestroyFn@91; AesEncryptFn@92; AesAeadFn@100; ChaChaCreateFn@112; ChaChaDestroyFn@114; ChaCha20XorFn@115; FreeblFns@125; nspr_lib@138; FREEBL_GetVector@144; freebl_result@149; init@156; freebl@162; require@166; load_freebl_fns@173; freebl_vector@209; GetVectorFn@211; AES_CreateContext@248; aes_context@268; AES_Encrypt@291; AES_AEAD@307; ChaCha20Poly1305_CreateContext@336; ChaCha20_Xor@349; chacha20_poly1305_op@362; destroy_aes_context@370; destroy_chacha20_context@376
Dependencies: std::ffi::CStr@15; std::@16; log::error@21; crate::@23; super::@68; generated::FREEBLVectorStr@79; nspr_lib::@210

`third_party/rust/nss-rs/src/freebl/vector.rs` | `eed1bd35155d89cd0506ee8b4b043414a9e30403` | 74499 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: __BindgenOpaqueArray@40; default@42; PRUint8@46; PRUint32@47; PRIntn@48; PRBool@50; PRFuncPtr@51; SECItem@52; _SECStatus@56; CK_ULONG@58; CK_HEDGE_TYPE@59; CK_ML_DSA_PARAMETER_SET_TYPE@60; DESContext@61; RC2Context@62; RC4Context@63; RC5Context@64; CamelliaContext@65; MD2Context@66; MD5Context@67; SHA1Context@68; SHA256Context@69; SHA224Context@70; SHA512Context@71; SHA384Context@72; SHA3_224Context@73; SHA3_256Context@74; SHA3_384Context@75; SHA3_512Context@76; SHAKE_128Context@77; SHAKE_256Context@78; AESKeyWrapContext@79; SEEDContext@80; ChaCha20Context@81; BLAKE2BContext@82; RSAPublicKey@83; RSAPrivateKey@84; PQGParams@86; PQGVerify@87; DSAPublicKey@88; DSAPrivateKey@89; MLDSAPrivateKey@90; MLDSAPublicKey@91; MLDSAContext@92; DHParams@94; DHPrivateKey@95; ECParams@96; ECPublicKey@97; ECPrivateKey@98; SECHashObject@99; HASH_HashType@113; CMACContext@114; CMACCipher@116; HMACContext@117; FREEBLVectorStr@120

`third_party/rust/nss-rs/src/hash.rs` | `554b84ba71bb21bbf8fe4cb9e84cd9d6f988295e` | 1628 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: HashAlgorithm@18; hash@45; Ok@49
Dependencies: crate::@7

`third_party/rust/nss-rs/src/hkdf.rs` | `6bd36d44d48172880ad35e246195a840aa02ce29` | 9216 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: HkdfAlgorithm@51; KeyMechanism@58; ParamItem@77; new@83; generate_key@119; import_key@133; extract@156; expand_label@173; Hkdf@200; import_secret@211; extract@239; expand_params@274; expand_key@288; expand_data@306
Dependencies: std::@9; crate::@15

`third_party/rust/nss-rs/src/hmac.rs` | `2cb07dcfb54f1fd6e172a61f89651b3c243e6acb` | 3132 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: HmacAlgorithm@26; hmac@65
Dependencies: std::ptr@9; crate::@11

`third_party/rust/nss-rs/src/hp/header_protection.rs` | `7b4962eb580ed6bdf914cb6dec54cfb9b7b8e9f5` | 5540 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: make_aes_ctx@27; Key@44; extract@50; try_clone@96; Self::Chacha@105; mask@109; Self::Chacha@129
Dependencies: std::@10; super::@15; crate::@16

`third_party/rust/nss-rs/src/hp/header_protection_blapi.rs` | `562501a27be4864807b451359b9f7d4f58d25176` | 4793 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Key@32; extract@47; try_clone@70; Self::Chacha@80; mask@84; Self::Chacha@105
Dependencies: std::os::raw::c_uint@10; zeroize::ZeroizeOnDrop@12; super::SAMPLE_SIZE@14; crate::@15

`third_party/rust/nss-rs/src/hp/mod.rs` | `0805bc17142c110ddfac07430a66cdd82e70be6a` | 2711 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: header_protection@34; Key@39; extract@55; try_clone@64; mask@73; fmt@79; tests@86; debug_format@94
Dependencies: std::@7; crate::@12; crate::@87

`third_party/rust/nss-rs/src/hpke.rs` | `91346b6a4e1a585c8908606a831a400d094f3be1` | 10697 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: KemAlgorithm@23; Config@29; new@36; kem@40; kdf@44; aead@48; supported@52; default@65; Exporter@74; export@75; destroy_hpke_context@78; new@85; export@101; HpkeS@120; new@128; config@137; enc@142; seal@151; export@162; Target@168; deref@169; HpkeR@175; new@183; config@203; decode_public_key@207; open@225; export@236; Target@242; deref@243; generate_key_pair@249; test@308; make@318; seal_open@327; seal_open_gcm@349; seal_open_chacha@354
Dependencies: std::@7; super::@14; crate::@18; super::@309; crate::@310

`third_party/rust/nss-rs/src/lib.rs` | `d7939b1bdc79bb8e522effda195798b55d59243c` | 6940 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: agent@9; agentio@10; auth@11; cert@12; constants@13; ech@14; util@16; err@18; exp@20; ext@21; freebl@23; hkdf@24; hp@25; aead@27; der@28; ec@29; hash@30; hmac@31; p11@32; pbkdf2@33; pk11_utils@34; prio@35; replay@36; secrets@37; selfencrypt@38; ssl@39; time@40; _link_anchor@53; nss_prelude@81; nss@95; NssLoaded@100; drop@108; version_check@119; enable_ssl_trace@133; init_once@139; init@190; init_db@206; assert_initialized@214; null_safe_slice@230
Dependencies: std::@42; log::error@49; windows::Win32::Security::Authentication::Identity::RtlGenRandom@54; crate::nss_prelude::@96

`third_party/rust/nss-rs/src/p11.rs` | `7491f5db2c1669f0b57a5afc2ae144fd1b7db20d` | 14728 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: hex_with_len@28; nss_p11@39; key_data@86; key_data_alt@98; fmt@113; key_data@136; fmt@160; internal@172; internal_key_slot@176; token_name@181; authenticate@191; check_user_password@199; logout@204; find_key_by_nickname@211; generate_token_key@224; all_token_slots@250; key_data@290; Some@297; as_bytes@301; fmt@307; default@317; destroy_pk11_context@322; randomize@336; randomize@351; RandomCache@358; randomize@376; random@401; test@416; randomness@426; cache_random_lengths@437; key_operations@461; null_pointer_error@489
Dependencies: std::@14; crate::@21; std::fmt::Write@29; crate::nss_prelude::@52; crate::null_safe_slice@58; std::ptr::null_mut@417; test_fixture::fixture_init@419; super::RandomCache@421; crate::@422; crate::randomize@427; crate::ech::generate_keys@462

`third_party/rust/nss-rs/src/pbkdf2.rs` | `63cca172e1ad0b5361b58573db81ddd865cdb206` | 4802 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: pbkdf2@25; tests@75; rfc_7914_vector_1@81; rfc_7914_vector_iter_2@95; pbkdf2_sha384_vector@107; pbkdf2_sha512_vector@118; deterministic_across_calls@129; different_salt_different_key@151
Dependencies: std::@7; crate::@9; test_fixture::fixture_init@76; super::@78

`third_party/rust/nss-rs/src/pk11_utils.rs` | `01aac33f39de48fea9a0d96e3d2bf7e352f0de66` | 3286 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Pkcs11Uri@10; percent_decode@14; u8::from_str_radix@22; percent_encode@34; parse@52; build@69; tests@74; parse_simple@80; parse_no_token@87; parse_multiple_attrs@94; parse_not_pkcs11@101; build_uri@107; roundtrip@116
Dependencies: crate::err::@7; std::fmt::Write@42; test_fixture::fixture_init@75; super::@77

`third_party/rust/nss-rs/src/prio.rs` | `4918c3738bd7225fe1b50e4a7102fe02590295c3` | 556 bytes | imported-path,source | UTF-8 | mode 100644

`third_party/rust/nss-rs/src/replay.rs` | `80b5ebca7e7d5c065eed949a3d1989a3b4515901` | 2791 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: AntiReplay@46; new@58; config_socket@76; tests@83; creation@87
Dependencies: std::@7; crate::@13; std::time::Duration@84

`third_party/rust/nss-rs/src/result.rs` | `0c0fdbd57b4bc7f0df217019bab8113d2cf1a522` | 3868 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: result@16; result_or_blocked@21; wrap_str_fn@25; result_helper@38; tests@58; set_error_code@67; is_ok@72; is_err@77; is_err_zero_code@98; blocked_as_error@117; is_blocked@135
Dependencies: std::ffi::CStr@7; crate::@9; test_fixture::fixture_init@59; super::@61; crate::@62

`third_party/rust/nss-rs/src/secrets.rs` | `ee32b00aa58f5583f3892a3ab6ee5cbe015f3ce5` | 4292 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: SecretDirection@38; from@44; DirectionalSecrets@50; put@55; has@60; take@64; Secrets@74; put_raw@99; put@105; SecretHolder@116; register@123; has@128; take_read@132; take_write@136; default@142
Dependencies: std::@9; enum_map::EnumMap@11; log::debug@12; strum::FromRepr@13; crate::@15

`third_party/rust/nss-rs/src/selfencrypt.rs` | `3b2397d298f65fd552977baed4b53e5d3098b579` | 6269 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: hex@20; SelfEncrypt@29; new@46; make_aead@57; rotate@70; seal@87; open@144
Dependencies: std::@7; log::@9; crate::@11

`third_party/rust/nss-rs/src/sig.rs` | `e3ce8b367950c7fbd70329f534e19c32ae8c509a` | 4122 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: SignatureAlgorithm@27; Signature@43; sign@49; verify@56; algorithm@61; bytes@65; tests@71; test_ecdsa_p384_sha384_verify@77
Dependencies: nss_rs::ec::@23; nss_rs::HashAlgorithm@24; base64::@72; super::@74

`third_party/rust/nss-rs/src/ssl.rs` | `96d1636da74dd8ba22566e7897967741262d7a4a` | 4615 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: nss_ssl@16; SSLOption@43; Opt@55; map_enabled@78; set@86; tests@142; num_ciphers@146
Dependencies: std::os::raw::@7; crate::@9; crate::@30; super::@143

`third_party/rust/nss-rs/src/time.rs` | `eb52c60155ff176b8ceb1d0d32a4466aa2fe3f53` | 10054 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: TimeZero@39; baseline@51; get_base@80; init@91; Time@97; from@103; Error@111; try_from@112; Error@127; try_into@128; from@149; Interval@156; Error@161; try_from@162; Error@170; try_into@171; TimeHolder@178; bind@189; set@193; default@200; test@207; convert_stable@217; past_prtime@229; past_instant@240; timezero_baseline_future@255; timezero_baseline_past@263; timezero_baseline_past_prtime@270; negative_interval@295; overflow_interval@304
Dependencies: std::@12; crate::@20; std::@208; super::@213; crate::err::Res@214

`third_party/rust/nss-rs/src/util.rs` | `28ad1b6a9cc718a9c01e398c8a5f9ca9ebff9116` | 9807 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: $name@20; from_ptr@29; Ok@36; into_result@38; Target@44; deref@46; drop@54; clone@64; as_slice@84; destroy_secitem@102; into_vec@116; destroy_secitem_array@126; Item@135; IntoIter@136; into_iter@137; as_ref@145; ScopedSECItemArrayIterator@150; Item@155; next@156; SECItemMut@171; drop@178; as_slice@191; SECItemBorrowed@218; as_mut@233; as_slice@241; wrap@273; wrap_struct@289
Dependencies: std::@7; crate::@9

`third_party/rust/nss-rs/tests/aead.rs` | `70cc17633d8089a6e01e69c580af008278f3935e` | 5311 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: common@18; make_secret@34; make_aead@39; aead_encrypt_decrypt@45; aead_encrypt_in_place_too_small_buffer@120; roundtrip_aes128@131; roundtrip_aes256@136; roundtrip_chacha20@141
Dependencies: nss_rs::@9; test_fixture::fixture_init@16

`third_party/rust/nss-rs/tests/aead_fips.rs` | `40b0ce7c54208b02f529cd462643ca5ed8a67a90` | 1828 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: common@25; blapi_fips_roundtrip@31
Dependencies: nss_rs::constants::@20; test_fixture::fixture_init_fips@23

`third_party/rust/nss-rs/tests/agent.rs` | `5224ce25c6e78701e679955a5afa9697f8fd5fc9` | 32049 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: handshake@10; make_client@19; make_server@25; basic@31; reject_certificate_fails_handshake@82; check_client_preinfo@105; check_server_preinfo@114; raw@124; ocsp_stapling_and_signed_cert_timestamps@171; chacha_client@193; server_prefers_first_client_share@214; server_prefers_second_client_share@235; p256_server@256; p256_server_hrr@271; alpn@292; bad_alpn@307; alpn_multi@318; alpn_server_pref@337; alpn_no_protocol@356; alpn_client_only@369; alpn_server_only@382; resume@395; zero_rtt@411; zero_rtt_no_eoed@435; RejectZeroRtt@465; check@467; reject_zero_rtt@474; close@498; close_client_twice@508; ech@518; ech_retry@539; connection_succeeds_when_server_and_client_support_cert_compr_copy@599; IncDecCompression@600; decode@608; encode@616; connection_succeeds_when_server_and_client_default_encoding@643; DefaultEncoding@644; decode@652; CopyCompressionNoEncoder@676; decode@682; connection_succeeds_when_server_and_client_support_cert_compr_copy_without_encoder@690; connection_succeeds_when_only_server_support_cert_compr@709; connection_succeeds_when_only_client_support_cert_compr@725; connection_fails_when_decoding_fails@741; CopyCompressionDecoderReturnsErr@742; decode@750; connection_fails_when_encoding_fails@773; CopyCompressionEncoderReturnsErr@774; encode@782; decode@790; connection_fails_encoder_returned_too_long@813; CompressionEncoderReturnsTooLong@814; encode@821; decode@829; connected_pair@851; export_keying_material_basic@860; export_keying_material_differs_across_connections@871; export_keying_material_different_labels@894; export_keying_material_different_contexts@913; export_keying_material_before_handshake@932; export_keying_material_zero_length@945; export_keying_material_same_for_both_sides@957
Dependencies: std::ffi::CStr@1; nss_rs::@3; test_fixture::@11; crate::handshake::@13

`third_party/rust/nss-rs/tests/common/mod.rs` | `781e18c9dc0b785ac9f05c93ddf5665660f798f0` | 1894 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: import_secret@19; roundtrip@24
Dependencies: nss_rs::@7

`third_party/rust/nss-rs/tests/ec.rs` | `b6c7c68f806c17c00192a0ef6c521fc9329b6110` | 3166 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: clone@14; export_raw_extractable@38; export_raw_sensitive_reports_failure@47; keygen_p256@57; keygen_p384@73; keygen_p521@89; keygen_ed25519@105; keygen_x25519@115
Dependencies: nss_rs::@7; test_fixture::fixture_init@11

`third_party/rust/nss-rs/tests/ext.rs` | `1ec1581ec39ab5732bdce82fe0adebb9e3cb4758` | 8893 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: handshake@18; NoopExtensionHandler@24; noop_extension_handler@29; SimpleExtensionHandler@45; write@57; handle@73; simple_extension@91; EchExtensionHandler@118; write@135; handle@157; ech_extension@178; ech_retry@214
Dependencies: std::@7; handshake::forward_records@9; nss_rs::@10; test_fixture::@16; crate::handshake::connect@19

`third_party/rust/nss-rs/tests/handshake.rs` | `ab90bfc1f3b13b340bd1bc7a556d2885b34c11d6` | 6161 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: forward_records@25; handshake@45; connect_at@87; connect@95; connect_fail@105; Resumption@117; PermissiveZeroRttChecker@125; default@130; check@136; zero_rtt_setup@147; resumption_setup@170
Dependencies: std::@9; log::info@11; nss_rs::@12; test_fixture::@16

`third_party/rust/nss-rs/tests/hkdf.rs` | `0ebaa4d7b5c4c3cde0e22115c80ff7b2deb1603b` | 6131 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: cipher_hash_len@36; import_keys@44; extract@52; extract_sha256@62; extract_sha384@73; derive_secret@85; derive_secret_sha256@97; derive_secret_sha384@108; expand_label@120; expand_label_sha256@138; expand_label_sha384@149; unsupported_version@162; unsupported_cipher@169
Dependencies: nss_rs::@7; test_fixture::fixture_init@15

`third_party/rust/nss-rs/tests/hp.rs` | `65c26a0cec4c304405e39e39061f28421cd174e0` | 2207 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: make_hp@16; hp_test@25; aes128@39; aes256@49; chacha20_ctr@59
Dependencies: nss_rs::@7; test_fixture::fixture_init@14

`third_party/rust/nss-rs/tests/init.rs` | `93c7a71e066006f8f2a0a24cfae5c20254bfce4f` | 1791 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: nss_init@27; init_nodb@34; init_withdb@44; init_idempotent@55
Dependencies: nss_rs::assert_initialized@14; nss_rs::init@16; nss_rs::init_db@18; nss_rs::nss_prelude::@28

`third_party/rust/nss-rs/tests/selfencrypt.rs` | `06f6f445db9d813658ec8e841b3fa1c13f4e20af` | 2926 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: se_create@18; sealed@26; seal_open@34; seal_rotate_open@41; seal_rotate_twice_open@49; damage_version@58; assert_bad_data@65; damage_salt@73; damage_ciphertext@81; damage_auth_tag@89; truncate@98; truncate_header@105
Dependencies: nss_rs::@10; test_fixture::fixture_init@15

`third_party/rust/num-bigint/.cargo-checksum.json` | `a9c178f3dbb0b12656fde4b830f9342d9b8623f8` | 4517 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-bigint/.cargo_vcs_info.json` | `e144459e81c34699bfa2faebb00611a3b7284c07` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-bigint/Cargo.toml` | `0218bbdfcec73647fd410388eb5656ffbefce07f` | 2045 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-bigint/Cargo.toml.orig` | `720512a62157b2acbe2d1cdaff1c5d948b03e21e` | 1510 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-bigint/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-bigint/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-bigint/README.md` | `cce185b9da331e615d2ee29a8d9a4f13a0d688eb` | 3152 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-bigint/RELEASES.md` | `bc4c35348d48d27aa5c00d060daa9aa8a4f98ca1` | 14450 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-bigint/benches/bigint.rs` | `2279527478b8d68b33d116ca4a1f9514aec6b821` | 9619 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: rng@11; multiply_bench@14; divide_bench@22; remainder_bench@30; factorial@38; fib@48; fib2@60; multiply_0@71; multiply_1@76; multiply_2@81; multiply_3@86; multiply_4@91; multiply_5@96; divide_0@101; divide_1@106; divide_2@111; divide_big_little@116; remainder_0@121; remainder_1@126; remainder_2@131; remainder_big_little@136; factorial_100@141; fib_100@146; fib_1000@151; fib_10000@156; fib2_100@161; fib2_1000@166; fib2_10000@171; fac_to_string@176; fib_to_string@182; to_str_radix_bench@187; to_str_radix_02@194; to_str_radix_08@199; to_str_radix_10@204; to_str_radix_10_2@209; to_str_radix_16@214; to_str_radix_36@219; from_str_radix_bench@223; from_str_radix_02@232; from_str_radix_08@237; from_str_radix_10@242; from_str_radix_16@247; from_str_radix_36@252; rand_bench@256; rand_64@263; rand_256@268; rand_1009@273; rand_2048@278; rand_4096@283; rand_8192@288; rand_65536@293; rand_131072@298; shl@303; shr@315; hash@327; pow_bench@338; pow_bench_bigexp@352; pow_bench_1e1000@370; pow_bench_1e10000@375; pow_bench_1e100000@380; modpow@400; modpow_even@410; to_u32_digits@421; iter_u32_digits@429; to_u64_digits@437; iter_u64_digits@445
Dependencies: num_bigint::@6; num_traits::@7; std::mem::replace@8; test::Bencher@9; rng::get_rng@12; std::collections::HashSet@328; num_traits::Pow@353

`third_party/rust/num-bigint/benches/factorial.rs` | `a1e7b3cf1a78356af382059182e8434e5fbfd22f` | 991 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: factorial_mul_biguint@11; factorial_mul_u32@20; factorial_div_biguint@28; factorial_div_u32@39
Dependencies: num_bigint::BigUint@5; num_traits::One@6; std::ops::@7; test::Bencher@8

`third_party/rust/num-bigint/benches/gcd.rs` | `c211b6ef27a39e80daa96e050c6da557eabad19a` | 1374 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: rng@11; bench@14; euclid@24; gcd_euclid_0064@37; gcd_euclid_0256@42; gcd_euclid_1024@47; gcd_euclid_4096@52; gcd_stein_0064@59; gcd_stein_0256@64; gcd_stein_1024@69; gcd_stein_4096@74
Dependencies: num_bigint::@6; num_integer::Integer@7; num_traits::Zero@8; test::Bencher@9; rng::get_rng@12

`third_party/rust/num-bigint/benches/rng/mod.rs` | `33e4f0fad353416b3ab25c451c7e8cee40ba80d8` | 954 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: get_rng@3; XorShiftStar@10; next_u32@15; next_u64@19; fill_bytes@27; try_fill_bytes@35
Dependencies: rand::RngCore@1

`third_party/rust/num-bigint/benches/roots.rs` | `7afc4f763cafbe352e995be878a4ef6462292d63` | 3124 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: rng@9; check@20; bench_sqrt@39; big64_sqrt@48; big1k_sqrt@53; big2k_sqrt@58; big4k_sqrt@63; bench_cbrt@67; big64_cbrt@76; big1k_cbrt@81; big2k_cbrt@86; big4k_cbrt@91; bench_nth_root@95; big64_nth_10@104; big1k_nth_10@109; big1k_nth_100@114; big1k_nth_1000@119; big1k_nth_10000@124; big2k_nth_10@129; big2k_nth_100@134; big2k_nth_1000@139; big2k_nth_10000@144; big4k_nth_10@149; big4k_nth_100@154; big4k_nth_1000@159; big4k_nth_10000@164
Dependencies: num_bigint::@6; test::Bencher@7; rng::get_rng@10

`third_party/rust/num-bigint/benches/shootout-pidigits.rs` | `b95d42cc40a5334adf4dd5276d5d4336fc26d6f1` | 4140 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Context@48; new@55; from_i32@63; extract_digit@67; next_term@78; eliminate_digit@85; pidigits@93; main@128
Dependencies: std::io@41; std::str::FromStr@42; num_bigint::BigInt@44; num_integer::Integer@45; num_traits::@46

`third_party/rust/num-bigint/src/bigint.rs` | `b4f84b9e8f25142d11fa4b79b02c3a114539f4f6` | 36441 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: addition@22; division@23; multiplication@24; subtraction@25; arbitrary@27; bits@28; convert@29; power@30; serde@31; shift@32; Sign@36; Output@43; neg@47; BigInt@57; clone@66; clone_from@74; hash@82; eq@93; partial_cmp@104; cmp@111; default@129; fmt@135; fmt@141; fmt@147; fmt@153; fmt@159; fmt@165; Output@177; not@179; Output@195; not@197; zero@208; set_zero@213; is_zero@219; one@231; set_one@239; is_one@245; abs@252; abs_sub@260; signum@269; is_positive@278; is_negative@283; UnsignedAbs@288; Unsigned@289; checked_uabs@291; CheckedUnsignedAbs@294; Unsigned@303; checked_uabs@306; Output@324; neg@327; Output@334; neg@337; div_rem@344; div_floor@357; mod_floor@374; div_mod_floor@391; div_ceil@410; gcd@430; lcm@436; gcd_lcm@443; extended_gcd_lcm@450; divides@462; is_multiple_of@468; is_even@474; is_odd@480; next_multiple_of@486; prev_multiple_of@496; dec@500; inc@504; nth_root@510; sqrt@520; cbrt@526; digits@533; digits_mut@537; normalize@541; capacity@548; len@552; ToBigInt@560; to_bigint@562; new@576; from_biguint@584; from_slice@598; assign_from_slice@606; from_bytes_be@634; from_bytes_le@642; from_signed_bytes_be@651; from_signed_bytes_le@659; parse_bytes@675; from_radix_be@696; from_radix_le@717; to_bytes_be@733; to_bytes_le@748; to_u32_digits@767; to_u64_digits@787; iter_u32_digits@806; iter_u64_digits@826; to_signed_bytes_be@841; to_signed_bytes_le@856; to_str_radix@872; to_radix_be@898; to_radix_le@917; sign@933; magnitude@950; into_parts@967; bits@974; to_biguint@980; checked_add@989; checked_sub@994; checked_mul@999; checked_div@1004; pow@1012; modpow@1024; modinv@1074; let@1077; sqrt@1088; cbrt@1094; nth_root@1100; trailing_zeros@1106; bit@1112; Ord::cmp@1123; set_bit@1140; Bytes@1159; from_be_bytes@1161; from_le_bytes@1165; Bytes@1171; to_be_bytes@1173; to_le_bytes@1177; test_from_biguint@1183; check@1184; test_from_slice@1199; check@1200; test_assign_from_slice@1215; check@1216
Dependencies: alloc::string::String@4; alloc::vec::Vec@5; core::cmp::Ordering::@6; core::default::Default@7; core::fmt@8; core::hash@9; core::ops::@10; core::str@11; num_integer::@13; num_traits::@14; self::Sign::@16; crate::big_digit::BigDigit@18; crate::biguint::to_str_radix_reversed@19; crate::biguint::@20; self::CheckedUnsignedAbs::@298

`third_party/rust/num-bigint/src/bigint/addition.rs` | `0d3a0e2a5404cbfe0f68f4c45afadad7219ddad5` | 6604 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@34; add@37; Output@50; add@53; Output@59; add@62; Output@68; add@71; add_assign@78; Output@92; add@95; add_assign@110; Output@117; add@120; add_assign@135; Output@142; add@145; add_assign@159; Output@170; add@173; Positive@175; Negative@176; add_assign@182; Positive@184; Negative@185; Output@191; add@194; Positive@196; Negative@197; add_assign@203; Positive@205; Negative@206; Output@212; add@215; Positive@217; Negative@218; add_assign@224; Positive@226; Negative@227; checked_add@234
Dependencies: super::CheckedUnsignedAbs::@1; super::Sign::@2; super::@3; crate::@5; core::cmp::Ordering::@7; core::iter::Sum@8; core::mem@9; core::ops::@10; num_traits::CheckedAdd@11

`third_party/rust/num-bigint/src/bigint/arbitrary.rs` | `3cb90b304dc1d5b6fc0adddd9c159e9f1d59bbff` | 1569 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: arbitrary@12; shrink@18; arbitrary@28; arbitrary_take_rest@34; size_hint@40
Dependencies: super::@3; crate::BigUint@4; alloc::boxed::Box@7

`third_party/rust/num-bigint/src/bigint/bits.rs` | `ac4fe1de164244140a21c96ffa60dcd6d9200cef` | 18177 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: negate_carry@29; bitand_pos_neg@39; bitand_neg_pos@51; Ord::cmp@58; bitand_neg_neg@72; Ord::cmp@83; Output@112; bitand@115; Output@134; bitand@137; bitand_assign@146; bitor_pos_neg@176; Ord::cmp@184; bitor_neg_pos@205; bitor_neg_neg@227; Output@251; bitor@254; Output@274; bitor@277; bitor_assign@286; bitxor_pos_neg@311; Ord::cmp@319; bitxor_neg_pos@344; Ord::cmp@352; bitxor_neg_neg@377; Ord::cmp@387; Output@412; bitxor@415; bitxor_assign@424; set_negative_bit@452
Dependencies: super::BigInt@1; super::Sign::@2; crate::big_digit::@4; crate::biguint::IntDigits@5; alloc::vec::Vec@7; core::cmp::Ordering::@8; core::ops::@9; num_traits::@10

`third_party/rust/num-bigint/src/bigint/convert.rs` | `d0e28b67e1b2b16bd88eab49aac9d64ac91101ad` | 11906 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Err@14; from_str@17; FromStrRadixErr@23; from_str_radix@27; to_i64@43; to_i128@60; to_u64@77; to_u128@86; to_f32@95; to_f64@101; Error@110; try_from@113; Error@119; try_from@122; from_i64@145; from_i128@150; from_u64@155; from_u128@160; from_f64@165; from@177; from@192; from@209; from@223; from@237; from@253; from@267; to_bigint@281; to_bigint@288; to_biguint@302; Error@312; try_from@315; Error@323; try_from@326; to_bigint@339; from@364; from_signed_bytes_be@374; Some@377; from_signed_bytes_le@392; Some@395; to_signed_bytes_be@410; to_signed_bytes_le@426; twos_complement_le@446; twos_complement_be@453; twos_complement@460
Dependencies: super::Sign::@1; super::@2; crate::TryFromBigIntError@4; crate::@5; alloc::vec::Vec@7; core::cmp::Ordering::@8; core::convert::TryFrom@9; core::str::@10; num_traits::@11

`third_party/rust/num-bigint/src/bigint/division.rs` | `0d4d23f364e1d33469898a4f04b97a1a9469adfe` | 11319 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@14; div@17; div_assign@25; Output@38; div@41; div_assign@48; Output@57; div@60; Output@66; div@69; div_assign@76; Output@85; div@88; Output@94; div@97; div_assign@104; Output@113; div@116; Output@126; div@129; Positive@131; Negative@132; div_assign@139; Positive@141; Negative@142; Output@151; div@154; Positive@156; Negative@157; Output@163; div@166; Positive@168; Negative@169; div_assign@176; Positive@178; Negative@179; Output@188; div@191; Positive@193; Negative@194; Output@200; div@203; Positive@205; Negative@206; div_assign@213; Positive@215; Negative@216; Output@225; div@228; Positive@230; Negative@231; Output@239; rem@242; rem_assign@256; Output@269; rem@272; rem_assign@279; Output@288; rem@291; Output@297; rem@300; rem_assign@307; Output@316; rem@319; Output@325; rem@328; rem_assign@335; Output@344; rem@347; Output@357; rem@360; rem_assign@367; Output@373; rem@376; Positive@378; Negative@379; Output@385; rem@388; rem_assign@395; Output@401; rem@404; Positive@406; Negative@407; Output@413; rem@416; rem_assign@423; Output@429; rem@432; Positive@434; Negative@435; checked_div@442; checked_div_euclid@452; checked_rem_euclid@460; checked_div_rem_euclid@467; div_euclid@474; rem_euclid@488; div_rem_euclid@501
Dependencies: super::CheckedUnsignedAbs::@1; super::Sign::NoSign@2; super::@3; crate::@5; core::ops::@7; num_integer::Integer@8; num_traits::@9

`third_party/rust/num-bigint/src/bigint/multiplication.rs` | `82e64c28610da9b2149c9f1b2ff392ef6336fdba` | 5406 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@12; mul@15; Output@27; mul@30; mul_assign@50; Output@75; mul@78; mul_assign@85; Output@94; mul@97; mul_assign@104; Output@113; mul@116; mul_assign@123; Output@136; mul@139; Positive@141; Negative@142; mul_assign@149; Positive@151; Negative@152; Output@161; mul@164; Positive@166; Negative@167; mul_assign@174; Positive@176; Negative@177; Output@186; mul@189; Positive@191; Negative@192; mul_assign@199; Positive@201; Negative@202; checked_mul@212
Dependencies: super::CheckedUnsignedAbs::@1; super::Sign::@2; super::@3; crate::@5; core::iter::Product@7; core::ops::@8; num_traits::@9

`third_party/rust/num-bigint/src/bigint/power.rs` | `ef254c8963453078a860fc2ddafd4533e720ac71` | 2409 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: powsign@13; Output@26; pow@29; Output@35; pow@38; Output@44; pow@47; Output@53; pow@56; modpow@71; let@87
Dependencies: super::BigInt@1; super::Sign::@2; crate::BigUint@4; num_integer::Integer@6; num_traits::@7

`third_party/rust/num-bigint/src/bigint/serde.rs` | `6c476920edcc81c8f4470d4d7c11c541d2201dc9` | 1791 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: serialize@10; deserialize@25; serialize@43; deserialize@54
Dependencies: super::@4; serde::de::@6; serde::@7

`third_party/rust/num-bigint/src/bigint/shift.rs` | `22bb7443ee0576a5f8c56ce7a4081502b46544ac` | 3377 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@10; $shx@13; Output@18; $shx@21; $shx_assign@27; Output@34; shl@37; Output@42; shl@45; shl_assign@51; Output@58; shr@61; Output@69; shr@72; shr_assign@81; shr_round_down@100
Dependencies: super::BigInt@1; super::Sign::NoSign@2; core::ops::@4; num_traits::@5

`third_party/rust/num-bigint/src/bigint/subtraction.rs` | `ef778549849c676559233635b5808fa1a8cc59a8` | 7683 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@33; sub@36; Output@49; sub@52; Output@58; sub@61; Output@67; sub@70; sub_assign@77; Output@91; sub@94; sub_assign@108; Output@115; sub@118; Output@124; sub@127; Output@133; sub@136; Output@142; sub@145; sub_assign@160; Output@167; sub@170; sub_assign@185; Output@196; sub@199; Positive@201; Negative@202; sub_assign@208; Positive@210; Negative@211; Output@217; sub@220; Positive@222; Negative@223; Output@229; sub@232; Positive@234; Negative@235; sub_assign@241; Positive@243; Negative@244; Output@250; sub@253; Positive@255; Negative@256; Output@262; sub@265; Positive@267; Negative@268; sub_assign@275; Positive@277; Negative@278; Output@284; sub@287; Positive@289; Negative@290; checked_sub@297
Dependencies: super::CheckedUnsignedAbs::@1; super::Sign::@2; super::@3; crate::@5; core::cmp::Ordering::@7; core::mem@8; core::ops::@9; num_traits::CheckedSub@10

`third_party/rust/num-bigint/src/bigrand.rs` | `e5cbacdbcded51497bc78d0dd5cf86f31872eec3` | 8686 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: RandBigInt@20; gen_biguint@22; gen_bigint@25; gen_biguint_below@29; gen_biguint_range@34; gen_bigint_range@39; gen_bits@42; gen_biguint@53; gen_biguint@63; gen_bigint@89; gen_biguint_below@113; gen_biguint_range@124; gen_bigint_range@133; UniformBigUint@148; X@154; new@157; new_inclusive@172; sample@184; sample_single@189; Sampler@199; UniformBigInt@204; X@210; new@213; new_inclusive@228; sample@240; sample_single@245; Sampler@255; RandomBits@262; new@268; sample@275; sample@282
Dependencies: rand::distributions::uniform::@5; rand::prelude::@6; crate::BigInt@8; crate::BigUint@9; crate::Sign::@10; crate::biguint::biguint_from_vec@12; num_integer::Integer@14; num_traits::@15; core::slice@64

`third_party/rust/num-bigint/src/biguint.rs` | `196fa32360d4237a71f1a06eb62a52fa15010b75` | 34848 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: addition@16; division@17; multiplication@18; subtraction@19; arbitrary@21; bits@22; convert@23; iter@24; monty@25; power@26; serde@27; shift@28; BigUint@34; clone@42; clone_from@49; hash@56; eq@64; partial_cmp@74; cmp@81; cmp_slice@87; Ord::cmp@91; default@99; fmt@105; fmt@111; fmt@117; fmt@123; fmt@131; fmt@137; zero@144; set_zero@149; is_zero@154; one@166; set_one@171; is_one@177; div_rem@186; div_floor@191; mod_floor@197; div_mod_floor@203; div_ceil@208; gcd@221; twos@223; lcm@257; gcd_lcm@268; divides@280; is_multiple_of@286; is_even@295; Some@298; is_odd@305; next_multiple_of@311; prev_multiple_of@321; dec@325; inc@329; fixpoint@335; nth_root@369; Some@400; sqrt@433; Some@448; cbrt@474; Some@489; ToBigUint@517; to_biguint@519; biguint_from_vec@526; new@538; from_slice@556; assign_from_slice@566; from_bytes_be@596; from_bytes_le@610; parse_bytes@635; from_radix_be@656; from_radix_le@676; to_bytes_be@691; to_bytes_le@708; to_u32_digits@730; to_u64_digits@749; iter_u32_digits@767; iter_u64_digits@786; to_str_radix@802; to_radix_be@823; to_radix_le@844; bits@850; normalize@861; normalized@873; pow@879; modpow@886; modinv@913; sqrt@972; cbrt@978; nth_root@984; trailing_zeros@990; trailing_ones@997; count_ones@1007; bit@1012; set_bit@1027; Bytes@1048; from_be_bytes@1050; from_le_bytes@1054; Bytes@1060; to_be_bytes@1062; to_le_bytes@1066; IntDigits@1071; digits@1072; digits_mut@1073; normalize@1074; capacity@1075; len@1076; digits@1081; digits_mut@1085; normalize@1089; capacity@1093; len@1097; u32_chunk_to_u64@1104; u32_to_u128@1116; u32_from_u128@1124; test_from_slice@1136; check@1137; test_from_slice@1149; check@1150; test_u32_u128@1170; test_u128_u32_roundtrip@1190
Dependencies: crate::big_digit::@1; alloc::string::String@3; alloc::vec::Vec@4; core::cmp@5; core::cmp::Ordering@6; core::default::Default@7; core::fmt@8; core::hash@9; core::mem@10; core::str@11; num_integer::@13; num_traits::@14; num_traits::FromPrimitive@401; num_traits::FromPrimitive@449; num_traits::FromPrimitive@490

`third_party/rust/num-bigint/src/biguint/addition.rs` | `b6711314fba4675912b3f784eddb373d17f20837` | 7109 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: adc@20; adc@30; adc@41; __add2@55; add2@82; Output@92; add@94; add_assign@101; Output@123; add@126; add_assign@134; Output@149; add@152; add_assign@161; add_assign@178; Output@194; add@197; add_assign@206; add_assign@231; checked_add@251
Dependencies: super::@1; crate::big_digit::@3; crate::UsizePromotion@4; core::iter::Sum@6; core::ops::@7; num_traits::CheckedAdd@8; core::arch::x86_64@11; core::arch::x86@14

`third_party/rust/num-bigint/src/biguint/arbitrary.rs` | `9d5c5ccf1d3df3524f35aba50f862c7c3dc2197b` | 1196 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: arbitrary@13; shrink@18; arbitrary@27; arbitrary_take_rest@31; size_hint@35
Dependencies: super::@3; crate::big_digit::BigDigit@5; alloc::boxed::Box@7; alloc::vec::Vec@8

`third_party/rust/num-bigint/src/biguint/bits.rs` | `42d7ec0c47b74b8bf47c09853d48ae3eaa1d78af` | 2662 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@11; bitand@14; Output@27; bitand@30; bitand_assign@37; Output@50; bitor@52; bitor_assign@59; Output@74; bitxor@76; bitxor_assign@83
Dependencies: super::@1; core::ops::@3

`third_party/rust/num-bigint/src/biguint/convert.rs` | `3daf3dcb0cdc97ece98f8d631a315c21464f7701` | 25086 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: fls@25; ilog2@29; Err@34; from_str@37; from_bitwise_digits_le@44; from_inexact_bitwise_digits_le@65; from_radix_digits_be@102; from_radix_be@155; from_radix_le@186; FromStrRadixErr@218; from_str_radix@221; high_bits_to_u64@272; to_i64@324; to_i128@329; to_u64@335; to_u128@353; to_f32@370; to_f64@382; Error@397; try_from@400; Error@406; try_from@409; from_i64@432; from_i128@441; from_u64@450; from_u128@455; from_f64@460; from@492; from@507; from@523; Error@538; try_from@541; to_biguint@557; to_biguint@566; from@591; to_bitwise_digits_le@601; to_inexact_bitwise_digits_le@629; to_radix_digits_le@671; to_radix_le@750; to_str_radix_reversed@770; get_radix_base@793; get_half_radix_base@802; test_radix_bases@843; test_half_radix_bases@856
Dependencies: super::@4; super::addition::add2@6; super::division::@7; super::multiplication::mac_with_carry@8; crate::big_digit::@10; crate::ParseBigIntError@11; crate::TryFromBigIntError@12; alloc::vec::Vec@14; core::cmp::Ordering::@15; core::convert::TryFrom@16; core::mem@17; core::str::FromStr@18; num_integer::@19; num_traits::float::FloatCore@20; num_traits::@21

`third_party/rust/num-bigint/src/biguint/division.rs` | `3dfb0bbb2d35528fc4b75313686453177217e46e` | 20786 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: div_wide@23; div_wide@34; div_half@75; div_rem_digit@85; rem_digit@110; sub_mul_digit_same_len@135; div_rem@161; div_rem_ref@208; div_rem_core@252; Output@350; div@353; Output@360; div@363; div_assign@370; Output@382; div@385; div_assign@392; Output@398; div@401; Output@411; div@414; div_assign@421; Output@429; div@433; div@443; Output@454; div@457; div_assign@465; Output@471; div@475; div@492; Output@508; rem@511; Output@522; rem@525; rem_assign@536; Output@548; rem@551; rem_assign@557; Output@563; rem@566; rem_assign@577; Some@580; Some@581; Output@603; rem@606; rem_assign@613; Output@619; rem@622; Output@629; rem@632; rem_assign@640; Output@646; rem@649; checked_div@657; checked_div_euclid@667; checked_rem_euclid@675; checked_div_rem_euclid@682; div_euclid@689; rem_euclid@695; div_rem_euclid@700
Dependencies: super::addition::__add2@1; super::@2; crate::big_digit::@4; crate::UsizePromotion@5; core::cmp::Ordering::@7; core::mem@8; core::ops::@9; num_integer::Integer@10; num_traits::@11; crate::big_digit::@76; super::u32_to_u128@476

`third_party/rust/num-bigint/src/biguint/iter.rs` | `066c9c1eb2653dae4410e0ab6954f2af9de5dcef` | 10249 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: U32Digits@6; U32Digits@12; new@23; Item@29; next@31; size_hint@36; nth@41; last@46; count@51; next_back@57; len@64; new@73; Item@90; next@92; Some@94; size_hint@114; last@120; count@131; next_back@137; Some@139; len@161; U64Digits@175; U64Digits@181; new@190; Item@196; next@198; size_hint@203; last@209; count@214; next_back@220; new@229; Item@235; next@237; size_hint@242; nth@247; last@252; count@257; next_back@263; len@272; test_iter_u32_digits@280; test_iter_u64_digits@301; test_iter_u32_digits_be@322; test_iter_u64_digits_be@343
Dependencies: core::iter::FusedIterator@1

`third_party/rust/num-bigint/src/biguint/monty.rs` | `a0b26b54545f73872f8e17671a1a44c3b76c802b` | 6850 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: MontyReducer@9; inv_mod_alt@15; new@32; montgomery@46; add_mul_vvw@92; sub_vv@106; add_ww@120; mul_add_www@130; monty_modpow@137
Dependencies: alloc::vec::Vec@1; core::mem@2; core::ops::Shl@3; num_traits::One@4; crate::big_digit::@6; crate::biguint::BigUint@7

`third_party/rust/num-bigint/src/biguint/multiplication.rs` | `e9d21384f76bac482e150d2918922019f0f012e1` | 20315 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: mac_with_carry@15; mul_with_carry@29; mac_digit@38; bigint_from_slice@60; mac3@67; let@87; mul3@410; scalar_mul@418; sub_sign@438; cmp_slice@447; Output@465; mul@468; mul_assign@493; Output@520; mul@523; mul_assign@530; Output@536; mul@539; mul_assign@547; mul_assign@557; Output@564; mul@567; mul_assign@576; mul_assign@589; checked_mul@602; test_sub_sign@610; sub_sign_i@614
Dependencies: super::addition::@1; super::subtraction::sub2@2; super::@3; crate::big_digit::@5; crate::Sign::@6; crate::@7; core::cmp::Ordering@9; core::iter::Product@10; core::ops::@11; num_traits::@12; crate::BigInt@611; num_traits::Num@612

`third_party/rust/num-bigint/src/biguint/power.rs` | `fa1c4926afad928780dc1278833820faf933dd3a` | 6243 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@10; pow@13; Output@31; pow@34; Output@40; pow@43; Output@55; pow@58; Output@66; pow@68; Output@96; pow@99; Output@105; pow@108; Output@117; pow@120; modpow@134; plain_modpow@149; Some@157; test_plain_modpow@221; test_pow_biguint@253
Dependencies: super::monty::monty_modpow@1; super::BigUint@2; crate::big_digit::@4; num_integer::Integer@6; num_traits::@7

`third_party/rust/num-bigint/src/biguint/serde.rs` | `84bdf5052803f6a1f8ea66c9aa1cdcc9c386744c` | 3849 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: cautious@13; serialize@24; serialize@35; deserialize@64; U32Visitor@72; Value@75; expecting@77; visit_seq@82; visit_seq@96
Dependencies: super::@4; alloc::vec::Vec@6; core::@7; serde::de::@8; serde::@9; serde::ser::SerializeSeq@39; crate::big_digit::BigDigit@100; num_integer::Integer@101

`third_party/rust/num-bigint/src/biguint/shift.rs` | `51483cd05c184713c822f587f4b5632683dcc91a` | 4892 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: biguint_shl@12; biguint_shl2@25; biguint_shr@54; biguint_shr2@67; Cow::Borrowed@74; Cow::Owned@75; Output@97; $shx@100; Output@105; $shx@108; $shx_assign@114; Output@121; shl@124; Output@129; shl@132; shl_assign@138; Output@146; shr@149; Output@154; shr@157; shr_assign@163
Dependencies: super::@1; crate::big_digit@3; alloc::borrow::Cow@5; alloc::vec::Vec@6; core::mem@7; core::ops::@8; num_traits::@9

`third_party/rust/num-bigint/src/biguint/subtraction.rs` | `47a5015f1ffafb4b580aa616f23731a8d36d9b6f` | 8258 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: sbb@20; sbb@30; sbb@41; sub2@48; __sub2rev@77; sub2rev@89; Output@112; sub@114; sub_assign@120; Output@127; sub@129; Output@151; sub@154; sub_assign@161; Output@168; sub@172; sub@182; Output@194; sub@197; sub_assign@206; sub_assign@213; Output@221; sub@225; sub@236; Output@248; sub@251; sub_assign@260; sub_assign@267; Output@276; sub@280; sub@291; checked_sub@305
Dependencies: super::BigUint@1; crate::big_digit::@3; crate::UsizePromotion@4; core::cmp::Ordering::@6; core::ops::@7; num_traits::CheckedSub@8; core::arch::x86_64@11; core::arch::x86@14

`third_party/rust/num-bigint/src/lib.rs` | `6e47479d0c0211c964aff4da7e9336280338c7e6` | 7522 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: macros@112; bigint@114; bigrand@115; biguint@116; UsizePromotion@119; UsizePromotion@121; IsizePromotion@124; IsizePromotion@126; ParseBigIntError@129; BigIntErrorKind@134; __description@140; empty@148; invalid@154; fmt@162; description@170; TryFromBigIntError@177; new@182; __description@186; into_original@192; description@203; fmt@209; big_digit@227; BigDigit@230; BigDigit@231; DoubleBigDigit@237; DoubleBigDigit@238; get_hi@249; get_lo@253; from_doublebigdigit@259; to_doublebigdigit@265
Dependencies: core::fmt@109; crate::BigIntErrorKind::@141

`third_party/rust/num-bigint/src/macros.rs` | `f2e21e3ba92fff8b7a056713a83537e0cc62dd55` | 13669 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@38; $method@41; Output@52; $method@55; Output@70; $method@73; Output@84; $method@87; Output@98; $method@101; Output@112; $method@115; Output@126; $method@129; $method@145; $method@156; Output@167; $method@170; Output@181; $method@184; Output@190; $method@193; Output@203; $method@206; Output@212; $method@215; Output@225; $method@228; Output@234; $method@237; Output@247; $method@250; Output@256; $method@259; Output@269; $method@272; Output@278; $method@281; Output@291; $method@294; Output@300; $method@303; Output@316; $method@320; Output@326; $method@330; $method@343; sum@449; product@465

`third_party/rust/num-bigint/tests/bigint.rs` | `fea5232e040a40652363892965918ab7ac2c5bee` | 46716 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: consts@17; macros@21; test_from_bytes_be@24; check@25; test_to_bytes_be@40; check@41; test_from_bytes_le@59; check@60; test_to_bytes_le@75; check@76; test_to_signed_bytes_le@94; check@95; test_from_signed_bytes_le@112; check@113; test_to_signed_bytes_be@132; check@133; test_from_signed_bytes_be@150; check@151; test_signed_bytes_be_round_trip@170; test_signed_bytes_le_round_trip@178; test_cmp@186; hash@228; test_hash@235; test_convert_i64@250; check@251; test_convert_i128@281; check@282; test_convert_u64@312; check@313; test_convert_u128@338; check@339; test_convert_f32@365; check@366; test_convert_f64@470; check@471; test_convert_to_biguint@566; check@567; test_convert_from_uint@583; test_convert_from_int@605; test_convert_from_biguint@651; test_add@661; test_sub@690; test_mul@719; test_div_mod_floor@755; check_sub@756; check@769; test_div_rem@812; check_sub@813; check@830; test_div_ceil@864; check_sub@865; check@869; test_div_rem_euclid@911; check_sub@912; check@920; test_checked_add@963; test_checked_sub@982; test_checked_mul@1001; test_checked_div@1027; test_gcd@1051; check@1052; test_lcm@1074; check@1075; test_is_multiple_of@1097; test_next_multiple_of@1109; test_prev_multiple_of@1145; test_abs_sub@1181; test_from_str_radix@1197; check@1198; test_lower_hex@1227; test_upper_hex@1237; test_binary@1247; test_octal@1260; test_display@1270; test_neg@1280; test_negative_shr@1288; test_iter_sum@1296; test_iter_product@1313; test_iter_sum_generic@1332; test_iter_product_generic@1341; test_pow@1354; test_bit@1385; test_set_bit@1405
Dependencies: num_bigint::BigUint@1; num_bigint::Sign::@2; num_bigint::@3; std::cmp::Ordering::@5; std::collections::hash_map::RandomState@6; std::hash::@7; std::iter::repeat@8; std::ops::Neg@9; std::@10; num_integer::Integer@12; num_traits::@13; crate::consts::@18

`third_party/rust/num-bigint/tests/bigint_bitwise.rs` | `94d92e1d77f91fa287d696279b264e22c3a450c1` | 5065 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: ValueVec@4; to_bigint@13; test_not@108; let@114; test_not_i64@124; test_bitwise@133; let@142; test_bitwise_i64@164
Dependencies: num_bigint::@1; num_traits::ToPrimitive@2; crate::ValueVec::@10

`third_party/rust/num-bigint/tests/bigint_scalar.rs` | `2a19fafb3e49056e2e7f9d33bb9e08371b3e4d3e` | 4651 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: consts@8; macros@12; test_scalar_add@15; check@16; test_scalar_sub@41; check@42; test_scalar_mul@67; check@68; test_scalar_div_rem@91; check_sub@92; check@116; test_scalar_div_rem_zero@152
Dependencies: num_bigint::BigInt@1; num_bigint::Sign::Plus@2; num_traits::@3; std::ops::Neg@5; std::panic::catch_unwind@6; crate::consts::@9

`third_party/rust/num-bigint/tests/biguint.rs` | `4e2c625917c627b3616a9b1b56b535bfc3d8d49e` | 62848 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: consts@18; macros@22; test_from_bytes_be@25; check@26; test_to_bytes_be@39; check@40; test_from_bytes_le@58; check@59; test_to_bytes_le@72; check@73; test_cmp@91; hash@127; test_hash@134; test_bitand@163; test_bitor@178; test_bitxor@193; test_shl@216; check@217; test_shr@363; check@364; test_convert_i64@507; check@508; test_convert_i128@531; check@532; test_convert_u64@556; check@557; test_convert_u128@579; check@580; test_convert_f32@603; check@604; test_convert_f64@691; check@692; test_convert_to_bigint@773; check@774; test_convert_from_uint@786; test_add@808; test_sub@823; test_sub_fail_on_underflow@839; test_mul@845; test_div_rem@871; test_div_rem_big_multiple@912; test_div_ceil@926; check@927; test_div_rem_euclid@963; check@964; test_checked_add@997; test_checked_sub@1010; test_checked_mul@1030; test_mul_overflow@1054; test_mul_overflow_2@1065; test_checked_div@1077; test_gcd@1096; check@1097; test_lcm@1114; check@1115; test_is_multiple_of@1134; test_next_multiple_of@1146; test_prev_multiple_of@1158; test_is_even@1170; to_str_pairs@1185; test_to_str_radix@1297; test_from_and_to_radix@1309; test_from_str_radix@1630; test_all_str_radix@1661; test_big_str@1675; test_lower_hex@1685; test_upper_hex@1695; test_binary@1705; test_octal@1718; test_display@1728; test_factor@1738; factor@1739; check@1750; test_bits@1763; test_iter_sum@1778; test_iter_product@1795; test_iter_sum_generic@1814; test_iter_product_generic@1823; test_pow@1836; test_trailing_zeros@1867; test_trailing_ones@1876; test_count_ones@1888; test_bit@1898; test_set_bit@1909
Dependencies: num_bigint::Sign::Plus@1; num_bigint::@2; num_bigint::@3; num_integer::Integer@4; std::cmp::Ordering::@6; std::collections::hash_map::RandomState@7; std::hash::@8; std::iter::repeat@9; std::str::FromStr@10; std::@11; num_traits::@13; crate::consts::@19; crate::hash@135

`third_party/rust/num-bigint/tests/biguint_scalar.rs` | `7c34f7ef7d8eb28c49064e78eba6e2e1bf256e00` | 3538 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: consts@6; macros@10; test_scalar_add@13; check@14; test_scalar_sub@32; check@33; test_scalar_mul@51; check@52; test_scalar_rem_noncommutative@70; test_scalar_div_rem@76; check@77; test_scalar_div_rem_zero@118
Dependencies: num_bigint::BigUint@1; num_traits::@2; std::panic::catch_unwind@4; crate::consts::@7

`third_party/rust/num-bigint/tests/consts/mod.rs` | `457fbd3631dd7a4317f852000403d17404bc5b85` | 1698 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/num-bigint/tests/fuzzed.rs` | `7ff5641915d97b76ee169c9db5fd14861aeb2643` | 13725 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: fuzzed_mul_1@7; fuzzed_mul_2@91
Dependencies: num_bigint::BigUint@3; num_traits::Num@4

`third_party/rust/num-bigint/tests/macros/mod.rs` | `b14cd577de0093098eb09e681e83da1fe49d274d` | 2766 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/num-bigint/tests/modpow.rs` | `d7a247b0e6b1ad427f8e8aaa128e0646f89b6db1` | 7274 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: biguint@55; check_modpow@60; test_modpow_single@75; test_modpow_small@85; test_modpow_big@96; bigint@111; check_modpow@116; check@117; test_modpow@149; test_modpow_small@159; test_modpow_big@173
Dependencies: num_bigint::BigUint@56; num_integer::Integer@57; num_traits::Num@58; num_bigint::BigInt@112; num_integer::Integer@113; num_traits::@114

`third_party/rust/num-bigint/tests/roots.rs` | `7110adf904ec7d783856ae1c29606301d11bdff9` | 3991 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: biguint@1; check@5; test_sqrt@30; test_cbrt@37; test_nth_root@43; test_nth_root_n_is_zero@51; test_nth_root_big@56; test_nth_root_googol@65; test_nth_root_twos@77; test_roots_rand1@97; bigint@114; check@118; test_nth_root@138; test_nth_root_x_neg_n_even@144; test_sqrt_x_neg@150; test_cbrt@155
Dependencies: num_bigint::BigUint@2; num_traits::@3; num_bigint::BigInt@115; num_traits::Signed@116

`third_party/rust/num-complex/.cargo-checksum.json` | `d33f158130e455c3c5dc3a61f1a4775fdcdabfd8` | 1081 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-complex/.cargo_vcs_info.json` | `b1dbb271d299c09fbdf3357bc13b2909dce0deb4` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-complex/Cargo.toml` | `bb9792a1928a46b59f297631d8101f46f66a784e` | 1838 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-complex/Cargo.toml.orig` | `987784c6dd7c345d3317ce1ff89679048bb41955` | 1319 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-complex/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-complex/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-complex/README.md` | `6075cd6832e85ef68f5fa7c3046e26847bf3627e` | 1613 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-complex/RELEASES.md` | `89a51e2a20ecb2e4b715eae991451efc809199d8` | 6645 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-complex/src/cast.rs` | `e12f5cd37ce7d864991ed7432bf73c3b3727c506` | 3371 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: $to@7; $from_xx@38; from@65; as_@78; test@84; test_to_primitive@88; test_from_primitive@102; test_num_cast@108; test_as_primitive@114
Dependencies: super::Complex@1; num_traits::@2; super::@85

`third_party/rust/num-complex/src/complex_float.rs` | `873fe737cd93831433f77f0a6c6cb45f6011f040` | 12192 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: private@10; Seal@15; ComplexFloat@28; Real@30; is_nan@33; is_infinite@37; is_finite@40; is_normal@44; recip@47; powi@50; powf@53; powc@56; sqrt@59; exp@62; exp2@65; expf@68; ln@71; log@74; log2@77; log10@80; cbrt@83; sin@86; cos@89; tan@92; asin@97; acos@102; atan@106; sinh@109; cosh@112; tanh@115; asinh@118; acosh@121; atanh@124; re@127; im@130; abs@133; l1_norm@138; arg@141; conj@146; $method@153; $method@163; Real@173; re@175; im@179; l1_norm@183; arg@187; powc@197; conj@201; expf@205; Real@242; re@244; im@248; abs@252; recip@256; l1_norm@262; is_nan@268; is_infinite@272; is_finite@276; is_normal@280; test@318; closef@326; close_to_tolf@330; test_exp2@340; test_exp@346; test_powi@352; test_powz@358; test_log2@364; test_log10@370; test_conj@376; test_is_nan@382; test_is_infinite@391; test_is_finite@403; test_is_normal@415; test_arg@427
Dependencies: core::ops::Neg@4; num_traits::@6; crate::Complex@8; num_traits::@11; crate::Complex@13; crate::@319; std::f64@324

`third_party/rust/num-complex/src/crand.rs` | `12d55e04ccea76ab8516cf8e30ba1842feedda22` | 4001 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: sample@13; ComplexDistribution@20; new@28; sample@39; test_rng@45; XorShiftStar@47; next_u32@52; next_u64@56; fill_bytes@64; try_fill_bytes@72; standard_f64@84; generic_standard_f64@94; generic_uniform_f64@105; generic_mixed_f64@121; generic_uniform_i32@136
Dependencies: crate::Complex@3; num_traits::Num@4; rand::distributions::Standard@5; rand::prelude::@6; rand::distributions::Uniform@106; rand::distributions::Uniform@122; rand::distributions::Uniform@137

`third_party/rust/num-complex/src/lib.rs` | `661b67b722ee3e9a8f6efdc1e89caa1e9a4a2370` | 94503 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: cast@39; pow@40; complex_float@43; crand@48; Complex@88; Complex32@96; c32@111; Complex64@116; c64@125; i@142; norm_sqr@149; scale@155; unscale@161; powu@167; conj@175; inv@181; powi@191; l1_norm@201; cis@211; norm@217; arg@222; to_polar@228; from_polar@233; exp@239; ln@270; sqrt@284; cbrt@332; powf@375; log@387; powc@397; expf@407; sin@415; cos@425; tan@435; asin@450; acos@465; atan@480; sinh@495; cosh@505; tanh@515; asinh@530; acosh@544; atanh@560; finv@595; fdiv@624; exp2@633; log2@641; log10@647; is_nan@655; is_infinite@661; is_finite@667; is_normal@673; from@692; from@699; Output@707; $method@710; Output@720; $method@723; Output@733; $method@736; Output@756; add@759; Output@768; sub@771; Output@780; mul@783; Output@792; mul_add@795; Output@803; mul_add@806; Output@816; div@819; div_trunc@831; Output@838; rem@841; opassign@849; add_assign@857; sub_assign@864; mul_assign@872; mul_add_assign@885; mul_add_assign@900; div_assign@908; rem_assign@923; add_assign@930; sub_assign@936; mul_assign@942; div_assign@949; rem_assign@956; $method@966; $method@972; Output@987; neg@990; Output@996; neg@999; Output@1005; inv@1008; Output@1014; inv@1017; Output@1025; $method@1028; Output@1033; $method@1036; Output@1041; $method@1044; Output@1050; $method@1053; Output@1058; $method@1061; Output@1066; $method@1069; Output@1084; add@1087; Output@1093; sub@1096; Output@1102; mul@1105; Output@1111; div@1114; Output@1123; rem@1126; Output@1135; add@1138; Output@1144; sub@1147; Output@1153; mul@1156; Output@1162; div@1165; Output@1171; rem@1174; zero@1193; is_zero@1198; set_zero@1203; one@1223; is_one@1228; set_one@1233; fmt_re_im@1270; fmt_complex@1313; fmt_complex@1323; fmt@1334; fmt@1343; fmt@1352; fmt@1361; fmt@1370; fmt@1379; fmt@1388; from_str_generic@1393; Err@1473; from_str@1476; FromStrRadixErr@1482; from_str_radix@1493; sum@1511; sum@1520; product@1529; product@1538; serialize@1551; deserialize@1564; ParseComplexError@1574; ComplexErrorKind@1579; expr_error@1586; unsupported_radix@1592; from_error@1598; description@1608; ComplexErrorKind::ParseError@1610; fmt@1618; ComplexErrorKind::ParseError@1620; hash@1628; test@1637; test_consts@1676; test@1678; test_scale_unscale@1692; test_conj@1701; test_inv@1709; test_divide_by_zero_natural@1716; test_inv_zero@1723; test_l1_norm@1730; test_pow@1741; float@1760; test_cis@1768; test_norm@1780; test@1781; test_arg@1793; test@1794; test_polar_conv@1804; test@1805; close@1814; close_to_tol@1818; close_naninf@1828; close_naninf_to_tol@1832; test_exp2@1878; test_exp@1883; test_ln@1929; test_powc@1946; test_powf@1973; test_log@1987; test_log2@1994; test_log10@1999; test_some_expf_cases@2004; test_sqrt@2019; test_sqrt_real@2039; test_sqrt_imag@2052; test_cbrt@2069; test_cbrt_real@2096; test_cbrt_imag@2118; test_sin@2135; test_cos@2148; test_tan@2161; test_asin@2174; test_acos@2195; test_atan@2215; test_sinh@2236; test_cosh@2252; test_tanh@2268; test_asinh@2284; test_acosh@2305; test_atanh@2325; test_exp_ln@2342; test_exp2_log@2350; test_trig_to_hyperbolic@2358; test_trig_identities@2370; test_hyperbolic_identites@2407; complex_arithmetic@2504; test_add@2509; test_sub@2521; test_mul@2533; test_mul_add_float@2549; test_mul_add@2574; test_div@2607; test_rem@2617; test_neg@2627; real_arithmetic@2636; test_add@2641; test_sub@2647; test_mul@2653; test_div@2659; test_rem@2665; test_div_rem_gaussian@2674; test_to_string@2683; test@2684; test_string_formatting@2697; test_hash@2721; test_hashset@2731; test_is_nan@2745; test_is_nan_special_cases@2752; test_is_infinite@2760; test_is_finite@2766; test_is_normal@2771; test_from_str@2780; test@2781; test_from_str_radix@2840; test@2841; test_error@2852; test_from_str_radix_fail@2875; test_from_str_fail@2881; test@2882; test_sum@2902; test_prod@2909; test_zero@2916; test_one@2929; test_const@2943
Dependencies: core::fmt@24; core::hash@26; core::iter::@27; core::ops::@28; core::str::FromStr@29; std::error::Error@31; num_traits::@33; num_traits::float::FloatCore@35; num_traits::float::@37; core::ops::@850; num_traits::@852; crate::Complex@854; std::string::ToString@1314; std::collections::hash_map::RandomState@1629; std::hash::@1630; super::@1640; super::@1641; core::f64@1642; core::str::FromStr@1643; std::string::@1645; num_traits::@1647; core::f64::INFINITY@1762; super::@1764; num_traits::@1765; super::@2505; num_traits::@2506; super::Complex@2575; super::super::Complex@2637; super::@2638; std::collections::HashSet@2732

`third_party/rust/num-complex/src/pow.rs` | `569f01daa592b191aa1a419108460c6f28e7d31e` | 5008 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@11; pow@14; Output@42; pow@45; Output@51; pow@54; Output@64; pow@67; Output@93; pow@96; Output@106; pow@109; Output@119; pow@122; Output@132; pow@135; Output@150; pow@153; Output@160; pow@163; Output@170; pow@173; Output@180; pow@183
Dependencies: super::Complex@1; core::ops::Neg@3; num_traits::Float@5; num_traits::@6

`third_party/rust/num-conv/.cargo-checksum.json` | `299d02713482a22b4a1d611c19db67112a1726b9` | 747 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-conv/.cargo_vcs_info.json` | `1486e9a7f3970b73ce3dd7236dc355cdeb9ef0a9` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-conv/Cargo.lock` | `41ed6931ece71683677e5d601e1a1455e7cc7976` | 152 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-conv/Cargo.toml` | `2d078a74da7cea34853ea26e54e6ef94d4c7bb4d` | 1540 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-conv/Cargo.toml.orig` | `5cda635425f8b04eb92dd26211974e590b843fba` | 873 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-conv/LICENSE-Apache` | `d8bca8b9f1d12a1fa4575001318824f5f961785a` | 11342 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-conv/LICENSE-MIT` | `7c7f78a5ed8b041d7e07f14110bbfa52eb350b6a` | 1055 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-conv/README.md` | `e3d182770ce147d54c3557de30622d803c9130f5` | 225 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-conv/src/lib.rs` | `c9b4b9ccc9061681f5e69bc44d7c5645cda0e834` | 5525 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: prelude@15; sealed@19; Integer@20; ExtendTargetSealed@33; extend@34; TruncateTargetSealed@37; truncate@38; ExtendTarget@46; TruncateTarget@52; Extend@71; extend@73; extend@79; Truncate@104; truncate@107; truncate@113; extend@138; truncate@164

`third_party/rust/num-derive/.cargo-checksum.json` | `56634ca00c1fc5a7225479d78ad0ec471a97f02f` | 1928 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-derive/.cargo_vcs_info.json` | `a00bc5fd17cdc03a15c53ed053ec3e03603ac199` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-derive/Cargo.toml` | `36a8899f152c7fe3cd0daa7caac011840213a9ef` | 1419 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-derive/Cargo.toml.orig` | `4a13a07ac4f503be71645c008adfc4dec7c6feb9` | 973 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-derive/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-derive/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-derive/README.md` | `20d66a63349a2c610293facc75e44cd5593b96f8` | 1914 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-derive/RELEASES.md` | `bbf6d533255d2abcfaae9063a38dff02d8d008b7` | 3933 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-derive/src/lib.rs` | `207602b928fb365898d51ae3194f4d306d1e55d4` | 33761 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Ok@77; Err@78; anon_const_trick@102; newtype_inner@115; Data::Struct@117; Fields::Unnamed@119; Fields::Named@126; NumTraits@140; to_tokens@146; new@152; wrap@184; from_primitive@242; from_i64@252; from_u64@256; from_isize@260; from_i8@264; from_i16@268; from_i32@272; from_i128@276; from_usize@280; from_u8@284; from_u16@288; from_u32@292; from_u128@296; from_f32@300; from_f64@304; Data::Enum@311; from_i64@350; from_u64@357; to_primitive@416; to_i64@426; to_u64@430; to_isize@434; to_i8@438; to_i16@442; to_i32@446; to_i128@450; to_usize@454; to_u8@458; to_u16@462; to_u32@466; to_u128@470; to_f32@474; to_f64@478; Data::Enum@485; to_i64@527; to_u64@532; num_ops@553; Output@559; add@561; Output@566; sub@568; Output@573; mul@575; Output@580; div@582; Output@587; rem@589; num_cast@602; from@612; zero@625; zero@635; is_zero@639; one@652; one@662; is_one@666; num@679; FromStrRadixErr@688; from_str_radix@690; float@704; nan@714; infinity@718; neg_infinity@722; neg_zero@726; min_value@730; min_positive_value@734; max_value@738; is_nan@742; is_infinite@746; is_finite@750; is_normal@754; classify@758; floor@762; ceil@766; round@770; trunc@774; fract@778; abs@782; signum@786; is_sign_positive@790; is_sign_negative@794; mul_add@798; recip@802; powi@806; powf@810; sqrt@814; exp@818; exp2@822; ln@826; log@830; log2@834; log10@838; max@842; min@846; abs_sub@850; cbrt@854; hypot@858; sin@862; cos@866; tan@870; asin@874; acos@878; atan@882; atan2@886; sin_cos@890; exp_m1@895; ln_1p@899; sinh@903; cosh@907; tanh@911; asinh@915; acosh@919; atanh@923; integer_decode@927; epsilon@931; to_degrees@935; to_radians@939; signed@953; abs@963; abs_sub@967; signum@971; is_positive@975; is_negative@979; unsigned@993
Dependencies: proc_macro::TokenStream@68; proc_macro2::@69; quote::quote@70; syn::@71

`third_party/rust/num-derive/tests/empty_enum.rs` | `173996c8ed3fa540ea473b0cd9da2e2e7b24e7d4` | 751 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Color@16; test_empty_enum@19

`third_party/rust/num-derive/tests/issue-16.rs` | `48cc2fbf8e83a7d0b26763cce4eac4386431ac8f` | 168 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: CLikeEnum@8

`third_party/rust/num-derive/tests/issue-6.rs` | `9eae7fb3f52460696abdd48b6887fe9a800cea16` | 371 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: SomeEnum@7; test_trivial_numeric_casts@12
Dependencies: num::@13

`third_party/rust/num-derive/tests/issue-9.rs` | `30c04d2f461925522a18d0ce5dde821a17481e80` | 372 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: SomeEnum@9; test_unused_qualifications@14
Dependencies: num::FromPrimitive@5; num::ToPrimitive@6

`third_party/rust/num-derive/tests/newtype-2015.rs` | `2b581907ec229123ef68d029736206087ab7ea39` | 71 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/num-derive/tests/newtype-2018.rs` | `814529ec8abbc13bb6bcf724a30914177417176b` | 71 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/num-derive/tests/newtype.rs` | `71b06b3932c3318d0f5ecce083356dd546986a94` | 2155 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: MyNum@11; test_derive_unsigned_works@14; do_nothing_on_unsigned@15; MyFloat@37; Output@40; neg@41; test_from_primitive@47; test_from_primitive_128@52; test_to_primitive@60; test_to_primitive_128@65; test_num_ops@72; test_num_cast@81; test_zero@86; test_one@91; test_num@96; test_float@101; test_signed@106
Dependencies: crate::num_renamed::@5; std::ops::Neg@8

`third_party/rust/num-derive/tests/no_implicit_prelude.rs` | `cb82decb8e711500c9f74b8e87ef359225c1c95e` | 233 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Color@6; NewI32@13
Dependencies: ::num_derive::@3

`third_party/rust/num-derive/tests/num_derive_without_num.rs` | `edebbecbfae9360d322767f2d1edcd14608bf644` | 614 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Direction@15

`third_party/rust/num-derive/tests/trivial-2015.rs` | `8309f0e8891b2ef34f6bfb6a9a64a5f7843f4f92` | 71 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/num-derive/tests/trivial-2018.rs` | `92b971bc83c8b7573063559d7f9e93343dc58dea` | 71 bytes | imported-path,test-path,source | UTF-8 | mode 100644

`third_party/rust/num-derive/tests/trivial.rs` | `d3b56b6a25b52b2959203651609e8bfc99c0f55a` | 1830 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Color@16; test_from_primitive_for_trivial_case@23; test_to_primitive_for_trivial_case@43; test_reflexive_for_trivial_case@54

`third_party/rust/num-derive/tests/with_custom_values.rs` | `9b202f4c51909f84d79758314d75508bccd1c050` | 2072 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: Color@16; test_from_primitive_for_enum_with_custom_value@24; test_to_primitive_for_enum_with_custom_value@46; test_reflexive_for_enum_with_custom_value@58

`third_party/rust/num-integer/.cargo-checksum.json` | `f2b910f02858646530f0d26620317947b57b089e` | 1342 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-integer/.cargo_vcs_info.json` | `3ab57853096f36b1938fbd277b0d27d664b613e1` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-integer/Cargo.toml` | `726ce6631390e3c7f659df0721767df8184a9830` | 1210 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-integer/Cargo.toml.orig` | `8c5fc92efd8f18dfd55867b8d32d0e6e98d036ca` | 750 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-integer/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-integer/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-integer/README.md` | `aefe368dc7bf24e726aff656e304e367356bde6c` | 1525 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-integer/RELEASES.md` | `9aeca2d978364bdacfa398d0fa10a1cbaf787b41` | 4159 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-integer/benches/average.rs` | `1f81ca6639c3addb1d6ec2ecb8162ded6d966909` | 13100 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: BenchInteger@15; lcg@20; NaiveAverage@34; naive_average_ceil@35; naive_average_floor@36; UncheckedAverage@39; unchecked_average_ceil@40; unchecked_average_floor@41; ModuloAverage@44; modulo_average_ceil@45; modulo_average_floor@46; naive_average_floor@52; Some@54; naive_average_ceil@66; Some@68; unchecked_average_floor@87; unchecked_average_ceil@90; modulo_average_ceil@100; modulo_average_floor@105; bench_unchecked@116; bench_ceil@128; bench_floor@153; $T@182; overflowing@194; small@204; rand@210; ceil@217; small@221; optimized@226; naive@232; unchecked@238; modulo@244; overflowing@250; optimized@255; naive@261; unchecked@267; modulo@273; rand@279; optimized@284; naive@290; unchecked@296; modulo@302; floor@310; small@314; optimized@319; naive@325; unchecked@331; modulo@337; overflowing@343; optimized@348; naive@354; unchecked@360; modulo@366; rand@372; optimized@377; naive@383; unchecked@389; modulo@395
Dependencies: num_integer::Integer@7; num_traits::@8; std::cmp::@9; std::fmt::Debug@10; test::@11; test::Bencher@183; num_integer::@184; super::@185; super::@186; super::@219; super::@223; super::@252; super::@281; super::@312; super::@316; super::@345; super::@374

`third_party/rust/num-integer/benches/gcd.rs` | `11b407b8ac4c0bae3623ef1015378c253e8c1a13` | 4877 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: GcdOld@11; gcd_old@12; gcd_old@21; gcd_old@79; fibonacci@116; run_bench@125; $T@146; bench_gcd@152; bench_gcd_old@157
Dependencies: num_integer::Integer@7; num_traits::@8; test::@9; crate::@147; num_integer::Integer@148; test::Bencher@149

`third_party/rust/num-integer/benches/roots.rs` | `b02ec86f4bcdfc3e0bf5034c676d5c08364281bf` | 4078 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: BenchInteger@12; bench@16; lcg@49; bench_rand@61; bench_rand_pos@77; bench_small@96; bench_small_pos@106; $T@120; sqrt_rand@125; sqrt_small@130; cbrt_rand@135; cbrt_small@140; fourth_root_rand@145; fourth_root_small@150; fifth_root_rand@155; fifth_root_small@160
Dependencies: num_integer::Integer@7; num_traits::checked_pow@8; num_traits::@9; test::@10; test::Bencher@121; num_integer::Roots@122

`third_party/rust/num-integer/src/average.rs` | `eb854d89bc06bfa348e961a4bfecde9bbde176cf` | 2548 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Average@5; average_ceil@23; average_floor@42; average_floor@56; average_ceil@62; average_floor@70; average_ceil@76
Dependencies: crate::Integer@1; core::ops::@2

`third_party/rust/num-integer/src/lib.rs` | `30fce2512a79768822ccae8754dbad9eb7e4f450` | 43031 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: roots@25; average@29; Integer@33; div_floor@50; mod_floor@74; div_ceil@92; gcd@110; lcm@122; gcd_lcm@138; extended_gcd@159; extended_gcd_lcm@196; divides@206; is_multiple_of@219; is_even@230; is_odd@241; div_rem@260; div_mod_floor@279; next_multiple_of@303; prev_multiple_of@336; dec@353; inc@370; ExtendedGcd@385; div_rem@393; div_floor@398; mod_floor@403; div_mod_floor@408; div_ceil@413; gcd@420; lcm@425; gcd_lcm@432; div_floor@441; mod_floor@454; div_mod_floor@467; div_ceil@479; gcd@491; extended_gcd_lcm@535; lcm@549; gcd_lcm@556; is_multiple_of@568; is_even@577; is_odd@583; div_rem@589; next_multiple_of@595; prev_multiple_of@607; $test_mod@618; test_division_rule@628; test_div_rem@633; test_nd_dr@634; test_div_mod_floor@657; test_nd_dm@658; test_gcd@682; test_gcd_cmp_with_euclidean@694; euclidean_gcd@695; test_gcd_min_val@714; test_gcd_min_val_min_val@728; test_gcd_min_val_0@735; test_gcd_0_min_val@742; test_lcm@748; test_gcd_lcm@760; test_extended_gcd_lcm@776; check@781; test_even@803; test_odd@816; test_multiple_of_one_limits@829; div_floor@853; mod_floor@859; div_ceil@864; gcd@870; extended_gcd_lcm@898; lcm@911; gcd_lcm@918; is_multiple_of@929; is_even@938; is_odd@944; div_rem@950; $test_mod@956; test_div_mod_floor@961; test_gcd@975; test_gcd_cmp_with_euclidean@984; euclidean_gcd@985; test_lcm@1001; test_gcd_lcm@1011; test_is_multiple_of@1020; test_even@1032; test_odd@1041; IterBinomial@1060; new@1088; Item@1101; next@1103; multiply_and_divide@1124; binomial@1148; multinomial@1170; test_lcm_overflow@1184; test_iter_binomial@1216; test_binomial@1259; test_multinomial@1315
Dependencies: core::mem@20; core::ops::Add@21; num_traits::@23; crate::Integer@619; core::mem@620; core::iter::once@761; crate::ExtendedGcd@777; core::fmt::Debug@778; num_traits::NumAssign@779; core::iter::once@786; crate::Integer@957; core::mem@958

`third_party/rust/num-integer/src/roots.rs` | `aed380247847f2a801e9f092448095e82458d86b` | 12665 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Roots@7; nth_root@53; sqrt@80; cbrt@106; sqrt@114; cbrt@121; nth_root@128; nth_root@136; sqrt@146; cbrt@152; fixpoint@171; bits@189; log2@194; nth_root@203; go@204; checked_pow@229; guess@245; guess@256; Some@264; sqrt@275; go@276; guess@298; guess@304; cbrt@316; go@317; guess@362; guess@368
Dependencies: crate::Integer@1; core::mem@2; num_traits::@3

`third_party/rust/num-integer/tests/average.rs` | `1c032fd95ed6fad0b19b814376da4997d8e0e04d` | 3183 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: $I@3; ceil@4; same_sign@8; different_sign@18; floor@28; same_sign@32; different_sign@42; $U@53; ceil@54; bounded@58; overflow@64; floor@71; bounded@75; overflow@81
Dependencies: num_integer::Average@5; num_integer::Average@29; num_integer::Average@55; num_integer::Average@72

`third_party/rust/num-integer/tests/roots.rs` | `359625c728c0474901bd5dc261f45f82f50195f6` | 6722 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: TestInteger@8; check@16; mantissa_max@50; extend@74; extend_shl@86; extend_shr@97; pos@108; neg@133; $I@160; zeroth_root@169; sqrt@174; sqrt_neg@180; cbrt@185; cbrt_neg@190; nth_root@195; nth_root_neg@204; bit_size@213; $U@222; zeroth_root@230; sqrt@235; cbrt@240; nth_root@245; bit_size@254
Dependencies: num_integer::Roots@1; num_traits::checked_pow@2; num_traits::@3; std::f64::MANTISSA_DIGITS@4; std::fmt::Debug@5; std::mem@6; crate::check@161; crate::neg@162; crate::pos@163; num_integer::Roots@164; std::mem@165; crate::check@223; crate::pos@224; num_integer::Roots@225; std::mem@226

`third_party/rust/num-iter/.cargo-checksum.json` | `a9006696d1532f566938705f9ec4414a143b21b9` | 748 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-iter/.cargo_vcs_info.json` | `c815971f97de743c756cfad0dc15deabfb430c2c` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-iter/Cargo.toml` | `71d53cbe23c21df94f7647e7f8ff1a2de6dd3b8f` | 1378 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-iter/Cargo.toml.orig` | `c9e042e7ecef309c6ebe4489af4b2ccaac760d7f` | 915 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-iter/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-iter/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-iter/README.md` | `737a622747c05b310bb1af710fcd034d76180024` | 1491 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-iter/RELEASES.md` | `abbd1560e1644872cbb7e091ace2ce38fe3a4647` | 2771 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-iter/src/lib.rs` | `31a579c4bea15da642f469eb8500df5ca4b6b2fb` | 20388 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Range@27; range@47; unsigned@59; Some@61; start_bound@67; end_bound@71; Item@81; next@84; size_hint@95; Some@108; next_back@126; RangeInclusive@138; range_inclusive@145; start_bound@156; end_bound@160; Item@169; next@172; Some@174; size_hint@187; Some@194; next_back@207; RangeStep@223; range_step@232; Item@249; next@252; Some@256; RangeStepInclusive@268; range_step_inclusive@278; Item@296; next@299; Some@305; RangeFrom@317; range_from@329; start_bound@340; end_bound@344; Item@353; next@356; size_hint@363; RangeStepFrom@370; range_step_from@382; Item@393; next@396; size_hint@403; tests@409; test_range@417; Foo@419; to_i64@422; to_u64@425; Output@431; add@433; eq@439; partial_cmp@445; clone@451; Output@457; mul@459; one@465; test_range_128@492; test_range_inclusive@530; test_range_inclusive_128@550; test_range_step@582; test_range_step_128@592; test_range_step_inclusive@604; test_range_step_inclusive_128@614; test_range_from@627; test_range_step_from@635
Dependencies: core::ops::@20; core::usize@21; num_integer::Integer@22; num_traits::@23; core::cmp::Ordering@410; core::iter@411; core::ops::@412; core::@413; num_traits::@414; core::@493; core::i128@551; core::u128::MAX@593; core::u128::MAX@615

`third_party/rust/num-rational/.cargo-checksum.json` | `7ecb4f181862bc49491c82ccc0fddd275faa1135` | 828 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-rational/.cargo_vcs_info.json` | `387b35b15467fdfa0e62f68a5e0219c0ca77e219` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-rational/Cargo.toml` | `3f23cd13c43a4bf9f6b2e3f6ef9cf3a597c9e0fb` | 1724 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-rational/Cargo.toml.orig` | `3e9b539e6fe22a600e6179ded39e9e27a2c1703e` | 1187 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-rational/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-rational/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-rational/README.md` | `9ddf0dd1379c24ba4b7c647ae0475882cd16ef76` | 1441 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-rational/RELEASES.md` | `d3779386df68cd95140bb9288b976e47627b810e` | 6451 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-rational/src/lib.rs` | `b1cf2a43178d6f2c97976f84b570dde58a43f87f` | 103573 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: pow@46; Ratio@51; Rational@63; Rational32@65; Rational64@67; BigRational@71; into_raw@86; new@108; from_integer@116; to_integer@122; is_integer@128; reduce@135; replace_with@153; reduced@177; recip@187; into_recip@192; floor@202; ceil@215; round@228; trunc@262; fract@270; pow@276; from_float@287; default@311; from@321; from@331; cmp@343; partial_cmp@396; eq@403; hash@413; recurse@416; iter_sum_product@428; sum@435; sum@444; product@453; product@462; opassign@471; add_assign@479; div_assign@495; mul_assign@508; rem_assign@520; sub_assign@535; add_assign@551; div_assign@558; mul_assign@567; rem_assign@577; sub_assign@585; $method@595; $method@601; Output@618; $method@621; Output@626; $method@629; Output@642; $method@645; Output@653; $method@656; Output@669; $method@672; Output@680; $method@683; Output@705; mul@707; Output@721; mul@723; Output@735; div@738; Output@752; div@755; Output@766; $method@768; Output@780; $method@782; checked_mul@799; checked_div@816; $method@862; Output@883; neg@886; Output@895; neg@898; Output@907; inv@910; Output@919; inv@922; zero@939; is_zero@944; set_zero@949; one@966; is_one@971; set_one@976; FromStrRadixErr@983; from_str_radix@986; abs@1012; abs_sub@1021; signum@1030; is_positive@1041; is_negative@1047; fmt@1058; fmt@1075; Err@1116; from_str@1119; Zero::is_zero@1134; from@1145; serialize@1155; deserialize@1168; ParseRatioError@1188; RatioErrorKind@1193; fmt@1199; description@1207; description@1213; from_i64@1223; from_i128@1227; from_u64@1231; from_u128@1235; from_f32@1239; from_f64@1243; from_i64@1251; from_i128@1255; from_u64@1259; from_u128@1263; from_f32@1267; from_f64@1271; approximate_float@1293; approximate_float_unsigned@1303; approximate_float@1312; approximate_float_unsigned@1328; Some@1360; Some@1365; let@1396; to_i64@1423; to_i128@1427; to_u64@1431; to_u128@1435; to_f64@1439; to_i64@1461; to_i128@1465; to_u64@1469; to_u128@1473; to_f64@1477; to_i64@1500; to_i128@1504; to_u64@1508; to_u128@1512; to_f64@1516; Bits@1536; bits@1537; bits@1542; bits@1548; ratio_to_f64@1557; let@1580; let@1593; Some@1594; ldexp@1651; let@1675; hash@1719; test@1728; to_big@1815; to_big@1822; test_test_constants@1830; test_new_reduce@1842; test_new_zero@1849; test_approximate_float@1854; test_cmp@1897; test_cmp_overflow@1914; check_cmp@1933; test_to_integer@1953; test_numer@1963; test_denom@1972; test_is_integer@1982; NoStdTester@1995; new@2002; clear@2009; write_str@2020; eq@2034; test_show@2062; arith@2149; test_add@2157; test@2158; test_assign@2172; test_add_overflow@2192; test_add_typed_overflow@2196; test_sub@2228; test@2229; test_assign@2243; test_sub_overflow@2262; test_sub_typed_overflow@2265; test_mul@2293; test@2294; test_assign@2308; test_mul_overflow@2327; test_mul_typed_overflow@2328; test_div@2382; test@2383; test_assign@2397; test_div_overflow@2416; test_div_typed_overflow@2417; test_rem@2471; test@2472; test_assign@2484; test_rem_overflow@2505; test_rem_typed_overflow@2508; test_neg@2540; test@2541; test_zero@2552; test_div_0@2561; test_checked_failures@2566; test_checked_zeros@2577; test_checked_min@2585; test_checked_max@2609; test_checked_min_max@2633; test_round@2649; test_fract@2708; test_recip@2716; test_recip_fail@2730; test_pow@2735; test@2736; test_big@2747; test_to_from_str@2771; test@2773; test_from_str_fail@2785; test@2786; test_from_float@2799; test@2801; test_from_float_fail@2846; test_signed@2858; test_hash@2879; test_into_pair@2896; test_from_pair@2903; ratio_iter_sum@2911; iter_sums@2914; ratio_iter_product@2932; iter_products@2935; test_num_zero@2958; test_num_one@2971; test_const@2984; test_ratio_to_i64@2998; test_ratio_to_i128@3006; test_big_ratio_to_f64@3017; test_ratio_to_f64@3070; test_ldexp@3097
Dependencies: core::cmp@27; core::fmt@28; core::fmt::@29; core::hash::@30; core::ops::@31; core::str::FromStr@32; std::error::Error@34; num_bigint::@37; num_integer::Integer@39; num_traits::float::FloatCore@40; num_traits::@41; crate::Ratio@429; core::iter::@430; num_integer::Integer@431; num_traits::@432; core::ops::@472; crate::Ratio@474; num_integer::Integer@475; num_traits::NumAssign@476; serde::de::Error@1172; serde::de::Unexpected@1173; core::f64::@1561; core::f64::@1652; std::collections::hash_map::RandomState@1720; std::hash::BuildHasher@1721; super::ldexp@1729; super::@1731; super::@1732; core::f64@1734; core::i32@1735; core::i64@1736; core::str::FromStr@1737; num_integer::Integer@1738; num_traits::ToPrimitive@1739; num_traits::@1740; core::cmp::Ordering@1915; core::fmt::@1992; super::super::@2150; super::@2151; core::fmt::Debug@2152; num_integer::Integer@2153; num_traits::@2154; std::string::@2772; num_traits::float::FloatCore@2800; core::@2847; core::f64::@3098

`third_party/rust/num-rational/src/pow.rs` | `33253320e7dfd637514746ea96744e040ca85e65` | 5354 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Output@9; pow@11; Output@26; pow@28; Output@36; pow@38; Output@53; pow@55; Output@66; pow@68; Output@90; pow@92; Output@100; pow@102; bigint@116; Output@121; pow@123; Output@131; pow@133; Output@148; pow@150; Output@158; pow@160
Dependencies: crate::Ratio@1; core::cmp@3; num_integer::Integer@4; num_traits::@5; super::@117; num_bigint::@118

`third_party/rust/num-traits/.cargo-checksum.json` | `c78e2cc13a8f4ef8acb7784da2e7331daf4efbb1` | 2436 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-traits/.cargo_vcs_info.json` | `7ee50d6f3e07694f647a1330de53974502fafb3d` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-traits/Cargo.toml` | `97ceb1b6d87832c5b0289c0c8e6bfc8dce53f2ea` | 1296 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num-traits/Cargo.toml.orig` | `226d4164cebe9f52662c48fcc6019b497b9bdd70` | 835 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-traits/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-traits/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num-traits/README.md` | `fd420705ffba21cfb976bb2ff3cb73afad70374c` | 1794 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-traits/RELEASES.md` | `5f23f56ad53ba5340442eb1b40c7e45dce6258d1` | 12754 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num-traits/build.rs` | `98b06befdb2d37c850eb6006bd1cdcab04691539` | 160 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: main@1

`third_party/rust/num-traits/src/bounds.rs` | `acc990ea503df24915e750a04a0f31ddc2a70d51` | 3870 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Bounded@7; min_value@10; max_value@12; LowerBounded@16; min_value@18; min_value@23; UpperBounded@29; max_value@31; max_value@36; min_value@45; max_value@50; min_value@72; max_value@75; min_value@101; max_value@105; wrapping_bounded@116; wrapping_bounded_i128@130; wrapping_is_bounded@144; require_bounded@145
Dependencies: core::num::Wrapping@1; core::@2; core::@3; core::@4

`third_party/rust/num-traits/src/cast.rs` | `a3e4dd8b7fd55be625137415060ba9d8316525e0` | 25904 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ToPrimitive@17; to_isize@21; to_i8@28; to_i16@35; to_i32@42; to_i64@48; to_i128@57; to_usize@64; to_u8@71; to_u16@78; to_u32@85; to_u64@91; to_u128@100; to_f32@108; to_f64@120; Some@122; $method@132; $method@148; to_isize@163; to_i8@164; to_i16@165; to_i32@166; to_i64@167; to_i128@168; to_usize@172; to_u8@173; to_u16@174; to_u32@175; to_u64@176; to_u128@177; to_f32@181; to_f64@185; $method@203; $method@218; to_isize@233; to_i8@234; to_i16@235; to_i32@236; to_i64@237; to_i128@238; to_usize@242; to_u8@243; to_u16@244; to_u32@245; to_u64@246; to_u128@247; to_f32@251; to_f64@255; $method@272; $method@292; $method@322; to_isize@349; to_i8@350; to_i16@351; to_i32@352; to_i64@353; to_i128@354; to_usize@358; to_u8@359; to_u16@360; to_u32@361; to_u64@362; to_u128@363; to_f32@367; to_f64@368; FromPrimitive@387; from_isize@391; from_i8@398; from_i16@405; from_i32@412; from_i64@418; from_i128@426; from_usize@433; from_u8@440; from_u16@447; from_u32@454; from_u64@460; from_u128@468; from_f32@475; from_f64@486; Some@488; from_isize@499; from_i8@503; from_i16@507; from_i32@511; from_i64@515; from_i128@519; from_usize@524; from_u8@528; from_u16@532; from_u32@536; from_u64@540; from_u128@544; from_f32@549; from_f64@553; $method@579; to_isize@587; to_i8@588; to_i16@589; to_i32@590; to_i64@591; to_i128@592; to_usize@594; to_u8@595; to_u16@596; to_u32@597; to_u64@598; to_u128@599; to_f32@601; to_f64@602; $method@610; from_isize@618; from_i8@619; from_i16@620; from_i32@621; from_i64@622; from_i128@623; from_usize@625; from_u8@626; from_u16@627; from_u32@628; from_u64@629; from_u128@630; from_f32@632; from_f64@633; cast@648; NumCast@653; from@666; from@674; from@699; AsPrimitive@730; as_@735
Dependencies: core::mem::size_of@1; core::num::Wrapping@2; core::@3; core::@4; core::@5

`third_party/rust/num-traits/src/float.rs` | `d0d21a5099b143c8841b4ce956f7d1bc142bc559` | 70306 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: FloatCore@13; infinity@29; neg_infinity@46; nan@63; neg_zero@82; min_value@99; min_positive_value@116; epsilon@133; max_value@150; is_nan@171; is_infinite@195; is_finite@218; is_normal@241; is_subnormal@267; classify@293; floor@318; ceil@352; round@385; trunc@427; fract@459; abs@488; signum@522; is_sign_positive@555; is_sign_negative@582; min@607; max@641; clamp@681; recip@704; powi@728; to_degrees@756; to_radians@775; integer_decode@798; integer_decode@814; fract@858; integer_decode@876; fract@920; Float@932; nan@942; infinity@955; neg_infinity@968; neg_zero@982; min_value@994; min_positive_value@1006; epsilon@1023; max_value@1036; is_nan@1050; is_infinite@1070; is_finite@1089; is_normal@1113; is_subnormal@1137; classify@1156; floor@1169; ceil@1182; round@1196; trunc@1209; fract@1224; abs@1244; signum@1263; is_sign_positive@1283; is_sign_negative@1303; mul_add@1323; recip@1334; powi@1348; powf@1360; sqrt@1377; exp@1393; exp2@1407; ln@1423; log@1442; log2@1456; log10@1470; to_degrees@1484; to_radians@1502; max@1518; min@1530; clamp@1545; abs_sub@1566; cbrt@1580; hypot@1596; sin@1610; cos@1624; tan@1637; asin@1654; acos@1671; atan@1686; atan2@1715; sin_cos@1733; exp_m1@1748; ln_1p@1764; sinh@1782; cosh@1800; tanh@1818; asinh@1832; acosh@1846; atanh@1861; integer_decode@1882; copysign@1905; abs_sub@1931; integer_decode@1936; integer_decode@2011; fract@2016; log@2021; integer_decode_f32@2049; integer_decode_f64@2063; abs_sub@2088; abs_sub@2134; FloatConst@2177; TAU@2181; LOG10_2@2186; LOG2_10@2191; TotalOrder@2248; total_cmp@2299; total_cmp@2306; total_cmp@2312; tests@2329; convert_deg_rad@2343; convert_deg_rad_std@2358; to_degrees_rounding@2372; extra_logs@2383; check@2386; copysign@2402; test_copysignf@2410; test_copysign_generic@2429; test_subnormal@2446; subnormal@2455; total_cmp@2461; check_eq@2466; check_lt@2469; check_gt@2472
Dependencies: core::cmp::Ordering@1; core::num::FpCategory@2; core::ops::@3; core::f32@5; core::f64@6; crate::@8; core::f64::consts@2330; crate::float::FloatCore@2344; crate::Float@2360; crate::float::FloatCore@2373; crate::float::@2384; crate::float::Float@2403; crate::float::Float@2411; core::ops::Neg@2412; crate::float::TotalOrder@2462; core::cmp::Ordering@2463; core::@2464

`third_party/rust/num-traits/src/identities.rs` | `c30cd1dc0b45e5847310f491cd6f988ce3de61d1` | 5440 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Zero@12; zero@20; set_zero@23; is_zero@28; ConstZero@33; zero@42; is_zero@46; is_zero@78; set_zero@82; zero@86; One@106; one@115; set_one@118; is_one@128; ConstOne@138; one@147; is_one@151; set_one@183; one@187; zero@203; one@209; wrapping_identities@214; wrapping_is_zero@230; require_zero@231; wrapping_is_one@235; require_one@236
Dependencies: core::num::Wrapping@1; core::ops::@2

`third_party/rust/num-traits/src/int.rs` | `c6284bf4e807563b23af37f2a926b58b966578c7` | 15786 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: PrimInt@34; count_ones@66; count_zeros@79; leading_ones@93; leading_zeros@109; trailing_ones@123; trailing_zeros@139; rotate_left@154; rotate_right@169; signed_shl@186; signed_shr@203; unsigned_shl@220; unsigned_shr@237; swap_bytes@251; reverse_bits@269; from_be@290; from_le@309; to_be@328; to_le@347; pow@358; one_per_byte@361; reverse_bits_fallback@377; count_ones@398; count_zeros@403; leading_ones@408; leading_zeros@413; trailing_ones@418; trailing_zeros@423; rotate_left@428; rotate_right@433; signed_shl@438; signed_shr@443; unsigned_shl@448; unsigned_shr@453; swap_bytes@458; reverse_bits@463; from_be@468; from_le@473; to_be@478; to_le@483; pow@488; tests@510; reverse_bits@514; reverse_bits_i128@552
Dependencies: core::ops::@1; crate::bounds::Bounded@3; crate::ops::checked::@4; crate::ops::saturating::Saturating@5; crate::@6; crate::int::PrimInt@511; core::@515; core::i128@553

`third_party/rust/num-traits/src/lib.rs` | `d392e920d836cae6aeeb874569ac70ccc91dfb09` | 21776 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: macros@53; bounds@55; cast@56; float@57; identities@58; int@59; ops@60; pow@61; real@62; sign@63; Num@67; FromStrRadixErr@68; from_str_radix@95; NumOps@101; NumRef@123; RefNum@132; NumAssignOps@138; NumAssign@151; NumAssignRef@158; FromStrRadixErr@164; from_str_radix@166; FromStrRadixErr@181; from_str_radix@182; FloatErrorKind@188; ParseFloatError@195; fmt@200; str_to_ascii_lower_eq_str@210; FromStrRadixErr@224; from_str_radix@226; slice_shift_char@254; let@259; Some@261; Some@262; Some@263; Some@277; Some@325; Some@356; let@365; Some@366; Some@367; Some@368; pow@373; clamp@402; clamp_min@422; clamp_max@440; clamp_test@450; clamp_nan_min@476; clamp_nan_max@483; clamp_nan_min_max@490; clamp_min_nan_min@497; clamp_max_nan_max@504; from_str_radix_unwrap@509; from_str_radix_multi_byte_fail@520; from_str_radix_ignore_case@529; wrapping_is_num@551; require_num@552; wrapping_from_str_radix@558; check_num_ops@574; compute@575; check_numref_ops@582; compute@583; check_refnum_ops@590; compute@591; check_refref_ops@601; compute@602; check_numassign_ops@612; compute@613; check_numassignref_ops@625; compute@626
Dependencies: core::fmt@25; core::num::Wrapping@26; core::ops::@27; core::ops::@28; self::FloatErrorKind::@229; self::ParseFloatError@230

`third_party/rust/num-traits/src/macros.rs` | `b97758e42c7354de4c20ca685c489588461ecc53` | 1397 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: $method@9; $method@16; $method@23; $method@30; $method@40

`third_party/rust/num-traits/src/ops/bytes.rs` | `f6a8030a2b58a052d672b448eef4d07c65fea137` | 8833 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: NumBytes@6; ToBytes@35; Bytes@36; to_be_bytes@48; to_le_bytes@60; to_ne_bytes@84; FromBytes@93; Bytes@94; from_be_bytes@106; from_le_bytes@118; from_ne_bytes@142; Bytes@154; to_be_bytes@157; to_le_bytes@162; to_ne_bytes@167; Bytes@173; from_be_bytes@176; from_le_bytes@181; from_ne_bytes@186; Bytes@196; to_be_bytes@199; to_le_bytes@204; to_ne_bytes@209; Bytes@215; from_be_bytes@218; from_le_bytes@223; from_ne_bytes@228; tests@259; convert_between_int_and_bytes@288; convert_between_float_and_bytes@294
Dependencies: core::borrow::@1; core::cmp::@2; core::fmt::Debug@3; core::hash::Hash@4; super::@260

`third_party/rust/num-traits/src/ops/checked.rs` | `da1eb3eae3e52c3c77760c62848cc65f44eec75e` | 10040 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: CheckedAdd@5; checked_add@8; $method@15; CheckedSub@37; checked_sub@40; CheckedMul@59; checked_mul@62; CheckedDiv@81; checked_div@84; CheckedRem@103; checked_rem@123; $method@144; CheckedNeg@152; checked_neg@169; CheckedShl@188; checked_shl@202; $method@209; CheckedShr@232; checked_shr@246
Dependencies: core::ops::@1

`third_party/rust/num-traits/src/ops/euclid.rs` | `fa7b317a288dc3c20b805e8e07e6c96c8b3d5310` | 9376 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Euclid@3; div_euclid@23; rem_euclid@48; div_rem_euclid@67; div_euclid@76; rem_euclid@81; div_euclid@97; rem_euclid@106; div_euclid@119; rem_euclid@128; CheckedEuclid@138; checked_div_euclid@141; checked_rem_euclid@145; checked_div_rem_euclid@163; checked_div_euclid@172; checked_rem_euclid@177; tests@188; euclid_unsigned@192; euclid_signed@213; euclid_float@237; euclid_checked@262
Dependencies: core::ops::@1; super::@189

`third_party/rust/num-traits/src/ops/inv.rs` | `7087d09d0162dc15935d2fccfb9864412d8b254d` | 931 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Inv@2; Output@4; inv@17; Output@21; inv@23; Output@28; inv@30; Output@35; inv@37; Output@42; inv@44

`third_party/rust/num-traits/src/ops/mod.rs` | `2128d86a2dab38c786e7571ba32a64e01d5594f2` | 137 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: bytes@1; checked@2; euclid@3; inv@4; mul_add@5; overflowing@6; saturating@7; wrapping@8

`third_party/rust/num-traits/src/ops/mul_add.rs` | `51beb5572681f4fdcc4dc6bfdae994c28f770689` | 3983 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: MulAdd@23; Output@25; mul_add@28; MulAddAssign@32; mul_add_assign@34; Output@39; mul_add@42; Output@49; mul_add@52; Output@60; mul_add@63; mul_add_assign@76; mul_add_assign@84; mul_add_assign@93; tests@104; mul_add_integer@108; mul_add_float@128
Dependencies: super::@105; core::@133

`third_party/rust/num-traits/src/ops/overflowing.rs` | `c7a35a51c1228ff72c40adbd7286b1097b27b196` | 4283 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: $method@9; OverflowingAdd@17; overflowing_add@20; OverflowingSub@38; overflowing_sub@41; OverflowingMul@59; overflowing_mul@62; test_overflowing_traits@80; overflowing_add@81; overflowing_sub@84; overflowing_mul@87
Dependencies: core::ops::@1; core::@2; core::@3

`third_party/rust/num-traits/src/ops/saturating.rs` | `16a0045767ac9520534cfacd7dd26246b5f01db3` | 5103 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Saturating@5; saturating_add@8; saturating_sub@12; saturating_add@19; saturating_sub@24; $method@38; SaturatingAdd@46; saturating_add@49; SaturatingSub@67; saturating_sub@70; SaturatingMul@88; saturating_mul@91; test_saturating_traits@111; saturating_add@112; saturating_sub@115; saturating_mul@118
Dependencies: core::ops::@1

`third_party/rust/num-traits/src/ops/wrapping.rs` | `3a8b3311675310ca28bea4df516e352ab20b94ac` | 11260 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: $method@8; $method@16; WrappingAdd@24; wrapping_add@27; WrappingSub@45; wrapping_sub@48; WrappingMul@66; wrapping_mul@69; $method@90; WrappingNeg@98; wrapping_neg@116; $method@136; WrappingShl@144; wrapping_shl@159; WrappingShr@177; wrapping_shr@192; wrapping_add@214; wrapping_sub@222; wrapping_mul@230; wrapping_neg@238; wrapping_shl@246; wrapping_shr@254; test_wrapping_traits@260; wrapping_add@261; wrapping_sub@264; wrapping_mul@267; wrapping_neg@270; wrapping_shl@273; wrapping_shr@276; wrapping_is_wrappingadd@294; require_wrappingadd@295; wrapping_is_wrappingsub@300; require_wrappingsub@301; wrapping_is_wrappingmul@306; require_wrappingmul@307; wrapping_is_wrappingneg@312; require_wrappingneg@313; wrapping_is_wrappingshl@318; require_wrappingshl@319; wrapping_is_wrappingshr@324; require_wrappingshr@325
Dependencies: core::num::Wrapping@1; core::ops::@2

`third_party/rust/num-traits/src/pow.rs` | `ef51c954d7b9705196d10fb04ae6fecc69a28eb0` | 6574 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Pow@6; Output@8; pow@18; Output@36; pow@38; Output@44; pow@46; Output@52; pow@54; Output@60; pow@62; float_impls@146; pow@179; checked_pow@220
Dependencies: crate::@1; core::num::Wrapping@2; core::ops::Mul@3; super::Pow@147; crate::Float@148

`third_party/rust/num-traits/src/real.rs` | `25ec873258ece9e7ecaa6f143a689b1a5f396685` | 22156 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Real@17; min_value@28; min_positive_value@40; epsilon@57; max_value@68; floor@81; ceil@94; round@108; trunc@121; fract@136; abs@156; signum@175; is_sign_positive@193; is_sign_negative@211; mul_add@231; recip@243; powi@257; powf@269; sqrt@290; exp@306; exp2@320; ln@340; log@363; log2@381; log10@400; to_degrees@413; to_radians@426; max@438; min@450; abs_sub@469; cbrt@483; hypot@499; sin@513; cos@527; tan@540; asin@562; acos@584; atan@599; atan2@628; sin_cos@646; exp_m1@661; ln_1p@682; sinh@700; cosh@718; tanh@736; asinh@750; acosh@764; atanh@779
Dependencies: core::ops::Neg@3; crate::@5

`third_party/rust/num-traits/src/sign.rs` | `a0d6b0fd6c0b174c81f1ca4d2efa0719cfca130b` | 5877 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: Signed@8; abs@14; abs_sub@20; signum@35; is_positive@38; is_negative@41; abs@48; abs_sub@53; signum@58; is_positive@67; is_negative@70; abs@82; abs_sub@87; signum@92; is_positive@97; is_negative@102; abs@112; abs_sub@120; signum@134; is_positive@140; is_negative@146; abs@162; abs_sub@171; signum@189; Unsigned@194; unsigned_wrapping_is_unsigned@207; require_unsigned@208; signed_wrapping_is_signed@213; require_signed@214
Dependencies: core::num::Wrapping@1; core::ops::Neg@2; crate::float::FloatCore@4; crate::Num@5

`third_party/rust/num-traits/tests/cast.rs` | `4f01d749ef93914a495e275475f31d43f2d9da17` | 12080 bytes | imported-path,test-path,source | UTF-8 | mode 100644
Declarations: to_primitive_float@17; wrapping_to_primitive@29; wrapping_is_toprimitive@55; require_toprimitive@56; wrapping_is_fromprimitive@61; require_fromprimitive@62; wrapping_is_numcast@67; require_numcast@68; as_primitive@73; float_to_integer_checks_overflow@85; cast_to_int_checks_overflow@94; cast_to_unsigned_int_checks_overflow@118; cast_to_i128_checks_overflow@142; dbg@157; dbg@162; let@182; RawOffset@203; raw_inc@204; raw_dec@205; raw_inc@209; raw_dec@213; raw_inc@219; raw_dec@223; cast_float_to_int_edge_cases@229; cast_float_to_i128_edge_cases@237; test_edge@245; cast_int_to_int_edge_cases@281; cast_int_to_128_edge_cases@296; newtype_from_primitive@314; New@316; from_i64@320; from_u64@324; check@338; newtype_to_primitive@352; New@354; to_i64@358; to_u64@362; check@376
Dependencies: num_traits::cast::@5; num_traits::Bounded@6; core::@8; core::@9; core::@10; core::fmt::Debug@12; core::mem@13; core::num::Wrapping@14; core::cmp::Ordering::@282; core::cmp::Ordering::@297

`third_party/rust/num/.cargo-checksum.json` | `d0ae60d1146d4bab2a9d7816b292c9eef9c68c90` | 748 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num/.cargo_vcs_info.json` | `7b711266a4aecdfd3612a45ffb489b7040ce6df6` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num/Cargo.toml` | `28cb5670bbb91faf628f9f626998e2c350658dda` | 2252 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num/Cargo.toml.orig` | `ac07a38df3d1b5e2c211e065cd8ef8230f8155df` | 1701 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num/LICENSE-MIT` | `39d4bdb5acd313c1a92dbeaa1c379aaf0596a315` | 1071 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num/README.md` | `f9ab46cfce8ca5ce3d3cdbd6d0271e6ff750847b` | 5234 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num/RELEASES.md` | `4fcb1a45add37796471c629438310e46ef1a274f` | 4589 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num/src/lib.rs` | `34b247fbd8eeb0303ed097ed592a9172c0ac36ff` | 3086 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: bigint@86; complex@90; integer@94; iter@98; traits@102; rational@106

`third_party/rust/num_cpus/.cargo-checksum.json` | `ced0174fce68f8d355a0dece63f32797aadc4460` | 3184 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/.cargo_vcs_info.json` | `2273b4739f2ad1ee49bcb0a212c53390fab106eb` | 94 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/.github/FUNDING.yml` | `9954063dcc7bb76719c38446fd41057fc968a5cd` | 41 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/.github/workflows/ci.yml` | `36dc5b9c1523a891efbdd6d3f6426b68059a74e0` | 3979 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/CHANGELOG.md` | `72b3e88381f0158b8c8264ed3a711262f94881bf` | 2006 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num_cpus/CONTRIBUTING.md` | `5685b08c6740b4d72632440e0ee6fb4576a0c1af` | 513 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num_cpus/Cargo.lock` | `29bff55ded149d922a164ce648c2b545dd06d841` | 579 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/Cargo.toml` | `29adde84785197ea9a1a1f538427e07dcec5488c` | 1001 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/rust/num_cpus/Cargo.toml.orig` | `6c63fbfc74e278bce0ee4e5921d0bce67dff0e6d` | 502 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/LICENSE-APACHE` | `16fe87b06e802f094b3fbb0894b137bca2b16ef1` | 10847 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/LICENSE-MIT` | `8e91dc998a9f8260d88079046200713c66684946` | 1044 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/README.md` | `74041b8de09978475148bcc0b4767ad791a6f738` | 595 bytes | imported-path,documentation | UTF-8 | mode 100644

`third_party/rust/num_cpus/ci/cgroups/Dockerfile` | `7636a477bf48ba32ea007429ccb429ae8d6ee0ec` | 101 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/examples/values.rs` | `041cfaf1eb6926c4f7c2e0a2b6cffa720cff9a09` | 150 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: main@3

`third_party/rust/num_cpus/fixtures/cgroups/cgroups/ceil/cpu.cfs_period_us` | `022f514ba121a5f357d0590f4751ece848012c6a` | 8 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/cgroups/ceil/cpu.cfs_quota_us` | `cb2bf3ec7a23e6b0f94b59ac092ad9cce2215afe` | 8 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/cgroups/good/cpu.cfs_period_us` | `022f514ba121a5f357d0590f4751ece848012c6a` | 8 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/cgroups/good/cpu.cfs_quota_us` | `16e37df1d1b6b60305c74dcd97d9b3289f73063e` | 8 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/cgroups/zero-period/cpu.cfs_period_us` | `77ac542d4fbf044fb1ea10086971de8ad97f8603` | 3 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/cgroups/zero-period/cpu.cfs_quota_us` | `26f3b3ddf286f4d90b3fd16585d4edaee0f74197` | 7 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/cgroup` | `a47f047247f2b44479440409ed231d8212e6bacf` | 55 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/mountinfo` | `37f4e25359f2bfcebf61be1216bcb8f966583cd1` | 715 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/mountinfo_multi_opt` | `e03a95b42597a5a0b68d911f87f320324ed7a5d3` | 733 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups/proc/cgroups/mountinfo_zero_opt` | `ad27a964f3aa6ca6ac6377e96391b5aae12261c7` | 706 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups2/cgroups/ceil/cpu.max` | `833a8f2d3b677f5be80c6e7c87bb2de860a659ce` | 14 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups2/cgroups/good/cpu.max` | `e469067a61a198cb50826deed50cf1da5dcd8509` | 14 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups2/cgroups/zero-period/cpu.max` | `24e757f51c35718afa8e0ff6cba233a44be18b88` | 9 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups2/proc/cgroups/cgroup` | `35b49db2c08ca19859102027ff1756559b8fd054` | 21 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups2/proc/cgroups/cgroup_multi` | `1a9282a6e41cfdff6b280ea9bfc0c5c1c598560f` | 38 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/fixtures/cgroups2/proc/cgroups/mountinfo` | `da36e4102ff5135d2e1ba48b66ed1f366eff5a79` | 444 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/rust/num_cpus/src/lib.rs` | `fa1267c665fd77cbfe4feb9bafc5c3e19cda9ec7` | 13329 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: linux@40; get@73; get_physical@108; get_num_physical_cpus@120; get_num_physical_cpus@126; get_num_physical_cpus_windows@127; Some@128; get_num_physical_cpus_windows@134; SYSTEM_LOGICAL_PROCESSOR_INFORMATION@145; GetLogicalProcessorInformation@152; get_num_cpus@209; SYSTEM_INFO@211; GetSystemInfo@226; get_num_cpus@239; get_num_cpus@266; get_num_physical_cpus@289; get_num_physical_cpus@313; get_num_physical_cpus@336; get_smt_threads_aix@337; Some@338; get_smt_threads_aix@344; get_num_cpus@364; get_num_cpus@381; bigtime_t@385; status_t@387; system_info@390; get_system_info@419; get_num_cpus@432; get_num_cpus@454; tests@459; env_var@460; test_get@465; test_get_physical@476
Dependencies: linux::@42; std::ptr@137; std::mem@138; std::ptr@240; std::ptr@267; std::ptr@290; std::ffi::CStr@314; std::ptr@315; std::mem@382

## Validation and limits

Every listed blob was read from the pinned Git tree and its Git SHA-1 was recomputed. Extraction is structural only. Read implementations, callers, build conditions, and tests before making a behavior claim. Runtime behavior and historical reasons remain unverified. Reproduce a file with `git show 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b:path` in the corresponding source clone. The full study coverage and navigation note records aggregate results.
