## lume-protobuf

### Scripts

- `npm publish`: Compiles proto files to typescript, builds package, and publishes to nexus
- `mvn clean package`: Compiles proto files to java classes and builds jar file

### Libraries

- `tsup`: Lightweight TS bundler
- `@bufbuild/protobuf-es`: Typescript compiler for Protobuf
- `protoc`: Install globally on machine for this project
- `maven`: Java build automation

### Notes

- Generated files are not saved to this repo, but `src/typescript/index.ts` required to export classes for package building
