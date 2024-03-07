helm install dubhe --create-namespace -n dubhe-system \
--set harbor.server="172.16.117.11:5000" \
--set harbor.username="admin" \
--set harbor.password="Harbor12345" \

--set prometheus.server="172.16.117.11:5000" \
--set harbor.server="172.16.117.11:5000" \
--set harbor.server="172.16.117.11:5000" \
--set harbor.server="172.16.117.11:5000" \
--set harbor.server="172.16.117.11:5000" \

.
helm uninstall dubhe -n dubhe-system
helm upgrade -i dubhe --create-namespace -n dubhe-system .