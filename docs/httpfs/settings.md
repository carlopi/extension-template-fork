|              name               |                                         description                                          | input_type | scope  |
|---------------------------------|----------------------------------------------------------------------------------------------|------------|--------|
| ca_cert_file                    | Path to a custom certificate file for self-signed certificates.                              | VARCHAR    | GLOBAL |
| enable_server_cert_verification | Enable server side certificate verification.                                                 | BOOLEAN    | GLOBAL |
| force_download                  | Forces upfront download of file                                                              | BOOLEAN    | GLOBAL |
| http_keep_alive                 | Keep alive connections. Setting this to false can help when running into connection failures | BOOLEAN    | GLOBAL |
| http_retries                    | HTTP retries on I/O error                                                                    | UBIGINT    | GLOBAL |
| http_retry_backoff              | Backoff factor for exponentially increasing retry wait time                                  | FLOAT      | GLOBAL |
| http_retry_wait_ms              | Time between retries                                                                         | UBIGINT    | GLOBAL |
| http_timeout                    | HTTP timeout read/write/connection/retry                                                     | UBIGINT    | GLOBAL |
| s3_access_key_id                | S3 Access Key ID                                                                             | VARCHAR    | GLOBAL |
| s3_endpoint                     | S3 Endpoint                                                                                  | VARCHAR    | GLOBAL |
| s3_region                       | S3 Region                                                                                    | VARCHAR    | GLOBAL |
| s3_secret_access_key            | S3 Access Key                                                                                | VARCHAR    | GLOBAL |
| s3_session_token                | S3 Session Token                                                                             | VARCHAR    | GLOBAL |
| s3_uploader_max_filesize        | S3 Uploader max filesize (between 50GB and 5TB)                                              | VARCHAR    | GLOBAL |
| s3_uploader_max_parts_per_file  | S3 Uploader max parts per file (between 1 and 10000)                                         | UBIGINT    | GLOBAL |
| s3_uploader_thread_limit        | S3 Uploader global thread limit                                                              | UBIGINT    | GLOBAL |
| s3_url_compatibility_mode       | Disable Globs and Query Parameters on S3 URLs                                                | BOOLEAN    | GLOBAL |
| s3_url_style                    | S3 URL style                                                                                 | VARCHAR    | GLOBAL |
| s3_use_ssl                      | S3 use SSL                                                                                   | BOOLEAN    | GLOBAL |
