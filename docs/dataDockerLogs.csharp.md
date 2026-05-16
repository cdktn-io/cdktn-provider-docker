# `dataDockerLogs` Submodule <a name="`dataDockerLogs` Submodule" id="@cdktn/provider-docker.dataDockerLogs"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataDockerLogs <a name="DataDockerLogs" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs docker_logs}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new DataDockerLogs(Construct Scope, string Id, DataDockerLogsConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig">DataDockerLogsConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig">DataDockerLogsConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toHclTerraform">ToHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetDetails">ResetDetails</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetDiscardHeaders">ResetDiscardHeaders</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetFollow">ResetFollow</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetLogsListStringEnabled">ResetLogsListStringEnabled</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetShowStderr">ResetShowStderr</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetShowStdout">ResetShowStdout</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetSince">ResetSince</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetTail">ResetTail</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetTimestamps">ResetTimestamps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetUntil">ResetUntil</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ResetDetails` <a name="ResetDetails" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetDetails"></a>

```csharp
private void ResetDetails()
```

##### `ResetDiscardHeaders` <a name="ResetDiscardHeaders" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetDiscardHeaders"></a>

```csharp
private void ResetDiscardHeaders()
```

##### `ResetFollow` <a name="ResetFollow" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetFollow"></a>

```csharp
private void ResetFollow()
```

##### `ResetId` <a name="ResetId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetLogsListStringEnabled` <a name="ResetLogsListStringEnabled" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetLogsListStringEnabled"></a>

```csharp
private void ResetLogsListStringEnabled()
```

##### `ResetShowStderr` <a name="ResetShowStderr" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetShowStderr"></a>

```csharp
private void ResetShowStderr()
```

##### `ResetShowStdout` <a name="ResetShowStdout" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetShowStdout"></a>

```csharp
private void ResetShowStdout()
```

##### `ResetSince` <a name="ResetSince" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetSince"></a>

```csharp
private void ResetSince()
```

##### `ResetTail` <a name="ResetTail" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetTail"></a>

```csharp
private void ResetTail()
```

##### `ResetTimestamps` <a name="ResetTimestamps" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetTimestamps"></a>

```csharp
private void ResetTimestamps()
```

##### `ResetUntil` <a name="ResetUntil" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.resetUntil"></a>

```csharp
private void ResetUntil()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a DataDockerLogs resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerLogs.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerLogs.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isTerraformDataSource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerLogs.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

DataDockerLogs.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a DataDockerLogs resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataDockerLogs to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataDockerLogs that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the DataDockerLogs to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.logsListString">LogsListString</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.detailsInput">DetailsInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.discardHeadersInput">DiscardHeadersInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.followInput">FollowInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.logsListStringEnabledInput">LogsListStringEnabledInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStderrInput">ShowStderrInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStdoutInput">ShowStdoutInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.sinceInput">SinceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.tailInput">TailInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.timestampsInput">TimestampsInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.untilInput">UntilInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.details">Details</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.discardHeaders">DiscardHeaders</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.follow">Follow</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.logsListStringEnabled">LogsListStringEnabled</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStderr">ShowStderr</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStdout">ShowStdout</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.since">Since</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.tail">Tail</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.timestamps">Timestamps</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.until">Until</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `LogsListString`<sup>Required</sup> <a name="LogsListString" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.logsListString"></a>

```csharp
public string[] LogsListString { get; }
```

- *Type:* string[]

---

##### `DetailsInput`<sup>Optional</sup> <a name="DetailsInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.detailsInput"></a>

```csharp
public bool|IResolvable DetailsInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `DiscardHeadersInput`<sup>Optional</sup> <a name="DiscardHeadersInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.discardHeadersInput"></a>

```csharp
public bool|IResolvable DiscardHeadersInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `FollowInput`<sup>Optional</sup> <a name="FollowInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.followInput"></a>

```csharp
public bool|IResolvable FollowInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `LogsListStringEnabledInput`<sup>Optional</sup> <a name="LogsListStringEnabledInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.logsListStringEnabledInput"></a>

```csharp
public bool|IResolvable LogsListStringEnabledInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `ShowStderrInput`<sup>Optional</sup> <a name="ShowStderrInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStderrInput"></a>

```csharp
public bool|IResolvable ShowStderrInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `ShowStdoutInput`<sup>Optional</sup> <a name="ShowStdoutInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStdoutInput"></a>

```csharp
public bool|IResolvable ShowStdoutInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SinceInput`<sup>Optional</sup> <a name="SinceInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.sinceInput"></a>

```csharp
public string SinceInput { get; }
```

- *Type:* string

---

##### `TailInput`<sup>Optional</sup> <a name="TailInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.tailInput"></a>

```csharp
public string TailInput { get; }
```

- *Type:* string

---

##### `TimestampsInput`<sup>Optional</sup> <a name="TimestampsInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.timestampsInput"></a>

