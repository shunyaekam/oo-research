# Research methods

Elapsed seconds sum the measured duration of recorded jobs. Input tokens include cached input. Token coverage counts hosted jobs with complete usage divided by hosted jobs observed. The ledger covers the scheduled worker. Interactive sessions and work before instrumentation have unknown cost.

| Problem | Runs | Failed or timed out | Job seconds | Input / output tokens | Token coverage |
|---|---:|---:|---:|---:|---:|
| bernasconi-table2 | 157 | 0 | 130.6 | — | — |
| e27-schmidt | 157 | 0 | 157.4 | — | — |
| gagatsos-2026-c1 | 590 | 0 | 1,534.5 | — | — |
| golay43 | 315 | 93 | 1,069.3 | — | — |
| lts-Arxiv.2607.27197.maxwell_conjecture.variants.three_charges.R1.H1 | 1 | 0 | 88.7 | 337,260 / 3,220 | 1/1 |
| lts-Arxiv.2607.27197.maxwell_conjecture.variants.three_equal_magnitudes | 4 | 4 | 517.2 | — | 0/3 |
| lts-Erdos1164.erdos_1164.R1.H2.R1.H1 | 3 | 1 | 489.7 | 878,620 / 8,904 | 2/3 |
| lts-Erdos1165.erdos_1165.R1.H1 | 1 | 0 | 146.0 | 975,341 / 4,634 | 1/1 |
| lts-Erdos1165.erdos_1165.R1.H2 | 1 | 0 | 143.0 | 842,263 / 4,374 | 1/1 |
| lts-Erdos1166.erdos_1166.variants.dembo_peres_rosen_zeitouni.R1.H2 | 1 | 0 | 91.9 | 494,151 / 3,149 | 1/1 |
| lts-OpenQuantumProblem23.hasSICPOVM_68.R1.H1 | 2 | 0 | 338.0 | 996,404 / 10,876 | 2/2 |
| lts-mo-338936 | 1 | 0 | 98.8 | 263,468 / 3,920 | 1/1 |
| lts-oeis-a284230 | 2 | 1 | 111.1 | 185,342 / 2,527 | 1/2 |
| oqp:A13 | 1 | 0 | 57.6 | 198,280 / 1,837 | 1/1 |
| oqp:A27 | 1 | 0 | 66.6 | 233,142 / 2,077 | 1/1 |
| refined-bmv | 167 | 3 | 477.2 | 727,597 / 9,879 | 7/10 |
| support-enumeration | 20 | 0 | 823.4 | — | — |
| thomson-10 | 39 | 0 | 18.1 | — | — |
| thomson-11 | 39 | 0 | 11.5 | — | — |
| thomson-13 | 40 | 0 | 16.6 | — | — |
| thomson-14 | 39 | 0 | 17.5 | — | — |
| werner-endpoint | 315 | 0 | 350.7 | 67,096 / 624 | 1/1 |

## Time to certificate

The endpoint is the first public commit containing a full target certificate. Calendar time starts at the first logged job for that target. Earlier work and costs outside the worker remain unmeasured.

