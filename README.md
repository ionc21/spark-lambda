# spark-lambda
Start vagrant: vagrant up
Log to the vagran box in cygwin:
 1. vagrant ssh
 2. copy spark-lambda-1.0-SNAPSHOT-shaded.jar into vagrant dir
 3. run:  ./bin/spark-submit --master yarn --deploy-mode cluster --class batch.BatchJob /vagrant/spark-lambda-1.0-SNAPSHOT-shaded.jar