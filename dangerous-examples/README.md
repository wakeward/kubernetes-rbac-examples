# Dangerous RBAC Examples

The Roles or ClusterRoles listed in this folder are dangerous examples and for educational purposes only.

| ID | Threat(s) | Explaination/Link |
| --- | --- | --- |
| clusterrole-core-star.yaml | `resource: serviceaccount/token` `verb: create` | [Token Request](https://kubernetes.io/docs/concepts/security/rbac-good-practices/#token-request) |
| clusterrole-core-star.yaml | `resource: nodes/proxy` `verb: get, create` | [Nodes Proxy](https://blog.aquasec.com/privilege-escalation-kubernetes-rbac) |
| clusterrole-cr-star.yaml | `resource: clusterroles` `verb: escalate, bind` | [Escalate & Bind](https://kubernetes.io/docs/concepts/security/rbac-good-practices/#escalate-verb)
