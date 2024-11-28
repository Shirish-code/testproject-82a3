Latest Logs From Latest Build
==============================

Generated On: 2024-11-28 21:23:56 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Shirish-code/Rasberrypie/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-28_21:11:30] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-28_21:11:49] STEP 2: Create topics started

  [INFO 2024-11-28_21:12:50] STEP 2: Completed

  [INFO 2024-11-28_21:13:29] STEP 3: producing data started

  [INFO 2024-11-28_21:13:39] MQTT connection established...

  [INFO 2024-11-28_21:13:46] STEP 4: Preprocessing started

  [INFO 2024-11-28_21:13:55] STEP 4: Preprocessing started

  [INFO 2024-11-28_21:14:03] STEP 7: Visualization started

  [INFO 2024-11-28_21:14:10] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-28_21:15:03] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-28_21:15:08] STEP 9: Starting privateGPT

  [INFO 2024-11-28_21:15:16] STEP 8: Starting docker push for: sajoshi4/testproject-82a3-amd64

  [INFO 2024-11-28_21:16:02] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-28_21:16:10] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit c37d4301818c sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-11-28_21:23:10] STEP 8: Successfully ran Docker push: docker push sajoshi4/testproject-82a3-amd64 - message=0

  [INFO 2024-11-28_21:23:54] STEP 10: Started to build the documentation

  [INFO 2024-11-28_21:23:58] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


