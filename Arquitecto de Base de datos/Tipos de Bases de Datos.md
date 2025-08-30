### 🧠 Tipos de Bases de Datos (Alta Escalabilidad)

| **Tipo** | **Descripción** | **Casos de Uso Común** | **Ejemplos** |
|----------|------------------|-------------------------|--------------|
| **Relacional (Row-based)** | Almacenan datos en filas y tablas con relaciones entre ellas. | ERP, CRM, sistemas financieros | PostgreSQL, Oracle, SQL Server |
| **Columnar (Column-based)** | Almacenan datos por columnas, optimizados para análisis masivo. | BI, OLAP, dashboards | BigQuery, Redshift, ClickHouse |
| **NoSQL (Documentos)** | Almacenan datos como documentos JSON o BSON. | Apps web, catálogos, datos flexibles | MongoDB, Couchbase |
| **NoSQL (Clave-Valor)** | Almacenan pares clave-valor, ultra rápidos. | Caché, sesiones, tokens | Redis, Aerospike |
| **NoSQL (Grafos)** | Modelan relaciones complejas entre entidades. | Redes sociales, recomendaciones | Neo4j, Amazon Neptune |
| **NoSQL (Columnar Distribuido)** | Similar a columnar, pero distribuido para alta disponibilidad. | IoT, telecomunicaciones | Cassandra, ScyllaDB |
| **Series de Tiempo** | Optimizadas para almacenar métricas con timestamp. | Monitoreo, IoT, sensores | InfluxDB, TimescaleDB |
| **Orientadas a Objetos** | Almacenan objetos como en programación orientada a objetos. | Aplicaciones científicas, simulaciones | db4o, ObjectDB |
| **Multimodelo** | Soportan múltiples modelos (relacional, documento, grafo, etc.) | Aplicaciones híbridas | ArangoDB, OrientDB |
| **Distribuidas / Data Lakes** | Almacenan datos en clústeres distribuidos, sin esquema rígido. | Big Data, AI, ML | Hadoop HDFS, Delta Lake, Iceberg |
| **In-Memory** | Almacenan datos en RAM para acceso ultra rápido. | Trading, juegos, análisis en tiempo real | Redis, MemSQL |
| **Federadas / Virtuales** | No almacenan datos, sino que los consultan desde múltiples fuentes. | Integración de datos, BI | Denodo, PrestoDB |
| **Ledger / Blockchain** | Almacenan datos inmutables con trazabilidad. | Finanzas, contratos inteligentes | Hyperledger, BigchainDB |



### 🔍 ¿Qué tipo elegir?

Depende de:
- **Volumen de datos** (GB, TB, PB, EB)
- **Tipo de acceso** (transaccional vs analítico)
- **Estructura de datos** (estructurado, semi-estructurado, no estructurado)
- **Escalabilidad requerida** (vertical vs horizontal)
- **Latencia aceptable** (milisegundos vs batch)


--- 

### 🧩 Diferencias entre Relacional vs Columnar

| **Aspecto** | **Relacional (Row-based)** | **Columnar (Column-based)** |
|-------------|-----------------------------|------------------------------|
| **Modelo de Almacenamiento** | Guarda los datos **fila por fila** | Guarda los datos **columna por columna** |
| **Ejemplos** | PostgreSQL, MySQL, Oracle, SQL Server | BigQuery, Redshift, ClickHouse, Vertica |
| **Optimizado para** | Transacciones (OLTP): inserciones, actualizaciones, consultas por ID | Analítica (OLAP): agregaciones, filtros, escaneos masivos |
| **Velocidad de Lectura** | Rápido para acceder a registros completos | Rápido para acceder a columnas específicas en grandes volúmenes |
| **Compresión** | Menor compresión (datos heterogéneos por fila) | Alta compresión (datos homogéneos por columna) |
| **Uso de Índices** | Índices tradicionales (B-Tree, Hash) | Menos dependiente de índices; escaneo eficiente por columna |
| **Carga de Trabajo Ideal** | Aplicaciones web, ERP, CRM, sistemas de facturación | BI, dashboards, análisis de logs, machine learning |
| **Escalabilidad** | Vertical (más CPU/RAM) o particionado horizontal | Horizontal (sharding, clústeres distribuidos) |
| **Ejemplo de Consulta** | `SELECT * FROM ventas WHERE id = 123` | `SELECT AVG(monto) FROM ventas WHERE fecha > '2025-01-01'` |

---

### 🔍 ¿Cuál elegir?

- Si tu sistema requiere **muchas transacciones por segundo**, como una API REST que consulta por ID o actualiza registros, lo ideal es una **base relacional**.
- Si tu sistema necesita **analizar millones de registros** para obtener promedios, sumas, tendencias, etc., lo mejor es una **base columnar**.
