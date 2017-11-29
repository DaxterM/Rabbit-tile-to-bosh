# Create rabbitMQ release deployment manifiest with loggregator 
```
bosh int template-manifests/rabbitmq-release.yml --vars-store vars/vars-file.yml -o ops/add-loggregator-release.yml > manifests/RabbitMQ-release.yml
```

# Create rabbitMQ  multi tenant broker release deployment manifiest
```
bosh int template-manifests/rabbit-multitenant-broker.yml --vars-store vars/vars-file.yml  > manifests/RabbitMQ-broker-manifiest.yml

```
