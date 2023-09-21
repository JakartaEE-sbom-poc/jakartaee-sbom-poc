# jakartaee-sbom-poc

* This repository contains a list of SBOM files generated using the cyclonedx-maven-plugin

* To query or analyse a SBOM, You can use the sbom-utility

* Please find below an example to inspect SBOM resources type for org.glassfish.jersey/project/3.1.3/bom.json

```bash
sbom-utility resource -i org.glassfish.jersey/project/3.1.3/bom.json
```



Each BOM path follows this path schema based on its Maven configuration: project.groupId/{project.groupId}/project.groupId/{project.artifactId}/${project.version}