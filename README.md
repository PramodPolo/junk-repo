# junk-repo

Adding a new line for testing jenkins
adding a 2nd new line

diff --git a/templates/network_data.yaml b/templates/network_data.yaml
index 7d96eec..4699e11 100644
--- a/templates/network_data.yaml
+++ b/templates/network_data.yaml
@@ -52,24 +52,24 @@
   vip: true
   vlan: 30
   name_lower: storage
-  ip_subnet: '172.16.1.0/24'
-  allocation_pools: [{'start': '172.16.1.4', 'end': '172.16.1.250'}]
+  ip_subnet: '172.18.0.0/24'
+  allocation_pools: [{'start': '172.18.0.4', 'end': '172.18.0.250'}]
   ipv6_subnet: 'fd00:fd00:fd00:3000::/64'
   ipv6_allocation_pools: [{'start': 'fd00:fd00:fd00:3000::10', 'end': 'fd00:fd00:fd00:3000:ffff:ffff:ffff:fffe'}]
 - name: StorageMgmt
   name_lower: storage_mgmt
   vip: true
   vlan: 40
-  ip_subnet: '172.16.3.0/24'
-  allocation_pools: [{'start': '172.16.3.4', 'end': '172.16.3.250'}]
+  ip_subnet: '172.19.0.0/24'
+  allocation_pools: [{'start': '172.19.0.4', 'end': '172.19.0.250'}]
   ipv6_subnet: 'fd00:fd00:fd00:4000::/64'
   ipv6_allocation_pools: [{'start': 'fd00:fd00:fd00:4000::10', 'end': 'fd00:fd00:fd00:4000:ffff:ffff:ffff:fffe'}]
 - name: InternalApi
   name_lower: internal_api
   vip: true
   vlan: 20
-  ip_subnet: '172.16.2.0/24'
-  allocation_pools: [{'start': '172.16.2.4', 'end': '172.16.2.250'}]
+  ip_subnet: '172.17.0.0/24'
+  allocation_pools: [{'start': '172.17.0.4', 'end': '172.17.0.250'}]
   ipv6_subnet: 'fd00:fd00:fd00:2000::/64'
   ipv6_allocation_pools: [{'start': 'fd00:fd00:fd00:2000::10', 'end': 'fd00:fd00:fd00:2000:ffff:ffff:ffff:fffe'}]
 - name: Tenant
