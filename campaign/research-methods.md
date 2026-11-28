# Research methods

Elapsed seconds sum the measured duration of recorded jobs. Input tokens include cached input. Token coverage counts hosted jobs with complete usage divided by hosted jobs observed. The ledger covers the scheduled worker. Interactive sessions and work before instrumentation have unknown cost.

| Problem | Runs | Failed or timed out | Job seconds | Input / output tokens | Token coverage |
|---|---:|---:|---:|---:|---:|
| bernasconi-table2 | 154 | 0 | 113.5 | — | — |
| e27-schmidt | 154 | 0 | 152.8 | — | — |
| gagatsos-2026-c1 | 579 | 0 | 1,510.1 | — | — |
| golay43 | 309 | 93 | 1,010.0 | — | — |
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
| refined-bmv | 164 | 3 | 473.0 | 727,597 / 9,879 | 7/10 |
| support-enumeration | 19 | 0 | 771.4 | — | — |
| thomson-10 | 39 | 0 | 18.1 | — | — |
| thomson-11 | 38 | 0 | 11.1 | — | — |
| thomson-13 | 39 | 0 | 16.3 | — | — |
| thomson-14 | 38 | 0 | 17.4 | — | — |
| werner-endpoint | 309 | 0 | 341.5 | 67,096 / 624 | 1/1 |

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
| [2026-11-28T17:21:29.145+00:00](method-runs/0e1de9b28b524118aca2c2d3ac299400.json) | thomson-10 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.2 | — |
| [2026-11-28T17:21:27.675+00:00](method-runs/df5a60ac60bc42448af8a978db0b3114.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 0.6 | — |
| [2026-11-28T17:21:26.942+00:00](method-runs/bae9a46efd56496bb8c9b14c3029ebe5.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 0.7 | — |
| [2026-11-28T17:21:26.756+00:00](method-runs/10ccb371190743168f3e7c9231555d31.json) | gagatsos-2026-c1 | search | wigner_search.search | — | completed / bounded_result | 0.2 | — |
| [2026-11-28T17:21:20.961+00:00](method-runs/45019b49d7464b45a3cc2f89736be7c8.json) | gagatsos-2026-c1 | search | coherent_band_search.py | — | completed / search_receipt | 2.6 | — |
| [2026-11-28T17:21:18.065+00:00](method-runs/79243a9e106043d6a385d1ab1f662a18.json) | gagatsos-2026-c1 | search | three_level_search.py | — | completed / search_receipt | 2.9 | — |
| [2026-11-28T17:21:15.823+00:00](method-runs/c87ab7050d2b40b68c0a604677355253.json) | gagatsos-2026-c1 | search | excited_pairs.py | — | completed / no_new_receipt | 2.2 | — |
| [2026-11-28T17:20:50.354+00:00](method-runs/ab96812fa2d549a2a0b2f6b1739d1eac.json) | bernasconi-table2 | search | checks/finite_spins.py | — | completed / no_new_receipt | 1.1 | — |
| [2026-11-28T17:20:49.530+00:00](method-runs/6b27fbfa69744128a724c957fc1b0332.json) | refined-bmv | search | checks/bmv_search.py | — | completed / no_new_receipt | 0.3 | — |
| [2026-11-28T17:20:27.028+00:00](method-runs/736c87d6a36342e9b0b8c2e7e55f5cd7.json) | golay43 | search | checks/golay/advance.py | — | completed / search_receipt | 22.5 | — |
| [2026-11-28T17:20:26.737+00:00](method-runs/d9a779a0f17a4003b80ad2815ebc196a.json) | golay43 | search | checks/golay43.py | — | completed / no_new_receipt | 0.3 | — |
| [2026-11-28T17:20:26.049+00:00](method-runs/3a27189ca1be4c8a9629304908dd3adb.json) | e27-schmidt | search | checks/schmidt7/pair_search.py | — | completed / search_receipt | 0.8 | — |
| [2026-11-28T17:08:44.965+00:00](method-runs/cbd85f692e7e4c0391d0884d8d73f9c4.json) | oqp:A27 | scout | source-screen | gpt-6.2-sol / low | completed / shortlist | 66.6 | 233,142 / 2,077 |
| [2026-11-28T17:08:39.205+00:00](method-runs/14c44e70b3b6491e97e3f2566c897957.json) | thomson-13 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.4 | — |
| [2026-11-28T17:08:36.815+00:00](method-runs/a333270138c94cf0a21b0d5b1f7977ad.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 0.4 | — |
| [2026-11-28T17:08:36.354+00:00](method-runs/28a6e4f5e1e44885b9356c59da0a5fe7.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 0.5 | — |
| [2026-11-28T17:08:36.210+00:00](method-runs/bff8c9d0f251439a9d6bb6f3b98324e8.json) | gagatsos-2026-c1 | search | wigner_search.search | — | completed / bounded_result | 0.2 | — |
| [2026-11-28T17:08:32.716+00:00](method-runs/49fa3a62ed7a4179b6db1f01934a7ba9.json) | gagatsos-2026-c1 | search | coherent_band_search.py | — | completed / search_receipt | 1.5 | — |
| [2026-11-28T17:08:30.184+00:00](method-runs/2ef2d57adf904f73a837b8866ee8b61d.json) | gagatsos-2026-c1 | search | three_level_search.py | — | completed / search_receipt | 2.5 | — |
| [2026-11-28T17:08:28.294+00:00](method-runs/f11eaaf363594e518fc2000bba2a09ff.json) | gagatsos-2026-c1 | search | excited_pairs.py | — | completed / no_new_receipt | 1.8 | — |
| [2026-11-28T17:08:03.346+00:00](method-runs/3c310a438221497380168a3e040f84a0.json) | bernasconi-table2 | search | checks/finite_spins.py | — | completed / no_new_receipt | 1.0 | — |
| [2026-11-28T17:08:02.569+00:00](method-runs/11ffe31d0a5d43308b494e97cc6af14c.json) | refined-bmv | search | checks/bmv_search.py | — | completed / no_new_receipt | 0.8 | — |
| [2026-11-28T17:07:25.491+00:00](method-runs/4fcbc5fc6a214226938ce04dba97d011.json) | golay43 | search | checks/golay/advance.py | — | completed / search_receipt | 37.0 | — |
| [2026-11-28T17:07:24.659+00:00](method-runs/89783a20aa7f49b0aa292bc64337b6e1.json) | golay43 | search | checks/golay43.py | — | completed / no_new_receipt | 0.6 | — |
| [2026-11-28T17:07:22.496+00:00](method-runs/8a4c97c2e5bf4a7083a3dd0f4a184826.json) | e27-schmidt | search | checks/schmidt7/pair_search.py | — | completed / search_receipt | 2.2 | — |
| [2026-11-28T07:49:16.782+00:00](method-runs/8d5c92715ae546c7af6d2fd17553a36b.json) | thomson-11 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.1 | — |
| [2026-11-28T07:49:15.709+00:00](method-runs/e8e22be72703404496779ecf366a290b.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 0.5 | — |
| [2026-11-28T07:49:15.113+00:00](method-runs/82764d3aa5244bc3b035c149476f1bd5.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 0.6 | — |
| [2026-11-28T07:49:14.921+00:00](method-runs/ca6f5150b8b7408dbf5f3247a8198355.json) | gagatsos-2026-c1 | search | wigner_search.search | — | completed / bounded_result | 0.2 | — |
| [2026-11-28T07:49:11.048+00:00](method-runs/f0be1228bac04132906f52958e7555b0.json) | gagatsos-2026-c1 | search | coherent_band_search.py | — | completed / search_receipt | 1.7 | — |
| [2026-11-28T07:49:09.471+00:00](method-runs/1feb30e2eac54854930817b61b0239fe.json) | gagatsos-2026-c1 | search | three_level_search.py | — | completed / search_receipt | 1.6 | — |
| [2026-11-28T07:49:08.569+00:00](method-runs/032df044703145ad9dd05a2f0c9c7788.json) | gagatsos-2026-c1 | search | excited_pairs.py | — | completed / no_new_receipt | 0.9 | — |
| [2026-11-28T07:48:58.486+00:00](method-runs/2ec902302f3b459e9b05d4c3b18c49b5.json) | bernasconi-table2 | search | checks/finite_spins.py | — | completed / no_new_receipt | 0.3 | — |
| [2026-11-28T07:48:58.331+00:00](method-runs/7e6b7c243f3540fd99306b2e48d0243c.json) | refined-bmv | search | checks/bmv_search.py | — | completed / no_new_receipt | 0.2 | — |
| [2026-11-28T07:48:48.502+00:00](method-runs/7f86c079b3924a2890584688af64fe9e.json) | golay43 | search | checks/golay/advance.py | — | completed / search_receipt | 9.8 | — |
| [2026-11-28T07:48:48.329+00:00](method-runs/57c2dea08d784fc481d93f0c964f5e96.json) | golay43 | search | checks/golay43.py | — | completed / no_new_receipt | 0.2 | — |
| [2026-11-28T07:48:47.956+00:00](method-runs/9fa8da9193554360ae473eaf8f208034.json) | e27-schmidt | search | checks/schmidt7/pair_search.py | — | completed / search_receipt | 0.4 | — |
| [2026-11-28T07:36:41.288+00:00](method-runs/22a5464d995e4469982b5e9fda152638.json) | thomson-14 | search | sphere_bounds.experiment | — | completed / bound_checked | 0.1 | — |
| [2026-11-28T07:36:39.071+00:00](method-runs/99c76b4550e845d9a02498a0a4849db8.json) | werner-endpoint | search | complex_search.search-5-copies | — | completed / bounded_result | 1.5 | — |
| [2026-11-28T07:36:37.394+00:00](method-runs/de7acfb39cc54eb8a9b58f1d39131bca.json) | werner-endpoint | search | complex_search.search-4-copies | — | completed / bounded_result | 1.7 | — |

## Search policy experiments

Each Golay policy constructs 24 circuits, split between 12 development seeds and 12 fresh evaluation seeds. Both policies receive the same seeds and the same number of pivot choices. Two signed stabilizer checks validate every circuit. The challenger advances inside this experiment only if it saves at least one gate on average, wins more pairs than it loses, and matches or improves the best gate count on each split. The physical target is at most 43 CNOTs.

| Week | Tree depths compared | Best CNOTs | Next tree depth | Seconds | Model tokens |
|---|---|---:|---:|---:|---:|
| [2026-W48](method-trials/v1-2026-W48.json) | 23 vs 12 | 47 | 23 | 3.22 | 0 |
