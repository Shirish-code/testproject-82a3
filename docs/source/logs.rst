Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 17:52:38 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Shirish-code/Rasberrypie/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_17:24:07] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_17:24:32] STEP 2: Create topics started

  [INFO 2024-12-05_17:25:06] STEP 2: Completed

  [INFO 2024-12-05_17:25:17] STEP 2: Create topics started

  [INFO 2024-12-05_17:25:52] STEP 2: Completed

  [INFO 2024-12-05_17:26:02] STEP 3: producing data started

  [INFO 2024-12-05_17:26:10] MQTT connection established...

  [INFO 2024-12-05_17:26:13] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:26:20] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:26:25] STEP 7: Visualization started

  [INFO 2024-12-05_17:26:33] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_17:27:14] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_17:27:19] STEP 9: Starting privateGPT

  [INFO 2024-12-05_17:27:35] STEP 3: producing data started

  [INFO 2024-12-05_17:27:43] MQTT connection established...

  [INFO 2024-12-05_17:27:48] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_17:27:49] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:27:55] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:28:01] STEP 7: Visualization started

  [INFO 2024-12-05_17:28:08] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_17:28:30] STEP 3: producing data started

  [INFO 2024-12-05_17:28:37] MQTT connection established...

  [INFO 2024-12-05_17:28:42] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:28:45] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_17:28:50] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:28:50] STEP 9: Starting privateGPT

  [INFO 2024-12-05_17:28:54] STEP 7: Visualization started

  [INFO 2024-12-05_17:29:02] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_17:29:14] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_17:29:25] STEP 8: Starting docker push for: sajoshi4/testproject-82a3-amd64

  [INFO 2024-12-05_17:30:03] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_17:30:08] STEP 9: Starting privateGPT

  [INFO 2024-12-05_17:30:17] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 58adcb6e3dfb sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-12-05_17:30:32] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_17:38:05] STEP 8: Successfully ran Docker push: docker push sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-12-05_17:39:01] STEP 8: Starting docker push for: sajoshi4/testproject-82a3-amd64

  [INFO 2024-12-05_17:39:44] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 58adcb6e3dfb sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-12-05_17:45:37] STEP 8: Successfully ran Docker push: docker push sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-12-05_17:45:49] STEP 8: Starting docker push for: sajoshi4/testproject-82a3-amd64

  [INFO 2024-12-05_17:46:23] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 58adcb6e3dfb sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-12-05_17:52:23] STEP 8: Successfully ran Docker push: docker push sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-12-05_17:52:36] STEP 10: Started to build the documentation

  [INFO 2024-12-05_17:52:41] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


