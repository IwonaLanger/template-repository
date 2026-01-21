# Custom Resource Topic

<!-- Use this template for a custom resource (CR) document that provides a sample custom resource and describes its fields. Additionally, the document points to the CustomResourceDefinition (CRD) used to create CRs of the given kind.

For the filename, follow the `{RESOURCE_NAME}.md` convention. For the title, use the name of the custom resource written in camel case. For example, "LogPipeline" or "Function". For reference, see [Telemetry Resources](https://github.com/kyma-project/telemetry-manager/blob/main/docs/user/resources/README.md) or [Serverless Resources](https://github.com/kyma-project/serverless/tree/main/docs/user/resources).

Some module teams update the resource documentation manually, while others use tools that autogenerate it from code files. For guidance on implementing autogeneration, see [Autogenenerate Custom Resource Documentation](TBD). Regardless of the approach you choose, maintain the basic structure of the file.
-->

The `{CRD name}` CustomResourceDefinition (CRD) is a detailed description of the kind of data and the format used to {provide the CRD description}. To get the up-to-date CRD and show the output in the `yaml` format, run this command:

```bash
kubectl get crd {CRD name} -o yaml
```

## Sample Custom Resource

<!-- In this section, provide an example custom resource created based on the CRD described in the introductory section. Describe the functionality of the CR and highlight all of the optional elements and the way they are utilized.
Provide the custom resource code sample in a ready-to-use format. -->

This is a sample resource that {provide a description of what the example presents}.

```yaml
apiVersion:
kind:
metadata:
  name:
{another_field}:
```

## Custom Resource Parameters
<!-- This section lists all the fields of the custom resource and provides their description. -->

This table lists all the possible parameters of a given resource together with their descriptions:

| Parameter   | Required |  Description |
|-------------|:---------:|--------------|
| **metadata.name** | Yes | Specifies the name of the CR. |
| **{another_parameter}** | {Yes/No} | {Parameter description} |

## Related Resources and Components

These are the resources related to this CR:

| Custom resource |   Description |
|-----------------|---------------|
| {Related CRD kind} |  {Briefly describe the relation between the resources}. |

These components use this CR:

| Component   |   Description |
|-------------|---------------|
| {Component name} |  {Briefly describe the relation between the CR and the given component}. |
