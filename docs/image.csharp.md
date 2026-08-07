# `image` Submodule <a name="`image` Submodule" id="@cdktn/provider-docker.image"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Image <a name="Image" id="@cdktn/provider-docker.image.Image"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image docker_image}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.Image.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new Image(Construct Scope, string Id, ImageConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.Image.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.image.Image.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.image.Image.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageConfig">ImageConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.image.Image.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.Image.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.image.Image.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.image.ImageConfig">ImageConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.Image.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.image.Image.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.image.Image.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.image.Image.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.image.Image.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.image.Image.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.image.Image.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.image.Image.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.image.Image.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.image.Image.putBuildAttribute">PutBuildAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.putTimeouts">PutTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetBuildAttribute">ResetBuildAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetForceRemove">ResetForceRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetKeepLocally">ResetKeepLocally</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetPlatform">ResetPlatform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetPullTriggers">ResetPullTriggers</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetTimeouts">ResetTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.resetTriggers">ResetTriggers</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.Image.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.image.Image.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.image.Image.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.image.Image.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.image.Image.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.image.Image.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.image.Image.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.image.Image.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.image.Image.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.image.Image.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.image.Image.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.image.Image.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.image.Image.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.image.Image.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.image.Image.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.image.Image.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.image.Image.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.image.Image.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.image.Image.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.image.Image.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.image.Image.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.image.Image.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.image.Image.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.image.Image.hasResourceMove"></a>

