@Library('test_shared_library')

def prod_deploy_name = "customer5-odoo15"

def test_deploy_name = "customer5-test-odoo15"

def odoo_version="15.0"

def dockerhub_repo_name = "customer5"

buildPipeline(stage:"test",dockerhub_repo_name:"${dockerhub_repo_name}",test_deploy_name:"${test_deploy_name}",prod_deploy_name:"${prod_deploy_name}",odoo_version:"${odoo_version}")
