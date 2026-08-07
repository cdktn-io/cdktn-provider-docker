# `compose` Submodule <a name="`compose` Submodule" id="@cdktn/provider-docker.compose"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Compose <a name="Compose" id="@cdktn/provider-docker.compose.Compose"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose docker_compose}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.compose.Compose.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new Compose(Construct Scope, string Id, ComposeConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.compose.ComposeConfig">ComposeConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.compose.ComposeConfig">ComposeConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetEnvFiles">ResetEnvFiles</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProfiles">ResetProfiles</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProjectDirectory">ResetProjectDirectory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProjectName">ResetProjectName</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetRemoveOrphans">ResetRemoveOrphans</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetWait">ResetWait</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetWaitTimeout">ResetWaitTimeout</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.compose.Compose.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.compose.Compose.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.compose.Compose.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.compose.Compose.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.compose.Compose.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.compose.Compose.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.compose.Compose.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.compose.Compose.hasResourceMove"></a>

```csharp
private TerraformResourceMoveByTarget|TerraformResourceMoveById HasResourceMove()
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.compose.Compose.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.compose.Compose.moveFromId"></a>

```csharp
private void MoveFromId(string Id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.compose.Compose.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.compose.Compose.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, string|double Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.index"></a>

- *Type:* string|double

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.compose.Compose.moveToId"></a>

```csharp
private void MoveToId(string Id)
```

Moves this resource to the resource corresponding to "id".

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.compose.Compose.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `ResetEnvFiles` <a name="ResetEnvFiles" id="@cdktn/provider-docker.compose.Compose.resetEnvFiles"></a>

```csharp
private void ResetEnvFiles()
```

##### `ResetProfiles` <a name="ResetProfiles" id="@cdktn/provider-docker.compose.Compose.resetProfiles"></a>

```csharp
private void ResetProfiles()
```

##### `ResetProjectDirectory` <a name="ResetProjectDirectory" id="@cdktn/provider-docker.compose.Compose.resetProjectDirectory"></a>

```csharp
private void ResetProjectDirectory()
```

##### `ResetProjectName` <a name="ResetProjectName" id="@cdktn/provider-docker.compose.Compose.resetProjectName"></a>

```csharp
private void ResetProjectName()
```

##### `ResetRemoveOrphans` <a name="ResetRemoveOrphans" id="@cdktn/provider-docker.compose.Compose.resetRemoveOrphans"></a>

```csharp
private void ResetRemoveOrphans()
```

##### `ResetWait` <a name="ResetWait" id="@cdktn/provider-docker.compose.Compose.resetWait"></a>

```csharp
private void ResetWait()
```

##### `ResetWaitTimeout` <a name="ResetWaitTimeout" id="@cdktn/provider-docker.compose.Compose.resetWaitTimeout"></a>

```csharp
private void ResetWaitTimeout()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.compose.Compose.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Compose.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.compose.Compose.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.compose.Compose.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Compose.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.compose.Compose.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.compose.Compose.isTerraformResource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Compose.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.compose.Compose.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Compose.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Compose to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Compose that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the Compose to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPathsInput">ConfigPathsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFilesInput">EnvFilesInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profilesInput">ProfilesInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput">ProjectDirectoryInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectNameInput">ProjectNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphansInput">RemoveOrphansInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitInput">WaitInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput">WaitTimeoutInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPaths">ConfigPaths</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFiles">EnvFiles</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profiles">Profiles</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectory">ProjectDirectory</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectName">ProjectName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphans">RemoveOrphans</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.wait">Wait</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeout">WaitTimeout</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.compose.Compose.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.compose.Compose.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.compose.Compose.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.compose.Compose.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.compose.Compose.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.compose.Compose.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.compose.Compose.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.compose.Compose.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.compose.Compose.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.compose.Compose.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.compose.Compose.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.compose.Compose.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `ConfigPathsInput`<sup>Optional</sup> <a name="ConfigPathsInput" id="@cdktn/provider-docker.compose.Compose.property.configPathsInput"></a>

```csharp
public string[] ConfigPathsInput { get; }
```

- *Type:* string[]

---

##### `EnvFilesInput`<sup>Optional</sup> <a name="EnvFilesInput" id="@cdktn/provider-docker.compose.Compose.property.envFilesInput"></a>

```csharp
public string[] EnvFilesInput { get; }
```

- *Type:* string[]

---

##### `ProfilesInput`<sup>Optional</sup> <a name="ProfilesInput" id="@cdktn/provider-docker.compose.Compose.property.profilesInput"></a>

```csharp
public string[] ProfilesInput { get; }
```

- *Type:* string[]

---

##### `ProjectDirectoryInput`<sup>Optional</sup> <a name="ProjectDirectoryInput" id="@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput"></a>

```csharp
public string ProjectDirectoryInput { get; }
```

- *Type:* string

---

##### `ProjectNameInput`<sup>Optional</sup> <a name="ProjectNameInput" id="@cdktn/provider-docker.compose.Compose.property.projectNameInput"></a>

```csharp
public string ProjectNameInput { get; }
```

- *Type:* string

---

##### `RemoveOrphansInput`<sup>Optional</sup> <a name="RemoveOrphansInput" id="@cdktn/provider-docker.compose.Compose.property.removeOrphansInput"></a>

```csharp
public bool|IResolvable RemoveOrphansInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `WaitInput`<sup>Optional</sup> <a name="WaitInput" id="@cdktn/provider-docker.compose.Compose.property.waitInput"></a>

```csharp
public bool|IResolvable WaitInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `WaitTimeoutInput`<sup>Optional</sup> <a name="WaitTimeoutInput" id="@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput"></a>

```csharp
public string WaitTimeoutInput { get; }
```

- *Type:* string

---

##### `ConfigPaths`<sup>Required</sup> <a name="ConfigPaths" id="@cdktn/provider-docker.compose.Compose.property.configPaths"></a>

```csharp
public string[] ConfigPaths { get; }
```

- *Type:* string[]

---

##### `EnvFiles`<sup>Required</sup> <a name="EnvFiles" id="@cdktn/provider-docker.compose.Compose.property.envFiles"></a>

```csharp
public string[] EnvFiles { get; }
```

- *Type:* string[]

---

##### `Profiles`<sup>Required</sup> <a name="Profiles" id="@cdktn/provider-docker.compose.Compose.property.profiles"></a>

```csharp
public string[] Profiles { get; }
```

- *Type:* string[]

---

##### `ProjectDirectory`<sup>Required</sup> <a name="ProjectDirectory" id="@cdktn/provider-docker.compose.Compose.property.projectDirectory"></a>

```csharp
public string ProjectDirectory { get; }
```

- *Type:* string

---

##### `ProjectName`<sup>Required</sup> <a name="ProjectName" id="@cdktn/provider-docker.compose.Compose.property.projectName"></a>

```csharp
public string ProjectName { get; }
```

- *Type:* string

---

##### `RemoveOrphans`<sup>Required</sup> <a name="RemoveOrphans" id="@cdktn/provider-docker.compose.Compose.property.removeOrphans"></a>

```csharp
public bool|IResolvable RemoveOrphans { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Wait`<sup>Required</sup> <a name="Wait" id="@cdktn/provider-docker.compose.Compose.property.wait"></a>

```csharp
public bool|IResolvable Wait { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `WaitTimeout`<sup>Required</sup> <a name="WaitTimeout" id="@cdktn/provider-docker.compose.Compose.property.waitTimeout"></a>

```csharp
public string WaitTimeout { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.compose.Compose.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ComposeConfig <a name="ComposeConfig" id="@cdktn/provider-docker.compose.ComposeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.compose.ComposeConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ComposeConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string[] ConfigPaths,
    string[] EnvFiles = null,
    string[] Profiles = null,
    string ProjectDirectory = null,
    string ProjectName = null,
    bool|IResolvable RemoveOrphans = null,
    bool|IResolvable Wait = null,
    string WaitTimeout = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.configPaths">ConfigPaths</a></code> | <code>string[]</code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.envFiles">EnvFiles</a></code> | <code>string[]</code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.profiles">Profiles</a></code> | <code>string[]</code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory">ProjectDirectory</a></code> | <code>string</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectName">ProjectName</a></code> | <code>string</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans">RemoveOrphans</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.wait">Wait</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout">WaitTimeout</a></code> | <code>string</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.compose.ComposeConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.compose.ComposeConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.compose.ComposeConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.compose.ComposeConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.compose.ComposeConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `ConfigPaths`<sup>Required</sup> <a name="ConfigPaths" id="@cdktn/provider-docker.compose.ComposeConfig.property.configPaths"></a>

```csharp
public string[] ConfigPaths { get; set; }
```

- *Type:* string[]

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `EnvFiles`<sup>Optional</sup> <a name="EnvFiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.envFiles"></a>

```csharp
public string[] EnvFiles { get; set; }
```

- *Type:* string[]

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#env_files Compose#env_files}

---

##### `Profiles`<sup>Optional</sup> <a name="Profiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.profiles"></a>

```csharp
public string[] Profiles { get; set; }
```

- *Type:* string[]

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#profiles Compose#profiles}

---

##### `ProjectDirectory`<sup>Optional</sup> <a name="ProjectDirectory" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory"></a>

```csharp
public string ProjectDirectory { get; set; }
```

- *Type:* string

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `ProjectName`<sup>Optional</sup> <a name="ProjectName" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectName"></a>

```csharp
public string ProjectName { get; set; }
```

- *Type:* string

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_name Compose#project_name}

---

##### `RemoveOrphans`<sup>Optional</sup> <a name="RemoveOrphans" id="@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans"></a>

```csharp
public bool|IResolvable RemoveOrphans { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `Wait`<sup>Optional</sup> <a name="Wait" id="@cdktn/provider-docker.compose.ComposeConfig.property.wait"></a>

```csharp
public bool|IResolvable Wait { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait Compose#wait}

---

##### `WaitTimeout`<sup>Optional</sup> <a name="WaitTimeout" id="@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout"></a>

```csharp
public string WaitTimeout { get; set; }
```

- *Type:* string

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---



