# Deploying - Prerequisites
* ECS-CLI: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI_installation.html

# Deploying - Running
ecs-cli compose start --region eu-west-1 --launch-type FARGATE --create-log-groups --cluster chungcloudapps-documentation

ecs-cli compose service create --region eu-west-1 --launch-type FARGATE --create-log-groups --cluster chungcloudapps-documentation

