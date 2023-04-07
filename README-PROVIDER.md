# Foo Resource Provider

The Lightstep Provider lets you manage [Lightstep](https://lightstep.com/) resources.

## Installing

This package is available for several languages/platforms:

### Node.js (JavaScript/TypeScript)

To use from JavaScript or TypeScript in Node.js, install using either `npm`:

```bash
npm install @pulumi/foo
```

or `yarn`:

```bash
yarn add @pulumi/lightstep
```

### Python

To use from Python, install using `pip`:

```bash
pip install pulumi_lightstep
```

### Go

To use from Go, use `go get` to grab the latest version of the library:

```bash
go get github.com/mnlumi/pulumi-lightstep/sdk/go/...
```

### .NET

To use from .NET, install using `dotnet add package`:

```bash
dotnet add package Pulumi.Lightstep
```

## Configuration

The following configuration points are available for the `lightstep` provider:

- `lighstep:apiKey` (environment: `LIGHTSTEP_API_KEY`) - the API key for `foo`
- `lighstep:organization` (environment: `LIGHTSTEP_ORGANIZATION`) - the region in which to deploy resources

## Reference

For detailed reference documentation, please visit [the Pulumi registry](https://www.pulumi.com/registry/packages/lighstep/api-docs/).
