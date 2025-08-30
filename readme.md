## 📊 Tabla Comparativa de Certificaciones en Bases de Datos

| Plataforma | Certificación                         | Nivel       | Costo Aprox. (USD) | Duración Examen | Código | Enfoque Principal                                         |
|------------|----------------------------------------|-------------|--------------------|------------------|--------|-----------------------------------------------------------|
| AWS        | [Database Specialty](https://aws.amazon.com/es/training/classroom/exam-readiness-aws-certified-database-specialty/)                     | Avanzado    | $300               | 180 min          | DBS-C01| Diseño, migración y operación de DBs en AWS              |
| Azure      | [DP-900: Data Fundamentals](https://learn.microsoft.com/es-es/credentials/certifications/azure-data-fundamentals/?practice-assessment-type=certification)              | Fundamental | $99                | 60 min           | DP-900 | Conceptos básicos de datos en Azure                      |
| Azure      | [DP-300: Administering Relational DBs](https://learn.microsoft.com/es-es/credentials/certifications/azure-database-administrator-associate/?practice-assessment-type=certification)   | Intermedio  | $165               | 120 min          | DP-300 | Administración de SQL Server en Azure                   |
| GCP        | [Cloud Database Engineer](https://www.cloudskillsboost.google/paths/22)                | Profesional | $200               | 120 min          | N/A    | Diseño y gestión de DBs en GCP                           |
| GCP        | Data Engineer                          | Profesional | $200               | 120 min          | N/A    | Incluye componentes de bases de datos                    |

 

## 💰 Costos Actualizados (2024)

| Certificación           | Costo Examen | Costo Recertificación | Validez       |
|------------------------|--------------|------------------------|---------------|
| AWS Database Specialty | $300         | $150                   | 3 años        |
| Azure DP-900           | $99          | -                      | Sin expiración|
| Azure DP-300           | $165         | -                      | Sin expiración|
| GCP Database Engineer  | $200         | $100                   | 2 años        |

 

## 📚 Recursos de Estudio Recomendados

### AWS Database Specialty
- **Documentación Oficial**: AWS Training and Certification  
- **Cursos**:
  - A Cloud Guru – AWS Certified Database Specialty  
  - Udemy – Curso de Stephane Maarek  
  - Linux Academy (ahora parte de A Cloud Guru)  
- **Práctica**: AWS Free Tier, laboratorios prácticos  

### Azure (DP-900 y DP-300)
- **Microsoft Learn**: Rutas de aprendizaje gratuitas  
- **Cursos**:
  - Microsoft Official Curriculum  
  - Pluralsight – Cursos de bases de datos en Azure  
  - Udemy – Cursos de Scott Duffy  
- **Práctica**: Cuenta gratuita de Azure ($200 crédito inicial)  

### GCP Database Engineer
- **Google Cloud Training**: Qwiklabs  
- **Cursos**:
  - Coursera – Google Cloud Professional  
  - Cloud Academy SkillBuilder – Cursos de GCP  
- **Práctica**: Google Cloud Free Tier  

 

## 🎯 Recomendación Estratégica

### Orden Sugerido:
1. **Azure DP-900** – Nivel fundamental, más fácil y económico  
2. **AWS Database Specialty** – Alta demanda en el mercado  
3. **GCP Database Engineer** – Menos común pero altamente valorado  

### Tiempo Estimado de Preparación:
- **Fundamental**: 2–4 semanas  
- **Especialty/Profesional**: 6–8 semanas cada una  

 

## 💡 Consejos Adicionales

1. **Experiencia Práctica**: Crea cuentas gratuitas en AWS, Azure y GCP  
2. **Comunidades**: Únete a foros y grupos de estudio  
3. **Exámenes de Práctica**: Invierte en tests oficiales o simuladores  
4. **Renovación**: Considera el calendario de recertificación  

 

## 🌐 Recursos Gratuitos

- **AWS Skill Builder** – Cursos gratuitos  
- **Microsoft Learn** – Contenido oficial gratuito  
- **Google Cloud Skills Boost** – Recursos gratuitos  
- **YouTube** – Tutoriales y sesiones técnicas

--- 
# tecnología de cada una de las nubes GCP, AWS , Azure

## 🧠 1. Computación

| Tecnología         | GCP                                           | AWS                                           | Azure                                         |
|-------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| **Máquinas Virtuales** | **Compute Engine**: VMs personalizables con escalado automático | **EC2**: VMs con múltiples tipos de instancias | **Virtual Machines**: VMs con opciones de escalado y disponibilidad |
| **Contenedores/Kubernetes** | **GKE**: Kubernetes gestionado con integración nativa | **EKS**: Kubernetes gestionado con soporte de IAM | **AKS**: Kubernetes gestionado con integración a Azure AD |
| **Serverless**     | **Cloud Run**: Ejecuta contenedores sin gestionar servidores <br> **Cloud Functions**: Funciones ligeras | **Lambda**: Ejecuta funciones sin servidor | **Azure Functions**: Funciones sin servidor para eventos y APIs |
| **Infraestructura como código** | **Deployment Manager**: plantillas YAML para recursos | **CloudFormation**: plantillas JSON/YAML | **ARM Templates / Bicep**: definición declarativa de recursos |

 

## 📦 2. Almacenamiento

| Tecnología         | GCP                                           | AWS                                           | Azure                                         |
|-------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| **Almacenamiento de objetos** | **Cloud Storage**: escalable, ideal para backups y archivos | **S3**: almacenamiento de objetos con alta durabilidad | **Blob Storage**: almacenamiento de objetos para datos no estructurados |
| **Almacenamiento de bloques** | **Persistent Disk**: discos para VMs | **EBS**: discos persistentes para EC2 | **Managed Disks**: discos para máquinas virtuales |
| **Almacenamiento de archivos** | **Filestore**: NFS gestionado | **EFS**: sistema de archivos elástico | **Azure Files**: sistema de archivos SMB/NFS |
| **Archivado**      | **Archive Storage**: para datos de acceso infrecuente | **Glacier**: almacenamiento de archivo de bajo costo | **Cool/Archive Tier**: niveles de almacenamiento para datos fríos |

 

## 🗄️ 3. Bases de Datos

| Tecnología         | GCP                                           | AWS                                           | Azure                                         |
|-------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| **Relacional**     | **Cloud SQL**: MySQL, PostgreSQL, SQL Server <br> Propósito: aplicaciones tradicionales, OLTP | **RDS**: MySQL, PostgreSQL, SQL Server, Oracle <br> Propósito: bases de datos relacionales gestionadas | **Azure SQL Database**: SQL Server como servicio <br> Propósito: aplicaciones empresariales |
| **Relacional distribuida** | **Spanner**: escalabilidad global, consistencia fuerte <br> Propósito: apps críticas con alta disponibilidad | **Aurora**: compatible con MySQL/PostgreSQL, alta disponibilidad <br> Propósito: rendimiento mejorado | **SQL Managed Instance**: migración de SQL Server local <br> Propósito: compatibilidad total con SQL Server |
| **NoSQL - Documentos** | **Firestore**: base de datos de documentos para apps móviles/web <br> Propósito: apps modernas con datos semiestructurados | **DynamoDB**: clave-valor/documentos, baja latencia <br> Propósito: apps de alto rendimiento | **Cosmos DB**: multimodelo, incluye documentos <br> Propósito: apps globales con baja latencia |
| **NoSQL - Columnar** | **Bigtable**: base de datos columnar para grandes volúmenes <br> Propósito: analítica en tiempo real | **Redshift**: almacén de datos columnar <br> Propósito: análisis de grandes volúmenes | **Synapse Analytics**: almacén de datos columnar <br> Propósito: análisis empresarial |
| **Multimodelo**     | — | — | **Cosmos DB**: soporta documentos, grafos, clave-valor, columnas <br> Propósito: flexibilidad para distintos modelos de datos |

 

## 🌐 4. Redes

| Tecnología         | GCP                                           | AWS                                           | Azure                                         |
|-------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| **Red privada virtual** | **VPC**: red privada con control de subredes y firewalls | **VPC**: red privada con control granular | **Virtual Network**: red privada con integración a servicios |
| **Balanceo de carga** | **Cloud Load Balancing**: global, HTTP(S), TCP/UDP | **Elastic Load Balancing**: varios tipos (ALB, NLB, CLB) | **Azure Load Balancer**: interno y externo |
| **CDN**            | **Cloud CDN**: entrega de contenido global | **CloudFront**: CDN con integración a S3 y Lambda | **Azure Front Door**: CDN con aceleración de aplicaciones |
| **VPN y conectividad** | **Cloud VPN / Interconnect** | **VPN Gateway / Direct Connect** | **VPN Gateway / ExpressRoute** |

 

## 🔐 5. Seguridad

| Tecnología         | GCP                                           | AWS                                           | Azure                                         |
|-------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| **Gestión de identidades** | **IAM**: control de acceso por roles | **IAM**: control granular por políticas | **Azure AD**: gestión de identidades y acceso |
| **Protección DDoS** | **Cloud Armor**: protección contra ataques | **AWS Shield**: protección automática | **Azure DDoS Protection**: mitigación de ataques |
| **Gestión de secretos** | **Secret Manager**: almacenamiento seguro de claves | **Secrets Manager**: gestión de secretos y rotación | **Key Vault**: almacenamiento seguro de secretos y certificados |
| **Auditoría y cumplimiento** | **Cloud Audit Logs** | **CloudTrail** | **Azure Monitor / Defender for Cloud** |

 

## 📊 6. Datos y Análisis

| Tecnología         | GCP                                           | AWS                                           | Azure                                         |
|-------------------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| **Almacén de datos** | **BigQuery**: SQL columnar, análisis masivo | **Redshift**: almacén de datos columnar | **Synapse Analytics**: análisis empresarial |
| **ETL / Integración** | **Dataflow**: procesamiento por lotes y streaming | **Glue**: ETL serverless | **Data Factory**: integración y transformación de datos |
| **BI / Visualización** | **Looker**: visualización y exploración de datos | **QuickSight**: BI interactivo | **Power BI**: visualización empresarial |
| **Streaming de datos** | **Pub/Sub**: mensajería en tiempo real | **Kinesis**: procesamiento de streams | **Event Hubs**: ingesta de eventos en tiempo real |
