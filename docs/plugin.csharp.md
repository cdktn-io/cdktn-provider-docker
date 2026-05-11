# `plugin` Submodule <a name="`plugin` Submodule" id="@cdktn/provider-docker.plugin"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Plugin <a name="Plugin" id="@cdktn/provider-docker.plugin.Plugin"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin docker_plugin}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.plugin.Plugin.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new Plugin(Construct Scope, string Id, PluginConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.plugin.PluginConfig">PluginConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.plugin.Plugin.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.plugin.Plugin.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.plugin.Plugin.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.plugin.PluginConfig">PluginConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.putGrantPermissions">PutGrantPermissions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetAlias">ResetAlias</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetEnabled">ResetEnabled</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetEnableTimeout">ResetEnableTimeout</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetEnv">ResetEnv</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetForceDestroy">ResetForceDestroy</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetForceDisable">ResetForceDisable</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetGrantAllPermissions">ResetGrantAllPermissions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetGrantPermissions">ResetGrantPermissions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.resetId">ResetId</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.plugin.Plugin.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.plugin.Plugin.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.plugin.Plugin.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.plugin.Plugin.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.plugin.Plugin.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.plugin.Plugin.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.plugin.Plugin.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.plugin.Plugin.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.plugin.Plugin.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.plugin.Plugin.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.plugin.Plugin.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.plugin.Plugin.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.plugin.Plugin.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.plugin.Plugin.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.plugin.Plugin.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.plugin.Plugin.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.plugin.Plugin.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.plugin.Plugin.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.plugin.Plugin.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.plugin.Plugin.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.plugin.Plugin.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.plugin.Plugin.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.plugin.Plugin.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.plugin.Plugin.hasResourceMove"></a>

