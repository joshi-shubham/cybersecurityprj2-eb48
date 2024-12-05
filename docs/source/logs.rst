Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 16:59:12 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/joshi-shubham/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_16:56:38] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_16:56:42] STEP 2: Create topics started

  [INFO 2024-12-05_16:56:57] STEP 2: Completed

  [INFO 2024-12-05_16:57:05] STEP 3: producing data started

  [INFO 2024-12-05_16:57:08] MQTT connection established...

  [INFO 2024-12-05_16:57:08] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:57:11] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:57:12] STEP 7: Visualization started

  [INFO 2024-12-05_16:57:18] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_16:57:25] STEP 9: Starting privateGPT

  [INFO 2024-12-05_16:57:31] STEP 8: Starting docker push for: shubjoshi/cybersecurityprj2-eb48-amd64

  [INFO 2024-12-05_16:57:42] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_16:57:58] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 81b87bcb2e8d shubjoshi/cybersecurityprj2-eb48-amd64 - message=0

  [INFO 2024-12-05_16:58:46] STEP 8: Successfully ran Docker push: docker push shubjoshi/cybersecurityprj2-eb48-amd64 - message=0

  [INFO 2024-12-05_16:59:11] STEP 10: Started to build the documentation

  [INFO 2024-12-05_16:59:13] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