```csharp
private TerraformResourceMoveByTarget|TerraformResourceMoveById HasResourceMove()
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.image.Image.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.Image.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.image.Image.importFrom.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.image.Image.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.Image.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.image.Image.moveFromId"></a>

```csharp
private void MoveFromId(string Id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.Image.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.image.Image.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, string|double Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.image.Image.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktn/provider-docker.image.Image.moveTo.parameter.index"></a>

- *Type:* string|double

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.image.Image.moveToId"></a>

```csharp
private void MoveToId(string Id)
```

Moves this resource to the resource corresponding to "id".

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.Image.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutBuildAttribute` <a name="PutBuildAttribute" id="@cdktn/provider-docker.image.Image.putBuildAttribute"></a>

```csharp
private void PutBuildAttribute(ImageBuild Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.image.Image.putBuildAttribute.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a>

---

##### `PutTimeouts` <a name="PutTimeouts" id="@cdktn/provider-docker.image.Image.putTimeouts"></a>

```csharp
private void PutTimeouts(ImageTimeouts Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.image.Image.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a>

---

##### `ResetBuildAttribute` <a name="ResetBuildAttribute" id="@cdktn/provider-docker.image.Image.resetBuildAttribute"></a>

```csharp
private void ResetBuildAttribute()
```

##### `ResetForceRemove` <a name="ResetForceRemove" id="@cdktn/provider-docker.image.Image.resetForceRemove"></a>

```csharp
private void ResetForceRemove()
```

##### `ResetKeepLocally` <a name="ResetKeepLocally" id="@cdktn/provider-docker.image.Image.resetKeepLocally"></a>

```csharp
private void ResetKeepLocally()
```

##### `ResetPlatform` <a name="ResetPlatform" id="@cdktn/provider-docker.image.Image.resetPlatform"></a>

```csharp
private void ResetPlatform()
```

##### `ResetPullTriggers` <a name="ResetPullTriggers" id="@cdktn/provider-docker.image.Image.resetPullTriggers"></a>

```csharp
private void ResetPullTriggers()
```

##### `ResetTimeouts` <a name="ResetTimeouts" id="@cdktn/provider-docker.image.Image.resetTimeouts"></a>

```csharp
private void ResetTimeouts()
```

##### `ResetTriggers` <a name="ResetTriggers" id="@cdktn/provider-docker.image.Image.resetTriggers"></a>

```csharp
private void ResetTriggers()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.Image.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.image.Image.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a Image resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.image.Image.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Image.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.image.Image.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.image.Image.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Image.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.image.Image.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.image.Image.isTerraformResource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Image.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.image.Image.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.image.Image.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Image.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a Image resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.image.Image.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.image.Image.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Image to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.image.Image.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Image that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.image.Image.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the Image to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.Image.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.image.Image.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.buildAttribute">BuildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference">ImageBuildOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.imageId">ImageId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.repoDigest">RepoDigest</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference">ImageTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.buildAttributeInput">BuildAttributeInput</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.forceRemoveInput">ForceRemoveInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.keepLocallyInput">KeepLocallyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.platformInput">PlatformInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.pullTriggersInput">PullTriggersInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.timeoutsInput">TimeoutsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.triggersInput">TriggersInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.forceRemove">ForceRemove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.keepLocally">KeepLocally</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.platform">Platform</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.pullTriggers">PullTriggers</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.Image.property.triggers">Triggers</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.image.Image.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.image.Image.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.Image.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.image.Image.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.image.Image.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.image.Image.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.image.Image.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.image.Image.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.image.Image.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.image.Image.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.image.Image.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.image.Image.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.image.Image.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.image.Image.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `BuildAttribute`<sup>Required</sup> <a name="BuildAttribute" id="@cdktn/provider-docker.image.Image.property.buildAttribute"></a>

```csharp
public ImageBuildOutputReference BuildAttribute { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuildOutputReference">ImageBuildOutputReference</a>

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.Image.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `ImageId`<sup>Required</sup> <a name="ImageId" id="@cdktn/provider-docker.image.Image.property.imageId"></a>

```csharp
public string ImageId { get; }
```

- *Type:* string

---

##### `RepoDigest`<sup>Required</sup> <a name="RepoDigest" id="@cdktn/provider-docker.image.Image.property.repoDigest"></a>

```csharp
public string RepoDigest { get; }
```

- *Type:* string

---

##### `Timeouts`<sup>Required</sup> <a name="Timeouts" id="@cdktn/provider-docker.image.Image.property.timeouts"></a>

```csharp
public ImageTimeoutsOutputReference Timeouts { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference">ImageTimeoutsOutputReference</a>

---

##### `BuildAttributeInput`<sup>Optional</sup> <a name="BuildAttributeInput" id="@cdktn/provider-docker.image.Image.property.buildAttributeInput"></a>

```csharp
public ImageBuild BuildAttributeInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a>

---

##### `ForceRemoveInput`<sup>Optional</sup> <a name="ForceRemoveInput" id="@cdktn/provider-docker.image.Image.property.forceRemoveInput"></a>

```csharp
public bool|IResolvable ForceRemoveInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `KeepLocallyInput`<sup>Optional</sup> <a name="KeepLocallyInput" id="@cdktn/provider-docker.image.Image.property.keepLocallyInput"></a>

```csharp
public bool|IResolvable KeepLocallyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.image.Image.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `PlatformInput`<sup>Optional</sup> <a name="PlatformInput" id="@cdktn/provider-docker.image.Image.property.platformInput"></a>

```csharp
public string PlatformInput { get; }
```

- *Type:* string

---

##### `PullTriggersInput`<sup>Optional</sup> <a name="PullTriggersInput" id="@cdktn/provider-docker.image.Image.property.pullTriggersInput"></a>

```csharp
public string[] PullTriggersInput { get; }
```

- *Type:* string[]

---

##### `TimeoutsInput`<sup>Optional</sup> <a name="TimeoutsInput" id="@cdktn/provider-docker.image.Image.property.timeoutsInput"></a>

```csharp
public IResolvable|ImageTimeouts TimeoutsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a>

---

##### `TriggersInput`<sup>Optional</sup> <a name="TriggersInput" id="@cdktn/provider-docker.image.Image.property.triggersInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> TriggersInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `ForceRemove`<sup>Required</sup> <a name="ForceRemove" id="@cdktn/provider-docker.image.Image.property.forceRemove"></a>

```csharp
public bool|IResolvable ForceRemove { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `KeepLocally`<sup>Required</sup> <a name="KeepLocally" id="@cdktn/provider-docker.image.Image.property.keepLocally"></a>

```csharp
public bool|IResolvable KeepLocally { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.image.Image.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Platform`<sup>Required</sup> <a name="Platform" id="@cdktn/provider-docker.image.Image.property.platform"></a>

```csharp
public string Platform { get; }
```

- *Type:* string

---

##### `PullTriggers`<sup>Required</sup> <a name="PullTriggers" id="@cdktn/provider-docker.image.Image.property.pullTriggers"></a>

```csharp
public string[] PullTriggers { get; }
```

- *Type:* string[]

---

##### `Triggers`<sup>Required</sup> <a name="Triggers" id="@cdktn/provider-docker.image.Image.property.triggers"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Triggers { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.Image.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.image.Image.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ImageBuild <a name="ImageBuild" id="@cdktn/provider-docker.image.ImageBuild"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.image.ImageBuild.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuild {
    string Context,
    string[] AdditionalContexts = null,
    IResolvable|ImageBuildAuthConfig[] AuthConfig = null,
    System.Collections.Generic.IDictionary<string, string> BuildArgs = null,
    string Builder = null,
    string BuildId = null,
    string BuildLogFile = null,
    string[] CacheFrom = null,
    string[] CacheTo = null,
    string CgroupParent = null,
    double CpuPeriod = null,
    double CpuQuota = null,
    string CpuSetCpus = null,
    string CpuSetMems = null,
    double CpuShares = null,
    string Dockerfile = null,
    string[] ExtraHosts = null,
    bool|IResolvable ForceRemove = null,
    string Isolation = null,
    System.Collections.Generic.IDictionary<string, string> Label = null,
    System.Collections.Generic.IDictionary<string, string> Labels = null,
    double Memory = null,
    double MemorySwap = null,
    string NetworkMode = null,
    bool|IResolvable NoCache = null,
    string Platform = null,
    string Provenance = null,
    bool|IResolvable PullParent = null,
    string RemoteContext = null,
    bool|IResolvable Remove = null,
    string Sbom = null,
    IResolvable|ImageBuildSecrets[] Secrets = null,
    string[] SecurityOpt = null,
    string SessionId = null,
    double ShmSize = null,
    bool|IResolvable Squash = null,
    bool|IResolvable SuppressOutput = null,
    string[] Tag = null,
    string Target = null,
    IResolvable|ImageBuildUlimit[] Ulimit = null,
    bool|IResolvable UseLegacyBuilder = null,
    string Version = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.context">Context</a></code> | <code>string</code> | Value to specify the build context. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.additionalContexts">AdditionalContexts</a></code> | <code>string[]</code> | A list of additional build contexts. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.authConfig">AuthConfig</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]</code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.buildArgs">BuildArgs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.builder">Builder</a></code> | <code>string</code> | The name of the buildx builder to use. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.buildId">BuildId</a></code> | <code>string</code> | BuildID is an optional identifier that can be passed together with the build request. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.buildLogFile">BuildLogFile</a></code> | <code>string</code> | Path to a file where the buildx log are written to. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cacheFrom">CacheFrom</a></code> | <code>string[]</code> | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cacheTo">CacheTo</a></code> | <code>string[]</code> | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cgroupParent">CgroupParent</a></code> | <code>string</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cpuPeriod">CpuPeriod</a></code> | <code>double</code> | The length of a CPU period in microseconds. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cpuQuota">CpuQuota</a></code> | <code>double</code> | Microseconds of CPU time that the container can get in a CPU period. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cpuSetCpus">CpuSetCpus</a></code> | <code>string</code> | CPUs in which to allow execution (e.g., `0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cpuSetMems">CpuSetMems</a></code> | <code>string</code> | MEMs in which to allow execution (`0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.cpuShares">CpuShares</a></code> | <code>double</code> | CPU shares (relative weight). |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.dockerfile">Dockerfile</a></code> | <code>string</code> | Name of the Dockerfile. Defaults to `Dockerfile`. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.extraHosts">ExtraHosts</a></code> | <code>string[]</code> | A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"]. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.forceRemove">ForceRemove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Always remove intermediate containers. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.isolation">Isolation</a></code> | <code>string</code> | Isolation represents the isolation technology of a container. The supported values are. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.label">Label</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Set metadata for an image. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.labels">Labels</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | User-defined key/value metadata. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.memory">Memory</a></code> | <code>double</code> | Set memory limit for build. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.memorySwap">MemorySwap</a></code> | <code>double</code> | Total memory (memory + swap), -1 to enable unlimited swap. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.networkMode">NetworkMode</a></code> | <code>string</code> | Set the networking mode for the RUN instructions during build. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.noCache">NoCache</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Do not use the cache when building the image. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.platform">Platform</a></code> | <code>string</code> | Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform). |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.provenance">Provenance</a></code> | <code>string</code> | Set provenance attestation for the build. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.pullParent">PullParent</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Attempt to pull the image even if an older image exists locally. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.remoteContext">RemoteContext</a></code> | <code>string</code> | A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.remove">Remove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Remove intermediate containers after a successful build. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.sbom">Sbom</a></code> | <code>string</code> | Set SBOM (Software Bill of Materials) attestation for the build. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.secrets">Secrets</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]</code> | secrets block. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.securityOpt">SecurityOpt</a></code> | <code>string[]</code> | The security options. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.sessionId">SessionId</a></code> | <code>string</code> | Set an ID for the build session. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.shmSize">ShmSize</a></code> | <code>double</code> | Size of /dev/shm in bytes. The size must be greater than 0. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.squash">Squash</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true the new layers are squashed into a new image with a single new layer. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.suppressOutput">SuppressOutput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Suppress the build output and print image ID on success. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.tag">Tag</a></code> | <code>string[]</code> | Name and optionally a tag in the 'name:tag' format. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.target">Target</a></code> | <code>string</code> | Set the target build stage to build. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.ulimit">Ulimit</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]</code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.useLegacyBuilder">UseLegacyBuilder</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuild.property.version">Version</a></code> | <code>string</code> | Version of the underlying builder to use. |

---

##### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuild.property.context"></a>

```csharp
public string Context { get; set; }
```

- *Type:* string

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#context Image#context}

---

##### `AdditionalContexts`<sup>Optional</sup> <a name="AdditionalContexts" id="@cdktn/provider-docker.image.ImageBuild.property.additionalContexts"></a>

```csharp
public string[] AdditionalContexts { get; set; }
```

- *Type:* string[]

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#additional_contexts Image#additional_contexts}

---

##### `AuthConfig`<sup>Optional</sup> <a name="AuthConfig" id="@cdktn/provider-docker.image.ImageBuild.property.authConfig"></a>

```csharp
public IResolvable|ImageBuildAuthConfig[] AuthConfig { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#auth_config Image#auth_config}

---

##### `BuildArgs`<sup>Optional</sup> <a name="BuildArgs" id="@cdktn/provider-docker.image.ImageBuild.property.buildArgs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> BuildArgs { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#build_args Image#build_args}

---

##### `Builder`<sup>Optional</sup> <a name="Builder" id="@cdktn/provider-docker.image.ImageBuild.property.builder"></a>

```csharp
public string Builder { get; set; }
```

- *Type:* string

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#builder Image#builder}

---

##### `BuildId`<sup>Optional</sup> <a name="BuildId" id="@cdktn/provider-docker.image.ImageBuild.property.buildId"></a>

```csharp
public string BuildId { get; set; }
```

- *Type:* string

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#build_id Image#build_id}

---

##### `BuildLogFile`<sup>Optional</sup> <a name="BuildLogFile" id="@cdktn/provider-docker.image.ImageBuild.property.buildLogFile"></a>

```csharp
public string BuildLogFile { get; set; }
```

- *Type:* string

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#build_log_file Image#build_log_file}

---

##### `CacheFrom`<sup>Optional</sup> <a name="CacheFrom" id="@cdktn/provider-docker.image.ImageBuild.property.cacheFrom"></a>

```csharp
public string[] CacheFrom { get; set; }
```

- *Type:* string[]

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cache_from Image#cache_from}

---

##### `CacheTo`<sup>Optional</sup> <a name="CacheTo" id="@cdktn/provider-docker.image.ImageBuild.property.cacheTo"></a>

```csharp
public string[] CacheTo { get; set; }
```

- *Type:* string[]

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cache_to Image#cache_to}

---

##### `CgroupParent`<sup>Optional</sup> <a name="CgroupParent" id="@cdktn/provider-docker.image.ImageBuild.property.cgroupParent"></a>

```csharp
public string CgroupParent { get; set; }
```

- *Type:* string

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cgroup_parent Image#cgroup_parent}

---

##### `CpuPeriod`<sup>Optional</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.image.ImageBuild.property.cpuPeriod"></a>

```csharp
public double CpuPeriod { get; set; }
```

- *Type:* double

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cpu_period Image#cpu_period}

---

##### `CpuQuota`<sup>Optional</sup> <a name="CpuQuota" id="@cdktn/provider-docker.image.ImageBuild.property.cpuQuota"></a>

```csharp
public double CpuQuota { get; set; }
```

- *Type:* double

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cpu_quota Image#cpu_quota}

---

##### `CpuSetCpus`<sup>Optional</sup> <a name="CpuSetCpus" id="@cdktn/provider-docker.image.ImageBuild.property.cpuSetCpus"></a>

```csharp
public string CpuSetCpus { get; set; }
```

- *Type:* string

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cpu_set_cpus Image#cpu_set_cpus}

---

##### `CpuSetMems`<sup>Optional</sup> <a name="CpuSetMems" id="@cdktn/provider-docker.image.ImageBuild.property.cpuSetMems"></a>

```csharp
public string CpuSetMems { get; set; }
```

- *Type:* string

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cpu_set_mems Image#cpu_set_mems}

---

##### `CpuShares`<sup>Optional</sup> <a name="CpuShares" id="@cdktn/provider-docker.image.ImageBuild.property.cpuShares"></a>

```csharp
public double CpuShares { get; set; }
```

- *Type:* double

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#cpu_shares Image#cpu_shares}

---

##### `Dockerfile`<sup>Optional</sup> <a name="Dockerfile" id="@cdktn/provider-docker.image.ImageBuild.property.dockerfile"></a>

```csharp
public string Dockerfile { get; set; }
```

- *Type:* string

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#dockerfile Image#dockerfile}

---

##### `ExtraHosts`<sup>Optional</sup> <a name="ExtraHosts" id="@cdktn/provider-docker.image.ImageBuild.property.extraHosts"></a>

```csharp
public string[] ExtraHosts { get; set; }
```

- *Type:* string[]

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#extra_hosts Image#extra_hosts}

---

##### `ForceRemove`<sup>Optional</sup> <a name="ForceRemove" id="@cdktn/provider-docker.image.ImageBuild.property.forceRemove"></a>

```csharp
public bool|IResolvable ForceRemove { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#force_remove Image#force_remove}

---

##### `Isolation`<sup>Optional</sup> <a name="Isolation" id="@cdktn/provider-docker.image.ImageBuild.property.isolation"></a>

```csharp
public string Isolation { get; set; }
```

- *Type:* string

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#isolation Image#isolation}

---

##### `Label`<sup>Optional</sup> <a name="Label" id="@cdktn/provider-docker.image.ImageBuild.property.label"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Label { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#label Image#label}

---

##### `Labels`<sup>Optional</sup> <a name="Labels" id="@cdktn/provider-docker.image.ImageBuild.property.labels"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Labels { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#labels Image#labels}

---

##### `Memory`<sup>Optional</sup> <a name="Memory" id="@cdktn/provider-docker.image.ImageBuild.property.memory"></a>

```csharp
public double Memory { get; set; }
```

- *Type:* double

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#memory Image#memory}

---

##### `MemorySwap`<sup>Optional</sup> <a name="MemorySwap" id="@cdktn/provider-docker.image.ImageBuild.property.memorySwap"></a>

```csharp
public double MemorySwap { get; set; }
```

- *Type:* double

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#memory_swap Image#memory_swap}

---

##### `NetworkMode`<sup>Optional</sup> <a name="NetworkMode" id="@cdktn/provider-docker.image.ImageBuild.property.networkMode"></a>

```csharp
public string NetworkMode { get; set; }
```

- *Type:* string

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#network_mode Image#network_mode}

---

##### `NoCache`<sup>Optional</sup> <a name="NoCache" id="@cdktn/provider-docker.image.ImageBuild.property.noCache"></a>

```csharp
public bool|IResolvable NoCache { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#no_cache Image#no_cache}

---

##### `Platform`<sup>Optional</sup> <a name="Platform" id="@cdktn/provider-docker.image.ImageBuild.property.platform"></a>

```csharp
public string Platform { get; set; }
```

- *Type:* string

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#platform Image#platform}

---

##### `Provenance`<sup>Optional</sup> <a name="Provenance" id="@cdktn/provider-docker.image.ImageBuild.property.provenance"></a>

```csharp
public string Provenance { get; set; }
```

- *Type:* string

Set provenance attestation for the build.

BuildKit v0.11+ adds provenance attestations by default, which creates OCI image manifests that some registries (like AWS Lambda) don't support. Set to `false` to disable. Valid values: `false`, `true`, `min`, `max`, `mode=min`, `mode=max`, or a full provenance specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#provenance Image#provenance}

---

##### `PullParent`<sup>Optional</sup> <a name="PullParent" id="@cdktn/provider-docker.image.ImageBuild.property.pullParent"></a>

```csharp
public bool|IResolvable PullParent { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#pull_parent Image#pull_parent}

---

##### `RemoteContext`<sup>Optional</sup> <a name="RemoteContext" id="@cdktn/provider-docker.image.ImageBuild.property.remoteContext"></a>

```csharp
public string RemoteContext { get; set; }
```

- *Type:* string

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#remote_context Image#remote_context}

---

##### `Remove`<sup>Optional</sup> <a name="Remove" id="@cdktn/provider-docker.image.ImageBuild.property.remove"></a>

```csharp
public bool|IResolvable Remove { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#remove Image#remove}

---

##### `Sbom`<sup>Optional</sup> <a name="Sbom" id="@cdktn/provider-docker.image.ImageBuild.property.sbom"></a>

```csharp
public string Sbom { get; set; }
```

- *Type:* string

Set SBOM (Software Bill of Materials) attestation for the build.

Set to `false` to disable. Valid values: `false`, `true`, or a full SBOM specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#sbom Image#sbom}

---

##### `Secrets`<sup>Optional</sup> <a name="Secrets" id="@cdktn/provider-docker.image.ImageBuild.property.secrets"></a>

```csharp
public IResolvable|ImageBuildSecrets[] Secrets { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#secrets Image#secrets}

---

##### `SecurityOpt`<sup>Optional</sup> <a name="SecurityOpt" id="@cdktn/provider-docker.image.ImageBuild.property.securityOpt"></a>

```csharp
public string[] SecurityOpt { get; set; }
```

- *Type:* string[]

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#security_opt Image#security_opt}

---

##### `SessionId`<sup>Optional</sup> <a name="SessionId" id="@cdktn/provider-docker.image.ImageBuild.property.sessionId"></a>

```csharp
public string SessionId { get; set; }
```

- *Type:* string

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#session_id Image#session_id}

---

##### `ShmSize`<sup>Optional</sup> <a name="ShmSize" id="@cdktn/provider-docker.image.ImageBuild.property.shmSize"></a>

```csharp
public double ShmSize { get; set; }
```

- *Type:* double

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#shm_size Image#shm_size}

---

##### `Squash`<sup>Optional</sup> <a name="Squash" id="@cdktn/provider-docker.image.ImageBuild.property.squash"></a>

```csharp
public bool|IResolvable Squash { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#squash Image#squash}

---

##### `SuppressOutput`<sup>Optional</sup> <a name="SuppressOutput" id="@cdktn/provider-docker.image.ImageBuild.property.suppressOutput"></a>

```csharp
public bool|IResolvable SuppressOutput { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#suppress_output Image#suppress_output}

---

##### `Tag`<sup>Optional</sup> <a name="Tag" id="@cdktn/provider-docker.image.ImageBuild.property.tag"></a>

```csharp
public string[] Tag { get; set; }
```

- *Type:* string[]

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#tag Image#tag}

---

##### `Target`<sup>Optional</sup> <a name="Target" id="@cdktn/provider-docker.image.ImageBuild.property.target"></a>

```csharp
public string Target { get; set; }
```

- *Type:* string

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#target Image#target}

---

##### `Ulimit`<sup>Optional</sup> <a name="Ulimit" id="@cdktn/provider-docker.image.ImageBuild.property.ulimit"></a>

```csharp
public IResolvable|ImageBuildUlimit[] Ulimit { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#ulimit Image#ulimit}

---

##### `UseLegacyBuilder`<sup>Optional</sup> <a name="UseLegacyBuilder" id="@cdktn/provider-docker.image.ImageBuild.property.useLegacyBuilder"></a>

```csharp
public bool|IResolvable UseLegacyBuilder { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#use_legacy_builder Image#use_legacy_builder}

---

##### `Version`<sup>Optional</sup> <a name="Version" id="@cdktn/provider-docker.image.ImageBuild.property.version"></a>

```csharp
public string Version { get; set; }
```

- *Type:* string

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#version Image#version}

---

### ImageBuildAuthConfig <a name="ImageBuildAuthConfig" id="@cdktn/provider-docker.image.ImageBuildAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildAuthConfig {
    string HostName,
    string Auth = null,
    string Email = null,
    string IdentityToken = null,
    string Password = null,
    string RegistryToken = null,
    string ServerAddress = null,
    string UserName = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.hostName">HostName</a></code> | <code>string</code> | hostname of the registry. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.auth">Auth</a></code> | <code>string</code> | the auth token. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.email">Email</a></code> | <code>string</code> | the user emal. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.identityToken">IdentityToken</a></code> | <code>string</code> | the identity token. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.password">Password</a></code> | <code>string</code> | the registry password. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.registryToken">RegistryToken</a></code> | <code>string</code> | the registry token. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.serverAddress">ServerAddress</a></code> | <code>string</code> | the server address. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig.property.userName">UserName</a></code> | <code>string</code> | the registry user name. |

---

##### `HostName`<sup>Required</sup> <a name="HostName" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.hostName"></a>

```csharp
public string HostName { get; set; }
```

- *Type:* string

hostname of the registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#host_name Image#host_name}

---

##### `Auth`<sup>Optional</sup> <a name="Auth" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.auth"></a>

```csharp
public string Auth { get; set; }
```

- *Type:* string

the auth token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#auth Image#auth}

---

##### `Email`<sup>Optional</sup> <a name="Email" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.email"></a>

```csharp
public string Email { get; set; }
```

- *Type:* string

the user emal.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#email Image#email}

---

##### `IdentityToken`<sup>Optional</sup> <a name="IdentityToken" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.identityToken"></a>

```csharp
public string IdentityToken { get; set; }
```

- *Type:* string

the identity token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#identity_token Image#identity_token}

---

##### `Password`<sup>Optional</sup> <a name="Password" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.password"></a>

```csharp
public string Password { get; set; }
```

- *Type:* string

the registry password.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#password Image#password}

---

##### `RegistryToken`<sup>Optional</sup> <a name="RegistryToken" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.registryToken"></a>

```csharp
public string RegistryToken { get; set; }
```

- *Type:* string

the registry token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#registry_token Image#registry_token}

---

##### `ServerAddress`<sup>Optional</sup> <a name="ServerAddress" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.serverAddress"></a>

```csharp
public string ServerAddress { get; set; }
```

- *Type:* string

the server address.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#server_address Image#server_address}

---

##### `UserName`<sup>Optional</sup> <a name="UserName" id="@cdktn/provider-docker.image.ImageBuildAuthConfig.property.userName"></a>

```csharp
public string UserName { get; set; }
```

- *Type:* string

the registry user name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#user_name Image#user_name}

---

### ImageBuildSecrets <a name="ImageBuildSecrets" id="@cdktn/provider-docker.image.ImageBuildSecrets"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.image.ImageBuildSecrets.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildSecrets {
    string Id,
    string Env = null,
    string Src = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecrets.property.id">Id</a></code> | <code>string</code> | ID of the secret. By default, secrets are mounted to /run/secrets/<id>. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecrets.property.env">Env</a></code> | <code>string</code> | Environment variable source of the secret. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecrets.property.src">Src</a></code> | <code>string</code> | File source of the secret. Takes precedence over `env`. |

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.ImageBuildSecrets.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

ID of the secret. By default, secrets are mounted to /run/secrets/<id>.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#id Image#id}

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Env`<sup>Optional</sup> <a name="Env" id="@cdktn/provider-docker.image.ImageBuildSecrets.property.env"></a>

```csharp
public string Env { get; set; }
```

- *Type:* string

Environment variable source of the secret.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#env Image#env}

---

##### `Src`<sup>Optional</sup> <a name="Src" id="@cdktn/provider-docker.image.ImageBuildSecrets.property.src"></a>

```csharp
public string Src { get; set; }
```

- *Type:* string

File source of the secret. Takes precedence over `env`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#src Image#src}

---

### ImageBuildUlimit <a name="ImageBuildUlimit" id="@cdktn/provider-docker.image.ImageBuildUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.image.ImageBuildUlimit.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildUlimit {
    double Hard,
    string Name,
    double Soft
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimit.property.hard">Hard</a></code> | <code>double</code> | soft limit. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimit.property.name">Name</a></code> | <code>string</code> | type of ulimit, e.g. `nofile`. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimit.property.soft">Soft</a></code> | <code>double</code> | hard limit. |

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.image.ImageBuildUlimit.property.hard"></a>

```csharp
public double Hard { get; set; }
```

- *Type:* double

soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#hard Image#hard}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.image.ImageBuildUlimit.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

type of ulimit, e.g. `nofile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#name Image#name}

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.image.ImageBuildUlimit.property.soft"></a>

```csharp
public double Soft { get; set; }
```

- *Type:* double

hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#soft Image#soft}

---

### ImageConfig <a name="ImageConfig" id="@cdktn/provider-docker.image.ImageConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.image.ImageConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string Name,
    ImageBuild BuildAttribute = null,
    bool|IResolvable ForceRemove = null,
    bool|IResolvable KeepLocally = null,
    string Platform = null,
    string[] PullTriggers = null,
    ImageTimeouts Timeouts = null,
    System.Collections.Generic.IDictionary<string, string> Triggers = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.name">Name</a></code> | <code>string</code> | The name of the Docker image, including any tags or SHA256 repo digests. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.buildAttribute">BuildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.forceRemove">ForceRemove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true, then the image is removed forcibly when the resource is destroyed. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.keepLocally">KeepLocally</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.platform">Platform</a></code> | <code>string</code> | The platform to use when pulling the image. Defaults to the platform of the current machine. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.pullTriggers">PullTriggers</a></code> | <code>string[]</code> | List of values which cause an image pull when changed. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.image.ImageConfig.property.triggers">Triggers</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | A map of arbitrary strings that, when changed, will force the `docker_image` resource to be replaced. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.image.ImageConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.image.ImageConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.image.ImageConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.image.ImageConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.image.ImageConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.image.ImageConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.image.ImageConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.image.ImageConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the Docker image, including any tags or SHA256 repo digests.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#name Image#name}

---

##### `BuildAttribute`<sup>Optional</sup> <a name="BuildAttribute" id="@cdktn/provider-docker.image.ImageConfig.property.buildAttribute"></a>

```csharp
public ImageBuild BuildAttribute { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#build Image#build}

---

##### `ForceRemove`<sup>Optional</sup> <a name="ForceRemove" id="@cdktn/provider-docker.image.ImageConfig.property.forceRemove"></a>

```csharp
public bool|IResolvable ForceRemove { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true, then the image is removed forcibly when the resource is destroyed.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#force_remove Image#force_remove}

---

##### `KeepLocally`<sup>Optional</sup> <a name="KeepLocally" id="@cdktn/provider-docker.image.ImageConfig.property.keepLocally"></a>

```csharp
public bool|IResolvable KeepLocally { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker local storage on destroy operation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#keep_locally Image#keep_locally}

---

##### `Platform`<sup>Optional</sup> <a name="Platform" id="@cdktn/provider-docker.image.ImageConfig.property.platform"></a>

```csharp
public string Platform { get; set; }
```

- *Type:* string

The platform to use when pulling the image. Defaults to the platform of the current machine.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#platform Image#platform}

---

##### `PullTriggers`<sup>Optional</sup> <a name="PullTriggers" id="@cdktn/provider-docker.image.ImageConfig.property.pullTriggers"></a>

```csharp
public string[] PullTriggers { get; set; }
```

- *Type:* string[]

List of values which cause an image pull when changed.

This is used to store the image digest from the registry when using the [docker_registry_image](../data-sources/registry_image.md).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#pull_triggers Image#pull_triggers}

---

##### `Timeouts`<sup>Optional</sup> <a name="Timeouts" id="@cdktn/provider-docker.image.ImageConfig.property.timeouts"></a>

```csharp
public ImageTimeouts Timeouts { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#timeouts Image#timeouts}

---

##### `Triggers`<sup>Optional</sup> <a name="Triggers" id="@cdktn/provider-docker.image.ImageConfig.property.triggers"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Triggers { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

A map of arbitrary strings that, when changed, will force the `docker_image` resource to be replaced.

This can be used to rebuild an image when contents of source code folders change

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#triggers Image#triggers}

---

### ImageTimeouts <a name="ImageTimeouts" id="@cdktn/provider-docker.image.ImageTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.image.ImageTimeouts.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageTimeouts {
    string Create = null,
    string Delete = null,
    string Update = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeouts.property.create">Create</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#create Image#create}. |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeouts.property.delete">Delete</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#delete Image#delete}. |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeouts.property.update">Update</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#update Image#update}. |

---

##### `Create`<sup>Optional</sup> <a name="Create" id="@cdktn/provider-docker.image.ImageTimeouts.property.create"></a>

```csharp
public string Create { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#create Image#create}.

---

##### `Delete`<sup>Optional</sup> <a name="Delete" id="@cdktn/provider-docker.image.ImageTimeouts.property.delete"></a>

```csharp
public string Delete { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#delete Image#delete}.

---

##### `Update`<sup>Optional</sup> <a name="Update" id="@cdktn/provider-docker.image.ImageTimeouts.property.update"></a>

```csharp
public string Update { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/image#update Image#update}.

---

## Classes <a name="Classes" id="Classes"></a>

### ImageBuildAuthConfigList <a name="ImageBuildAuthConfigList" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildAuthConfigList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.get"></a>

```csharp
private ImageBuildAuthConfigOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildAuthConfigList.property.internalValue"></a>

```csharp
public IResolvable|ImageBuildAuthConfig[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]

---


### ImageBuildAuthConfigOutputReference <a name="ImageBuildAuthConfigOutputReference" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildAuthConfigOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetAuth">ResetAuth</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetEmail">ResetEmail</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetIdentityToken">ResetIdentityToken</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetPassword">ResetPassword</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetRegistryToken">ResetRegistryToken</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetServerAddress">ResetServerAddress</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetUserName">ResetUserName</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAuth` <a name="ResetAuth" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetAuth"></a>

```csharp
private void ResetAuth()
```

##### `ResetEmail` <a name="ResetEmail" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetEmail"></a>

```csharp
private void ResetEmail()
```

##### `ResetIdentityToken` <a name="ResetIdentityToken" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetIdentityToken"></a>

```csharp
private void ResetIdentityToken()
```

##### `ResetPassword` <a name="ResetPassword" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetPassword"></a>

```csharp
private void ResetPassword()
```

##### `ResetRegistryToken` <a name="ResetRegistryToken" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetRegistryToken"></a>

```csharp
private void ResetRegistryToken()
```

##### `ResetServerAddress` <a name="ResetServerAddress" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetServerAddress"></a>

```csharp
private void ResetServerAddress()
```

##### `ResetUserName` <a name="ResetUserName" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.resetUserName"></a>

```csharp
private void ResetUserName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.authInput">AuthInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.emailInput">EmailInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.hostNameInput">HostNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.identityTokenInput">IdentityTokenInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.passwordInput">PasswordInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.registryTokenInput">RegistryTokenInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.serverAddressInput">ServerAddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.userNameInput">UserNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.auth">Auth</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.email">Email</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.hostName">HostName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.identityToken">IdentityToken</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.password">Password</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.registryToken">RegistryToken</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.serverAddress">ServerAddress</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.userName">UserName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AuthInput`<sup>Optional</sup> <a name="AuthInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.authInput"></a>

```csharp
public string AuthInput { get; }
```

- *Type:* string

---

##### `EmailInput`<sup>Optional</sup> <a name="EmailInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.emailInput"></a>

```csharp
public string EmailInput { get; }
```

- *Type:* string

---

##### `HostNameInput`<sup>Optional</sup> <a name="HostNameInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.hostNameInput"></a>

```csharp
public string HostNameInput { get; }
```

- *Type:* string

---

##### `IdentityTokenInput`<sup>Optional</sup> <a name="IdentityTokenInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.identityTokenInput"></a>

```csharp
public string IdentityTokenInput { get; }
```

- *Type:* string

---

##### `PasswordInput`<sup>Optional</sup> <a name="PasswordInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.passwordInput"></a>

```csharp
public string PasswordInput { get; }
```

- *Type:* string

---

##### `RegistryTokenInput`<sup>Optional</sup> <a name="RegistryTokenInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.registryTokenInput"></a>

```csharp
public string RegistryTokenInput { get; }
```

- *Type:* string

---

##### `ServerAddressInput`<sup>Optional</sup> <a name="ServerAddressInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.serverAddressInput"></a>

```csharp
public string ServerAddressInput { get; }
```

- *Type:* string

---

##### `UserNameInput`<sup>Optional</sup> <a name="UserNameInput" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.userNameInput"></a>

```csharp
public string UserNameInput { get; }
```

- *Type:* string

---

##### `Auth`<sup>Required</sup> <a name="Auth" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.auth"></a>

```csharp
public string Auth { get; }
```

- *Type:* string

---

##### `Email`<sup>Required</sup> <a name="Email" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.email"></a>

```csharp
public string Email { get; }
```

- *Type:* string

---

##### `HostName`<sup>Required</sup> <a name="HostName" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.hostName"></a>

```csharp
public string HostName { get; }
```

- *Type:* string

---

##### `IdentityToken`<sup>Required</sup> <a name="IdentityToken" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.identityToken"></a>

```csharp
public string IdentityToken { get; }
```

- *Type:* string

---

##### `Password`<sup>Required</sup> <a name="Password" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.password"></a>

```csharp
public string Password { get; }
```

- *Type:* string

---

##### `RegistryToken`<sup>Required</sup> <a name="RegistryToken" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.registryToken"></a>

```csharp
public string RegistryToken { get; }
```

- *Type:* string

---

##### `ServerAddress`<sup>Required</sup> <a name="ServerAddress" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.serverAddress"></a>

```csharp
public string ServerAddress { get; }
```

- *Type:* string

---

##### `UserName`<sup>Required</sup> <a name="UserName" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.userName"></a>

```csharp
public string UserName { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildAuthConfigOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ImageBuildAuthConfig InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>

---


### ImageBuildOutputReference <a name="ImageBuildOutputReference" id="@cdktn/provider-docker.image.ImageBuildOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.putAuthConfig">PutAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.putSecrets">PutSecrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.putUlimit">PutUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetAdditionalContexts">ResetAdditionalContexts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetAuthConfig">ResetAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuildArgs">ResetBuildArgs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuilder">ResetBuilder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuildId">ResetBuildId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuildLogFile">ResetBuildLogFile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCacheFrom">ResetCacheFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCacheTo">ResetCacheTo</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCgroupParent">ResetCgroupParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuPeriod">ResetCpuPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuQuota">ResetCpuQuota</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuSetCpus">ResetCpuSetCpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuSetMems">ResetCpuSetMems</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuShares">ResetCpuShares</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetDockerfile">ResetDockerfile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetExtraHosts">ResetExtraHosts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetForceRemove">ResetForceRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetIsolation">ResetIsolation</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetLabel">ResetLabel</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetLabels">ResetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetMemory">ResetMemory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetMemorySwap">ResetMemorySwap</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetNetworkMode">ResetNetworkMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetNoCache">ResetNoCache</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetPlatform">ResetPlatform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetProvenance">ResetProvenance</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetPullParent">ResetPullParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetRemoteContext">ResetRemoteContext</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetRemove">ResetRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetSbom">ResetSbom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetSecrets">ResetSecrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetSecurityOpt">ResetSecurityOpt</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetSessionId">ResetSessionId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetShmSize">ResetShmSize</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetSquash">ResetSquash</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetSuppressOutput">ResetSuppressOutput</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetTag">ResetTag</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetTarget">ResetTarget</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetUlimit">ResetUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetUseLegacyBuilder">ResetUseLegacyBuilder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.resetVersion">ResetVersion</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.image.ImageBuildOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.image.ImageBuildOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutAuthConfig` <a name="PutAuthConfig" id="@cdktn/provider-docker.image.ImageBuildOutputReference.putAuthConfig"></a>

```csharp
private void PutAuthConfig(IResolvable|ImageBuildAuthConfig[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.image.ImageBuildOutputReference.putAuthConfig.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]

---

##### `PutSecrets` <a name="PutSecrets" id="@cdktn/provider-docker.image.ImageBuildOutputReference.putSecrets"></a>

```csharp
private void PutSecrets(IResolvable|ImageBuildSecrets[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.image.ImageBuildOutputReference.putSecrets.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]

---

##### `PutUlimit` <a name="PutUlimit" id="@cdktn/provider-docker.image.ImageBuildOutputReference.putUlimit"></a>

```csharp
private void PutUlimit(IResolvable|ImageBuildUlimit[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.image.ImageBuildOutputReference.putUlimit.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]

---

##### `ResetAdditionalContexts` <a name="ResetAdditionalContexts" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetAdditionalContexts"></a>

```csharp
private void ResetAdditionalContexts()
```

##### `ResetAuthConfig` <a name="ResetAuthConfig" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetAuthConfig"></a>

```csharp
private void ResetAuthConfig()
```

##### `ResetBuildArgs` <a name="ResetBuildArgs" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuildArgs"></a>

```csharp
private void ResetBuildArgs()
```

##### `ResetBuilder` <a name="ResetBuilder" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuilder"></a>

```csharp
private void ResetBuilder()
```

##### `ResetBuildId` <a name="ResetBuildId" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuildId"></a>

```csharp
private void ResetBuildId()
```

##### `ResetBuildLogFile` <a name="ResetBuildLogFile" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetBuildLogFile"></a>

```csharp
private void ResetBuildLogFile()
```

##### `ResetCacheFrom` <a name="ResetCacheFrom" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCacheFrom"></a>

```csharp
private void ResetCacheFrom()
```

##### `ResetCacheTo` <a name="ResetCacheTo" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCacheTo"></a>

```csharp
private void ResetCacheTo()
```

##### `ResetCgroupParent` <a name="ResetCgroupParent" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCgroupParent"></a>

```csharp
private void ResetCgroupParent()
```

##### `ResetCpuPeriod` <a name="ResetCpuPeriod" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuPeriod"></a>

```csharp
private void ResetCpuPeriod()
```

##### `ResetCpuQuota` <a name="ResetCpuQuota" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuQuota"></a>

```csharp
private void ResetCpuQuota()
```

##### `ResetCpuSetCpus` <a name="ResetCpuSetCpus" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuSetCpus"></a>

```csharp
private void ResetCpuSetCpus()
```

##### `ResetCpuSetMems` <a name="ResetCpuSetMems" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuSetMems"></a>

```csharp
private void ResetCpuSetMems()
```

##### `ResetCpuShares` <a name="ResetCpuShares" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetCpuShares"></a>

```csharp
private void ResetCpuShares()
```

##### `ResetDockerfile` <a name="ResetDockerfile" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetDockerfile"></a>

```csharp
private void ResetDockerfile()
```

##### `ResetExtraHosts` <a name="ResetExtraHosts" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetExtraHosts"></a>

```csharp
private void ResetExtraHosts()
```

##### `ResetForceRemove` <a name="ResetForceRemove" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetForceRemove"></a>

```csharp
private void ResetForceRemove()
```

##### `ResetIsolation` <a name="ResetIsolation" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetIsolation"></a>

```csharp
private void ResetIsolation()
```

##### `ResetLabel` <a name="ResetLabel" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetLabel"></a>

```csharp
private void ResetLabel()
```

##### `ResetLabels` <a name="ResetLabels" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetLabels"></a>

```csharp
private void ResetLabels()
```

##### `ResetMemory` <a name="ResetMemory" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetMemory"></a>

```csharp
private void ResetMemory()
```

##### `ResetMemorySwap` <a name="ResetMemorySwap" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetMemorySwap"></a>

```csharp
private void ResetMemorySwap()
```

##### `ResetNetworkMode` <a name="ResetNetworkMode" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetNetworkMode"></a>

```csharp
private void ResetNetworkMode()
```

##### `ResetNoCache` <a name="ResetNoCache" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetNoCache"></a>

```csharp
private void ResetNoCache()
```

##### `ResetPlatform` <a name="ResetPlatform" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetPlatform"></a>

```csharp
private void ResetPlatform()
```

##### `ResetProvenance` <a name="ResetProvenance" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetProvenance"></a>

```csharp
private void ResetProvenance()
```

##### `ResetPullParent` <a name="ResetPullParent" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetPullParent"></a>

```csharp
private void ResetPullParent()
```

##### `ResetRemoteContext` <a name="ResetRemoteContext" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetRemoteContext"></a>

```csharp
private void ResetRemoteContext()
```

##### `ResetRemove` <a name="ResetRemove" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetRemove"></a>

```csharp
private void ResetRemove()
```

##### `ResetSbom` <a name="ResetSbom" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetSbom"></a>

```csharp
private void ResetSbom()
```

##### `ResetSecrets` <a name="ResetSecrets" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetSecrets"></a>

```csharp
private void ResetSecrets()
```

##### `ResetSecurityOpt` <a name="ResetSecurityOpt" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetSecurityOpt"></a>

```csharp
private void ResetSecurityOpt()
```

##### `ResetSessionId` <a name="ResetSessionId" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetSessionId"></a>

```csharp
private void ResetSessionId()
```

##### `ResetShmSize` <a name="ResetShmSize" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetShmSize"></a>

```csharp
private void ResetShmSize()
```

##### `ResetSquash` <a name="ResetSquash" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetSquash"></a>

```csharp
private void ResetSquash()
```

##### `ResetSuppressOutput` <a name="ResetSuppressOutput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetSuppressOutput"></a>

```csharp
private void ResetSuppressOutput()
```

##### `ResetTag` <a name="ResetTag" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetTag"></a>

```csharp
private void ResetTag()
```

##### `ResetTarget` <a name="ResetTarget" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetTarget"></a>

```csharp
private void ResetTarget()
```

##### `ResetUlimit` <a name="ResetUlimit" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetUlimit"></a>

```csharp
private void ResetUlimit()
```

##### `ResetUseLegacyBuilder` <a name="ResetUseLegacyBuilder" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetUseLegacyBuilder"></a>

```csharp
private void ResetUseLegacyBuilder()
```

##### `ResetVersion` <a name="ResetVersion" id="@cdktn/provider-docker.image.ImageBuildOutputReference.resetVersion"></a>

```csharp
private void ResetVersion()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList">ImageBuildAuthConfigList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.secrets">Secrets</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList">ImageBuildSecretsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.ulimit">Ulimit</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList">ImageBuildUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.additionalContextsInput">AdditionalContextsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.authConfigInput">AuthConfigInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildArgsInput">BuildArgsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.builderInput">BuilderInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildIdInput">BuildIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildLogFileInput">BuildLogFileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheFromInput">CacheFromInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheToInput">CacheToInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cgroupParentInput">CgroupParentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.contextInput">ContextInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuPeriodInput">CpuPeriodInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuQuotaInput">CpuQuotaInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetCpusInput">CpuSetCpusInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetMemsInput">CpuSetMemsInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSharesInput">CpuSharesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.dockerfileInput">DockerfileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.extraHostsInput">ExtraHostsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.forceRemoveInput">ForceRemoveInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.isolationInput">IsolationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.labelInput">LabelInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.labelsInput">LabelsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.memoryInput">MemoryInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.memorySwapInput">MemorySwapInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.networkModeInput">NetworkModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.noCacheInput">NoCacheInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.platformInput">PlatformInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.provenanceInput">ProvenanceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.pullParentInput">PullParentInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.remoteContextInput">RemoteContextInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.removeInput">RemoveInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.sbomInput">SbomInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.secretsInput">SecretsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.securityOptInput">SecurityOptInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.sessionIdInput">SessionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.shmSizeInput">ShmSizeInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.squashInput">SquashInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.suppressOutputInput">SuppressOutputInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.tagInput">TagInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.targetInput">TargetInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.ulimitInput">UlimitInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.useLegacyBuilderInput">UseLegacyBuilderInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.versionInput">VersionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.additionalContexts">AdditionalContexts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildArgs">BuildArgs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.builder">Builder</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildId">BuildId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildLogFile">BuildLogFile</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheFrom">CacheFrom</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheTo">CacheTo</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cgroupParent">CgroupParent</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.context">Context</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuPeriod">CpuPeriod</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuQuota">CpuQuota</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetCpus">CpuSetCpus</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetMems">CpuSetMems</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuShares">CpuShares</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.dockerfile">Dockerfile</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.extraHosts">ExtraHosts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.forceRemove">ForceRemove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.isolation">Isolation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.label">Label</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.labels">Labels</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.memory">Memory</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.memorySwap">MemorySwap</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.networkMode">NetworkMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.noCache">NoCache</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.platform">Platform</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.provenance">Provenance</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.pullParent">PullParent</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.remoteContext">RemoteContext</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.remove">Remove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.sbom">Sbom</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.securityOpt">SecurityOpt</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.sessionId">SessionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.shmSize">ShmSize</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.squash">Squash</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.suppressOutput">SuppressOutput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.tag">Tag</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.target">Target</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.useLegacyBuilder">UseLegacyBuilder</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.version">Version</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AuthConfig`<sup>Required</sup> <a name="AuthConfig" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.authConfig"></a>

```csharp
public ImageBuildAuthConfigList AuthConfig { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuildAuthConfigList">ImageBuildAuthConfigList</a>

---

##### `Secrets`<sup>Required</sup> <a name="Secrets" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.secrets"></a>

```csharp
public ImageBuildSecretsList Secrets { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuildSecretsList">ImageBuildSecretsList</a>

---

##### `Ulimit`<sup>Required</sup> <a name="Ulimit" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.ulimit"></a>

```csharp
public ImageBuildUlimitList Ulimit { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuildUlimitList">ImageBuildUlimitList</a>

---

##### `AdditionalContextsInput`<sup>Optional</sup> <a name="AdditionalContextsInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.additionalContextsInput"></a>

```csharp
public string[] AdditionalContextsInput { get; }
```

- *Type:* string[]

---

##### `AuthConfigInput`<sup>Optional</sup> <a name="AuthConfigInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.authConfigInput"></a>

```csharp
public IResolvable|ImageBuildAuthConfig[] AuthConfigInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildAuthConfig">ImageBuildAuthConfig</a>[]

---

##### `BuildArgsInput`<sup>Optional</sup> <a name="BuildArgsInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildArgsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> BuildArgsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `BuilderInput`<sup>Optional</sup> <a name="BuilderInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.builderInput"></a>

```csharp
public string BuilderInput { get; }
```

- *Type:* string

---

##### `BuildIdInput`<sup>Optional</sup> <a name="BuildIdInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildIdInput"></a>

```csharp
public string BuildIdInput { get; }
```

- *Type:* string

---

##### `BuildLogFileInput`<sup>Optional</sup> <a name="BuildLogFileInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildLogFileInput"></a>

```csharp
public string BuildLogFileInput { get; }
```

- *Type:* string

---

##### `CacheFromInput`<sup>Optional</sup> <a name="CacheFromInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheFromInput"></a>

```csharp
public string[] CacheFromInput { get; }
```

- *Type:* string[]

---

##### `CacheToInput`<sup>Optional</sup> <a name="CacheToInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheToInput"></a>

```csharp
public string[] CacheToInput { get; }
```

- *Type:* string[]

---

##### `CgroupParentInput`<sup>Optional</sup> <a name="CgroupParentInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cgroupParentInput"></a>

```csharp
public string CgroupParentInput { get; }
```

- *Type:* string

---

##### `ContextInput`<sup>Optional</sup> <a name="ContextInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.contextInput"></a>

```csharp
public string ContextInput { get; }
```

- *Type:* string

---

##### `CpuPeriodInput`<sup>Optional</sup> <a name="CpuPeriodInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuPeriodInput"></a>

```csharp
public double CpuPeriodInput { get; }
```

- *Type:* double

---

##### `CpuQuotaInput`<sup>Optional</sup> <a name="CpuQuotaInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuQuotaInput"></a>

```csharp
public double CpuQuotaInput { get; }
```

- *Type:* double

---

##### `CpuSetCpusInput`<sup>Optional</sup> <a name="CpuSetCpusInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetCpusInput"></a>

```csharp
public string CpuSetCpusInput { get; }
```

- *Type:* string

---

##### `CpuSetMemsInput`<sup>Optional</sup> <a name="CpuSetMemsInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetMemsInput"></a>

```csharp
public string CpuSetMemsInput { get; }
```

- *Type:* string

---

##### `CpuSharesInput`<sup>Optional</sup> <a name="CpuSharesInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSharesInput"></a>

```csharp
public double CpuSharesInput { get; }
```

- *Type:* double

---

##### `DockerfileInput`<sup>Optional</sup> <a name="DockerfileInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.dockerfileInput"></a>

```csharp
public string DockerfileInput { get; }
```

- *Type:* string

---

##### `ExtraHostsInput`<sup>Optional</sup> <a name="ExtraHostsInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.extraHostsInput"></a>

```csharp
public string[] ExtraHostsInput { get; }
```

- *Type:* string[]

---

##### `ForceRemoveInput`<sup>Optional</sup> <a name="ForceRemoveInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.forceRemoveInput"></a>

```csharp
public bool|IResolvable ForceRemoveInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `IsolationInput`<sup>Optional</sup> <a name="IsolationInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.isolationInput"></a>

```csharp
public string IsolationInput { get; }
```

- *Type:* string

---

##### `LabelInput`<sup>Optional</sup> <a name="LabelInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.labelInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LabelInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `LabelsInput`<sup>Optional</sup> <a name="LabelsInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.labelsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LabelsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `MemoryInput`<sup>Optional</sup> <a name="MemoryInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.memoryInput"></a>

```csharp
public double MemoryInput { get; }
```

- *Type:* double

---

##### `MemorySwapInput`<sup>Optional</sup> <a name="MemorySwapInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.memorySwapInput"></a>

```csharp
public double MemorySwapInput { get; }
```

- *Type:* double

---

##### `NetworkModeInput`<sup>Optional</sup> <a name="NetworkModeInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.networkModeInput"></a>

```csharp
public string NetworkModeInput { get; }
```

- *Type:* string

---

##### `NoCacheInput`<sup>Optional</sup> <a name="NoCacheInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.noCacheInput"></a>

```csharp
public bool|IResolvable NoCacheInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `PlatformInput`<sup>Optional</sup> <a name="PlatformInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.platformInput"></a>

```csharp
public string PlatformInput { get; }
```

- *Type:* string

---

##### `ProvenanceInput`<sup>Optional</sup> <a name="ProvenanceInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.provenanceInput"></a>

```csharp
public string ProvenanceInput { get; }
```

- *Type:* string

---

##### `PullParentInput`<sup>Optional</sup> <a name="PullParentInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.pullParentInput"></a>

```csharp
public bool|IResolvable PullParentInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RemoteContextInput`<sup>Optional</sup> <a name="RemoteContextInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.remoteContextInput"></a>

```csharp
public string RemoteContextInput { get; }
```

- *Type:* string

---

##### `RemoveInput`<sup>Optional</sup> <a name="RemoveInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.removeInput"></a>

```csharp
public bool|IResolvable RemoveInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SbomInput`<sup>Optional</sup> <a name="SbomInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.sbomInput"></a>

```csharp
public string SbomInput { get; }
```

- *Type:* string

---

##### `SecretsInput`<sup>Optional</sup> <a name="SecretsInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.secretsInput"></a>

```csharp
public IResolvable|ImageBuildSecrets[] SecretsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]

---

##### `SecurityOptInput`<sup>Optional</sup> <a name="SecurityOptInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.securityOptInput"></a>

```csharp
public string[] SecurityOptInput { get; }
```

- *Type:* string[]

---

##### `SessionIdInput`<sup>Optional</sup> <a name="SessionIdInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.sessionIdInput"></a>

```csharp
public string SessionIdInput { get; }
```

- *Type:* string

---

##### `ShmSizeInput`<sup>Optional</sup> <a name="ShmSizeInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.shmSizeInput"></a>

```csharp
public double ShmSizeInput { get; }
```

- *Type:* double

---

##### `SquashInput`<sup>Optional</sup> <a name="SquashInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.squashInput"></a>

```csharp
public bool|IResolvable SquashInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SuppressOutputInput`<sup>Optional</sup> <a name="SuppressOutputInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.suppressOutputInput"></a>

```csharp
public bool|IResolvable SuppressOutputInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `TagInput`<sup>Optional</sup> <a name="TagInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.tagInput"></a>

```csharp
public string[] TagInput { get; }
```

- *Type:* string[]

---

##### `TargetInput`<sup>Optional</sup> <a name="TargetInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.targetInput"></a>

```csharp
public string TargetInput { get; }
```

- *Type:* string

---

##### `UlimitInput`<sup>Optional</sup> <a name="UlimitInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.ulimitInput"></a>

```csharp
public IResolvable|ImageBuildUlimit[] UlimitInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]

---

##### `UseLegacyBuilderInput`<sup>Optional</sup> <a name="UseLegacyBuilderInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.useLegacyBuilderInput"></a>

```csharp
public bool|IResolvable UseLegacyBuilderInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `VersionInput`<sup>Optional</sup> <a name="VersionInput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.versionInput"></a>

```csharp
public string VersionInput { get; }
```

- *Type:* string

---

##### `AdditionalContexts`<sup>Required</sup> <a name="AdditionalContexts" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.additionalContexts"></a>

```csharp
public string[] AdditionalContexts { get; }
```

- *Type:* string[]

---

##### `BuildArgs`<sup>Required</sup> <a name="BuildArgs" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildArgs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> BuildArgs { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Builder`<sup>Required</sup> <a name="Builder" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.builder"></a>

```csharp
public string Builder { get; }
```

- *Type:* string

---

##### `BuildId`<sup>Required</sup> <a name="BuildId" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildId"></a>

```csharp
public string BuildId { get; }
```

- *Type:* string

---

##### `BuildLogFile`<sup>Required</sup> <a name="BuildLogFile" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.buildLogFile"></a>

```csharp
public string BuildLogFile { get; }
```

- *Type:* string

---

##### `CacheFrom`<sup>Required</sup> <a name="CacheFrom" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheFrom"></a>

```csharp
public string[] CacheFrom { get; }
```

- *Type:* string[]

---

##### `CacheTo`<sup>Required</sup> <a name="CacheTo" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cacheTo"></a>

```csharp
public string[] CacheTo { get; }
```

- *Type:* string[]

---

##### `CgroupParent`<sup>Required</sup> <a name="CgroupParent" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cgroupParent"></a>

```csharp
public string CgroupParent { get; }
```

- *Type:* string

---

##### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.context"></a>

```csharp
public string Context { get; }
```

- *Type:* string

---

##### `CpuPeriod`<sup>Required</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuPeriod"></a>

```csharp
public double CpuPeriod { get; }
```

- *Type:* double

---

##### `CpuQuota`<sup>Required</sup> <a name="CpuQuota" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuQuota"></a>

```csharp
public double CpuQuota { get; }
```

- *Type:* double

---

##### `CpuSetCpus`<sup>Required</sup> <a name="CpuSetCpus" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetCpus"></a>

```csharp
public string CpuSetCpus { get; }
```

- *Type:* string

---

##### `CpuSetMems`<sup>Required</sup> <a name="CpuSetMems" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuSetMems"></a>

```csharp
public string CpuSetMems { get; }
```

- *Type:* string

---

##### `CpuShares`<sup>Required</sup> <a name="CpuShares" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.cpuShares"></a>

```csharp
public double CpuShares { get; }
```

- *Type:* double

---

##### `Dockerfile`<sup>Required</sup> <a name="Dockerfile" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.dockerfile"></a>

```csharp
public string Dockerfile { get; }
```

- *Type:* string

---

##### `ExtraHosts`<sup>Required</sup> <a name="ExtraHosts" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.extraHosts"></a>

```csharp
public string[] ExtraHosts { get; }
```

- *Type:* string[]

---

##### `ForceRemove`<sup>Required</sup> <a name="ForceRemove" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.forceRemove"></a>

```csharp
public bool|IResolvable ForceRemove { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Isolation`<sup>Required</sup> <a name="Isolation" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.isolation"></a>

```csharp
public string Isolation { get; }
```

- *Type:* string

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.label"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Label { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Labels`<sup>Required</sup> <a name="Labels" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.labels"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Labels { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Memory`<sup>Required</sup> <a name="Memory" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.memory"></a>

```csharp
public double Memory { get; }
```

- *Type:* double

---

##### `MemorySwap`<sup>Required</sup> <a name="MemorySwap" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.memorySwap"></a>

```csharp
public double MemorySwap { get; }
```

- *Type:* double

---

##### `NetworkMode`<sup>Required</sup> <a name="NetworkMode" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.networkMode"></a>

```csharp
public string NetworkMode { get; }
```

- *Type:* string

---

##### `NoCache`<sup>Required</sup> <a name="NoCache" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.noCache"></a>

```csharp
public bool|IResolvable NoCache { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Platform`<sup>Required</sup> <a name="Platform" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.platform"></a>

```csharp
public string Platform { get; }
```

- *Type:* string

---

##### `Provenance`<sup>Required</sup> <a name="Provenance" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.provenance"></a>

```csharp
public string Provenance { get; }
```

- *Type:* string

---

##### `PullParent`<sup>Required</sup> <a name="PullParent" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.pullParent"></a>

```csharp
public bool|IResolvable PullParent { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RemoteContext`<sup>Required</sup> <a name="RemoteContext" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.remoteContext"></a>

```csharp
public string RemoteContext { get; }
```

- *Type:* string

---

##### `Remove`<sup>Required</sup> <a name="Remove" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.remove"></a>

```csharp
public bool|IResolvable Remove { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Sbom`<sup>Required</sup> <a name="Sbom" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.sbom"></a>

```csharp
public string Sbom { get; }
```

- *Type:* string

---

##### `SecurityOpt`<sup>Required</sup> <a name="SecurityOpt" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.securityOpt"></a>

```csharp
public string[] SecurityOpt { get; }
```

- *Type:* string[]

---

##### `SessionId`<sup>Required</sup> <a name="SessionId" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.sessionId"></a>

```csharp
public string SessionId { get; }
```

- *Type:* string

---

##### `ShmSize`<sup>Required</sup> <a name="ShmSize" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.shmSize"></a>

```csharp
public double ShmSize { get; }
```

- *Type:* double

---

##### `Squash`<sup>Required</sup> <a name="Squash" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.squash"></a>

```csharp
public bool|IResolvable Squash { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SuppressOutput`<sup>Required</sup> <a name="SuppressOutput" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.suppressOutput"></a>

```csharp
public bool|IResolvable SuppressOutput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Tag`<sup>Required</sup> <a name="Tag" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.tag"></a>

```csharp
public string[] Tag { get; }
```

- *Type:* string[]

---

##### `Target`<sup>Required</sup> <a name="Target" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.target"></a>

```csharp
public string Target { get; }
```

- *Type:* string

---

##### `UseLegacyBuilder`<sup>Required</sup> <a name="UseLegacyBuilder" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.useLegacyBuilder"></a>

```csharp
public bool|IResolvable UseLegacyBuilder { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Version`<sup>Required</sup> <a name="Version" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.version"></a>

```csharp
public string Version { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildOutputReference.property.internalValue"></a>

```csharp
public ImageBuild InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.image.ImageBuild">ImageBuild</a>

---


### ImageBuildSecretsList <a name="ImageBuildSecretsList" id="@cdktn/provider-docker.image.ImageBuildSecretsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildSecretsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.image.ImageBuildSecretsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.image.ImageBuildSecretsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.image.ImageBuildSecretsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildSecretsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildSecretsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildSecretsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildSecretsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.image.ImageBuildSecretsList.get"></a>

```csharp
private ImageBuildSecretsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.image.ImageBuildSecretsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildSecretsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildSecretsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildSecretsList.property.internalValue"></a>

```csharp
public IResolvable|ImageBuildSecrets[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>[]

---


### ImageBuildSecretsOutputReference <a name="ImageBuildSecretsOutputReference" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildSecretsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resetEnv">ResetEnv</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resetSrc">ResetSrc</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetEnv` <a name="ResetEnv" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resetEnv"></a>

```csharp
private void ResetEnv()
```

##### `ResetSrc` <a name="ResetSrc" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.resetSrc"></a>

```csharp
private void ResetSrc()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.envInput">EnvInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.srcInput">SrcInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.env">Env</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.src">Src</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `EnvInput`<sup>Optional</sup> <a name="EnvInput" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.envInput"></a>

```csharp
public string EnvInput { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `SrcInput`<sup>Optional</sup> <a name="SrcInput" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.srcInput"></a>

```csharp
public string SrcInput { get; }
```

- *Type:* string

---

##### `Env`<sup>Required</sup> <a name="Env" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.env"></a>

```csharp
public string Env { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Src`<sup>Required</sup> <a name="Src" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.src"></a>

```csharp
public string Src { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildSecretsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ImageBuildSecrets InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildSecrets">ImageBuildSecrets</a>

---


### ImageBuildUlimitList <a name="ImageBuildUlimitList" id="@cdktn/provider-docker.image.ImageBuildUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildUlimitList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.image.ImageBuildUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.image.ImageBuildUlimitList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.image.ImageBuildUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildUlimitList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildUlimitList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildUlimitList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildUlimitList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.image.ImageBuildUlimitList.get"></a>

```csharp
private ImageBuildUlimitOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.image.ImageBuildUlimitList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildUlimitList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildUlimitList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildUlimitList.property.internalValue"></a>

```csharp
public IResolvable|ImageBuildUlimit[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>[]

---


### ImageBuildUlimitOutputReference <a name="ImageBuildUlimitOutputReference" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageBuildUlimitOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.hardInput">HardInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.softInput">SoftInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.hard">Hard</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.soft">Soft</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `HardInput`<sup>Optional</sup> <a name="HardInput" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.hardInput"></a>

```csharp
public double HardInput { get; }
```

- *Type:* double

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `SoftInput`<sup>Optional</sup> <a name="SoftInput" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.softInput"></a>

```csharp
public double SoftInput { get; }
```

- *Type:* double

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.hard"></a>

```csharp
public double Hard { get; }
```

- *Type:* double

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.soft"></a>

```csharp
public double Soft { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageBuildUlimitOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ImageBuildUlimit InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageBuildUlimit">ImageBuildUlimit</a>

---


### ImageTimeoutsOutputReference <a name="ImageTimeoutsOutputReference" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ImageTimeoutsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resetCreate">ResetCreate</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resetDelete">ResetDelete</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resetUpdate">ResetUpdate</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetCreate` <a name="ResetCreate" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resetCreate"></a>

```csharp
private void ResetCreate()
```

##### `ResetDelete` <a name="ResetDelete" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resetDelete"></a>

```csharp
private void ResetDelete()
```

##### `ResetUpdate` <a name="ResetUpdate" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.resetUpdate"></a>

```csharp
private void ResetUpdate()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.createInput">CreateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.deleteInput">DeleteInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.updateInput">UpdateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.create">Create</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.delete">Delete</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.update">Update</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `CreateInput`<sup>Optional</sup> <a name="CreateInput" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.createInput"></a>

```csharp
public string CreateInput { get; }
```

- *Type:* string

---

##### `DeleteInput`<sup>Optional</sup> <a name="DeleteInput" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.deleteInput"></a>

```csharp
public string DeleteInput { get; }
```

- *Type:* string

---

##### `UpdateInput`<sup>Optional</sup> <a name="UpdateInput" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.updateInput"></a>

```csharp
public string UpdateInput { get; }
```

- *Type:* string

---

##### `Create`<sup>Required</sup> <a name="Create" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.create"></a>

```csharp
public string Create { get; }
```

- *Type:* string

---

##### `Delete`<sup>Required</sup> <a name="Delete" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.delete"></a>

```csharp
public string Delete { get; }
```

- *Type:* string

---

##### `Update`<sup>Required</sup> <a name="Update" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.update"></a>

```csharp
public string Update { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.image.ImageTimeoutsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ImageTimeouts InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.image.ImageTimeouts">ImageTimeouts</a>

---



