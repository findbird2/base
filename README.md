# neural-network-hydroaccustic-signal-classification

This project represents a neural network for classifying hydroaccustic signals.

Hydroaccustic signals are represented by the spectre of the signal

Deeplearning4J used

2026-04-20 16:30:01.023]  Started by user Тарасов Игорь Юрьевич (4111617) - ООО "ГК Иннотех"
[2026-04-20 16:30:01.024]  Running as Тарасов Игорь Юрьевич (4111617) - ООО "ГК Иннотех"
[2026-04-20 16:30:01.161]  Obtained jenkins/pipelines/cd/Deploy/pipeline.Jenkinsfile from git ssh://git@git.sfera.test.vtb.ru:7999/AFS_DEPLOY/dp6.git
[2026-04-20 16:30:01.161]  Resume disabled by user, switching to high-performance, low-durability mode.
[2026-04-20 16:30:01.208]  Loading library global_ppor_start_finish_deployment_lib@master
[2026-04-20 16:30:01.209]  Attempting to resolve master from remote references...
[2026-04-20 16:30:01.210]   > JGit ls-remote # timeout=10
[2026-04-20 16:30:01.491]  Found match: refs/heads/master revision 3330dc4348bdc80cf5f1d1ac053ab60b814dabf3
[2026-04-20 16:30:01.495]  The recommended git tool is: NONE
[2026-04-20 16:30:01.496]  using credential common_sfera_i_ppsc
[2026-04-20 16:30:01.501]  Fetching changes from the remote Git repository
[2026-04-20 16:30:01.502]  Fetching without tags
[2026-04-20 16:30:01.502]   > JGit fetch # timeout=10
[2026-04-20 16:30:01.870]  Checking out Revision 3330dc4348bdc80cf5f1d1ac053ab60b814dabf3 (master)
[2026-04-20 16:30:01.879]  Commit message: "Add (start/finish)Deployment_lin"
[2026-04-20 16:30:01.896]  [SferaSCMListener] Remote repository: ssh://git@git.sfera.test.vtb.ru:7999/common_code/global_ppor_start_finish_deployment_lib.git
[2026-04-20 16:30:02.246]  [Pipeline] Start of Pipeline
[2026-04-20 16:30:02.363]  [Pipeline] node
[2026-04-20 16:30:03.413]  Running on p0afsc-agc008lk in /app/jenkins-agent/workspace/AFS/DP7-CD/ift/▶️ Деплой
[2026-04-20 16:30:03.433]  [Pipeline] {
[2026-04-20 16:30:03.470]  [Pipeline] dir
[2026-04-20 16:30:03.470]  Running in /app/jenkins-agent/workspace/AFS/DP7-CD/ift/▶️ Деплой/automation
[2026-04-20 16:30:03.487]  [Pipeline] {
[2026-04-20 16:30:03.534]  [Pipeline] checkout
[2026-04-20 16:30:03.559]  Selected Git installation does not exist. Using Default
[2026-04-20 16:30:03.559]  Selected Git installation does not exist. Using Default
[2026-04-20 16:30:03.560]  The recommended git tool is: jgit
[2026-04-20 16:30:03.732]  using credential git_credentials
[2026-04-20 16:30:03.788]  Cloning the remote Git repository
[2026-04-20 16:30:03.795]   > JGit fetch # timeout=10
[2026-04-20 16:30:04.039]  remote: Enumerating objects
[2026-04-20 16:30:04.039]  remote: Counting objects
[2026-04-20 16:30:04.040]  remote: Compressing objects
[2026-04-20 16:30:04.042]  Receiving objects
[2026-04-20 16:30:05.607]  Avoid second fetch
[2026-04-20 16:30:05.277]  Resolving deltas
[2026-04-20 16:30:05.662]  Checking out Revision 480f64d36ae09831ae664ae943af59b9f14ff3bf (origin/dreampipe)
[2026-04-20 16:30:07.244]  Commit message: "From code-synchronizer. Date: 25-02-2026-14:41"
[2026-04-20 16:30:07.363]  [SferaSCMListener] Remote repository: ssh://git@git.sfera.test.vtb.ru:7999/AFS_DEPLOY/dp6.git
[2026-04-20 16:30:07.383]  [Pipeline] }
[2026-04-20 16:30:07.412]  [Pipeline] // dir
[2026-04-20 16:30:07.452]  [Pipeline] load
[2026-04-20 16:30:07.683]  [Pipeline] { (automation/jenkins/lib/workspaceProcessing.groovy)
[2026-04-20 16:30:07.720]  [Pipeline] load
[2026-04-20 16:30:07.783]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:07.821]  [Pipeline] }
[2026-04-20 16:30:07.853]  [Pipeline] // load
[2026-04-20 16:30:07.890]  [Pipeline] load
[2026-04-20 16:30:07.952]  [Pipeline] { (automation/jenkins/lib/git.groovy)
[2026-04-20 16:30:07.991]  [Pipeline] load
[2026-04-20 16:30:08.057]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:08.092]  [Pipeline] }
[2026-04-20 16:30:08.121]  [Pipeline] // load
[2026-04-20 16:30:08.159]  [Pipeline] }
[2026-04-20 16:30:08.186]  [Pipeline] // load
[2026-04-20 16:30:08.226]  [Pipeline] }
[2026-04-20 16:30:08.254]  [Pipeline] // load
[2026-04-20 16:30:08.296]  [Pipeline] load
[2026-04-20 16:30:08.407]  [Pipeline] { (automation/jenkins/lib/params.groovy)
[2026-04-20 16:30:08.447]  [Pipeline] load
[2026-04-20 16:30:08.503]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:08.542]  [Pipeline] }
[2026-04-20 16:30:08.571]  [Pipeline] // load
[2026-04-20 16:30:08.609]  [Pipeline] }
[2026-04-20 16:30:08.637]  [Pipeline] // load
[2026-04-20 16:30:08.675]  [Pipeline] load
[2026-04-20 16:30:08.820]  [Pipeline] { (automation/jenkins/lib/dpcli.groovy)
[2026-04-20 16:30:08.870]  [Pipeline] load
[2026-04-20 16:30:08.930]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:08.973]  [Pipeline] }
[2026-04-20 16:30:09.020]  [Pipeline] // load
[2026-04-20 16:30:09.069]  [Pipeline] }
[2026-04-20 16:30:09.101]  [Pipeline] // load
[2026-04-20 16:30:09.152]  [Pipeline] load
[2026-04-20 16:30:09.220]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:09.270]  [Pipeline] }
[2026-04-20 16:30:09.304]  [Pipeline] // load
[2026-04-20 16:30:09.348]  [Pipeline] load
[2026-04-20 16:30:09.617]  [Pipeline] { (automation/jenkins/lib/envs.groovy)
[2026-04-20 16:30:09.660]  [Pipeline] }
[2026-04-20 16:30:09.692]  [Pipeline] // load
[2026-04-20 16:30:09.745]  [Pipeline] load
[2026-04-20 16:30:09.862]  [Pipeline] { (automation/jenkins/lib/docker.groovy)
[2026-04-20 16:30:09.908]  [Pipeline] load
[2026-04-20 16:30:09.971]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:10.015]  [Pipeline] }
[2026-04-20 16:30:10.050]  [Pipeline] // load
[2026-04-20 16:30:10.101]  [Pipeline] }
[2026-04-20 16:30:10.136]  [Pipeline] // load
[2026-04-20 16:30:10.182]  [Pipeline] load
[2026-04-20 16:30:10.274]  [Pipeline] { (automation/jenkins/lib/deploy.groovy)
[2026-04-20 16:30:10.333]  [Pipeline] load
[2026-04-20 16:30:10.411]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:10.467]  [Pipeline] }
[2026-04-20 16:30:10.501]  [Pipeline] // load
[2026-04-20 16:30:10.549]  [Pipeline] load
[2026-04-20 16:30:10.615]  [Pipeline] { (automation/jenkins/lib/git.groovy)
[2026-04-20 16:30:10.665]  [Pipeline] load
[2026-04-20 16:30:10.732]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:10.789]  [Pipeline] }
[2026-04-20 16:30:10.829]  [Pipeline] // load
[2026-04-20 16:30:10.881]  [Pipeline] }
[2026-04-20 16:30:10.918]  [Pipeline] // load
[2026-04-20 16:30:10.968]  [Pipeline] }
[2026-04-20 16:30:11.007]  [Pipeline] // load
[2026-04-20 16:30:11.057]  [Pipeline] load
[2026-04-20 16:30:11.160]  [Pipeline] { (automation/jenkins/lib/stages.groovy)
[2026-04-20 16:30:11.208]  [Pipeline] load
[2026-04-20 16:30:11.273]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:11.325]  [Pipeline] }
[2026-04-20 16:30:11.360]  [Pipeline] // load
[2026-04-20 16:30:11.405]  [Pipeline] }
[2026-04-20 16:30:11.440]  [Pipeline] // load
[2026-04-20 16:30:11.498]  [Pipeline] load
[2026-04-20 16:30:11.724]  [Pipeline] { (automation/jenkins/lib/bridge.groovy)
[2026-04-20 16:30:11.777]  [Pipeline] load
[2026-04-20 16:30:11.846]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:11.896]  [Pipeline] }
[2026-04-20 16:30:11.935]  [Pipeline] // load
[2026-04-20 16:30:11.985]  [Pipeline] }
[2026-04-20 16:30:12.040]  [Pipeline] // load
[2026-04-20 16:30:12.120]  [Pipeline] load
[2026-04-20 16:30:12.328]  [Pipeline] { (automation/jenkins/lib/context.groovy)
[2026-04-20 16:30:12.432]  [Pipeline] load
[2026-04-20 16:30:12.520]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:12.579]  [Pipeline] }
[2026-04-20 16:30:12.634]  [Pipeline] // load
[2026-04-20 16:30:12.835]  [Pipeline] load
[2026-04-20 16:30:12.919]  [Pipeline] { (automation/jenkins/lib/git.groovy)
[2026-04-20 16:30:13.016]  [Pipeline] load
[2026-04-20 16:30:13.122]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:13.186]  [Pipeline] }
[2026-04-20 16:30:13.237]  [Pipeline] // load
[2026-04-20 16:30:13.300]  [Pipeline] }
[2026-04-20 16:30:13.342]  [Pipeline] // load
[2026-04-20 16:30:13.595]  [Pipeline] }
[2026-04-20 16:30:13.661]  [Pipeline] // load
[2026-04-20 16:30:13.763]  [Pipeline] load
[2026-04-20 16:30:14.146]  [Pipeline] { (automation/jenkins/lib/checksum.groovy)
[2026-04-20 16:30:14.215]  [Pipeline] load
[2026-04-20 16:30:14.325]  [Pipeline] { (automation/jenkins/lib/logger.groovy)
[2026-04-20 16:30:14.429]  [Pipeline] }
[2026-04-20 16:30:14.541]  [Pipeline] // load
[2026-04-20 16:30:14.665]  [Pipeline] }
[2026-04-20 16:30:14.766]  [Pipeline] // load
[2026-04-20 16:30:14.989]  [Pipeline] dir
[2026-04-20 16:30:14.989]  Running in /app/jenkins-agent/workspace/AFS/DP7-CD/ift/▶️ Деплой/automation
[2026-04-20 16:30:15.059]  [Pipeline] {
[2026-04-20 16:30:15.152]  [Pipeline] fileExists
[2026-04-20 16:30:15.252]  [Pipeline] echo
[2026-04-20 16:30:15.265]  [1m[94m[INFO] Проверка целостности файлов...[0m
[2026-04-20 16:30:15.365]  [Pipeline] sh
[2026-04-20 16:30:16.065]  + set -euo pipefail
[2026-04-20 16:30:16.065]  + find jenkins/lib jenkins/pipelines jenkins/seed.Jenkinsfile config/schema cli/__dppackages__ cli/pipeline_toolkit cli/src cli/dpcli.py -type f -print0
[2026-04-20 16:30:16.065]  + xargs -0 sha256sum
[2026-04-20 16:30:16.065]  + sort -z
[2026-04-20 16:30:16.345]  [Pipeline] writeFile
[2026-04-20 16:30:16.534]  [Pipeline] sh
[2026-04-20 16:30:17.178]  + diff -u .checksums.sha256 .checksums.sha256.current
[2026-04-20 16:30:17.178]  + true
[2026-04-20 16:30:17.475]  [Pipeline] sh
[2026-04-20 16:30:18.268]  + rm -f .checksums.sha256.current
[2026-04-20 16:30:18.542]  [Pipeline] echo
[2026-04-20 16:30:18.552]  [1m[31m[WARN] !!! CHECKSUM MISMATCH !!![0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] Обнаружены различия между ожидаемыми и текущими чексуммами файлов:[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] [0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] --- .checksums.sha256	2026-04-20 16:30:06.964943751 +0300[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +++ .checksums.sha256.current	2026-04-20 16:30:16.361032605 +0300[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] @@ -773,7 +773,7 @@[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  f614ffd30a1ced42186cf121b6b896b1d446977274e03e93111e7248761e8af8  cli/src/workers/cli/context/cd/steps/post_deploy/step_set_status_delayed_deploy.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  2d5c56684c53850f10f38b7d64ddefbf0cd049e583d4520c11d046c593942cff  cli/src/workers/cli/context/cd/steps/rollback/__init__.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  b70b1f0033e705cb544af491ee3e218d3141454648f9c9c12e028d1c2648a19b  cli/src/workers/cli/context/cd/steps/rollback/step_rollback_chart.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] -e41220c7d8f36005e3bc2cd4fc4427d47e560bc37458ea0cbd04c02587891766  cli/src/workers/cli/context/cd/steps/rollback/step_rollback_db.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +ebed73d5bbad2b6cd8f58aea7a13bc318142b1593459513e41c227b3cf669951  cli/src/workers/cli/context/cd/steps/rollback/step_rollback_db.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  8e0811bb6446bea6d236751a2b555876f1e8e886fb0baade8df67e39f8aaeeb1  cli/src/workers/cli/context/cd/tasks/build/download_supply.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855  cli/src/workers/cli/context/cd/tasks/build/__init__.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  fde82619be89232e0b083905d8ae4af5a5c2600830be6b942ec29a6c98be4da8  cli/src/workers/cli/context/cd/tasks/canary/changeweight.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] @@ -880,7 +880,7 @@[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  6ea934936cbfb98ad47fa570940b5bbbda465e9925f542d9103dd5611f0fd64c  cli/src/workers/cli/context/ci/steps/upload/step_upload_supply.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  b1cb2e704d338c81bd21a1f3b833209bb73c09d4907f73a907aa3a73d852a432  cli/src/workers/cli/context/ci/steps/upload/step_upload_to_distr_supply.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  8379ec6374c3537b237b24ac9b55e860e8512f477d8204997ad6adab9164cd2b  cli/src/workers/cli/context/ci/steps/upload/step_upload_to_s3.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] -09a64d9027280260ac819521566ffd823fbc3c6fa178e4ca1bd4ea1873b0d809  cli/src/workers/cli/context/ci/steps/upload/step_upload_to_trigger_repo.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +911938bd07d21d32e90ffa340747b287db0c10a8a352e61a5e9727667c9e67a8  cli/src/workers/cli/context/ci/steps/upload/step_upload_to_trigger_repo.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  302a49e1f7919b3d361abf483430de2d791eb400087b00c6e0671c4b904dba9d  cli/src/workers/cli/context/ci/tasks/execute/build_docker.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  b54d9c41ba9440cf9fa2eed3a1c8b489838c66cec17ad5f8274aa3883d33f714  cli/src/workers/cli/context/ci/tasks/execute/build_project.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  5c5f37b3a30b6f8847a6e9332d5b0ea6831f1fdd81bf642cd412463aaf73df07  cli/src/workers/cli/context/ci/tasks/execute/cleaning_old_delivery_desc_files.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] @@ -915,7 +915,7 @@[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  ba4255083ae4b9e01834b1bb8b1820c81e348d8382d37cecf6e6190f94ca3dc1  config/schema/modules/dast.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  4e267bb01a28319181c5013cbeb3079331683d5b89afc6cb36ce3a952303ecb7  config/schema/modules/dbMigration.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  0020dd9b48f09bbd35a6901ee203c01f3f173108ffd580fb35aa3b18251a0bd9  config/schema/modules/deliveryHelper.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] -2916193dab7aff42fa91c593e000f24ddb69e6210d2fd9b46448c1661cdc4451  config/schema/modules/delivery.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +cefc1a412aaed1394f6061ebf5995479ab1353ce747c869a4a5ed92ba0f256a0  config/schema/modules/delivery.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  19a8e655f4e5d522619df50545653759cf42868f1fdf7e6c9cb65a16546d12e7  config/schema/modules/deployResult.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  279e798eefc777f6742a7898a1455a09b1713177004a0929cf30a0536b09a8c3  config/schema/modules/docker.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  c0f47a8e826faaef710a4d82c06e15d88c3b24dee98550c388e11ba31a57289b  config/schema/modules/gradle.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] @@ -927,9 +927,9 @@[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  75d0f09400b378473f567d624ded5e34de5df6b74146ba65ec8f22c90cc97d04  config/schema/modules/multiSupplyDeploy.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  2fc345bab1b643a591d54dcd970dcd8937fadb89ccd5c16d5b58e4b3f60a04b0  config/schema/modules/netChecker.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  aab2ab87811dfa4cc6ec1dfd244ca05635c36fcee27b7f1acf5b4a559c4b5df0  config/schema/modules/nodejs.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] -aedfe652ecc3f73ec46742ae1464e80a41be3fd4a14b61618f0a57cc656d3c83  config/schema/modules/sca.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +51a7d91f0e1f5d37ee15a55cba8cd04a7c853930beb4e2c43688b705e40e0f72  config/schema/modules/sca.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  54bd343691c2a610f57e546c65157896ed759e618e47219ff1e9e890b68b4be5  config/schema/modules/sharedImages.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] -b0762ae57aad6bd303a9c0ddb018b1245104b011f1368f92c34779b1af1ea079  config/schema/modules/solar.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +b670f769038eb1d6b6f9d7dcd455a869f214d1a35dd57fde89ec41735d1eb247  config/schema/modules/solar.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  67227c3c1bebb828d58ae527026980b430e4408e7486e2ed9ed32cabe915526d  config/schema/modules/sonar.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  44918d113baec28dff23eff8bc00fb34f92d4c5bd0f47f77a7f660e5702b0012  config/schema/modules/standalone.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  4f62f45d8b91f83ee24dc0218af891e150b8383acfef92404abbffca908f0f09  config/schema/modules/startFinishDeployment.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] @@ -962,7 +962,7 @@[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  64f541e2e98677678948a1733f79264f1948859f1e70a177af57ae054184890a  jenkins/pipelines/cd/Deploy/handlers.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  8d037aefa0c4151268cf9c3f2c8ae2407b46f421eab936f773d92e8b05f39434  jenkins/pipelines/cd/DeployMicrofronts/pipeline.Jenkinsfile[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  69684a1112ee5b98adb8126821a5ff3f94f55cf5f5b8988dcdf7bae444ea24ce  jenkins/pipelines/cd/DeployMicrofronts/ui.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] -1a951f64de72fa05e6992633421eb53e4c61ccbe941085b2513dd51aeaf9e93d  jenkins/pipelines/cd/Deploy/pipeline.Jenkinsfile[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] +5bfcdf32fe9a540f9934f33123fffa2a0c7f0df535c7d7ad5266dc4cace7e564  jenkins/pipelines/cd/Deploy/pipeline.Jenkinsfile[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  a8d7ed05e30285f199650779c6cdfae0c6234f135dd9e074572107b2ab392436  jenkins/pipelines/cd/DeployStandalone/pipeline.Jenkinsfile[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  00451a085aee8c0ccebb968deda266b24008d1d43b466eebd1bb5463369c45a0  jenkins/pipelines/cd/DeployStandalone/ui.yaml[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN]  cd4312d829c73415a9d20ec2235e386393c1cafdce05d255e386965209256d8e  jenkins/pipelines/cd/Deploy/test_handlers.py[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] [0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] Это может означать:[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] - Файлы были изменены после выпуска релиза[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] - Используется неактуальная версия кода[0m
[2026-04-20 16:30:18.552]  [1m[31m[WARN] - Возможна компрометация файлов[0m
[2026-04-20 16:30:18.601]  [Pipeline] }
[2026-04-20 16:30:18.670]  [Pipeline] // dir
[2026-04-20 16:30:18.740]  [Pipeline] stash
[2026-04-20 16:30:23.691]  Stashed 4134 file(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/stashes/automationDir.tgz
[2026-04-20 16:30:23.918]  [Pipeline] echo
[2026-04-20 16:30:23.933]  [1m[94m[INFO] В данной сборке используется фильтр агентов: p0afsc-agc005lk,p0afsc-agc008lk,p0afsc-agc009lk,p0afsc-agc010lk,p0ppor-apc196lk,p0ppor-apc197lk,p0ppor-apc198lk,p0ppor-apc199lk,p0ppor-apc200lk,p0ppor-apc201lk,p0ppor-apc202lk,p0ppor-apc203lk,p0ppor-apc204lk,p0ppor-apc205lk,p0ppor-apc206lk,p0ppor-apc207lk,p0ppor-apc208lk,p0ppor-apc209lk,p0ppor-apc210lk,p0ppor-apc211lk,p0ppor-apc212lk,p0ppor-apc213lk,p0ppor-apc214lk,p0ppor-apc215lk[0m
[2026-04-20 16:30:24.038]  [Pipeline] echo
[2026-04-20 16:30:24.055]  [1m[94m[INFO] [NODE BLOCK] Выбран агент: p0afsc-agc008lk[0m
[2026-04-20 16:30:24.159]  [Pipeline] }
[2026-04-20 16:30:24.250]  [Pipeline] // node
[2026-04-20 16:30:25.126]  [Pipeline] node
[2026-04-20 16:30:30.453]  Running on p0afsc-agc008lk in /app/jenkins-agent/workspace/AFS/DP7-CD/ift/▶️ Деплой
[2026-04-20 16:30:30.622]  [Pipeline] {
[2026-04-20 16:30:31.049]  [Pipeline] timeout
[2026-04-20 16:30:31.050]  Timeout set to expire after 1 hr 0 min without activity
[2026-04-20 16:30:31.163]  [Pipeline] {
[2026-04-20 16:30:31.459]  [Pipeline] stage
[2026-04-20 16:30:31.619]  [Pipeline] { (Загрузка контекста)
[2026-04-20 16:30:31.997]  [Pipeline] script
[2026-04-20 16:30:32.135]  [Pipeline] {
[2026-04-20 16:30:32.346]  [Pipeline] echo
[2026-04-20 16:30:32.376]  [1m[94m[INFO] [PIPELINE BLOCK] Выбран агент: p0afsc-agc008lk[0m
[2026-04-20 16:30:32.523]  [Pipeline] fileExists
[2026-04-20 16:30:32.873]  [Pipeline] echo
[2026-04-20 16:30:32.928]  [1m[94m[INFO] Подготовка рабочей директории[0m
[2026-04-20 16:30:33.838]  [Pipeline] sh
[2026-04-20 16:30:34.577]  + [[ false == \t\r\u\e ]]
[2026-04-20 16:30:34.577]  + set +x
[2026-04-20 16:30:34.934]  [Pipeline] echo
[2026-04-20 16:30:34.954]  [1m[94m[INFO] Установлена рабочая директория: /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf[0m
[2026-04-20 16:30:35.231]  [Pipeline] configFileProvider
[2026-04-20 16:30:35.235]  provisioning config files...
[2026-04-20 16:30:35.381]  copy managed file [DP_CONTEXT_PARAMS] to file:/app/jenkins-agent/workspace/AFS/DP7-CD/ift/▶️%20Деплой@tmp/config5474957622470911628tmp
[2026-04-20 16:30:35.678]  [Pipeline] {
[2026-04-20 16:30:35.793]  [Pipeline] readProperties
[2026-04-20 16:30:35.990]  [Pipeline] echo
[2026-04-20 16:30:36.158]  [1m[94m[INFO] Найдены новые контекстные параметры: [PIPELINE_INCLUDE_CI:false, PIPELINE_ALIAS:cdl, PIPELINE_INCLUDE_UTILS:true, PIPELINE_INCLUDE_CD:true][0m
[2026-04-20 16:30:36.247]  [Pipeline] }
[2026-04-20 16:30:36.265]  Deleting 1 temporary files
[2026-04-20 16:30:36.363]  [Pipeline] // configFileProvider
[2026-04-20 16:30:36.533]  [Pipeline] }
[2026-04-20 16:30:36.659]  [Pipeline] // script
[2026-04-20 16:30:36.784]  [Pipeline] }
[2026-04-20 16:30:36.930]  [Pipeline] // stage
[2026-04-20 16:30:36.931]  stage: 'Загрузка контекста', duration: 00:00:04.958
[2026-04-20 16:30:37.053]  [Pipeline] stage
[2026-04-20 16:30:37.155]  [Pipeline] { (🔧 Подготовка окружения)
[2026-04-20 16:30:37.352]  [Pipeline] dir
[2026-04-20 16:30:37.352]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf
[2026-04-20 16:30:37.436]  [Pipeline] {
[2026-04-20 16:30:37.553]  [Pipeline] script
[2026-04-20 16:30:37.641]  [Pipeline] {
[2026-04-20 16:30:37.733]  [Pipeline] echo
[2026-04-20 16:30:37.749]  [1m[94m[INFO] <<<<<<<<< 🔧 ПОДГОТОВКА ОКРУЖЕНИЯ - СТАРТ >>>>>>>>>>[0m
[2026-04-20 16:30:37.895]  [Pipeline] tool
[2026-04-20 16:30:38.067]  [Pipeline] tool
[2026-04-20 16:30:38.231]  [Pipeline] tool
[2026-04-20 16:30:38.434]  [Pipeline] tool
[2026-04-20 16:30:38.615]  [Pipeline] dir
[2026-04-20 16:30:38.615]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/automation/cli
[2026-04-20 16:30:38.718]  [Pipeline] {
[2026-04-20 16:30:39.184]  [Pipeline] echo
[2026-04-20 16:30:39.238]  [DEBUG] [bridge] Выполняем команду (json):
[2026-04-20 16:30:39.239]  [DEBUG] <json-payload> | '/app/jenkins-agent/tools/com.cloudbees.jenkins.plugins.customtools.CustomTool/python-3.11.6-linux-x64/bin/python3' -m 'pipeline_toolkit' 'config_ui' '--mode' 'cd' '--pipeline-alias' 'cdl' '--pipeline-stand' 'ift'
[2026-04-20 16:30:39.373]  [Pipeline] sh
[2026-04-20 16:30:40.036]  + set -eo pipefail
[2026-04-20 16:30:40.036]  + cat
[2026-04-20 16:30:40.036]  + /app/jenkins-agent/tools/com.cloudbees.jenkins.plugins.customtools.CustomTool/python-3.11.6-linux-x64/bin/python3 -m pipeline_toolkit config_ui --mode cd --pipeline-alias cdl --pipeline-stand ift
[2026-04-20 16:30:42.263]  [Pipeline] echo
[2026-04-20 16:30:42.276]  [DEBUG] [bridge] stdout:
[2026-04-20 16:30:42.276]  [DEBUG] {
[2026-04-20 16:30:42.276]  [DEBUG]   "payload": {
[2026-04-20 16:30:42.276]  [DEBUG]     "alias": "cdl",
[2026-04-20 16:30:42.276]  [DEBUG]     "config": {
[2026-04-20 16:30:42.276]  [DEBUG]       "additionalParameters": {
[2026-04-20 16:30:42.276]  [DEBUG]         "agentSelect": [
[2026-04-20 16:30:42.276]  [DEBUG]           "p0afsc-agc005lk",
[2026-04-20 16:30:42.276]  [DEBUG]           "p0afsc-agc008lk",
[2026-04-20 16:30:42.276]  [DEBUG]           "p0afsc-agc009lk",
[2026-04-20 16:30:42.276]  [DEBUG]           "p0afsc-agc010lk",
[2026-04-20 16:30:42.276]  [DEBUG]           "p0ppor-apc196lk",
[2026-04-20 16:30:42.276]  [DEBUG]           "p0ppor-apc197lk",
[2026-04-20 16:30:42.276]  [DEBUG]           "p0ppo...
[2026-04-20 16:30:42.459]  [Pipeline] }
[2026-04-20 16:30:42.535]  [Pipeline] // dir
[2026-04-20 16:30:42.633]  [Pipeline] echo
[2026-04-20 16:30:42.651]  [DEBUG] Запись yaml файла: automation/config/_dp-merged.yaml
[2026-04-20 16:30:42.729]  [Pipeline] sh
[2026-04-20 16:30:43.429]  + rm -f automation/config/_dp-merged.yaml
[2026-04-20 16:30:43.697]  [Pipeline] writeYaml
[2026-04-20 16:30:43.986]  [Pipeline] archiveArtifacts
[2026-04-20 16:30:44.039]  Archiving artifacts
[2026-04-20 16:30:44.180]  The file automation/config/_dp-merged.yaml has been uploaded successfully.
[2026-04-20 16:30:44.295]  Uploaded 1 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:30:44.380]  [Pipeline] stash
[2026-04-20 16:30:48.487]  Stashed 4539 file(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/stashes/automationDir.tgz
[2026-04-20 16:30:48.574]  [Pipeline] echo
[2026-04-20 16:30:48.590]  [DEBUG] Выбранная ветка для репозитория с контурозависимыми параметрами UI: delivery/DLVR-260420145359/dreampipe-ift.
[2026-04-20 16:30:48.688]  [Pipeline] echo
[2026-04-20 16:30:48.708]  [1m[94m[INFO] Скачиваем репозиторий контурозависимых параметров[0m
[2026-04-20 16:30:48.805]  [Pipeline] dir
[2026-04-20 16:30:48.806]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo
[2026-04-20 16:30:48.879]  [Pipeline] {
[2026-04-20 16:30:48.960]  [Pipeline] checkout
[2026-04-20 16:30:49.025]  The recommended git tool is: NONE
[2026-04-20 16:30:49.173]  using credential cdl_si_afs_ssh
[2026-04-20 16:30:49.228]  Cloning the remote Git repository
[2026-04-20 16:30:49.234]   > JGit fetch # timeout=10
[2026-04-20 16:30:49.655]  remote: Enumerating objects
[2026-04-20 16:30:49.657]  remote: Counting objects
[2026-04-20 16:30:49.693]  remote: Compressing objects
[2026-04-20 16:30:49.720]  Receiving objects
[2026-04-20 16:30:52.147]  Resolving deltas
[2026-04-20 16:30:52.392]  Avoid second fetch
[2026-04-20 16:30:52.512]  Checking out Revision af4ccc110a927a52fda25853c5962da0f9969a3e (refs/remotes/origin/delivery/DLVR-260420145359/dreampipe-ift)
[2026-04-20 16:30:52.748]  Commit message: "From code-synchronizer. Date: 20-04-2026-14:24"
[2026-04-20 16:30:52.748]  First time build. Skipping changelog.
[2026-04-20 16:30:52.767]  [SferaSCMListener] Remote repository: ssh://git@git.sfera.test.vtb.ru:7999/afs_deploy/dp6-inventory.git
[2026-04-20 16:30:52.855]  [Pipeline] sshagent
[2026-04-20 16:30:52.863]  [ssh-agent] Using credentials cdl_si_AFS@region.vtb.ru
[2026-04-20 16:30:52.863]  [ssh-agent] Looking for ssh-agent implementation...
[2026-04-20 16:30:53.072]  [ssh-agent]   Exec ssh-agent (binary ssh-agent on a remote machine)
[2026-04-20 16:30:53.075]  $ ssh-agent
[2026-04-20 16:30:53.344]  SSH_AUTH_SOCK=/tmp/ssh-r3ICs0Zi3Xx8/agent.520110
[2026-04-20 16:30:53.344]  SSH_AGENT_PID=520112
[2026-04-20 16:30:53.448]  Running ssh-add (command line suppressed)
[2026-04-20 16:30:53.455]  Identity added: /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo@tmp/private_key_1856319410617727868.key (cdl_si_AFS@region.vtb.ru)
[2026-04-20 16:30:53.736]  [ssh-agent] Started.
[2026-04-20 16:30:53.800]  [Pipeline] {
[2026-04-20 16:30:53.883]  [Pipeline] sh
[2026-04-20 16:30:54.520]  + git submodule update --init --recursive
[2026-04-20 16:30:54.769]  [Pipeline] }
[2026-04-20 16:30:54.772]  $ ssh-agent -k
[2026-04-20 16:30:54.776]  unset SSH_AUTH_SOCK;
[2026-04-20 16:30:54.776]  unset SSH_AGENT_PID;
[2026-04-20 16:30:54.776]  echo Agent pid 520112 killed;
[2026-04-20 16:30:55.049]  [ssh-agent] Stopped.
[2026-04-20 16:30:55.117]  [Pipeline] // sshagent
[2026-04-20 16:30:55.208]  [Pipeline] echo
[2026-04-20 16:30:55.228]  [DEBUG] Репозиторий ssh://git@git.sfera.test.vtb.ru:7999/afs_deploy/dp6-inventory.git успешно клонирован, Ветка: delivery/DLVR-260420145359/dreampipe-ift
[2026-04-20 16:30:55.304]  [Pipeline] }
[2026-04-20 16:30:55.376]  [Pipeline] // dir
[2026-04-20 16:30:55.462]  [Pipeline] echo
[2026-04-20 16:30:55.478]  [1m[94m[INFO] Скачиваем репозиторий c метачартами[0m
[2026-04-20 16:30:55.573]  [Pipeline] dir
[2026-04-20 16:30:55.597]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo
[2026-04-20 16:30:55.675]  [Pipeline] {
[2026-04-20 16:30:55.776]  [Pipeline] checkout
[2026-04-20 16:30:55.803]  The recommended git tool is: NONE
[2026-04-20 16:30:55.920]  using credential cdl_si_afs_ssh
[2026-04-20 16:30:55.968]  Cloning the remote Git repository
[2026-04-20 16:30:55.974]   > JGit fetch # timeout=10
[2026-04-20 16:30:56.157]  remote: Enumerating objects
[2026-04-20 16:30:56.157]  remote: Counting objects
[2026-04-20 16:30:56.157]  remote: Compressing objects
[2026-04-20 16:30:56.159]  Receiving objects
[2026-04-20 16:30:57.320]  Avoid second fetch
[2026-04-20 16:30:57.373]  Checking out Revision 480f64d36ae09831ae664ae943af59b9f14ff3bf (origin/dreampipe)
[2026-04-20 16:30:57.010]  Resolving deltas
[2026-04-20 16:30:58.718]  Commit message: "From code-synchronizer. Date: 25-02-2026-14:41"
[2026-04-20 16:30:58.931]  [SferaSCMListener] Remote repository: ssh://git@git.sfera.test.vtb.ru:7999/afs_deploy/dp6.git
[2026-04-20 16:30:59.025]  [Pipeline] sshagent
[2026-04-20 16:30:59.032]  [ssh-agent] Using credentials cdl_si_AFS@region.vtb.ru
[2026-04-20 16:30:59.032]  [ssh-agent] Looking for ssh-agent implementation...
[2026-04-20 16:30:59.189]  [ssh-agent]   Exec ssh-agent (binary ssh-agent on a remote machine)
[2026-04-20 16:30:59.192]  $ ssh-agent
[2026-04-20 16:30:59.491]  SSH_AUTH_SOCK=/tmp/ssh-wEZXFF8t4c71/agent.520160
[2026-04-20 16:30:59.491]  SSH_AGENT_PID=520162
[2026-04-20 16:30:59.588]  Running ssh-add (command line suppressed)
[2026-04-20 16:30:59.595]  Identity added: /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo@tmp/private_key_17590389663206113214.key (cdl_si_AFS@region.vtb.ru)
[2026-04-20 16:30:59.892]  [ssh-agent] Started.
[2026-04-20 16:30:59.964]  [Pipeline] {
[2026-04-20 16:31:00.058]  [Pipeline] sh
[2026-04-20 16:31:00.724]  + git submodule update --init --recursive
[2026-04-20 16:31:00.959]  [Pipeline] }
[2026-04-20 16:31:00.962]  $ ssh-agent -k
[2026-04-20 16:31:00.966]  unset SSH_AUTH_SOCK;
[2026-04-20 16:31:00.966]  unset SSH_AGENT_PID;
[2026-04-20 16:31:00.966]  echo Agent pid 520162 killed;
[2026-04-20 16:31:01.238]  [ssh-agent] Stopped.
[2026-04-20 16:31:01.309]  [Pipeline] // sshagent
[2026-04-20 16:31:01.415]  [Pipeline] echo
[2026-04-20 16:31:01.435]  [DEBUG] Репозиторий ssh://git@git.sfera.test.vtb.ru:7999/afs_deploy/dp6.git успешно клонирован, Ветка: dreampipe
[2026-04-20 16:31:01.517]  [Pipeline] }
[2026-04-20 16:31:01.589]  [Pipeline] // dir
[2026-04-20 16:31:01.686]  [Pipeline] echo
[2026-04-20 16:31:01.705]  [1m[94m[INFO] Репозиторий dpcli не указан. Используем коробочный cli.[0m
[2026-04-20 16:31:01.779]  [Pipeline] sh
[2026-04-20 16:31:02.412]  + mv /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/automation/cli /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/cli
[2026-04-20 16:31:02.669]  [Pipeline] echo
[2026-04-20 16:31:02.688]  [1m[94m[INFO] Конфигурационный файл: [dp-cdl.yaml], Контур: [cdl], Стенд: [ift], Агент: [p0afsc-agc008lk][0m
[2026-04-20 16:31:02.776]  [Pipeline] echo
[2026-04-20 16:31:02.797]  [1m[94m[INFO] <<<<<<<<< 🔧 ПОДГОТОВКА ОКРУЖЕНИЯ - ЗАВЕРШЕНО >>>>>>>>>>[0m
[2026-04-20 16:31:02.884]  [Pipeline] }
[2026-04-20 16:31:02.954]  [Pipeline] // script
[2026-04-20 16:31:03.053]  [Pipeline] }
[2026-04-20 16:31:03.218]  [Pipeline] // dir
[2026-04-20 16:31:03.242]  Post stage
[2026-04-20 16:31:03.362]  [Pipeline] dir
[2026-04-20 16:31:03.362]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf
[2026-04-20 16:31:03.447]  [Pipeline] {
[2026-04-20 16:31:03.569]  [Pipeline] archiveArtifacts
[2026-04-20 16:31:03.653]  Archiving artifacts
[2026-04-20 16:31:03.809]  The file automation/config/_dp-merged.yaml has been uploaded successfully.
[2026-04-20 16:31:03.958]  Uploaded 1 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:31:04.062]  [Pipeline] }
[2026-04-20 16:31:04.206]  [Pipeline] // dir
[2026-04-20 16:31:04.417]  [Pipeline] }
[2026-04-20 16:31:04.537]  [Pipeline] // stage
[2026-04-20 16:31:04.539]  stage: '🔧 Подготовка окружения', duration: 00:00:27.171
[2026-04-20 16:31:04.691]  [Pipeline] stage
[2026-04-20 16:31:04.867]  [Pipeline] { (🚀 Деплой)
[2026-04-20 16:31:05.115]  [Pipeline] withCredentials
[2026-04-20 16:31:05.141]  Masking supported pattern matches of $CRED_NEXUS or $CRED_NEXUS_PSW
[2026-04-20 16:31:05.237]  [Pipeline] {
[2026-04-20 16:31:05.352]  [Pipeline] sh
[2026-04-20 16:31:06.048]  + id -g jenkins-agent
[2026-04-20 16:31:06.364]  [Pipeline] sh
[2026-04-20 16:31:07.040]  + id -u jenkins-agent
[2026-04-20 16:31:07.388]  [Pipeline] withEnv
[2026-04-20 16:31:07.485]  [Pipeline] {
[2026-04-20 16:31:07.633]  [Pipeline] dir
[2026-04-20 16:31:07.634]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf
[2026-04-20 16:31:07.726]  [Pipeline] {
[2026-04-20 16:31:07.845]  [Pipeline] script
[2026-04-20 16:31:07.948]  [Pipeline] {
[2026-04-20 16:31:08.111]  [Pipeline] echo
[2026-04-20 16:31:08.143]  [DEBUG] ssh key id 'cdl_si_afs_ssh'
[2026-04-20 16:31:08.239]  [Pipeline] echo
[2026-04-20 16:31:08.262]  [DEBUG] DEPLOY_TOKEN id 'ifk8s-afsc-6f4598-afs408_token'
[2026-04-20 16:31:08.390]  [Pipeline] echo
[2026-04-20 16:31:08.413]  [DEBUG] CI_VAULT_KEY id 'ansible_afs'
[2026-04-20 16:31:08.529]  [Pipeline] echo
[2026-04-20 16:31:08.550]  [1m[94m[INFO] Текущая версия поставки: 0.0.529[0m
[2026-04-20 16:31:08.649]  [Pipeline] echo
[2026-04-20 16:31:08.668]  [DEBUG] Запись yaml файла: automation/config/_dp-merged.yaml
[2026-04-20 16:31:08.915]  [Pipeline] sh
[2026-04-20 16:31:09.588]  + rm -f automation/config/_dp-merged.yaml
[2026-04-20 16:31:09.871]  [Pipeline] writeYaml
[2026-04-20 16:31:10.154]  [Pipeline] archiveArtifacts
[2026-04-20 16:31:10.189]  Archiving artifacts
[2026-04-20 16:31:10.334]  The file automation/config/_dp-merged.yaml has been uploaded successfully.
[2026-04-20 16:31:10.487]  Uploaded 1 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:31:10.614]  [Pipeline] echo
[2026-04-20 16:31:10.640]  [DEBUG] Запись yaml файла: automation/config/_dp-merged_0.0.529.yaml
[2026-04-20 16:31:10.755]  [Pipeline] sh
[2026-04-20 16:31:11.452]  + rm -f automation/config/_dp-merged_0.0.529.yaml
[2026-04-20 16:31:11.783]  [Pipeline] writeYaml
[2026-04-20 16:31:12.090]  [Pipeline] archiveArtifacts
[2026-04-20 16:31:12.135]  Archiving artifacts
[2026-04-20 16:31:12.269]  The file automation/config/_dp-merged_0.0.529.yaml has been uploaded successfully.
[2026-04-20 16:31:12.411]  Uploaded 1 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:31:12.562]  [Pipeline] withCredentials
[2026-04-20 16:31:12.839]  Masking supported pattern matches of $MAIN_KEY_FILE or $CI_VAULT_KEY or $DEPLOY_TOKEN
[2026-04-20 16:31:12.965]  [Pipeline] {
[2026-04-20 16:31:13.114]  [Pipeline] echo
[2026-04-20 16:31:13.148]  [DEBUG] My env.CRED_NEXUS_USER 'cdl_si_AFS@region.vtb.ru'
[2026-04-20 16:31:13.296]  [Pipeline] dir
[2026-04-20 16:31:13.296]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/runtime_artifacts
[2026-04-20 16:31:13.426]  [Pipeline] {
[2026-04-20 16:31:13.578]  [Pipeline] writeFile
[2026-04-20 16:31:13.771]  [Pipeline] }
[2026-04-20 16:31:13.883]  [Pipeline] // dir
[2026-04-20 16:31:14.019]  [Pipeline] fileExists
[2026-04-20 16:31:14.228]  [Pipeline] sh
[2026-04-20 16:31:14.264]  Warning: A secret was passed to "sh" using Groovy String interpolation, which is insecure.
[2026-04-20 16:31:14.265]  		 Affected argument(s) used the following variable(s): [MAIN_KEY_FILE]
[2026-04-20 16:31:14.265]  		 See https://jenkins.io/redirect/groovy-string-interpolation for details.
[2026-04-20 16:31:14.884]  + grep 'BUILD_\|DEPLOY_\|GE_\|CI_PROJECT_DIR\|CRED_NEXUS_\|PATH_TO_\|KUBECONFIG\|CI_VAULT_KEY\|WORKSPACE\|STARTED_BY'
[2026-04-20 16:31:14.884]  + env
[2026-04-20 16:31:14.884]  + [[ -f docker-shell-script.sh ]]
[2026-04-20 16:31:14.884]  + touch docker-shell-script.sh
[2026-04-20 16:31:14.884]  + chmod +x docker-shell-script.sh
[2026-04-20 16:31:14.884]  + cat ****
[2026-04-20 16:31:14.884]  + docker network ls
[2026-04-20 16:31:14.884]  + grep -q dreambuild_UNRPEbwhAembHlf
[2026-04-20 16:31:14.884]  + docker network create dreambuild_UNRPEbwhAembHlf
[2026-04-20 16:31:14.884]  ddf82f1801e16cf871d38987a7776430c762193bd4c000ff38b05f0f4f2fb78d
[2026-04-20 16:31:15.257]  [Pipeline] writeFile
[2026-04-20 16:31:15.458]  [Pipeline] writeFile
[2026-04-20 16:31:15.679]  [Pipeline] sh
[2026-04-20 16:31:16.372]  + cat temp-auth-file.txt
[2026-04-20 16:31:16.372]  + docker login -u cdl_si_AFS@region.vtb.ru --password-stdin docker.repo-cd.sfera.test.vtb.ru:3000
[2026-04-20 16:31:16.372]  WARNING! Your password will be stored unencrypted in /app/jenkins-agent/.docker/config.json.
[2026-04-20 16:31:16.372]  Configure a credential helper to remove this warning. See
[2026-04-20 16:31:16.372]  https://docs.docker.com/engine/reference/commandline/login/#credentials-store
[2026-04-20 16:31:16.372]  
[2026-04-20 16:31:16.372]  Login Succeeded
[2026-04-20 16:31:16.372]  + rm -f temp-auth-file.txt
[2026-04-20 16:31:16.372]  + docker run --rm -w /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf --env-file /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/env.file -v /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf:/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf --network dreambuild_UNRPEbwhAembHlf -e HOME=/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf --entrypoint /bin/sh docker.repo-cd.sfera.test.vtb.ru:3000/afs-docker-test-g/dreamdock/runtime/cd:5.2.6 docker-shell-script.sh
[2026-04-20 16:31:18.344]  Agent pid 9
[2026-04-20 16:31:18.344]  Identity added: /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/main.key (cdl_si_AFS@region.vtb.ru)
[2026-04-20 16:31:18.344]  helm version:
[2026-04-20 16:31:18.344]  version.BuildInfo{Version:"v3.17.0", GitCommit:"301108edc7ac2a8ba79e4ebf5701b0b6ce6a31e4", GitTreeState:"clean", GoVersion:"go1.23.4"}
[2026-04-20 16:31:23.692]  [94m[1mStart job: Download Supply[0m
[2026-04-20 16:31:23.692]  [94m[1mContour name <ift> in <delivery/DLVR-260420145359/dreampipe-ift
[2026-04-20 16:31:23.692]  >
[2026-04-20 16:31:23.692]  [0m
[2026-04-20 16:31:23.692]  [94m[1mMessage for checkout commit:[0m
[2026-04-20 16:31:23.692]  commit af4ccc110a927a52fda25853c5962da0f9969a3e (af4ccc11)
[2026-04-20 16:31:23.692]  Author:	code-synchronizer <dlvry_sfera_i_ppsc@region.vtb.ru>
[2026-04-20 16:31:23.692]  Date:	2026-04-20 14:24:35+03:00
[2026-04-20 16:31:23.692]  
[2026-04-20 16:31:23.692]  From code-synchronizer. Date: 20-04-2026-14:24
[2026-04-20 16:31:23.692]  
[2026-04-20 16:31:23.692]  [94m[1mAnalyzing information source about supply:[0m
[2026-04-20 16:31:23.692]  	RESULT: We use INIT_SUPPLY_ARTIFACT as a supply location source
[2026-04-20 16:31:23.692]  [94m[1mOrdered artifact: afs-maven-test-g:supply.afs:supply:0.0.529:zip[0m
[2026-04-20 16:31:23.692]  ##teamcity[setParameter name='FEEDBACK_VERSION' value='0.0.529']
[2026-04-20 16:31:23.692]  [94m[1mWe are ready to download supply.[0m
[2026-04-20 16:31:23.692]  [32m[1mSupply version: 0.0.529[0m
[2026-04-20 16:31:23.692]  [32m[1mSupply was successfully downloaded 1381 bytes[0m
[2026-04-20 16:31:23.692]  [94m[1mTest supply archive integrity[0m
[2026-04-20 16:31:23.692]  ##teamcity[setParameter name='startDeployment.VERSION' value='0.0.529']
[2026-04-20 16:31:23.693]  [94m[1mChecking image avalability for app afsc-get-deviceid with tag 0.0.1-20260420144701
[2026-04-20 16:31:23.693]  [0m
[2026-04-20 16:31:23.693]  [94m[1mThere are following tags for this image:
[2026-04-20 16:31:23.693]   b'{"name":"afsc-get-deviceid","tags":["0.0.1-20260119171022","0.0.1-20260119193009","0.0.1-20260119205211","0.0.1-20260120114328","0.0.1-20260120131226","0.0.1-20260317080220","0.0.1-20260317133222","0.0.1-20260420144701"]}'
[2026-04-20 16:31:23.693]  [0m
[2026-04-20 16:31:23.693]  [94m[1mTag 0.0.1-20260420144701 for image afsc-get-deviceid was found in registry https://docker.repo-cd.sfera.test.vtb.ru:3000/v2/afs-docker-test-g and will be added to install scenario
[2026-04-20 16:31:23.693]  [0m
[2026-04-20 16:31:23.693]  [94m[1mChecking image avalability for app afsc-get-deviceid-dbmigration with tag 0.0.1-20260420144701
[2026-04-20 16:31:23.693]  [0m
[2026-04-20 16:31:23.693]  [94m[1mThere are following tags for this image:
[2026-04-20 16:31:23.693]   b'{"name":"afsc-get-deviceid-dbmigration","tags":["0.0.1-20260119171022","0.0.1-20260119193009","0.0.1-20260119205211","0.0.1-20260120114328","0.0.1-20260120131226","0.0.1-20260317080220","0.0.1-20260317133222","0.0.1-20260420144701"]}'
[2026-04-20 16:31:23.693]  [0m
[2026-04-20 16:31:23.693]  [94m[1mTag 0.0.1-20260420144701 for image afsc-get-deviceid-dbmigration was found in registry https://docker.repo-cd.sfera.test.vtb.ru:3000/v2/afs-docker-test-g and will be added to install scenario
[2026-04-20 16:31:23.693]  [0m
[2026-04-20 16:31:23.693]  [94m[1mClone the repository and make an initial commit in the master if needed...[0m
[2026-04-20 16:31:23.693]  [94m[1mRepository ready to work. Currently on a branch: ift[0m
[2026-04-20 16:31:23.693]  [94m[1mWe can track feedback deploy/rollback items, parameters configured[0m
[2026-04-20 16:31:23.693]  [94m[1mAdd changes to file (mode: w): /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/FeedBackRepo/deploy.log, len: 507[0m
[2026-04-20 16:31:23.693]  [94m[1mbuild apps value builder, meta True[0m
[2026-04-20 16:31:23.693]  [94m[1mbuild apps value builder, meta True[0m
[2026-04-20 16:31:23.693]  [94m[1mThese apps will be deployed:[0m
[2026-04-20 16:31:23.693]  [94m[1m['afsc-get-deviceid:0.0.1-20260420144701', 'afsc-get-deviceid-dbmigration:0.0.1-20260420144701'][0m
[2026-04-20 16:31:23.693]  [94m[1mThese infra charts will be deployed:[0m
[2026-04-20 16:31:23.693]  [94m[1m[][0m
[2026-04-20 16:31:23.693]  [32m[1mDone.[0m
[2026-04-20 16:31:25.068]  [94m[1mManifest file: `/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/automation/config/vendor/dreampipe.json` not exists, skip custom script execution...[0m
[2026-04-20 16:31:27.088]  [94m[1mStart job: Backup before deployment[0m
[2026-04-20 16:31:27.088]  [94m[1mSkip backup resources. BACKUP_RESOURCES = na[0m
[2026-04-20 16:31:29.716]  [94m[1mStart job: Cleanup job[0m
[2026-04-20 16:31:29.716]  [94m[1mGlobalVariables.CLEANUP_OLD_DB_MIGRATION_JOB=True[0m
[2026-04-20 16:31:29.716]  [94m[1mGlobalVariables.KEEP_NUMBER_OF_JOB_AFTER_CLEANUP=5[0m
[2026-04-20 16:31:29.716]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:29.716]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:29.716]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:29.716]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:29.716]  [94m[1mstart clean old db migration job[0m
[2026-04-20 16:31:29.716]  [94m[1msearch job....[0m
[2026-04-20 16:31:29.716]  [94m[1mRun command: kubectl get job --namespace=ifk8s-afsc-6f4598-afs408 --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --sort-by=.metadata.creationTimestamp --no-headers -o json.[0m
[2026-04-20 16:31:29.716]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:29.716]  [94m[1mthe name of the jobs to delete: [][0m
[2026-04-20 16:31:29.716]  [94m[1mstop clean old db migration job[0m
[2026-04-20 16:31:31.678]  [94m[1mDBG-IAC-pre[0m
[2026-04-20 16:31:41.336]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:41.336]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:41.336]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:41.336]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:41.336]  [32m[1mDone.[0m
[2026-04-20 16:31:41.336]  [94m[1mHelm releases:[0m
[2026-04-20 16:31:41.336]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:41.336]  ========================== Installed Helm Releases ==========================
[2026-04-20 16:31:41.336]  NAME                       	NAMESPACE               	REVISION	UPDATED                                	STATUS  	CHART                            	APP VERSION
[2026-04-20 16:31:41.336]  afsc-adapter-history       	ifk8s-afsc-6f4598-afs408	7       	2025-12-10 13:24:32.509906239 +0000 UTC	deployed	afsc-adapter-history-0.1.0       	latest     
[2026-04-20 16:31:41.336]  afsc-admin-console-backend 	ifk8s-afsc-6f4598-afs408	2       	2025-09-17 15:01:32.993360987 +0000 UTC	deployed	afsc-admin-console-frontend-0.1.0	latest     
[2026-04-20 16:31:41.336]  afsc-admin-console-frontend	ifk8s-afsc-6f4598-afs408	5       	2026-02-18 09:39:23.559147431 +0000 UTC	deployed	afsc-admin-console-frontend-0.1.0	latest     
[2026-04-20 16:31:41.336]  afsc-atfa-rule-synchronizer	ifk8s-afsc-6f4598-afs408	17      	2026-02-17 10:15:00.101725262 +0000 UTC	deployed	afsc-atfa-rule-synchronizer-0.1.0	latest     
[2026-04-20 16:31:41.336]  afsc-audit-exporter        	ifk8s-afsc-6f4598-afs408	18      	2025-12-12 10:04:09.029437204 +0000 UTC	deployed	afsc-audit-exporter-0.1.0        	latest     
[2026-04-20 16:31:41.336]  afsc-cb-limit-loader       	ifk8s-afsc-6f4598-afs408	1       	2026-04-16 14:12:55.424138388 +0000 UTC	deployed	afsc-cb-limit-loader-0.1.0       	latest     
[2026-04-20 16:31:41.336]  afsc-crosslinks-ul-proxy   	ifk8s-afsc-6f4598-afs408	2       	2025-11-27 08:14:50.674744536 +0000 UTC	deployed	afsc-crosslinks-ul-proxy-0.1.0   	latest     
[2026-04-20 16:31:41.336]  afsc-get-deviceid          	ifk8s-afsc-6f4598-afs408	14      	2026-04-20 12:39:40.23612751 +0000 UTC 	deployed	afsc-get-deviceid-0.1.0          	latest     
[2026-04-20 16:31:41.336]  afsc-koul-card-status      	ifk8s-afsc-6f4598-afs408	1       	2026-04-20 10:05:27.534100294 +0000 UTC	deployed	afsc-koul-card-status-0.1.0      	latest     
[2026-04-20 16:31:41.336]  afsc-mdm-get-card          	ifk8s-afsc-6f4598-afs408	34      	2026-01-29 09:46:56.69952024 +0000 UTC 	deployed	afsc-parb-proxy-0.1.0            	latest     
[2026-04-20 16:31:41.337]  afsc-mvd-loader            	ifk8s-afsc-6f4598-afs408	43      	2026-01-29 09:50:19.728401504 +0000 UTC	deployed	afsc-parb-proxy-0.1.0            	latest     
[2026-04-20 16:31:41.337]  afsc-notification-adapter  	ifk8s-afsc-6f4598-afs408	17      	2026-04-13 15:00:47.813527095 +0000 UTC	deployed	afsc-notification-adapter-0.1.0  	latest     
[2026-04-20 16:31:41.337]  afsc-oss-push-proxy        	ifk8s-afsc-6f4598-afs408	20      	2026-03-18 13:59:48.472337104 +0000 UTC	deployed	afsc-oss-push-proxy-0.1.0        	latest     
[2026-04-20 16:31:41.337]  afsc-parb-proxy            	ifk8s-afsc-6f4598-afs408	22      	2026-01-29 09:43:26.739283808 +0000 UTC	deployed	afsc-parb-proxy-0.1.0            	latest     
[2026-04-20 16:31:41.337]  afsc-spark                 	ifk8s-afsc-6f4598-afs408	43      	2026-04-01 12:26:19.090746567 +0000 UTC	deployed	afsc-spark-0.1.0                 	latest     
[2026-04-20 16:31:41.337]  afsc-spark-ui              	ifk8s-afsc-6f4598-afs408	10      	2026-04-01 14:46:17.523873253 +0000 UTC	deployed	afsc-spark-ui-0.1.0              	latest     
[2026-04-20 16:31:41.337]  afsc-spm-card-status       	ifk8s-afsc-6f4598-afs408	28      	2026-02-11 09:48:05.840543004 +0000 UTC	deployed	afsc-spm-card-status-0.1.0       	latest     
[2026-04-20 16:31:41.337]  afsc-usbs-proxy            	ifk8s-afsc-6f4598-afs408	66      	2026-03-06 09:11:44.936330595 +0000 UTC	deployed	afsc-usbs-proxy-0.1.0            	latest     
[2026-04-20 16:31:41.337]  auto-certificates          	ifk8s-afsc-6f4598-afs408	454     	2026-04-20 12:37:59.963702878 +0000 UTC	deployed	auto-certificates-0.1.0          	latest     
[2026-04-20 16:31:41.337]  db-migration-job           	ifk8s-afsc-6f4598-afs408	442     	2026-04-20 12:38:05.424982167 +0000 UTC	deployed	db-migration-job-0.0.1           	auto       
[2026-04-20 16:31:41.337]  epa-emulator               	ifk8s-afsc-6f4598-afs408	449     	2026-04-20 12:39:00.941283758 +0000 UTC	deployed	epa-emulator-0.1.0               	latest     
[2026-04-20 16:31:41.337]  omni-kafka-emulator        	ifk8s-afsc-6f4598-afs408	449     	2026-04-20 12:39:05.50092731 +0000 UTC 	deployed	omni-kafka-emulator-0.1.0        	latest     
[2026-04-20 16:31:41.337]  omni-tsau-emulator         	ifk8s-afsc-6f4598-afs408	448     	2026-04-20 12:39:09.878516095 +0000 UTC	deployed	omni-tsau-emulator-0.1.0         	latest     
[2026-04-20 16:31:41.337]  omni-tsct-emulator         	ifk8s-afsc-6f4598-afs408	449     	2026-04-20 12:39:14.369068359 +0000 UTC	deployed	omni-tsct-emulator-0.1.0         	latest     
[2026-04-20 16:31:41.337]  omni-tsrm-emulator         	ifk8s-afsc-6f4598-afs408	449     	2026-04-20 12:39:18.726943158 +0000 UTC	deployed	omni-tsrm-emulator-0.1.0         	latest     
[2026-04-20 16:31:41.337]  tsam-configuration         	ifk8s-afsc-6f4598-afs408	455     	2026-04-20 12:39:23.089192862 +0000 UTC	deployed	tsam-configuration-0.1.0         	latest     
[2026-04-20 16:31:41.337]  tslg-configuration         	ifk8s-afsc-6f4598-afs408	455     	2026-04-20 12:39:27.503336649 +0000 UTC	deployed	tslg-configuration-0.1.0         	latest     
[2026-04-20 16:31:41.337]  
[2026-04-20 16:31:41.337]  =============================================================================
[2026-04-20 16:31:41.337]  
[2026-04-20 16:31:41.337]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:41.337]  [94m[1mWe can track feedback deploy/rollback items, parameters configured[0m
[2026-04-20 16:31:41.337]  [94m[1mAdd changes to file (mode: a+): /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/FeedBackRepo/deploy.log, len: 4764[0m
[2026-04-20 16:31:41.337]  [94m[1mThis app chart(s) will be installed (upgraded):[0m
[2026-04-20 16:31:41.337]  [94m[1mauto-certificates
[2026-04-20 16:31:41.337]  db-migration-job
[2026-04-20 16:31:41.337]  epa-emulator
[2026-04-20 16:31:41.337]  omni-kafka-emulator
[2026-04-20 16:31:41.337]  omni-tsau-emulator
[2026-04-20 16:31:41.337]  omni-tsct-emulator
[2026-04-20 16:31:41.337]  omni-tsrm-emulator
[2026-04-20 16:31:41.337]  tsam-configuration
[2026-04-20 16:31:41.337]  tslg-configuration[0m
[2026-04-20 16:31:41.337]  [94m[1mbuild infra value builder, meta True[0m
[2026-04-20 16:31:41.337]  [94m[1mUpgrading helm chart auto-certificates[0m
[2026-04-20 16:31:41.337]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:41.337]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:41.337]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:41.337]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/auto-certificates.[0m
[2026-04-20 16:31:41.337]  [94m[1mCall mode.[0m
[2026-04-20 16:31:41.337]  auto-certificates was added to queue for deploy.
[2026-04-20 16:31:41.337]  [94m[1mUpgrading helm chart db-migration-job[0m
[2026-04-20 16:31:41.338]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:41.338]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:41.338]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:41.338]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/db-migration-job.[0m
[2026-04-20 16:31:41.338]  [94m[1mCall mode.[0m
[2026-04-20 16:31:41.338]  db-migration-job was added to queue for deploy.
[2026-04-20 16:31:41.338]  [94m[1mUpgrading helm chart epa-emulator[0m
[2026-04-20 16:31:41.338]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:41.338]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:41.338]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:41.338]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/epa-emulator.[0m
[2026-04-20 16:31:41.338]  [94m[1mCall mode.[0m
[2026-04-20 16:31:41.338]  epa-emulator was added to queue for deploy.
[2026-04-20 16:31:41.338]  [94m[1mUpgrading helm chart omni-kafka-emulator[0m
[2026-04-20 16:31:41.338]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:41.338]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:41.338]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:41.338]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-kafka-emulator.[0m
[2026-04-20 16:31:41.338]  [94m[1mCall mode.[0m
[2026-04-20 16:31:41.338]  omni-kafka-emulator was added to queue for deploy.
[2026-04-20 16:31:41.338]  [94m[1mUpgrading helm chart omni-tsau-emulator[0m
[2026-04-20 16:31:41.338]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:41.338]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:41.338]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:41.338]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsau-emulator.[0m
[2026-04-20 16:31:41.338]  [94m[1mCall mode.[0m
[2026-04-20 16:31:41.338]  omni-tsau-emulator was added to queue for deploy.
[2026-04-20 16:31:41.338]  [94m[1mUpgrading helm chart omni-tsct-emulator[0m
[2026-04-20 16:31:41.338]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:41.338]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:41.338]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:44.719]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsct-emulator.[0m
[2026-04-20 16:31:44.719]  [94m[1mCall mode.[0m
[2026-04-20 16:31:44.720]  omni-tsct-emulator was added to queue for deploy.
[2026-04-20 16:31:44.720]  [94m[1mUpgrading helm chart omni-tsrm-emulator[0m
[2026-04-20 16:31:44.720]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:44.720]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:44.720]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:44.720]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsrm-emulator.[0m
[2026-04-20 16:31:44.720]  [94m[1mCall mode.[0m
[2026-04-20 16:31:44.720]  omni-tsrm-emulator was added to queue for deploy.
[2026-04-20 16:31:44.720]  [94m[1mUpgrading helm chart tsam-configuration[0m
[2026-04-20 16:31:44.720]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:44.720]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:44.720]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:44.720]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/tsam-configuration.[0m
[2026-04-20 16:31:44.720]  [94m[1mCall mode.[0m
[2026-04-20 16:31:44.720]  tsam-configuration was added to queue for deploy.
[2026-04-20 16:31:44.720]  [94m[1mUpgrading helm chart tslg-configuration[0m
[2026-04-20 16:31:44.720]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:31:44.720]  [94m[1mUse variables from ift[0m
[2026-04-20 16:31:44.720]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:31:44.720]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/tslg-configuration.[0m
[2026-04-20 16:31:44.720]  [94m[1mCall mode.[0m
[2026-04-20 16:31:44.720]  tslg-configuration was added to queue for deploy.
[2026-04-20 16:31:44.720]  [94m[1mProject page: https://console.apps.ik7-kube01.test.vtb.ru/k8s/cluster/namespaces/ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:31:44.720]  [94m[1mЗапуск helm diff, опция трехстороннего сравнения three-way-merge: True[0m
[2026-04-20 16:31:44.720]  [94m[1mОпция helm_diff_three_way_merge включена[0m
[2026-04-20 16:31:44.720]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 auto-certificates /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/auto-certificates --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691896 --values /tmp/tmplyy2wd3w --values /tmp/tmp30q8uuq4-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:31:44.720]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:44.720]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 db-migration-job /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/db-migration-job --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmp4znw8it3 --values /tmp/tmpbajkfey9-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/db-migration-job-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/db-migration-job-secret-values.yaml.tmp -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-secret-values.yaml.tmp.[0m
[2026-04-20 16:31:44.720]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:44.721]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 epa-emulator /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/epa-emulator --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmp43dn62p6 --values /tmp/tmpuo6q2y_l-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:31:44.721]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:44.721]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 omni-kafka-emulator /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-kafka-emulator --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmp8ps9_5nq --values /tmp/tmpbi5dcphh-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:31:44.721]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:44.721]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 omni-tsau-emulator /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsau-emulator --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmpa7uj3925 --values /tmp/tmpsno8x4gx-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:31:44.721]  [94m[1mNormal mode.[0m
[2026-04-20 16:31:44.721]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 omni-tsct-emulator /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsct-emulator --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmph7k1l5d2 --values /tmp/tmpzqsizhv_-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:31:44.721]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.319]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 omni-tsrm-emulator /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsrm-emulator --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmpe1_sxav0 --values /tmp/tmpecv_rxrs-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:32:55.319]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.319]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 tsam-configuration /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/tsam-configuration --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmpk6kw8hyq --values /tmp/tmpmb1g345j-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:32:55.320]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.320]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 tslg-configuration /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/tslg-configuration --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776691900 --values /tmp/tmptz1cgrdi --values /tmp/tmp206yov44-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp.[0m
[2026-04-20 16:32:55.320]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.320]  [94m[1mRun command: zip -j --password *** /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/custom_chart_helm_diff_rendered_templates.zip /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/custom_chart_helm_diff_success.info /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/custom_chart_helm_diff_errors.info.[0m
[2026-04-20 16:32:55.320]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.320]  [94m[1mRun parallel process with pid: 659, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'auto-certificates', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/auto-certificates', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691896', '--values', '/tmp/tmplyy2wd3w', '--values', '/tmp/tmp30q8uuq4-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:32:55.320]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest auto-certificates.[0m
[2026-04-20 16:32:55.320]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.320]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:32:55.320]  [94m[1m{'auto-certificates': {}}[0m
[2026-04-20 16:32:55.320]  [94m[1m[2026-04-20 13:31:50.724991] [info] Application: auto-certificates has been successfully deployed[0m
[2026-04-20 16:32:55.320]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:32:55.320]  [32m[1mApplication auto-certificates is ready and available[0m
[2026-04-20 16:32:55.320]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:32:55.320]  [94m[1mRun parallel process with pid: 681, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'db-migration-job', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/db-migration-job', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmp4znw8it3', '--values', '/tmp/tmpbajkfey9-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/db-migration-job-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/db-migration-job-secret-values.yaml.tmp', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-secret-values.yaml.tmp'][0m
[2026-04-20 16:32:55.321]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest db-migration-job.[0m
[2026-04-20 16:32:55.321]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.321]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:32:55.321]  [94m[1m{'db-migration-job': {}}[0m
[2026-04-20 16:32:55.321]  [94m[1m[2026-04-20 13:32:45.616734] [info] Application: db-migration-job has been successfully deployed[0m
[2026-04-20 16:32:55.321]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:32:55.321]  [32m[1mApplication db-migration-job is ready and available[0m
[2026-04-20 16:32:55.321]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:32:55.321]  [94m[1mRun parallel process with pid: 704, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'epa-emulator', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/epa-emulator', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmp43dn62p6', '--values', '/tmp/tmpuo6q2y_l-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:32:55.321]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest epa-emulator.[0m
[2026-04-20 16:32:55.321]  [94m[1mNormal mode.[0m
[2026-04-20 16:32:55.321]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:32:55.321]  [94m[1m{'epa-emulator': {}}[0m
[2026-04-20 16:32:55.321]  [94m[1m[2026-04-20 13:32:49.965827] [info] Application: epa-emulator has been successfully deployed[0m
[2026-04-20 16:32:55.321]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:32:55.321]  [32m[1mApplication epa-emulator is ready and available[0m
[2026-04-20 16:32:55.321]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:15.489]  [94m[1mRun parallel process with pid: 726, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'omni-kafka-emulator', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-kafka-emulator', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmp8ps9_5nq', '--values', '/tmp/tmpbi5dcphh-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:33:15.490]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest omni-kafka-emulator.[0m
[2026-04-20 16:33:15.490]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:15.490]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:33:15.490]  [94m[1m{'omni-kafka-emulator': {}}[0m
[2026-04-20 16:33:15.490]  [94m[1m[2026-04-20 13:32:54.446683] [info] Application: omni-kafka-emulator has been successfully deployed[0m
[2026-04-20 16:33:15.490]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:33:15.490]  [32m[1mApplication omni-kafka-emulator is ready and available[0m
[2026-04-20 16:33:15.490]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:15.490]  [94m[1mRun parallel process with pid: 747, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'omni-tsau-emulator', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsau-emulator', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmpa7uj3925', '--values', '/tmp/tmpsno8x4gx-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:33:15.490]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest omni-tsau-emulator.[0m
[2026-04-20 16:33:15.490]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:15.490]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:33:15.490]  [94m[1m{'omni-tsau-emulator': {}}[0m
[2026-04-20 16:33:15.490]  [94m[1m[2026-04-20 13:32:58.806102] [info] Application: omni-tsau-emulator has been successfully deployed[0m
[2026-04-20 16:33:15.490]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:33:15.490]  [32m[1mApplication omni-tsau-emulator is ready and available[0m
[2026-04-20 16:33:15.490]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:15.490]  [94m[1mRun parallel process with pid: 768, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'omni-tsct-emulator', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsct-emulator', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmph7k1l5d2', '--values', '/tmp/tmpzqsizhv_-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:33:15.490]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest omni-tsct-emulator.[0m
[2026-04-20 16:33:15.490]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:15.490]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:33:15.490]  [94m[1m{'omni-tsct-emulator': {}}[0m
[2026-04-20 16:33:15.490]  [94m[1m[2026-04-20 13:33:03.209382] [info] Application: omni-tsct-emulator has been successfully deployed[0m
[2026-04-20 16:33:15.490]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:33:15.490]  [32m[1mApplication omni-tsct-emulator is ready and available[0m
[2026-04-20 16:33:15.490]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:15.490]  [94m[1mRun parallel process with pid: 790, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'omni-tsrm-emulator', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/omni-tsrm-emulator', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmpe1_sxav0', '--values', '/tmp/tmpecv_rxrs-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:33:15.491]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest omni-tsrm-emulator.[0m
[2026-04-20 16:33:15.491]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:15.491]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:33:15.491]  [94m[1m{'omni-tsrm-emulator': {}}[0m
[2026-04-20 16:33:15.491]  [94m[1m[2026-04-20 13:33:07.579930] [info] Application: omni-tsrm-emulator has been successfully deployed[0m
[2026-04-20 16:33:15.491]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:33:15.491]  [32m[1mApplication omni-tsrm-emulator is ready and available[0m
[2026-04-20 16:33:15.491]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:15.491]  [94m[1mRun parallel process with pid: 813, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'tsam-configuration', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/tsam-configuration', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmpk6kw8hyq', '--values', '/tmp/tmpmb1g345j-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:33:15.491]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest tsam-configuration.[0m
[2026-04-20 16:33:15.491]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:15.491]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:33:15.491]  [94m[1m{'tsam-configuration': {}}[0m
[2026-04-20 16:33:15.491]  [94m[1m[2026-04-20 13:33:12.016645] [info] Application: tsam-configuration has been successfully deployed[0m
[2026-04-20 16:33:15.491]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:33:15.491]  [32m[1mApplication tsam-configuration is ready and available[0m
[2026-04-20 16:33:15.491]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:15.491]  [94m[1mRun parallel process with pid: 836, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'tslg-configuration', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/pre/tslg-configuration', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776691900', '--values', '/tmp/tmptz1cgrdi', '--values', '/tmp/tmp206yov44-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/SharedChartsValues/shared-secret-values.yaml.tmp'][0m
[2026-04-20 16:33:18.128]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest tslg-configuration.[0m
[2026-04-20 16:33:18.128]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.128]  [94m[1mRendered entities: {}[0m
[2026-04-20 16:33:18.128]  [94m[1m{'tslg-configuration': {}}[0m
[2026-04-20 16:33:18.128]  [94m[1m[2026-04-20 13:33:16.630302] [info] Application: tslg-configuration has been successfully deployed[0m
[2026-04-20 16:33:18.128]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:33:18.128]  [32m[1mApplication tslg-configuration is ready and available[0m
[2026-04-20 16:33:18.128]  [32m[1m[success] Applications are ready[0m
[2026-04-20 16:33:18.128]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.128]  [32m[1mSUCCESS: auto-certificates[0m
[2026-04-20 16:33:18.128]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: db-migration-job[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: epa-emulator[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: omni-kafka-emulator[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: omni-tsau-emulator[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: omni-tsct-emulator[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: omni-tsrm-emulator[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: tsam-configuration[0m
[2026-04-20 16:33:18.129]  [94m[1mNormal mode.[0m
[2026-04-20 16:33:18.129]  [32m[1mSUCCESS: tslg-configuration[0m
[2026-04-20 16:43:37.376]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.376]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.376]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.376]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.376]  [32m[1mDone.[0m
[2026-04-20 16:43:37.376]  [94m[1mbuild apps value builder, meta True[0m
[2026-04-20 16:43:37.376]  [94m[1mThis app chart(s) will be installed (upgraded):[0m
[2026-04-20 16:43:37.376]  [94m[1mafsc-get-deviceid[0m
[2026-04-20 16:43:37.376]  [94m[1mbuild apps value builder, meta True[0m
[2026-04-20 16:43:37.376]  [94m[1mUpgrading helm chart afsc-get-deviceid[0m
[2026-04-20 16:43:37.376]  [94m[1mUse inventories dirs /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo[0m
[2026-04-20 16:43:37.376]  [94m[1mUse variables from ift[0m
[2026-04-20 16:43:37.376]  [94m[1mUpdating dependencies[0m
[2026-04-20 16:43:37.376]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 dependency update --skip-refresh /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/meta.[0m
[2026-04-20 16:43:37.376]  [94m[1mCall mode.[0m
[2026-04-20 16:43:37.376]  [94m[1mUpdating helm-afsc-get-deviceid with name afsc-get-deviceid.[0m
[2026-04-20 16:43:37.376]  [94m[1mUpdating helm-afsc-get-deviceid with version 0.0.1.[0m
[2026-04-20 16:43:37.376]  afsc-get-deviceid was added to queue for deploy.
[2026-04-20 16:43:37.376]  [94m[1mProject page: https://console.apps.ik7-kube01.test.vtb.ru/k8s/cluster/namespaces/ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:43:37.376]  [94m[1mЗапуск helm diff, опция трехстороннего сравнения three-way-merge: True[0m
[2026-04-20 16:43:37.376]  [94m[1mОпция helm_diff_three_way_merge включена[0m
[2026-04-20 16:43:37.377]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 diff upgrade --allow-unreleased -C 1 afsc-get-deviceid /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/meta --set dp.meta.supply=0.0.529 --set dp.meta.deployTimestamp=1776692003 --set dp.meta.appVersion=0.0.1 --set dp.meta.commit=1dcc45f6 --set dp.meta.imageTag=0.0.1-20260420144701 --values /tmp/tmpcayaq61z --values /tmp/tmp7xomnzwi-dp-user-cdl_si_AFS@region.vtb.ru -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/common-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/secrets-values.yaml.tmp -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-values.yaml -f /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-secret-values.yaml.tmp.[0m
[2026-04-20 16:43:37.377]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.377]  [94m[1mRun command: zip -j --password *** /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/custom_chart_helm_diff_rendered_templates.zip /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/custom_chart_helm_diff_success.info /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/custom_chart_helm_diff_errors.info.[0m
[2026-04-20 16:43:37.377]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.377]  [94m[1mRun parallel process with pid: 1031, with command: ['helm', '--kubeconfig', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config', '--namespace', 'ifk8s-afsc-6f4598-afs408', 'upgrade', '-i', '--history-max', '3', 'afsc-get-deviceid', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/MetaRepo/meta', '--set', 'dp.meta.supply=0.0.529', '--set', 'dp.meta.deployTimestamp=1776692003', '--set', 'dp.meta.appVersion=0.0.1', '--set', 'dp.meta.commit=1dcc45f6', '--set', 'dp.meta.imageTag=0.0.1-20260420144701', '--values', '/tmp/tmpcayaq61z', '--values', '/tmp/tmp7xomnzwi-dp-user-cdl_si_AFS@region.vtb.ru', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/global-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/common-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/secrets-values.yaml.tmp', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-values.yaml', '-f', '/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-secret-values.yaml.tmp'][0m
[2026-04-20 16:43:37.377]  [94m[1mRun command: helm --kubeconfig /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/config --namespace ifk8s-afsc-6f4598-afs408 get manifest afsc-get-deviceid.[0m
[2026-04-20 16:43:37.377]  [94m[1mNormal mode.[0m
[2026-04-20 16:43:37.377]  [94m[1mRendered entities: {'afsc-get-deviceid': 'Deployment'}[0m
[2026-04-20 16:43:37.377]  [94m[1m{'afsc-get-deviceid': {'afsc-get-deviceid': 'Deployment'}}[0m
[2026-04-20 16:43:37.377]  [94m[1mUsing project: ifk8s-afsc-6f4598-afs408[0m
[2026-04-20 16:43:37.377]  [33m[1mApplication afsc-get-deviceid may be unavailable, not all entities are ready
[2026-04-20 16:43:37.377]  Not ready entities: {'afsc-get-deviceid': 'Deployment'}[0m
[2026-04-20 16:43:37.377]  [33m[1mE1010: Seems like afsc-get-deviceid can not scale! Can't wait more than 600 seconds[0m
[2026-04-20 16:43:37.377]  [31m[1mThere were errors during deploy, please check logs[0m
[2026-04-20 16:43:37.377]  [41m[1mFor detailed log check: Artifacts -> dprun.detailed.log[0m
[2026-04-20 16:43:37.651]  [Pipeline] }
[2026-04-20 16:43:37.812]  [Pipeline] // withCredentials
[2026-04-20 16:43:37.936]  [Pipeline] echo
[2026-04-20 16:43:37.959]  [1m[31m[WARN] !!!!!!!!!!!!!!!! 'script returned exit code 1'[0m
[2026-04-20 16:43:38.064]  [Pipeline] sh
[2026-04-20 16:43:38.872]  + jq -r '.meta | keys[]' ResultUnPacked/data.json
[2026-04-20 16:43:39.204]  [Pipeline] echo
[2026-04-20 16:43:39.234]  [1m[94m[INFO] No manually specified apps to install. The following apps were extracted from data.json: [afsc-get-deviceid][0m
[2026-04-20 16:43:39.359]  [Pipeline] sh
[2026-04-20 16:43:40.035]  + jq -r '.meta."afsc-get-deviceid".image_tag' ResultUnPacked/data.json
[2026-04-20 16:43:40.404]  [Pipeline] }
[2026-04-20 16:43:40.519]  [Pipeline] // script
[2026-04-20 16:43:40.668]  [Pipeline] }
[2026-04-20 16:43:40.779]  [Pipeline] // dir
[2026-04-20 16:43:40.859]  Post stage
[2026-04-20 16:43:40.986]  [Pipeline] dir
[2026-04-20 16:43:40.986]  Running in /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf
[2026-04-20 16:43:41.098]  [Pipeline] {
[2026-04-20 16:43:41.204]  [Pipeline] script
[2026-04-20 16:43:41.311]  [Pipeline] {
[2026-04-20 16:43:41.461]  [Pipeline] writeFile
[2026-04-20 16:43:41.651]  [Pipeline] sh
[2026-04-20 16:43:42.296]  + docker run --rm -w /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf --env-file /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/env.file -v /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf:/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf --network dreambuild_UNRPEbwhAembHlf -e HOME=/app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf --entrypoint /bin/sh docker.repo-cd.sfera.test.vtb.ru:3000/afs-docker-test-g/dreamdock/runtime/cd:5.2.6 docker-shell-script.sh
[2026-04-20 16:43:44.256]  dpcli.py, version 7.7.0
[2026-04-20 16:43:46.216]  [94m[1mStart job: sens data cleaning[0m
[2026-04-20 16:43:46.216]  [94m[1mdebug info[0m
[2026-04-20 16:43:46.216]  [94m[1mcurrent_directory: /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf[0m
[2026-04-20 16:43:46.216]  File /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/secrets-values.yaml.tmp has been successfully deleted.
[2026-04-20 16:43:46.216]  File /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/EnvConfigRepo/ift/namespace/helm/ChartsValues/afsc-get-deviceid/app-secret-values.yaml.tmp has been successfully deleted.
[2026-04-20 16:43:48.168]  + docker network rm dreambuild_UNRPEbwhAembHlf
[2026-04-20 16:43:48.624]  dreambuild_UNRPEbwhAembHlf
[2026-04-20 16:43:48.624]  + docker logout docker.repo-cd.sfera.test.vtb.ru:3000
[2026-04-20 16:43:48.624]  Removing login credentials for docker.repo-cd.sfera.test.vtb.ru:3000
[2026-04-20 16:43:48.875]  [Pipeline] echo
[2026-04-20 16:43:48.902]  [1m[94m[INFO] Запускаем очистку старых тегов runtime образа[0m
[2026-04-20 16:43:48.992]  [Pipeline] sh
[2026-04-20 16:43:49.670]  + docker images --filter=reference=docker.repo-cd.sfera.test.vtb.ru:3000/afs-docker-test-g/dreamdock/runtime/cd --format '{{.Tag}}:{{.ID}}'
[2026-04-20 16:43:49.670]  + grep -v '<none>'
[2026-04-20 16:43:49.670]  + sort -V
[2026-04-20 16:43:49.978]  [Pipeline] echo
[2026-04-20 16:43:50.004]  [DEBUG] Список тегов на агенте (ТЕГ:ID): [5.2.6:b49254180ef7]
[2026-04-20 16:43:50.119]  [Pipeline] echo
[2026-04-20 16:43:50.149]  [DEBUG] Последняя версия: 5.2.6
[2026-04-20 16:43:50.272]  [Pipeline] sh
[2026-04-20 16:43:50.936]  + docker images --filter=reference=docker.repo-cd.sfera.test.vtb.ru:3000/afs-docker-test-g/dreamdock/runtime/cd --format '{{.Tag}}:{{.ID}}'
[2026-04-20 16:43:50.936]  + grep '<none>'
[2026-04-20 16:43:50.936]  + true
[2026-04-20 16:43:51.279]  [Pipeline] zip
[2026-04-20 16:43:51.452]  Compress /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/ResultUnPacked to /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/ResultPacked.zip
[2026-04-20 16:43:51.504]  Compressed 2 entries.
[2026-04-20 16:43:51.504]  Archiving /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/ResultPacked.zip
[2026-04-20 16:43:51.585]  The file ResultPacked.zip has been uploaded successfully.
[2026-04-20 16:43:51.701]  Uploaded 1 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:43:51.792]  [Pipeline] zip
[2026-04-20 16:43:51.964]  Compress /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/runtime_artifacts to /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/runtime_artifacts.zip
[2026-04-20 16:43:52.013]  Compressed 1 entries.
[2026-04-20 16:43:52.013]  Archiving /app/jenkins-agent/workspace/AFS/UNRPEbwhAembHlf/runtime_artifacts.zip
[2026-04-20 16:43:52.092]  The file runtime_artifacts.zip has been uploaded successfully.
[2026-04-20 16:43:52.205]  Uploaded 1 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:43:52.300]  [Pipeline] archiveArtifacts
[2026-04-20 16:43:52.380]  Archiving artifacts
[2026-04-20 16:43:52.545]  The file dprun.detailed.log has been uploaded successfully.
[2026-04-20 16:43:52.558]  The file custom_chart_helm_diff_rendered_templates.zip has been uploaded successfully.
[2026-04-20 16:43:52.571]  The file invcommitid.txt has been uploaded successfully.
[2026-04-20 16:43:52.687]  Uploaded 3 artifact(s) to https://k37-tdos-ceph01.test.vtb.ru/p0-ppor-cdl-buildlogs-2/jenkins/33d48cb4-124d-4fe5-8add-e24e27f35b58/286/artifacts
[2026-04-20 16:43:52.802]  [Pipeline] }
[2026-04-20 16:43:52.909]  [Pipeline] // script
[2026-04-20 16:43:53.034]  [Pipeline] cleanWs
[2026-04-20 16:43:53.160]  [WS-CLEANUP] Deleting project workspace...
[2026-04-20 16:43:53.160]  [WS-CLEANUP] Deferred wipeout is disabled by the job configuration...
[2026-04-20 16:43:53.966]  [WS-CLEANUP] done
[2026-04-20 16:43:54.095]  [Pipeline] }
[2026-04-20 16:43:54.194]  [Pipeline] // dir
[2026-04-20 16:43:54.373]  [Pipeline] }
[2026-04-20 16:43:54.489]  [Pipeline] // withEnv
[2026-04-20 16:43:54.656]  [Pipeline] }
[2026-04-20 16:43:54.790]  [Pipeline] // withCredentials
[2026-04-20 16:43:54.955]  [Pipeline] }
[2026-04-20 16:43:55.112]  [Pipeline] // stage
[2026-04-20 16:43:55.113]  stage: '🚀 Деплой', duration: 00:12:49.999
[2026-04-20 16:43:55.300]  [Pipeline] }
[2026-04-20 16:43:55.436]  [Pipeline] // timeout
[2026-04-20 16:43:55.614]  [Pipeline] }
[2026-04-20 16:43:55.744]  [Pipeline] // node
[2026-04-20 16:43:56.082]  [Pipeline] End of Pipeline
[2026-04-20 16:43:56.155]  hudson.remoting.ProxyException: groovy.lang.MissingPropertyException: No such property: supplyVer for class: WorkflowScript
[2026-04-20 16:43:56.155]  	at org.codehaus.groovy.runtime.ScriptBytecodeAdapter.unwrap(ScriptBytecodeAdapter.java:53)
[2026-04-20 16:43:56.155]  	at org.codehaus.groovy.runtime.ScriptBytecodeAdapter.getProperty(ScriptBytecodeAdapter.java:458)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker$7.call(Checker.java:355)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.GroovyInterceptor.onGetProperty(GroovyInterceptor.java:68)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.scriptsecurity.sandbox.groovy.SandboxInterceptor.onGetProperty(SandboxInterceptor.java:355)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker$7.call(Checker.java:353)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker.checkedGetProperty(Checker.java:357)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker.checkedGetProperty(Checker.java:333)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker.checkedGetProperty(Checker.java:333)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker.checkedGetProperty(Checker.java:333)
[2026-04-20 16:43:56.155]  	at org.kohsuke.groovy.sandbox.impl.Checker.checkedGetProperty(Checker.java:333)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.sandbox.SandboxInvoker.getProperty(SandboxInvoker.java:29)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.impl.PropertyAccessBlock.rawGet(PropertyAccessBlock.java:20)
[2026-04-20 16:43:56.155]  	at WorkflowScript.run(WorkflowScript:242)
[2026-04-20 16:43:56.155]  	at ___cps.transform___(Native Method)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.impl.PropertyishBlock$ContinuationImpl.get(PropertyishBlock.java:74)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.LValueBlock$GetAdapter.receive(LValueBlock.java:30)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.impl.PropertyishBlock$ContinuationImpl.fixName(PropertyishBlock.java:66)
[2026-04-20 16:43:56.155]  	at jdk.internal.reflect.GeneratedMethodAccessor693.invoke(Unknown Source)
[2026-04-20 16:43:56.155]  	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
[2026-04-20 16:43:56.155]  	at java.base/java.lang.reflect.Method.invoke(Method.java:566)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.impl.ContinuationPtr$ContinuationImpl.receive(ContinuationPtr.java:72)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.impl.ConstantBlock.eval(ConstantBlock.java:21)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.Next.step(Next.java:83)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.Continuable$1.call(Continuable.java:174)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.Continuable$1.call(Continuable.java:163)
[2026-04-20 16:43:56.155]  	at org.codehaus.groovy.runtime.GroovyCategorySupport$ThreadCategoryInfo.use(GroovyCategorySupport.java:129)
[2026-04-20 16:43:56.155]  	at org.codehaus.groovy.runtime.GroovyCategorySupport.use(GroovyCategorySupport.java:268)
[2026-04-20 16:43:56.155]  	at com.cloudbees.groovy.cps.Continuable.run0(Continuable.java:163)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.SandboxContinuable.access$001(SandboxContinuable.java:18)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.SandboxContinuable.run0(SandboxContinuable.java:51)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.CpsThread.runNextChunk(CpsThread.java:185)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.CpsThreadGroup.run(CpsThreadGroup.java:413)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.CpsThreadGroup$2.call(CpsThreadGroup.java:325)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.CpsThreadGroup$2.call(CpsThreadGroup.java:289)
[2026-04-20 16:43:56.155]  	at org.jenkinsci.plugins.workflow.cps.CpsVmExecutorService$2.call(CpsVmExecutorService.java:67)
[2026-04-20 16:43:56.155]  	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[2026-04-20 16:43:56.155]  	at hudson.remoting.SingleLaneExecutorService$1.run(SingleLaneExecutorService.java:139)
[2026-04-20 16:43:56.155]  	at jenkins.util.ContextResettingExecutorService$1.run(ContextResettingExecutorService.java:28)
[2026-04-20 16:43:56.155]  	at jenkins.security.ImpersonatingExecutorService$1.run(ImpersonatingExecutorService.java:68)
[2026-04-20 16:43:56.155]  	at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:515)
[2026-04-20 16:43:56.155]  	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
[2026-04-20 16:43:56.155]  	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128)
[2026-04-20 16:43:56.155]  	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)
[2026-04-20 16:43:56.155]  	at java.base/java.lang.Thread.run(Thread.java:829)
[2026-04-20 16:43:56.203]  Finished: FAILURE

