index=apigateway-prdidx  api="Intuit.pfm.accounts.transactiontrendservice"


(index=iks) ((sourcetype=eventrouter AND event.involvedObject.namespace=pfm-accounts-transactiontrendservice-usw2-prd) OR ( kubernetes_namespace=pfm-accounts-transactiontrendservice-usw2-prd)) kubernetes_cluster=cg-money-prd-usw2-k8s