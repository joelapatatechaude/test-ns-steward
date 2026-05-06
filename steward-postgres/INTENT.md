A PostgreSQL database running the official Red Hat container image (rhel9/postgresql-15).

- Deployment named "database", single replica, Recreate strategy
- Persistent storage: 2Gi on px-csi-db-repl2, mounted at /var/lib/pgsql/data
- ClusterIP service on port 5432
- Database name: steward, user: steward
- ArgoCD project: steward
