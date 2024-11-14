Latest Logs From Latest Build
==============================

Generated On: 2024-11-14 19:20:44 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/joshi-shubham/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-14_19:10:13] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-14_19:10:24] STEP 2: Create topics started

  [INFO 2024-11-14_19:11:15] STEP 2: Completed

  [INFO 2024-11-14_19:11:40] STEP 3: producing data started

  [INFO 2024-11-14_19:11:52] MQTT connection established...

  [INFO 2024-11-14_19:11:59] STEP 4: Preprocessing started

  [INFO 2024-11-14_19:12:10] STEP 4: Preprocessing started

  [INFO 2024-11-14_19:12:17] STEP 7: Visualization started

  [INFO 2024-11-14_19:12:24] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-14_19:12:48] STEP 9: Starting privateGPT

  [INFO 2024-11-14_19:13:01] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-14_19:13:18] STEP 8: Starting docker push for: shubjoshi/cybersecurityprj2-eb48-amd64

  [INFO 2024-11-14_19:14:32] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 9dffda24c0f3 shubjoshi/cybersecurityprj2-eb48-amd64 - message=0

  [INFO 2024-11-14_19:18:48] STEP 8: Successfully ran Docker push: docker push shubjoshi/cybersecurityprj2-eb48-amd64 - message=0

  [INFO 2024-11-14_19:20:40] STEP 10: Started to build the documentation

  [INFO 2024-11-14_19:20:49] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


