helm upgrade -i dubhe-dev --create-namespace -n dubhe-dev \
--set nacos.replicas=3 .
helm uninstall dubhe -n dubhe-dev .