```csharp
private TerraformResourceMoveByTarget|TerraformResourceMoveById HasResourceMove()
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.plugin.Plugin.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.plugin.Plugin.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.plugin.Plugin.importFrom.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.plugin.Plugin.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.Plugin.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.plugin.Plugin.moveFromId"></a>

```csharp
private void MoveFromId(string Id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.plugin.Plugin.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.plugin.Plugin.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, string|double Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.plugin.Plugin.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktn/provider-docker.plugin.Plugin.moveTo.parameter.index"></a>

- *Type:* string|double

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.plugin.Plugin.moveToId"></a>

```csharp
private void MoveToId(string Id)
```

Moves this resource to the resource corresponding to "id".

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.plugin.Plugin.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutGrantPermissions` <a name="PutGrantPermissions" id="@cdktn/provider-docker.plugin.Plugin.putGrantPermissions"></a>

```csharp
private void PutGrantPermissions(IResolvable|PluginGrantPermissions[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.plugin.Plugin.putGrantPermissions.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]

---

##### `ResetAlias` <a name="ResetAlias" id="@cdktn/provider-docker.plugin.Plugin.resetAlias"></a>

```csharp
private void ResetAlias()
```

##### `ResetEnabled` <a name="ResetEnabled" id="@cdktn/provider-docker.plugin.Plugin.resetEnabled"></a>

```csharp
private void ResetEnabled()
```

##### `ResetEnableTimeout` <a name="ResetEnableTimeout" id="@cdktn/provider-docker.plugin.Plugin.resetEnableTimeout"></a>

```csharp
private void ResetEnableTimeout()
```

##### `ResetEnv` <a name="ResetEnv" id="@cdktn/provider-docker.plugin.Plugin.resetEnv"></a>

```csharp
private void ResetEnv()
```

##### `ResetForceDestroy` <a name="ResetForceDestroy" id="@cdktn/provider-docker.plugin.Plugin.resetForceDestroy"></a>

```csharp
private void ResetForceDestroy()
```

##### `ResetForceDisable` <a name="ResetForceDisable" id="@cdktn/provider-docker.plugin.Plugin.resetForceDisable"></a>

```csharp
private void ResetForceDisable()
```

##### `ResetGrantAllPermissions` <a name="ResetGrantAllPermissions" id="@cdktn/provider-docker.plugin.Plugin.resetGrantAllPermissions"></a>

```csharp
private void ResetGrantAllPermissions()
```

##### `ResetGrantPermissions` <a name="ResetGrantPermissions" id="@cdktn/provider-docker.plugin.Plugin.resetGrantPermissions"></a>

```csharp
private void ResetGrantPermissions()
```

##### `ResetId` <a name="ResetId" id="@cdktn/provider-docker.plugin.Plugin.resetId"></a>

```csharp
private void ResetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a Plugin resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.plugin.Plugin.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Plugin.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.plugin.Plugin.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.plugin.Plugin.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Plugin.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.plugin.Plugin.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.plugin.Plugin.isTerraformResource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Plugin.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.plugin.Plugin.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.plugin.Plugin.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Plugin.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a Plugin resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.plugin.Plugin.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.plugin.Plugin.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Plugin to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.plugin.Plugin.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Plugin that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.plugin.Plugin.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the Plugin to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.grantPermissions">GrantPermissions</a></code> | <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList">PluginGrantPermissionsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.pluginReference">PluginReference</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.aliasInput">AliasInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.enabledInput">EnabledInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.enableTimeoutInput">EnableTimeoutInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.envInput">EnvInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.forceDestroyInput">ForceDestroyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.forceDisableInput">ForceDisableInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.grantAllPermissionsInput">GrantAllPermissionsInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.grantPermissionsInput">GrantPermissionsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.alias">Alias</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.enabled">Enabled</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.enableTimeout">EnableTimeout</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.env">Env</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.forceDestroy">ForceDestroy</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.forceDisable">ForceDisable</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.grantAllPermissions">GrantAllPermissions</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.name">Name</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.plugin.Plugin.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.plugin.Plugin.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.plugin.Plugin.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.plugin.Plugin.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.plugin.Plugin.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.plugin.Plugin.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.plugin.Plugin.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.plugin.Plugin.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.plugin.Plugin.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.plugin.Plugin.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.plugin.Plugin.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.plugin.Plugin.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.plugin.Plugin.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.plugin.Plugin.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `GrantPermissions`<sup>Required</sup> <a name="GrantPermissions" id="@cdktn/provider-docker.plugin.Plugin.property.grantPermissions"></a>

```csharp
public PluginGrantPermissionsList GrantPermissions { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList">PluginGrantPermissionsList</a>

---

##### `PluginReference`<sup>Required</sup> <a name="PluginReference" id="@cdktn/provider-docker.plugin.Plugin.property.pluginReference"></a>

```csharp
public string PluginReference { get; }
```

- *Type:* string

---

##### `AliasInput`<sup>Optional</sup> <a name="AliasInput" id="@cdktn/provider-docker.plugin.Plugin.property.aliasInput"></a>

```csharp
public string AliasInput { get; }
```

- *Type:* string

---

##### `EnabledInput`<sup>Optional</sup> <a name="EnabledInput" id="@cdktn/provider-docker.plugin.Plugin.property.enabledInput"></a>

```csharp
public bool|IResolvable EnabledInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `EnableTimeoutInput`<sup>Optional</sup> <a name="EnableTimeoutInput" id="@cdktn/provider-docker.plugin.Plugin.property.enableTimeoutInput"></a>

```csharp
public double EnableTimeoutInput { get; }
```

- *Type:* double

---

##### `EnvInput`<sup>Optional</sup> <a name="EnvInput" id="@cdktn/provider-docker.plugin.Plugin.property.envInput"></a>

```csharp
public string[] EnvInput { get; }
```

- *Type:* string[]

---

##### `ForceDestroyInput`<sup>Optional</sup> <a name="ForceDestroyInput" id="@cdktn/provider-docker.plugin.Plugin.property.forceDestroyInput"></a>

```csharp
public bool|IResolvable ForceDestroyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `ForceDisableInput`<sup>Optional</sup> <a name="ForceDisableInput" id="@cdktn/provider-docker.plugin.Plugin.property.forceDisableInput"></a>

```csharp
public bool|IResolvable ForceDisableInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `GrantAllPermissionsInput`<sup>Optional</sup> <a name="GrantAllPermissionsInput" id="@cdktn/provider-docker.plugin.Plugin.property.grantAllPermissionsInput"></a>

```csharp
public bool|IResolvable GrantAllPermissionsInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `GrantPermissionsInput`<sup>Optional</sup> <a name="GrantPermissionsInput" id="@cdktn/provider-docker.plugin.Plugin.property.grantPermissionsInput"></a>

```csharp
public IResolvable|PluginGrantPermissions[] GrantPermissionsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.plugin.Plugin.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.plugin.Plugin.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `Alias`<sup>Required</sup> <a name="Alias" id="@cdktn/provider-docker.plugin.Plugin.property.alias"></a>

```csharp
public string Alias { get; }
```

- *Type:* string

---

##### `Enabled`<sup>Required</sup> <a name="Enabled" id="@cdktn/provider-docker.plugin.Plugin.property.enabled"></a>

```csharp
public bool|IResolvable Enabled { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `EnableTimeout`<sup>Required</sup> <a name="EnableTimeout" id="@cdktn/provider-docker.plugin.Plugin.property.enableTimeout"></a>

```csharp
public double EnableTimeout { get; }
```

- *Type:* double

---

##### `Env`<sup>Required</sup> <a name="Env" id="@cdktn/provider-docker.plugin.Plugin.property.env"></a>

```csharp
public string[] Env { get; }
```

- *Type:* string[]

---

##### `ForceDestroy`<sup>Required</sup> <a name="ForceDestroy" id="@cdktn/provider-docker.plugin.Plugin.property.forceDestroy"></a>

```csharp
public bool|IResolvable ForceDestroy { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `ForceDisable`<sup>Required</sup> <a name="ForceDisable" id="@cdktn/provider-docker.plugin.Plugin.property.forceDisable"></a>

```csharp
public bool|IResolvable ForceDisable { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `GrantAllPermissions`<sup>Required</sup> <a name="GrantAllPermissions" id="@cdktn/provider-docker.plugin.Plugin.property.grantAllPermissions"></a>

```csharp
public bool|IResolvable GrantAllPermissions { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.plugin.Plugin.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.plugin.Plugin.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.Plugin.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.plugin.Plugin.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### PluginConfig <a name="PluginConfig" id="@cdktn/provider-docker.plugin.PluginConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.plugin.PluginConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new PluginConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string Name,
    string Alias = null,
    bool|IResolvable Enabled = null,
    double EnableTimeout = null,
    string[] Env = null,
    bool|IResolvable ForceDestroy = null,
    bool|IResolvable ForceDisable = null,
    bool|IResolvable GrantAllPermissions = null,
    IResolvable|PluginGrantPermissions[] GrantPermissions = null,
    string Id = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.name">Name</a></code> | <code>string</code> | Docker Plugin name. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.alias">Alias</a></code> | <code>string</code> | Docker Plugin alias. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.enabled">Enabled</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true` the plugin is enabled. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.enableTimeout">EnableTimeout</a></code> | <code>double</code> | HTTP client timeout to enable the plugin. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.env">Env</a></code> | <code>string[]</code> | The environment variables in the form of `KEY=VALUE`, e.g. `DEBUG=0`. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.forceDestroy">ForceDestroy</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true, then the plugin is destroyed forcibly. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.forceDisable">ForceDisable</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true, then the plugin is disabled forcibly. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.grantAllPermissions">GrantAllPermissions</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true, grant all permissions necessary to run the plugin. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.grantPermissions">GrantPermissions</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]</code> | grant_permissions block. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#id Plugin#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.plugin.PluginConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.plugin.PluginConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.plugin.PluginConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.plugin.PluginConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.plugin.PluginConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.plugin.PluginConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.plugin.PluginConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.plugin.PluginConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Docker Plugin name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#name Plugin#name}

---

##### `Alias`<sup>Optional</sup> <a name="Alias" id="@cdktn/provider-docker.plugin.PluginConfig.property.alias"></a>

```csharp
public string Alias { get; set; }
```

- *Type:* string

Docker Plugin alias.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#alias Plugin#alias}

---

##### `Enabled`<sup>Optional</sup> <a name="Enabled" id="@cdktn/provider-docker.plugin.PluginConfig.property.enabled"></a>

```csharp
public bool|IResolvable Enabled { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true` the plugin is enabled. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#enabled Plugin#enabled}

---

##### `EnableTimeout`<sup>Optional</sup> <a name="EnableTimeout" id="@cdktn/provider-docker.plugin.PluginConfig.property.enableTimeout"></a>

```csharp
public double EnableTimeout { get; set; }
```

- *Type:* double

HTTP client timeout to enable the plugin.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#enable_timeout Plugin#enable_timeout}

---

##### `Env`<sup>Optional</sup> <a name="Env" id="@cdktn/provider-docker.plugin.PluginConfig.property.env"></a>

```csharp
public string[] Env { get; set; }
```

- *Type:* string[]

The environment variables in the form of `KEY=VALUE`, e.g. `DEBUG=0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#env Plugin#env}

---

##### `ForceDestroy`<sup>Optional</sup> <a name="ForceDestroy" id="@cdktn/provider-docker.plugin.PluginConfig.property.forceDestroy"></a>

```csharp
public bool|IResolvable ForceDestroy { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true, then the plugin is destroyed forcibly.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#force_destroy Plugin#force_destroy}

---

##### `ForceDisable`<sup>Optional</sup> <a name="ForceDisable" id="@cdktn/provider-docker.plugin.PluginConfig.property.forceDisable"></a>

```csharp
public bool|IResolvable ForceDisable { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true, then the plugin is disabled forcibly.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#force_disable Plugin#force_disable}

---

##### `GrantAllPermissions`<sup>Optional</sup> <a name="GrantAllPermissions" id="@cdktn/provider-docker.plugin.PluginConfig.property.grantAllPermissions"></a>

```csharp
public bool|IResolvable GrantAllPermissions { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true, grant all permissions necessary to run the plugin.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#grant_all_permissions Plugin#grant_all_permissions}

---

##### `GrantPermissions`<sup>Optional</sup> <a name="GrantPermissions" id="@cdktn/provider-docker.plugin.PluginConfig.property.grantPermissions"></a>

```csharp
public IResolvable|PluginGrantPermissions[] GrantPermissions { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]

grant_permissions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#grant_permissions Plugin#grant_permissions}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktn/provider-docker.plugin.PluginConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#id Plugin#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### PluginGrantPermissions <a name="PluginGrantPermissions" id="@cdktn/provider-docker.plugin.PluginGrantPermissions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.plugin.PluginGrantPermissions.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new PluginGrantPermissions {
    string Name,
    string[] Value
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions.property.name">Name</a></code> | <code>string</code> | The name of the permission. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions.property.value">Value</a></code> | <code>string[]</code> | The value of the permission. |

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.plugin.PluginGrantPermissions.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the permission.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#name Plugin#name}

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.plugin.PluginGrantPermissions.property.value"></a>

```csharp
public string[] Value { get; set; }
```

- *Type:* string[]

The value of the permission.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/plugin#value Plugin#value}

---

## Classes <a name="Classes" id="Classes"></a>

### PluginGrantPermissionsList <a name="PluginGrantPermissionsList" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new PluginGrantPermissionsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.get"></a>

```csharp
private PluginGrantPermissionsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsList.property.internalValue"></a>

```csharp
public IResolvable|PluginGrantPermissions[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>[]

---


### PluginGrantPermissionsOutputReference <a name="PluginGrantPermissionsOutputReference" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new PluginGrantPermissionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.valueInput">ValueInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.value">Value</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `ValueInput`<sup>Optional</sup> <a name="ValueInput" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.valueInput"></a>

```csharp
public string[] ValueInput { get; }
```

- *Type:* string[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.value"></a>

```csharp
public string[] Value { get; }
```

- *Type:* string[]

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.plugin.PluginGrantPermissionsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|PluginGrantPermissions InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.plugin.PluginGrantPermissions">PluginGrantPermissions</a>

---



