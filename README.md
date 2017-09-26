# Mesosphere DCOS

./bin/spark-shell --master mesos://192.168.65.90:5050 --conf spark.mesos.executor.docker.image=mesosphere/spark:1.0.9-2.1.0-1-hadoop-2.6 --conf spark.mesos.executor.home=/opt/spark/dist
