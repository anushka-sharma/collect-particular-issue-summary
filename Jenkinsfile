pipeline{
agent any
stages{

stage('Jenkins job'){
steps{
 
sh 'curl -X GET \
  'http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/api/2/search?jql=project%3DAVR&fields=key%2Csummary%2Cdescription&maxResults=1000&startAt=0' \
  -H 'accept: application/json' \
  -H 'authorization: Basic cmlnOmRpZ2l0YWxyaWdAMTIz' \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 3334c5d3-e569-fafe-2d2a-ac86aebcf1f3''
  }
  }
  }
  }