| Certified target | Observed hours to release | Job seconds before release | Input / output tokens | Token coverage |
|---|---:|---:|---:|---:|
| [wei-10-2-4](https://github.com/shunyaekam/oo-research/blob/main/certificates/wei-10-2-4.json) | Unmeasured | — | — | — |
| [wei-12-3-4](https://github.com/shunyaekam/oo-research/blob/main/certificates/wei-12-3-4.json) | Unmeasured | — | — | — |
| [wei-12-4-4](https://github.com/shunyaekam/oo-research/blob/main/certificates/wei-12-4-4.json) | Unmeasured | — | — | — |

## Latest attempts

| Started (UTC) | Problem | Stage | Method | Model / effort | Status / outcome | Job seconds | Input / output tokens |
|---|---|---|---|---|---|---:|---:|
| [2026-11-28T18:00:02.781+00:00](method-runs/c107b99c91fa465799231ae8447fd2f2.json) | thomson-13 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.3 | — |
| [2026-11-28T17:59:58.972+00:00](method-runs/7112b3d0f4bf44be8fbf7a10ad78b21e.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 1.1 | — |
| [2026-11-28T17:59:58.528+00:00](method-runs/bef7c399628540d88a332ac6f23a0982.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 0.4 | — |
| [2026-11-28T17:59:58.379+00:00](method-runs/151d8ffc97594b31bb3e8434dd76e17b.json) | gagatsos-2026-c1 | search | wigner_search.search | — | completed / bounded_result | 0.2 | — |
| [2026-11-28T17:59:52.866+00:00](method-runs/6afb836e03fa4814b6762865ce6a0440.json) | gagatsos-2026-c1 | search | coherent_band_search.py | — | completed / search_receipt | 2.1 | — |
| [2026-11-28T17:59:51.237+00:00](method-runs/1751435a82f04621b1ec746a7a9c81c1.json) | gagatsos-2026-c1 | search | three_level_search.py | — | completed / search_receipt | 1.6 | — |
| [2026-11-28T17:59:50.020+00:00](method-runs/60c0dc1ce45449fa97fb40b1100a4567.json) | gagatsos-2026-c1 | search | excited_pairs.py | — | completed / no_new_receipt | 1.2 | — |
| [2026-11-28T17:59:37.369+00:00](method-runs/04ef4ad412614e6c950f16cf1f40927f.json) | bernasconi-table2 | search | checks/finite_spins.py | — | completed / no_new_receipt | 0.4 | — |
| [2026-11-28T17:59:37.149+00:00](method-runs/3c944b45097e4fdbab73b1dbb5922d8e.json) | refined-bmv | search | checks/bmv_search.py | — | completed / no_new_receipt | 0.2 | — |
| [2026-11-28T17:59:24.520+00:00](method-runs/1049bd3b498f43a8883948f868f8c040.json) | golay43 | search | checks/golay/advance.py | — | completed / search_receipt | 12.6 | — |
| [2026-11-28T17:59:24.300+00:00](method-runs/e8590ea3ed1f434dbc02bc245b4fe319.json) | golay43 | search | checks/golay43.py | — | completed / no_new_receipt | 0.2 | — |
| [2026-11-28T17:59:22.934+00:00](method-runs/30d8ab7492a147edbb05c66e7f08b28b.json) | e27-schmidt | search | checks/schmidt7/pair_search.py | — | completed / search_receipt | 1.4 | — |
| [2026-11-28T17:47:01.667+00:00](method-runs/6a49ed255d9b4beaa31194cb4cc98de0.json) | thomson-11 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.4 | — |
| [2026-11-28T17:46:58.558+00:00](method-runs/5194b1f083c04fd9a9c4748b9e389939.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 0.5 | — |
| [2026-11-28T17:46:58.115+00:00](method-runs/2647c3fc562f4a44a4589a1dd6f745ff.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 0.4 | — |
| [2026-11-28T17:46:57.879+00:00](method-runs/2c0ff74dc14a499781639b088a776d3b.json) | gagatsos-2026-c1 | search | wigner_search.search | — | completed / bounded_result | 0.3 | — |
| [2026-11-28T17:46:40.915+00:00](method-runs/a808d8dd6c374173a3a7208f6ef0807a.json) | gagatsos-2026-c1 | search | coherent_band_search.py | — | completed / search_receipt | 4.2 | — |
| [2026-11-28T17:46:36.454+00:00](method-runs/1b3f83e6d5e04cf39ae29754338c0fbd.json) | gagatsos-2026-c1 | search | three_level_search.py | — | completed / search_receipt | 4.4 | — |
| [2026-11-28T17:46:30.770+00:00](method-runs/d91c63f8b9384fe5a29830d045aeb9ce.json) | gagatsos-2026-c1 | search | excited_pairs.py | — | completed / no_new_receipt | 5.6 | — |
| [2026-11-28T17:45:19.159+00:00](method-runs/752f0c849d954a06bd2cb547415193e4.json) | bernasconi-table2 | search | checks/finite_spins.py | — | completed / no_new_receipt | 16.1 | — |
| [2026-11-28T17:45:15.427+00:00](method-runs/c325ef11190f4fe9801549fa9adf545c.json) | refined-bmv | search | checks/bmv_search.py | — | completed / no_new_receipt | 3.7 | — |
| [2026-11-28T17:44:41.812+00:00](method-runs/ebf35346e74b4772b9bb53f6d785eb16.json) | golay43 | search | checks/golay/advance.py | — | completed / search_receipt | 33.6 | — |
| [2026-11-28T17:44:41.238+00:00](method-runs/43bbce36d81747e4b0879cbfdb4f88f2.json) | golay43 | search | checks/golay43.py | — | completed / no_new_receipt | 0.6 | — |
| [2026-11-28T17:44:38.820+00:00](method-runs/d9398a5c14d44b11bdcb788288085cad.json) | e27-schmidt | search | checks/schmidt7/pair_search.py | — | completed / search_receipt | 2.5 | — |
| [2026-11-28T17:32:53.836+00:00](method-runs/147cd2cd387f47c38d55e41a60d0a438.json) | support-enumeration | search | continuous.advance_frontier | — | completed / search_receipt | 52.0 | — |
| [2026-11-28T17:32:53.688+00:00](method-runs/3bd71eaf23a0437c90a654cfb6f98ecd.json) | thomson-14 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.1 | — |
| [2026-11-28T17:32:49.355+00:00](method-runs/38982ca859c847b5a77d42f4a5083224.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 2.9 | — |
| [2026-11-28T17:32:45.591+00:00](method-runs/3faefbddde624de28a74435703541162.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 3.8 | — |
| [2026-11-28T17:32:43.008+00:00](method-runs/c40a9a1d8c2a4c6bb76924c39568624f.json) | gagatsos-2026-c1 | search | coherent_band_search.py | — | completed / search_receipt | 1.5 | — |
| [2026-11-28T17:32:41.347+00:00](method-runs/8863188b1c3d40da877bdff6644a639c.json) | gagatsos-2026-c1 | search | three_level_search.py | — | completed / search_receipt | 1.7 | — |
| [2026-11-28T17:32:39.767+00:00](method-runs/abf68c70740d4678b3369da66a17de8d.json) | gagatsos-2026-c1 | search | excited_pairs.py | — | completed / no_new_receipt | 1.6 | — |
| [2026-11-28T17:32:25.307+00:00](method-runs/c336eaa7d3344074a3a180c65e62c0ba.json) | bernasconi-table2 | search | checks/finite_spins.py | — | completed / no_new_receipt | 0.4 | — |
| [2026-11-28T17:32:25.066+00:00](method-runs/e50214c365b8454ca12307af8717004b.json) | refined-bmv | search | checks/bmv_search.py | — | completed / no_new_receipt | 0.2 | — |
| [2026-11-28T17:32:12.937+00:00](method-runs/edad24035cab4ff6b6f3d18c31cd8df0.json) | golay43 | search | checks/golay/advance.py | — | completed / search_receipt | 12.1 | — |
| [2026-11-28T17:32:12.722+00:00](method-runs/c5fbf1a9caf04954ad9877aac748358f.json) | golay43 | search | checks/golay43.py | — | completed / no_new_receipt | 0.2 | — |
| [2026-11-28T17:32:12.150+00:00](method-runs/3758192ebafe4655b408abf037f91ebc.json) | e27-schmidt | search | checks/schmidt7/pair_search.py | — | completed / search_receipt | 0.6 | — |
| [2026-11-28T17:21:29.145+00:00](method-runs/0e1de9b28b524118aca2c2d3ac299400.json) | thomson-10 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.2 | — |
| [2026-11-28T17:21:27.675+00:00](method-runs/df5a60ac60bc42448af8a978db0b3114.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 0.6 | — |
| [2026-11-28T17:21:26.942+00:00](method-runs/bae9a46efd56496bb8c9b14c3029ebe5.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 0.7 | — |
| [2026-11-28T17:21:26.756+00:00](method-runs/10ccb371190743168f3e7c9231555d31.json) | gagatsos-2026-c1 | search | wigner_search.search | — | completed / bounded_result | 0.2 | — |

## Search policy experiments

Each Golay policy constructs 24 circuits, split between 12 development seeds and 12 fresh evaluation seeds. Both policies receive the same seeds and the same number of pivot choices. Two signed stabilizer checks validate every circuit. The challenger advances inside this experiment only if it saves at least one gate on average, wins more pairs than it loses, and matches or improves the best gate count on each split. The physical target is at most 43 CNOTs.

| Week | Tree depths compared | Best CNOTs | Next tree depth | Seconds | Model tokens |
|---|---|---:|---:|---:|---:|
| [2026-W48](method-trials/v1-2026-W48.json) | 23 vs 12 | 47 | 23 | 3.22 | 0 |
