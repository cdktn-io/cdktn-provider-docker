# `dataDockerRegistryImageTags` Submodule <a name="`dataDockerRegistryImageTags` Submodule" id="@cdktn/provider-docker.dataDockerRegistryImageTags"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataDockerRegistryImageTags <a name="DataDockerRegistryImageTags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags docker_registry_image_tags}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new DataDockerRegistryImageTags(Construct Scope, string Id, DataDockerRegistryImageTagsConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig">DataDockerRegistryImageTagsConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig">DataDockerRegistryImageTagsConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform">ToHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify">ResetInsecureSkipVerify</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver">ResetStrictSemver</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ResetInsecureSkipVerify` <a name="ResetInsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify"></a>

```csharp
private void ResetInsecureSkipVerify()
```

##### `ResetStrictSemver` <a name="ResetStrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver"></a>

```csharp
private void ResetStrictSemver()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerRegistryImageTags.IsConstruct(object X);
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerRegistryImageTags.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerRegistryImageTags.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerRegistryImageTags.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataDockerRegistryImageTags to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataDockerRegistryImageTags that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the DataDockerRegistryImageTags to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags">Tags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput">InsecureSkipVerifyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput">StrictSemverInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver">StrictSemver</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Tags`<sup>Required</sup> <a name="Tags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags"></a>

```csharp
public string[] Tags { get; }
```

- *Type:* string[]

---

##### `InsecureSkipVerifyInput`<sup>Optional</sup> <a name="InsecureSkipVerifyInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput"></a>

```csharp
public bool|IResolvable InsecureSkipVerifyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `StrictSemverInput`<sup>Optional</sup> <a name="StrictSemverInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput"></a>

```csharp
public bool|IResolvable StrictSemverInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `InsecureSkipVerify`<sup>Required</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify"></a>

```csharp
public bool|IResolvable InsecureSkipVerify { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `StrictSemver`<sup>Required</sup> <a name="StrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver"></a>

```csharp
public bool|IResolvable StrictSemver { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataDockerRegistryImageTagsConfig <a name="DataDockerRegistryImageTagsConfig" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new DataDockerRegistryImageTagsConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string Name,
    bool|IResolvable InsecureSkipVerify = null,
    bool|IResolvable StrictSemver = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name">Name</a></code> | <code>string</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver">StrictSemver</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, only stable semantic version tags are returned. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `InsecureSkipVerify`<sup>Optional</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify"></a>

```csharp
public bool|IResolvable InsecureSkipVerify { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `StrictSemver`<sup>Optional</sup> <a name="StrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver"></a>

```csharp
public bool|IResolvable StrictSemver { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---



