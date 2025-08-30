### 🧠 Clasificación de los datos

| **Tipo de Dato** | **Descripción** | **Ejemplos** | **Bases de Datos Comunes** |
|------------------|------------------|--------------|-----------------------------|
| **Estructurados** | Datos organizados en tablas con columnas bien definidas (esquema fijo). | SQL, CSV, Excel | PostgreSQL, MySQL, Oracle, SQL Server |
| **Semi-estructurados** | Datos con estructura flexible, pero con etiquetas o claves. No requieren esquema rígido. | JSON, XML, YAML | MongoDB, Couchbase, Elasticsearch |
| **No estructurados** | Datos sin estructura definida, difíciles de organizar en tablas. | Imágenes, videos, audios, documentos | Hadoop HDFS, S3, Data Lakes |
| **Multimedia** | Subtipo de no estructurados, enfocados en contenido visual o auditivo. | MP4, JPG, MP3, PDF | Data Lakes, BLOB en SQL, MongoDB GridFS |
| **Series de tiempo** | Datos indexados por tiempo, usados para métricas y monitoreo. | Logs, sensores, precios históricos | InfluxDB, TimescaleDB, Prometheus |
| **Geoespaciales** | Datos que representan ubicaciones, coordenadas, mapas. | Puntos GPS, polígonos | PostGIS, MongoDB, Oracle Spatial |
| **Grafos** | Datos que representan relaciones entre entidades (nodos y aristas). | Redes sociales, recomendaciones | Neo4j, Amazon Neptune |
| **Clave-Valor** | Datos simples donde cada valor está asociado a una clave única. | Cache, sesiones | Redis, DynamoDB |
| **Columnar** | Datos almacenados por columnas en lugar de filas, optimizados para análisis. | OLAP, BI | BigQuery, Redshift, ClickHouse |
| **Documentales** | Datos almacenados como documentos completos (JSON, BSON). | Catálogos, perfiles | MongoDB, CouchDB |
| **Binarios** | Datos en formato binario, usados para archivos grandes. | Archivos, imágenes | BLOB, BYTEA, GridFS |

---

### 📌 ¿Por qué es importante esta clasificación?

- **Estructurados** → ideales para transacciones y reportes.
- **Semi-estructurados** → flexibles para APIs y datos cambiantes.
- **No estructurados** → útiles en almacenamiento masivo y análisis con IA.
- **Series de tiempo** → esenciales en monitoreo y IoT.
- **Grafos** → perfectos para relaciones complejas.
- **Columnar** → optimizados para análisis masivo.
