# AWS Elasticsearch Service

* Upgrade ES Version

* check lambdas/delete_elasticsearch_indice.zip is in ptt-alertor bucket

* update lambda function from s3 zip file

    ```console
    aws lambda update-function-code --function-name Delete_ES_Indice --s3-bucket ptt-alertor-2020-bucket --s3-key lambdas/delete_elasticsearch_indice.zip
    ```