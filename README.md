# tomcat-owb

CDI support for Apache Tomcat 9+

## Microprofile CDI extensions

CDI microprofile extensions as listed in: org.apache.tomee.microprofile.TomEEMicroProfileListener

### Configuration
org.apache.geronimo.config:geronimo-config
"org.apache.geronimo.config.cdi.ConfigExtension"
### Fault Tolerance
org.apache.geronimo.safeguard:safeguard-parent
"org.apache.safeguard.impl.cdi.SafeguardExtension"
### JSON Web Tokens
Note: Unusable outside TomEE
org.apache.tomee:mp-jwt
"org.apache.tomee.microprofile.jwt.cdi.MPJWTCDIExtension"
### Health
org.apache.geronimo:geronimo-health
"org.apache.geronimo.microprofile.impl.health.cdi.GeronimoHealthExtension"
### Metrics
org.apache.geronimo:geronimo-metrics
"org.apache.geronimo.microprofile.metrics.cdi.MetricsExtension"
### OpenTracing
org.apache.geronimo:geronimo-opentracing-parent
"org.apache.geronimo.microprofile.opentracing.microprofile.cdi.OpenTracingExtension"
### OpenAPI
org.apache.geronimo:geronimo-openapi
"org.apache.geronimo.microprofile.openapi.cdi.GeronimoOpenAPIExtension"
### Rest client
org.apache.cxf:cxf-rt-rs-mp-client
"org.apache.cxf.microprofile.client.cdi.RestClientExtension"
