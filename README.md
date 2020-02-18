### Protofiles repository

This repo contains Protobuf definitions for all the microservices organised in folders.

The pipeline will generate libraries in format `ca101-proto-{lang}`.

### Folder structure
```bash
.
+-- services
|   +-- your-service
|       +-- service.proto # gRPC service definition
|       +-- messages.proto # Protobuf messages
+-- entities # shared Protobuf messages
|   +-- user.proto
```

It's **recommended** to use conventional commits for correct versioning.

---
Highly inspired by this [gist](https://gist.github.com/bobbytables/2fab9ac9509867b5acfe2bb5693aee71) 🙏
