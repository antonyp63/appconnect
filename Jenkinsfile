#!groovy

@Library('MicroserviceBuilder') _
microserviceBuilderPipeline {
  image = 'ap-ace-microclimate'
  registry = 'icpcluster.icp:8500/team1'
  chartFolder="ace-helm-master/ibm-ace-dev-for-microclimate"
  namespace='team1'
}