```csharp
public bool|IResolvable TimestampsInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `UntilInput`<sup>Optional</sup> <a name="UntilInput" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.untilInput"></a>

```csharp
public string UntilInput { get; }
```

- *Type:* string

---

##### `Details`<sup>Required</sup> <a name="Details" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.details"></a>

```csharp
public bool|IResolvable Details { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `DiscardHeaders`<sup>Required</sup> <a name="DiscardHeaders" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.discardHeaders"></a>

```csharp
public bool|IResolvable DiscardHeaders { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Follow`<sup>Required</sup> <a name="Follow" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.follow"></a>

```csharp
public bool|IResolvable Follow { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `LogsListStringEnabled`<sup>Required</sup> <a name="LogsListStringEnabled" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.logsListStringEnabled"></a>

```csharp
public bool|IResolvable LogsListStringEnabled { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `ShowStderr`<sup>Required</sup> <a name="ShowStderr" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStderr"></a>

```csharp
public bool|IResolvable ShowStderr { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `ShowStdout`<sup>Required</sup> <a name="ShowStdout" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.showStdout"></a>

```csharp
public bool|IResolvable ShowStdout { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Since`<sup>Required</sup> <a name="Since" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.since"></a>

```csharp
public string Since { get; }
```

- *Type:* string

---

##### `Tail`<sup>Required</sup> <a name="Tail" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.tail"></a>

```csharp
public string Tail { get; }
```

- *Type:* string

---

##### `Timestamps`<sup>Required</sup> <a name="Timestamps" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.timestamps"></a>

```csharp
public bool|IResolvable Timestamps { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Until`<sup>Required</sup> <a name="Until" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.until"></a>

```csharp
public string Until { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogs.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataDockerLogsConfig <a name="DataDockerLogsConfig" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new DataDockerLogsConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string Name,
    bool|IResolvable Details = null,
    bool|IResolvable DiscardHeaders = null,
    bool|IResolvable Follow = null,
    string Id = null,
    bool|IResolvable LogsListStringEnabled = null,
    bool|IResolvable ShowStderr = null,
    bool|IResolvable ShowStdout = null,
    string Since = null,
    string Tail = null,
    bool|IResolvable Timestamps = null,
    string Until = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.name">Name</a></code> | <code>string</code> | The name of the Docker Container. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.details">Details</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#details DataDockerLogs#details}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.discardHeaders">DiscardHeaders</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Discard headers that docker appends to each log entry. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.follow">Follow</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#follow DataDockerLogs#follow}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#id DataDockerLogs#id}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.logsListStringEnabled">LogsListStringEnabled</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true populate computed value `logs_list_string`. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.showStderr">ShowStderr</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#show_stderr DataDockerLogs#show_stderr}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.showStdout">ShowStdout</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#show_stdout DataDockerLogs#show_stdout}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.since">Since</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#since DataDockerLogs#since}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.tail">Tail</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#tail DataDockerLogs#tail}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.timestamps">Timestamps</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#timestamps DataDockerLogs#timestamps}. |
| <code><a href="#@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.until">Until</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#until DataDockerLogs#until}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the Docker Container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#name DataDockerLogs#name}

---

##### `Details`<sup>Optional</sup> <a name="Details" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.details"></a>

```csharp
public bool|IResolvable Details { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#details DataDockerLogs#details}.

---

##### `DiscardHeaders`<sup>Optional</sup> <a name="DiscardHeaders" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.discardHeaders"></a>

```csharp
public bool|IResolvable DiscardHeaders { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Discard headers that docker appends to each log entry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#discard_headers DataDockerLogs#discard_headers}

---

##### `Follow`<sup>Optional</sup> <a name="Follow" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.follow"></a>

```csharp
public bool|IResolvable Follow { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#follow DataDockerLogs#follow}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#id DataDockerLogs#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `LogsListStringEnabled`<sup>Optional</sup> <a name="LogsListStringEnabled" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.logsListStringEnabled"></a>

```csharp
public bool|IResolvable LogsListStringEnabled { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true populate computed value `logs_list_string`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#logs_list_string_enabled DataDockerLogs#logs_list_string_enabled}

---

##### `ShowStderr`<sup>Optional</sup> <a name="ShowStderr" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.showStderr"></a>

```csharp
public bool|IResolvable ShowStderr { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#show_stderr DataDockerLogs#show_stderr}.

---

##### `ShowStdout`<sup>Optional</sup> <a name="ShowStdout" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.showStdout"></a>

```csharp
public bool|IResolvable ShowStdout { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#show_stdout DataDockerLogs#show_stdout}.

---

##### `Since`<sup>Optional</sup> <a name="Since" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.since"></a>

```csharp
public string Since { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#since DataDockerLogs#since}.

---

##### `Tail`<sup>Optional</sup> <a name="Tail" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.tail"></a>

```csharp
public string Tail { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#tail DataDockerLogs#tail}.

---

##### `Timestamps`<sup>Optional</sup> <a name="Timestamps" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.timestamps"></a>

```csharp
public bool|IResolvable Timestamps { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#timestamps DataDockerLogs#timestamps}.

---

##### `Until`<sup>Optional</sup> <a name="Until" id="@cdktn/provider-docker.dataDockerLogs.DataDockerLogsConfig.property.until"></a>

```csharp
public string Until { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/logs#until DataDockerLogs#until}.

---



