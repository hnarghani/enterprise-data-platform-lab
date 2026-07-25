Enterprise Data Platform

                 Users
                    │
                    ▼
              Apache Superset
                    │
                    ▼
          Trino / Hive / Spark SQL
                    │
                    ▼
     Iceberg / Paimon (Lakehouse)
                    │
                    ▼
         Spark      Flink
            │          │
            └────┬─────┘
                 ▼
              Kafka
                 │
      ┌──────────┴──────────┐
      ▼                     ▼
 Database CDC         REST APIs
      │
      ▼
 PostgreSQL / MySQL
