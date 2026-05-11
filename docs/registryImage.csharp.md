# `registryImage` Submodule <a name="`registryImage` Submodule" id="@cdktn/provider-docker.registryImage"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### RegistryImage <a name="RegistryImage" id="@cdktn/provider-docker.registryImage.RegistryImage"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image docker_registry_image}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImage(Construct Scope, string Id, RegistryImageConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig">RegistryImageConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig">RegistryImageConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig">PutAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute">PutBuildAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts">PutTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig">ResetAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute">ResetBuildAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify">ResetInsecureSkipVerify</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely">ResetKeepRemotely</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts">ResetTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers">ResetTriggers</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImage.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.registryImage.RegistryImage.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.registryImage.RegistryImage.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove"></a>

```csharp
private TerraformResourceMoveByTarget|TerraformResourceMoveById HasResourceMove()
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId"></a>

```csharp
private void MoveFromId(string Id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, string|double Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.index"></a>

- *Type:* string|double

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId"></a>

```csharp
private void MoveToId(string Id)
```

Moves this resource to the resource corresponding to "id".

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutAuthConfig` <a name="PutAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig"></a>

```csharp
private void PutAuthConfig(RegistryImageAuthConfig Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `PutBuildAttribute` <a name="PutBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute"></a>

```csharp
private void PutBuildAttribute(RegistryImageBuild Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `PutTimeouts` <a name="PutTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts"></a>

```csharp
private void PutTimeouts(RegistryImageTimeouts Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `ResetAuthConfig` <a name="ResetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig"></a>

```csharp
private void ResetAuthConfig()
```

##### `ResetBuildAttribute` <a name="ResetBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute"></a>

```csharp
private void ResetBuildAttribute()
```

##### `ResetId` <a name="ResetId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetInsecureSkipVerify` <a name="ResetInsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify"></a>

```csharp
private void ResetInsecureSkipVerify()
```

##### `ResetKeepRemotely` <a name="ResetKeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely"></a>

```csharp
private void ResetKeepRemotely()
```

##### `ResetTimeouts` <a name="ResetTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts"></a>

```csharp
private void ResetTimeouts()
```

##### `ResetTriggers` <a name="ResetTriggers" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers"></a>

```csharp
private void ResetTriggers()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.registryImage.RegistryImage.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

RegistryImage.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.registryImage.RegistryImage.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

RegistryImage.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

RegistryImage.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

RegistryImage.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the RegistryImage to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing RegistryImage that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the RegistryImage to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute">BuildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest">Sha256Digest</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput">AuthConfigInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput">BuildAttributeInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput">InsecureSkipVerifyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput">KeepRemotelyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput">TimeoutsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput">TriggersInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely">KeepRemotely</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggers">Triggers</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.registryImage.RegistryImage.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.registryImage.RegistryImage.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.registryImage.RegistryImage.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.registryImage.RegistryImage.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `AuthConfig`<sup>Required</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig"></a>

```csharp
public RegistryImageAuthConfigOutputReference AuthConfig { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a>

---

##### `BuildAttribute`<sup>Required</sup> <a name="BuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute"></a>

```csharp
public RegistryImageBuildOutputReference BuildAttribute { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a>

---

##### `Sha256Digest`<sup>Required</sup> <a name="Sha256Digest" id="@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest"></a>

```csharp
public string Sha256Digest { get; }
```

- *Type:* string

---

##### `Timeouts`<sup>Required</sup> <a name="Timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts"></a>

```csharp
public RegistryImageTimeoutsOutputReference Timeouts { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a>

---

##### `AuthConfigInput`<sup>Optional</sup> <a name="AuthConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput"></a>

```csharp
public RegistryImageAuthConfig AuthConfigInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `BuildAttributeInput`<sup>Optional</sup> <a name="BuildAttributeInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput"></a>

```csharp
public RegistryImageBuild BuildAttributeInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `InsecureSkipVerifyInput`<sup>Optional</sup> <a name="InsecureSkipVerifyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput"></a>

```csharp
public bool|IResolvable InsecureSkipVerifyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `KeepRemotelyInput`<sup>Optional</sup> <a name="KeepRemotelyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput"></a>

```csharp
public bool|IResolvable KeepRemotelyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `TimeoutsInput`<sup>Optional</sup> <a name="TimeoutsInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput"></a>

```csharp
public IResolvable|RegistryImageTimeouts TimeoutsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `TriggersInput`<sup>Optional</sup> <a name="TriggersInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> TriggersInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImage.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `InsecureSkipVerify`<sup>Required</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify"></a>

```csharp
public bool|IResolvable InsecureSkipVerify { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `KeepRemotely`<sup>Required</sup> <a name="KeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely"></a>

```csharp
public bool|IResolvable KeepRemotely { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImage.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Triggers`<sup>Required</sup> <a name="Triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggers"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Triggers { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### RegistryImageAuthConfig <a name="RegistryImageAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageAuthConfig {
    string Address,
    string Password = null,
    string Username = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address">Address</a></code> | <code>string</code> | The address of the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password">Password</a></code> | <code>string</code> | The password for the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username">Username</a></code> | <code>string</code> | The username for the Docker registry. |

---

##### `Address`<sup>Required</sup> <a name="Address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address"></a>

```csharp
public string Address { get; set; }
```

- *Type:* string

The address of the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#address RegistryImage#address}

---

##### `Password`<sup>Optional</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password"></a>

```csharp
public string Password { get; set; }
```

- *Type:* string

The password for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `Username`<sup>Optional</sup> <a name="Username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username"></a>

```csharp
public string Username { get; set; }
```

- *Type:* string

The username for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#username RegistryImage#username}

---

### RegistryImageBuild <a name="RegistryImageBuild" id="@cdktn/provider-docker.registryImage.RegistryImageBuild"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuild {
    string Context,
    string[] AdditionalContexts = null,
    IResolvable|RegistryImageBuildAuthConfig[] AuthConfig = null,
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
    IResolvable|RegistryImageBuildSecrets[] Secrets = null,
    string[] SecurityOpt = null,
    string SessionId = null,
    double ShmSize = null,
    bool|IResolvable Squash = null,
    bool|IResolvable SuppressOutput = null,
    string[] Tag = null,
    string Target = null,
    IResolvable|RegistryImageBuildUlimit[] Ulimit = null,
    bool|IResolvable UseLegacyBuilder = null,
    string Version = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context">Context</a></code> | <code>string</code> | Value to specify the build context. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts">AdditionalContexts</a></code> | <code>string[]</code> | A list of additional build contexts. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig">AuthConfig</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]</code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs">BuildArgs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder">Builder</a></code> | <code>string</code> | The name of the buildx builder to use. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId">BuildId</a></code> | <code>string</code> | BuildID is an optional identifier that can be passed together with the build request. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile">BuildLogFile</a></code> | <code>string</code> | Path to a file where the buildx log are written to. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom">CacheFrom</a></code> | <code>string[]</code> | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo">CacheTo</a></code> | <code>string[]</code> | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent">CgroupParent</a></code> | <code>string</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod">CpuPeriod</a></code> | <code>double</code> | The length of a CPU period in microseconds. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota">CpuQuota</a></code> | <code>double</code> | Microseconds of CPU time that the container can get in a CPU period. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus">CpuSetCpus</a></code> | <code>string</code> | CPUs in which to allow execution (e.g., `0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems">CpuSetMems</a></code> | <code>string</code> | MEMs in which to allow execution (`0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares">CpuShares</a></code> | <code>double</code> | CPU shares (relative weight). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile">Dockerfile</a></code> | <code>string</code> | Name of the Dockerfile. Defaults to `Dockerfile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts">ExtraHosts</a></code> | <code>string[]</code> | A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"]. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove">ForceRemove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Always remove intermediate containers. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation">Isolation</a></code> | <code>string</code> | Isolation represents the isolation technology of a container. The supported values are. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label">Label</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Set metadata for an image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels">Labels</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | User-defined key/value metadata. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory">Memory</a></code> | <code>double</code> | Set memory limit for build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap">MemorySwap</a></code> | <code>double</code> | Total memory (memory + swap), -1 to enable unlimited swap. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode">NetworkMode</a></code> | <code>string</code> | Set the networking mode for the RUN instructions during build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache">NoCache</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Do not use the cache when building the image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform">Platform</a></code> | <code>string</code> | Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance">Provenance</a></code> | <code>string</code> | Set provenance attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent">PullParent</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Attempt to pull the image even if an older image exists locally. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext">RemoteContext</a></code> | <code>string</code> | A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove">Remove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Remove intermediate containers after a successful build. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom">Sbom</a></code> | <code>string</code> | Set SBOM (Software Bill of Materials) attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets">Secrets</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]</code> | secrets block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt">SecurityOpt</a></code> | <code>string[]</code> | The security options. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId">SessionId</a></code> | <code>string</code> | Set an ID for the build session. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize">ShmSize</a></code> | <code>double</code> | Size of /dev/shm in bytes. The size must be greater than 0. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash">Squash</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true the new layers are squashed into a new image with a single new layer. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput">SuppressOutput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Suppress the build output and print image ID on success. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag">Tag</a></code> | <code>string[]</code> | Name and optionally a tag in the 'name:tag' format. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target">Target</a></code> | <code>string</code> | Set the target build stage to build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit">Ulimit</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]</code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder">UseLegacyBuilder</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version">Version</a></code> | <code>string</code> | Version of the underlying builder to use. |

---

##### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context"></a>

```csharp
public string Context { get; set; }
```

- *Type:* string

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#context RegistryImage#context}

---

##### `AdditionalContexts`<sup>Optional</sup> <a name="AdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts"></a>

```csharp
public string[] AdditionalContexts { get; set; }
```

- *Type:* string[]

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#additional_contexts RegistryImage#additional_contexts}

---

##### `AuthConfig`<sup>Optional</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig"></a>

```csharp
public IResolvable|RegistryImageBuildAuthConfig[] AuthConfig { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `BuildArgs`<sup>Optional</sup> <a name="BuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> BuildArgs { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#build_args RegistryImage#build_args}

---

##### `Builder`<sup>Optional</sup> <a name="Builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder"></a>

```csharp
public string Builder { get; set; }
```

- *Type:* string

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#builder RegistryImage#builder}

---

##### `BuildId`<sup>Optional</sup> <a name="BuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId"></a>

```csharp
public string BuildId { get; set; }
```

- *Type:* string

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#build_id RegistryImage#build_id}

---

##### `BuildLogFile`<sup>Optional</sup> <a name="BuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile"></a>

```csharp
public string BuildLogFile { get; set; }
```

- *Type:* string

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#build_log_file RegistryImage#build_log_file}

---

##### `CacheFrom`<sup>Optional</sup> <a name="CacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom"></a>

```csharp
public string[] CacheFrom { get; set; }
```

- *Type:* string[]

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cache_from RegistryImage#cache_from}

---

##### `CacheTo`<sup>Optional</sup> <a name="CacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo"></a>

```csharp
public string[] CacheTo { get; set; }
```

- *Type:* string[]

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cache_to RegistryImage#cache_to}

---

##### `CgroupParent`<sup>Optional</sup> <a name="CgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent"></a>

```csharp
public string CgroupParent { get; set; }
```

- *Type:* string

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cgroup_parent RegistryImage#cgroup_parent}

---

##### `CpuPeriod`<sup>Optional</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod"></a>

```csharp
public double CpuPeriod { get; set; }
```

- *Type:* double

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cpu_period RegistryImage#cpu_period}

---

##### `CpuQuota`<sup>Optional</sup> <a name="CpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota"></a>

```csharp
public double CpuQuota { get; set; }
```

- *Type:* double

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cpu_quota RegistryImage#cpu_quota}

---

##### `CpuSetCpus`<sup>Optional</sup> <a name="CpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus"></a>

```csharp
public string CpuSetCpus { get; set; }
```

- *Type:* string

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cpu_set_cpus RegistryImage#cpu_set_cpus}

---

##### `CpuSetMems`<sup>Optional</sup> <a name="CpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems"></a>

```csharp
public string CpuSetMems { get; set; }
```

- *Type:* string

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cpu_set_mems RegistryImage#cpu_set_mems}

---

##### `CpuShares`<sup>Optional</sup> <a name="CpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares"></a>

```csharp
public double CpuShares { get; set; }
```

- *Type:* double

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#cpu_shares RegistryImage#cpu_shares}

---

##### `Dockerfile`<sup>Optional</sup> <a name="Dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile"></a>

```csharp
public string Dockerfile { get; set; }
```

- *Type:* string

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#dockerfile RegistryImage#dockerfile}

---

##### `ExtraHosts`<sup>Optional</sup> <a name="ExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts"></a>

```csharp
public string[] ExtraHosts { get; set; }
```

- *Type:* string[]

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#extra_hosts RegistryImage#extra_hosts}

---

##### `ForceRemove`<sup>Optional</sup> <a name="ForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove"></a>

```csharp
public bool|IResolvable ForceRemove { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#force_remove RegistryImage#force_remove}

---

##### `Isolation`<sup>Optional</sup> <a name="Isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation"></a>

```csharp
public string Isolation { get; set; }
```

- *Type:* string

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#isolation RegistryImage#isolation}

---

##### `Label`<sup>Optional</sup> <a name="Label" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Label { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#label RegistryImage#label}

---

##### `Labels`<sup>Optional</sup> <a name="Labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Labels { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#labels RegistryImage#labels}

---

##### `Memory`<sup>Optional</sup> <a name="Memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory"></a>

```csharp
public double Memory { get; set; }
```

- *Type:* double

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#memory RegistryImage#memory}

---

##### `MemorySwap`<sup>Optional</sup> <a name="MemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap"></a>

```csharp
public double MemorySwap { get; set; }
```

- *Type:* double

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#memory_swap RegistryImage#memory_swap}

---

##### `NetworkMode`<sup>Optional</sup> <a name="NetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode"></a>

```csharp
public string NetworkMode { get; set; }
```

- *Type:* string

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#network_mode RegistryImage#network_mode}

---

##### `NoCache`<sup>Optional</sup> <a name="NoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache"></a>

```csharp
public bool|IResolvable NoCache { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#no_cache RegistryImage#no_cache}

---

##### `Platform`<sup>Optional</sup> <a name="Platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform"></a>

```csharp
public string Platform { get; set; }
```

- *Type:* string

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#platform RegistryImage#platform}

---

##### `Provenance`<sup>Optional</sup> <a name="Provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance"></a>

```csharp
public string Provenance { get; set; }
```

- *Type:* string

Set provenance attestation for the build.

BuildKit v0.11+ adds provenance attestations by default, which creates OCI image manifests that some registries (like AWS Lambda) don't support. Set to `false` to disable. Valid values: `false`, `true`, `min`, `max`, `mode=min`, `mode=max`, or a full provenance specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#provenance RegistryImage#provenance}

---

##### `PullParent`<sup>Optional</sup> <a name="PullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent"></a>

```csharp
public bool|IResolvable PullParent { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#pull_parent RegistryImage#pull_parent}

---

##### `RemoteContext`<sup>Optional</sup> <a name="RemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext"></a>

```csharp
public string RemoteContext { get; set; }
```

- *Type:* string

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#remote_context RegistryImage#remote_context}

---

##### `Remove`<sup>Optional</sup> <a name="Remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove"></a>

```csharp
public bool|IResolvable Remove { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#remove RegistryImage#remove}

---

##### `Sbom`<sup>Optional</sup> <a name="Sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom"></a>

```csharp
public string Sbom { get; set; }
```

- *Type:* string

Set SBOM (Software Bill of Materials) attestation for the build.

Set to `false` to disable. Valid values: `false`, `true`, or a full SBOM specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#sbom RegistryImage#sbom}

---

##### `Secrets`<sup>Optional</sup> <a name="Secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets"></a>

```csharp
public IResolvable|RegistryImageBuildSecrets[] Secrets { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#secrets RegistryImage#secrets}

---

##### `SecurityOpt`<sup>Optional</sup> <a name="SecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt"></a>

```csharp
public string[] SecurityOpt { get; set; }
```

- *Type:* string[]

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#security_opt RegistryImage#security_opt}

---

##### `SessionId`<sup>Optional</sup> <a name="SessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId"></a>

```csharp
public string SessionId { get; set; }
```

- *Type:* string

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#session_id RegistryImage#session_id}

---

##### `ShmSize`<sup>Optional</sup> <a name="ShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize"></a>

```csharp
public double ShmSize { get; set; }
```

- *Type:* double

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#shm_size RegistryImage#shm_size}

---

##### `Squash`<sup>Optional</sup> <a name="Squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash"></a>

```csharp
public bool|IResolvable Squash { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#squash RegistryImage#squash}

---

##### `SuppressOutput`<sup>Optional</sup> <a name="SuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput"></a>

```csharp
public bool|IResolvable SuppressOutput { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#suppress_output RegistryImage#suppress_output}

---

##### `Tag`<sup>Optional</sup> <a name="Tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag"></a>

```csharp
public string[] Tag { get; set; }
```

- *Type:* string[]

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#tag RegistryImage#tag}

---

##### `Target`<sup>Optional</sup> <a name="Target" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target"></a>

```csharp
public string Target { get; set; }
```

- *Type:* string

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#target RegistryImage#target}

---

##### `Ulimit`<sup>Optional</sup> <a name="Ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit"></a>

```csharp
public IResolvable|RegistryImageBuildUlimit[] Ulimit { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#ulimit RegistryImage#ulimit}

---

##### `UseLegacyBuilder`<sup>Optional</sup> <a name="UseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder"></a>

```csharp
public bool|IResolvable UseLegacyBuilder { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#use_legacy_builder RegistryImage#use_legacy_builder}

---

##### `Version`<sup>Optional</sup> <a name="Version" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version"></a>

```csharp
public string Version { get; set; }
```

- *Type:* string

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#version RegistryImage#version}

---

### RegistryImageBuildAuthConfig <a name="RegistryImageBuildAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildAuthConfig {
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
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName">HostName</a></code> | <code>string</code> | hostname of the registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth">Auth</a></code> | <code>string</code> | the auth token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email">Email</a></code> | <code>string</code> | the user emal. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken">IdentityToken</a></code> | <code>string</code> | the identity token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password">Password</a></code> | <code>string</code> | the registry password. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken">RegistryToken</a></code> | <code>string</code> | the registry token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress">ServerAddress</a></code> | <code>string</code> | the server address. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName">UserName</a></code> | <code>string</code> | the registry user name. |

---

##### `HostName`<sup>Required</sup> <a name="HostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName"></a>

```csharp
public string HostName { get; set; }
```

- *Type:* string

hostname of the registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#host_name RegistryImage#host_name}

---

##### `Auth`<sup>Optional</sup> <a name="Auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth"></a>

```csharp
public string Auth { get; set; }
```

- *Type:* string

the auth token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#auth RegistryImage#auth}

---

##### `Email`<sup>Optional</sup> <a name="Email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email"></a>

```csharp
public string Email { get; set; }
```

- *Type:* string

the user emal.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#email RegistryImage#email}

---

##### `IdentityToken`<sup>Optional</sup> <a name="IdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken"></a>

```csharp
public string IdentityToken { get; set; }
```

- *Type:* string

the identity token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#identity_token RegistryImage#identity_token}

---

##### `Password`<sup>Optional</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password"></a>

```csharp
public string Password { get; set; }
```

- *Type:* string

the registry password.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `RegistryToken`<sup>Optional</sup> <a name="RegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken"></a>

```csharp
public string RegistryToken { get; set; }
```

- *Type:* string

the registry token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#registry_token RegistryImage#registry_token}

---

##### `ServerAddress`<sup>Optional</sup> <a name="ServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress"></a>

```csharp
public string ServerAddress { get; set; }
```

- *Type:* string

the server address.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#server_address RegistryImage#server_address}

---

##### `UserName`<sup>Optional</sup> <a name="UserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName"></a>

```csharp
public string UserName { get; set; }
```

- *Type:* string

the registry user name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#user_name RegistryImage#user_name}

---

### RegistryImageBuildSecrets <a name="RegistryImageBuildSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildSecrets {
    string Id,
    string Env = null,
    string Src = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id">Id</a></code> | <code>string</code> | ID of the secret. By default, secrets are mounted to /run/secrets/<id>. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env">Env</a></code> | <code>string</code> | Environment variable source of the secret. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src">Src</a></code> | <code>string</code> | File source of the secret. Takes precedence over `env`. |

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

ID of the secret. By default, secrets are mounted to /run/secrets/<id>.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#id RegistryImage#id}

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Env`<sup>Optional</sup> <a name="Env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env"></a>

```csharp
public string Env { get; set; }
```

- *Type:* string

Environment variable source of the secret.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#env RegistryImage#env}

---

##### `Src`<sup>Optional</sup> <a name="Src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src"></a>

```csharp
public string Src { get; set; }
```

- *Type:* string

File source of the secret. Takes precedence over `env`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#src RegistryImage#src}

---

### RegistryImageBuildUlimit <a name="RegistryImageBuildUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildUlimit {
    double Hard,
    string Name,
    double Soft
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard">Hard</a></code> | <code>double</code> | soft limit. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name">Name</a></code> | <code>string</code> | type of ulimit, e.g. `nofile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft">Soft</a></code> | <code>double</code> | hard limit. |

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard"></a>

```csharp
public double Hard { get; set; }
```

- *Type:* double

soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#hard RegistryImage#hard}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

type of ulimit, e.g. `nofile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft"></a>

```csharp
public double Soft { get; set; }
```

- *Type:* double

hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#soft RegistryImage#soft}

---

### RegistryImageConfig <a name="RegistryImageConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string Name,
    RegistryImageAuthConfig AuthConfig = null,
    RegistryImageBuild BuildAttribute = null,
    string Id = null,
    bool|IResolvable InsecureSkipVerify = null,
    bool|IResolvable KeepRemotely = null,
    RegistryImageTimeouts Timeouts = null,
    System.Collections.Generic.IDictionary<string, string> Triggers = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name">Name</a></code> | <code>string</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute">BuildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely">KeepRemotely</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers">Triggers</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `AuthConfig`<sup>Optional</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig"></a>

```csharp
public RegistryImageAuthConfig AuthConfig { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `BuildAttribute`<sup>Optional</sup> <a name="BuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute"></a>

```csharp
public RegistryImageBuild BuildAttribute { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `InsecureSkipVerify`<sup>Optional</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify"></a>

```csharp
public bool|IResolvable InsecureSkipVerify { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `KeepRemotely`<sup>Optional</sup> <a name="KeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely"></a>

```csharp
public bool|IResolvable KeepRemotely { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `Timeouts`<sup>Optional</sup> <a name="Timeouts" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts"></a>

```csharp
public RegistryImageTimeouts Timeouts { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `Triggers`<sup>Optional</sup> <a name="Triggers" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Triggers { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

### RegistryImageTimeouts <a name="RegistryImageTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageTimeouts {
    string Create = null,
    string Delete = null,
    string Update = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create">Create</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#create RegistryImage#create}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete">Delete</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#delete RegistryImage#delete}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update">Update</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#update RegistryImage#update}. |

---

##### `Create`<sup>Optional</sup> <a name="Create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create"></a>

```csharp
public string Create { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#create RegistryImage#create}.

---

##### `Delete`<sup>Optional</sup> <a name="Delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete"></a>

```csharp
public string Delete { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#delete RegistryImage#delete}.

---

##### `Update`<sup>Optional</sup> <a name="Update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update"></a>

```csharp
public string Update { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/registry_image#update RegistryImage#update}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistryImageAuthConfigOutputReference <a name="RegistryImageAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageAuthConfigOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword">ResetPassword</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername">ResetUsername</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetPassword` <a name="ResetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword"></a>

```csharp
private void ResetPassword()
```

##### `ResetUsername` <a name="ResetUsername" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername"></a>

```csharp
private void ResetUsername()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput">AddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput">PasswordInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput">UsernameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address">Address</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password">Password</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username">Username</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AddressInput`<sup>Optional</sup> <a name="AddressInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput"></a>

```csharp
public string AddressInput { get; }
```

- *Type:* string

---

##### `PasswordInput`<sup>Optional</sup> <a name="PasswordInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput"></a>

```csharp
public string PasswordInput { get; }
```

- *Type:* string

---

##### `UsernameInput`<sup>Optional</sup> <a name="UsernameInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput"></a>

```csharp
public string UsernameInput { get; }
```

- *Type:* string

---

##### `Address`<sup>Required</sup> <a name="Address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address"></a>

```csharp
public string Address { get; }
```

- *Type:* string

---

##### `Password`<sup>Required</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password"></a>

```csharp
public string Password { get; }
```

- *Type:* string

---

##### `Username`<sup>Required</sup> <a name="Username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username"></a>

```csharp
public string Username { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue"></a>

```csharp
public RegistryImageAuthConfig InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---


### RegistryImageBuildAuthConfigList <a name="RegistryImageBuildAuthConfigList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildAuthConfigList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get"></a>

```csharp
private RegistryImageBuildAuthConfigOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageBuildAuthConfig[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

---


### RegistryImageBuildAuthConfigOutputReference <a name="RegistryImageBuildAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildAuthConfigOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth">ResetAuth</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail">ResetEmail</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken">ResetIdentityToken</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword">ResetPassword</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken">ResetRegistryToken</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress">ResetServerAddress</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName">ResetUserName</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAuth` <a name="ResetAuth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth"></a>

```csharp
private void ResetAuth()
```

##### `ResetEmail` <a name="ResetEmail" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail"></a>

```csharp
private void ResetEmail()
```

##### `ResetIdentityToken` <a name="ResetIdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken"></a>

```csharp
private void ResetIdentityToken()
```

##### `ResetPassword` <a name="ResetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword"></a>

```csharp
private void ResetPassword()
```

##### `ResetRegistryToken` <a name="ResetRegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken"></a>

```csharp
private void ResetRegistryToken()
```

##### `ResetServerAddress` <a name="ResetServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress"></a>

```csharp
private void ResetServerAddress()
```

##### `ResetUserName` <a name="ResetUserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName"></a>

```csharp
private void ResetUserName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput">AuthInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput">EmailInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput">HostNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput">IdentityTokenInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput">PasswordInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput">RegistryTokenInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput">ServerAddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput">UserNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth">Auth</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email">Email</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName">HostName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken">IdentityToken</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password">Password</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken">RegistryToken</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress">ServerAddress</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName">UserName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AuthInput`<sup>Optional</sup> <a name="AuthInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput"></a>

```csharp
public string AuthInput { get; }
```

- *Type:* string

---

##### `EmailInput`<sup>Optional</sup> <a name="EmailInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput"></a>

```csharp
public string EmailInput { get; }
```

- *Type:* string

---

##### `HostNameInput`<sup>Optional</sup> <a name="HostNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput"></a>

```csharp
public string HostNameInput { get; }
```

- *Type:* string

---

##### `IdentityTokenInput`<sup>Optional</sup> <a name="IdentityTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput"></a>

```csharp
public string IdentityTokenInput { get; }
```

- *Type:* string

---

##### `PasswordInput`<sup>Optional</sup> <a name="PasswordInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput"></a>

```csharp
public string PasswordInput { get; }
```

- *Type:* string

---

##### `RegistryTokenInput`<sup>Optional</sup> <a name="RegistryTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput"></a>

```csharp
public string RegistryTokenInput { get; }
```

- *Type:* string

---

##### `ServerAddressInput`<sup>Optional</sup> <a name="ServerAddressInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput"></a>

```csharp
public string ServerAddressInput { get; }
```

- *Type:* string

---

##### `UserNameInput`<sup>Optional</sup> <a name="UserNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput"></a>

```csharp
public string UserNameInput { get; }
```

- *Type:* string

---

##### `Auth`<sup>Required</sup> <a name="Auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth"></a>

```csharp
public string Auth { get; }
```

- *Type:* string

---

##### `Email`<sup>Required</sup> <a name="Email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email"></a>

```csharp
public string Email { get; }
```

- *Type:* string

---

##### `HostName`<sup>Required</sup> <a name="HostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName"></a>

```csharp
public string HostName { get; }
```

- *Type:* string

---

##### `IdentityToken`<sup>Required</sup> <a name="IdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken"></a>

```csharp
public string IdentityToken { get; }
```

- *Type:* string

---

##### `Password`<sup>Required</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password"></a>

```csharp
public string Password { get; }
```

- *Type:* string

---

##### `RegistryToken`<sup>Required</sup> <a name="RegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken"></a>

```csharp
public string RegistryToken { get; }
```

- *Type:* string

---

##### `ServerAddress`<sup>Required</sup> <a name="ServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress"></a>

```csharp
public string ServerAddress { get; }
```

- *Type:* string

---

##### `UserName`<sup>Required</sup> <a name="UserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName"></a>

```csharp
public string UserName { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageBuildAuthConfig InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>

---


### RegistryImageBuildOutputReference <a name="RegistryImageBuildOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig">PutAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets">PutSecrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit">PutUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts">ResetAdditionalContexts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig">ResetAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs">ResetBuildArgs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder">ResetBuilder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId">ResetBuildId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile">ResetBuildLogFile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom">ResetCacheFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo">ResetCacheTo</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent">ResetCgroupParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod">ResetCpuPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota">ResetCpuQuota</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus">ResetCpuSetCpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems">ResetCpuSetMems</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares">ResetCpuShares</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile">ResetDockerfile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts">ResetExtraHosts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove">ResetForceRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation">ResetIsolation</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel">ResetLabel</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels">ResetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory">ResetMemory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap">ResetMemorySwap</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode">ResetNetworkMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache">ResetNoCache</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform">ResetPlatform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance">ResetProvenance</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent">ResetPullParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext">ResetRemoteContext</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove">ResetRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom">ResetSbom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets">ResetSecrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt">ResetSecurityOpt</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId">ResetSessionId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize">ResetShmSize</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash">ResetSquash</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput">ResetSuppressOutput</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag">ResetTag</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget">ResetTarget</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit">ResetUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder">ResetUseLegacyBuilder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion">ResetVersion</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutAuthConfig` <a name="PutAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig"></a>

```csharp
private void PutAuthConfig(IResolvable|RegistryImageBuildAuthConfig[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

---

##### `PutSecrets` <a name="PutSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets"></a>

```csharp
private void PutSecrets(IResolvable|RegistryImageBuildSecrets[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

---

##### `PutUlimit` <a name="PutUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit"></a>

```csharp
private void PutUlimit(IResolvable|RegistryImageBuildUlimit[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

---

##### `ResetAdditionalContexts` <a name="ResetAdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts"></a>

```csharp
private void ResetAdditionalContexts()
```

##### `ResetAuthConfig` <a name="ResetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig"></a>

```csharp
private void ResetAuthConfig()
```

##### `ResetBuildArgs` <a name="ResetBuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs"></a>

```csharp
private void ResetBuildArgs()
```

##### `ResetBuilder` <a name="ResetBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder"></a>

```csharp
private void ResetBuilder()
```

##### `ResetBuildId` <a name="ResetBuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId"></a>

```csharp
private void ResetBuildId()
```

##### `ResetBuildLogFile` <a name="ResetBuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile"></a>

```csharp
private void ResetBuildLogFile()
```

##### `ResetCacheFrom` <a name="ResetCacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom"></a>

```csharp
private void ResetCacheFrom()
```

##### `ResetCacheTo` <a name="ResetCacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo"></a>

```csharp
private void ResetCacheTo()
```

##### `ResetCgroupParent` <a name="ResetCgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent"></a>

```csharp
private void ResetCgroupParent()
```

##### `ResetCpuPeriod` <a name="ResetCpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod"></a>

```csharp
private void ResetCpuPeriod()
```

##### `ResetCpuQuota` <a name="ResetCpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota"></a>

```csharp
private void ResetCpuQuota()
```

##### `ResetCpuSetCpus` <a name="ResetCpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus"></a>

```csharp
private void ResetCpuSetCpus()
```

##### `ResetCpuSetMems` <a name="ResetCpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems"></a>

```csharp
private void ResetCpuSetMems()
```

##### `ResetCpuShares` <a name="ResetCpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares"></a>

```csharp
private void ResetCpuShares()
```

##### `ResetDockerfile` <a name="ResetDockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile"></a>

```csharp
private void ResetDockerfile()
```

##### `ResetExtraHosts` <a name="ResetExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts"></a>

```csharp
private void ResetExtraHosts()
```

##### `ResetForceRemove` <a name="ResetForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove"></a>

```csharp
private void ResetForceRemove()
```

##### `ResetIsolation` <a name="ResetIsolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation"></a>

```csharp
private void ResetIsolation()
```

##### `ResetLabel` <a name="ResetLabel" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel"></a>

```csharp
private void ResetLabel()
```

##### `ResetLabels` <a name="ResetLabels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels"></a>

```csharp
private void ResetLabels()
```

##### `ResetMemory` <a name="ResetMemory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory"></a>

```csharp
private void ResetMemory()
```

##### `ResetMemorySwap` <a name="ResetMemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap"></a>

```csharp
private void ResetMemorySwap()
```

##### `ResetNetworkMode` <a name="ResetNetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode"></a>

```csharp
private void ResetNetworkMode()
```

##### `ResetNoCache` <a name="ResetNoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache"></a>

```csharp
private void ResetNoCache()
```

##### `ResetPlatform` <a name="ResetPlatform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform"></a>

```csharp
private void ResetPlatform()
```

##### `ResetProvenance` <a name="ResetProvenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance"></a>

```csharp
private void ResetProvenance()
```

##### `ResetPullParent` <a name="ResetPullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent"></a>

```csharp
private void ResetPullParent()
```

##### `ResetRemoteContext` <a name="ResetRemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext"></a>

```csharp
private void ResetRemoteContext()
```

##### `ResetRemove` <a name="ResetRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove"></a>

```csharp
private void ResetRemove()
```

##### `ResetSbom` <a name="ResetSbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom"></a>

```csharp
private void ResetSbom()
```

##### `ResetSecrets` <a name="ResetSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets"></a>

```csharp
private void ResetSecrets()
```

##### `ResetSecurityOpt` <a name="ResetSecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt"></a>

```csharp
private void ResetSecurityOpt()
```

##### `ResetSessionId` <a name="ResetSessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId"></a>

```csharp
private void ResetSessionId()
```

##### `ResetShmSize` <a name="ResetShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize"></a>

```csharp
private void ResetShmSize()
```

##### `ResetSquash` <a name="ResetSquash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash"></a>

```csharp
private void ResetSquash()
```

##### `ResetSuppressOutput` <a name="ResetSuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput"></a>

```csharp
private void ResetSuppressOutput()
```

##### `ResetTag` <a name="ResetTag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag"></a>

```csharp
private void ResetTag()
```

##### `ResetTarget` <a name="ResetTarget" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget"></a>

```csharp
private void ResetTarget()
```

##### `ResetUlimit` <a name="ResetUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit"></a>

```csharp
private void ResetUlimit()
```

##### `ResetUseLegacyBuilder` <a name="ResetUseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder"></a>

```csharp
private void ResetUseLegacyBuilder()
```

##### `ResetVersion` <a name="ResetVersion" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion"></a>

```csharp
private void ResetVersion()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets">Secrets</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit">Ulimit</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput">AdditionalContextsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput">AuthConfigInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput">BuildArgsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput">BuilderInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput">BuildIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput">BuildLogFileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput">CacheFromInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput">CacheToInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput">CgroupParentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput">ContextInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput">CpuPeriodInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput">CpuQuotaInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput">CpuSetCpusInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput">CpuSetMemsInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput">CpuSharesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput">DockerfileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput">ExtraHostsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput">ForceRemoveInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput">IsolationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput">LabelInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput">LabelsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput">MemoryInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput">MemorySwapInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput">NetworkModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput">NoCacheInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput">PlatformInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput">ProvenanceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput">PullParentInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput">RemoteContextInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput">RemoveInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput">SbomInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput">SecretsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput">SecurityOptInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput">SessionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput">ShmSizeInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput">SquashInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput">SuppressOutputInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput">TagInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput">TargetInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput">UlimitInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput">UseLegacyBuilderInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput">VersionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts">AdditionalContexts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs">BuildArgs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder">Builder</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId">BuildId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile">BuildLogFile</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom">CacheFrom</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo">CacheTo</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent">CgroupParent</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context">Context</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod">CpuPeriod</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota">CpuQuota</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus">CpuSetCpus</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems">CpuSetMems</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares">CpuShares</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile">Dockerfile</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts">ExtraHosts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove">ForceRemove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation">Isolation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label">Label</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels">Labels</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory">Memory</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap">MemorySwap</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode">NetworkMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache">NoCache</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform">Platform</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance">Provenance</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent">PullParent</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext">RemoteContext</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove">Remove</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom">Sbom</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt">SecurityOpt</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId">SessionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize">ShmSize</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash">Squash</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput">SuppressOutput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag">Tag</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target">Target</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder">UseLegacyBuilder</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version">Version</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AuthConfig`<sup>Required</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig"></a>

```csharp
public RegistryImageBuildAuthConfigList AuthConfig { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a>

---

##### `Secrets`<sup>Required</sup> <a name="Secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets"></a>

```csharp
public RegistryImageBuildSecretsList Secrets { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a>

---

##### `Ulimit`<sup>Required</sup> <a name="Ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit"></a>

```csharp
public RegistryImageBuildUlimitList Ulimit { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a>

---

##### `AdditionalContextsInput`<sup>Optional</sup> <a name="AdditionalContextsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput"></a>

```csharp
public string[] AdditionalContextsInput { get; }
```

- *Type:* string[]

---

##### `AuthConfigInput`<sup>Optional</sup> <a name="AuthConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput"></a>

```csharp
public IResolvable|RegistryImageBuildAuthConfig[] AuthConfigInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

---

##### `BuildArgsInput`<sup>Optional</sup> <a name="BuildArgsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> BuildArgsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `BuilderInput`<sup>Optional</sup> <a name="BuilderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput"></a>

```csharp
public string BuilderInput { get; }
```

- *Type:* string

---

##### `BuildIdInput`<sup>Optional</sup> <a name="BuildIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput"></a>

```csharp
public string BuildIdInput { get; }
```

- *Type:* string

---

##### `BuildLogFileInput`<sup>Optional</sup> <a name="BuildLogFileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput"></a>

```csharp
public string BuildLogFileInput { get; }
```

- *Type:* string

---

##### `CacheFromInput`<sup>Optional</sup> <a name="CacheFromInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput"></a>

```csharp
public string[] CacheFromInput { get; }
```

- *Type:* string[]

---

##### `CacheToInput`<sup>Optional</sup> <a name="CacheToInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput"></a>

```csharp
public string[] CacheToInput { get; }
```

- *Type:* string[]

---

##### `CgroupParentInput`<sup>Optional</sup> <a name="CgroupParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput"></a>

```csharp
public string CgroupParentInput { get; }
```

- *Type:* string

---

##### `ContextInput`<sup>Optional</sup> <a name="ContextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput"></a>

```csharp
public string ContextInput { get; }
```

- *Type:* string

---

##### `CpuPeriodInput`<sup>Optional</sup> <a name="CpuPeriodInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput"></a>

```csharp
public double CpuPeriodInput { get; }
```

- *Type:* double

---

##### `CpuQuotaInput`<sup>Optional</sup> <a name="CpuQuotaInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput"></a>

```csharp
public double CpuQuotaInput { get; }
```

- *Type:* double

---

##### `CpuSetCpusInput`<sup>Optional</sup> <a name="CpuSetCpusInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput"></a>

```csharp
public string CpuSetCpusInput { get; }
```

- *Type:* string

---

##### `CpuSetMemsInput`<sup>Optional</sup> <a name="CpuSetMemsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput"></a>

```csharp
public string CpuSetMemsInput { get; }
```

- *Type:* string

---

##### `CpuSharesInput`<sup>Optional</sup> <a name="CpuSharesInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput"></a>

```csharp
public double CpuSharesInput { get; }
```

- *Type:* double

---

##### `DockerfileInput`<sup>Optional</sup> <a name="DockerfileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput"></a>

```csharp
public string DockerfileInput { get; }
```

- *Type:* string

---

##### `ExtraHostsInput`<sup>Optional</sup> <a name="ExtraHostsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput"></a>

```csharp
public string[] ExtraHostsInput { get; }
```

- *Type:* string[]

---

##### `ForceRemoveInput`<sup>Optional</sup> <a name="ForceRemoveInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput"></a>

```csharp
public bool|IResolvable ForceRemoveInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `IsolationInput`<sup>Optional</sup> <a name="IsolationInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput"></a>

```csharp
public string IsolationInput { get; }
```

- *Type:* string

---

##### `LabelInput`<sup>Optional</sup> <a name="LabelInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LabelInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `LabelsInput`<sup>Optional</sup> <a name="LabelsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LabelsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `MemoryInput`<sup>Optional</sup> <a name="MemoryInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput"></a>

```csharp
public double MemoryInput { get; }
```

- *Type:* double

---

##### `MemorySwapInput`<sup>Optional</sup> <a name="MemorySwapInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput"></a>

```csharp
public double MemorySwapInput { get; }
```

- *Type:* double

---

##### `NetworkModeInput`<sup>Optional</sup> <a name="NetworkModeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput"></a>

```csharp
public string NetworkModeInput { get; }
```

- *Type:* string

---

##### `NoCacheInput`<sup>Optional</sup> <a name="NoCacheInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput"></a>

```csharp
public bool|IResolvable NoCacheInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `PlatformInput`<sup>Optional</sup> <a name="PlatformInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput"></a>

```csharp
public string PlatformInput { get; }
```

- *Type:* string

---

##### `ProvenanceInput`<sup>Optional</sup> <a name="ProvenanceInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput"></a>

```csharp
public string ProvenanceInput { get; }
```

- *Type:* string

---

##### `PullParentInput`<sup>Optional</sup> <a name="PullParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput"></a>

```csharp
public bool|IResolvable PullParentInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RemoteContextInput`<sup>Optional</sup> <a name="RemoteContextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput"></a>

```csharp
public string RemoteContextInput { get; }
```

- *Type:* string

---

##### `RemoveInput`<sup>Optional</sup> <a name="RemoveInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput"></a>

```csharp
public bool|IResolvable RemoveInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SbomInput`<sup>Optional</sup> <a name="SbomInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput"></a>

```csharp
public string SbomInput { get; }
```

- *Type:* string

---

##### `SecretsInput`<sup>Optional</sup> <a name="SecretsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput"></a>

```csharp
public IResolvable|RegistryImageBuildSecrets[] SecretsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

---

##### `SecurityOptInput`<sup>Optional</sup> <a name="SecurityOptInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput"></a>

```csharp
public string[] SecurityOptInput { get; }
```

- *Type:* string[]

---

##### `SessionIdInput`<sup>Optional</sup> <a name="SessionIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput"></a>

```csharp
public string SessionIdInput { get; }
```

- *Type:* string

---

##### `ShmSizeInput`<sup>Optional</sup> <a name="ShmSizeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput"></a>

```csharp
public double ShmSizeInput { get; }
```

- *Type:* double

---

##### `SquashInput`<sup>Optional</sup> <a name="SquashInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput"></a>

```csharp
public bool|IResolvable SquashInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SuppressOutputInput`<sup>Optional</sup> <a name="SuppressOutputInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput"></a>

```csharp
public bool|IResolvable SuppressOutputInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `TagInput`<sup>Optional</sup> <a name="TagInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput"></a>

```csharp
public string[] TagInput { get; }
```

- *Type:* string[]

---

##### `TargetInput`<sup>Optional</sup> <a name="TargetInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput"></a>

```csharp
public string TargetInput { get; }
```

- *Type:* string

---

##### `UlimitInput`<sup>Optional</sup> <a name="UlimitInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput"></a>

```csharp
public IResolvable|RegistryImageBuildUlimit[] UlimitInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

---

##### `UseLegacyBuilderInput`<sup>Optional</sup> <a name="UseLegacyBuilderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput"></a>

```csharp
public bool|IResolvable UseLegacyBuilderInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `VersionInput`<sup>Optional</sup> <a name="VersionInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput"></a>

```csharp
public string VersionInput { get; }
```

- *Type:* string

---

##### `AdditionalContexts`<sup>Required</sup> <a name="AdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts"></a>

```csharp
public string[] AdditionalContexts { get; }
```

- *Type:* string[]

---

##### `BuildArgs`<sup>Required</sup> <a name="BuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> BuildArgs { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Builder`<sup>Required</sup> <a name="Builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder"></a>

```csharp
public string Builder { get; }
```

- *Type:* string

---

##### `BuildId`<sup>Required</sup> <a name="BuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId"></a>

```csharp
public string BuildId { get; }
```

- *Type:* string

---

##### `BuildLogFile`<sup>Required</sup> <a name="BuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile"></a>

```csharp
public string BuildLogFile { get; }
```

- *Type:* string

---

##### `CacheFrom`<sup>Required</sup> <a name="CacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom"></a>

```csharp
public string[] CacheFrom { get; }
```

- *Type:* string[]

---

##### `CacheTo`<sup>Required</sup> <a name="CacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo"></a>

```csharp
public string[] CacheTo { get; }
```

- *Type:* string[]

---

##### `CgroupParent`<sup>Required</sup> <a name="CgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent"></a>

```csharp
public string CgroupParent { get; }
```

- *Type:* string

---

##### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context"></a>

```csharp
public string Context { get; }
```

- *Type:* string

---

##### `CpuPeriod`<sup>Required</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod"></a>

```csharp
public double CpuPeriod { get; }
```

- *Type:* double

---

##### `CpuQuota`<sup>Required</sup> <a name="CpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota"></a>

```csharp
public double CpuQuota { get; }
```

- *Type:* double

---

##### `CpuSetCpus`<sup>Required</sup> <a name="CpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus"></a>

```csharp
public string CpuSetCpus { get; }
```

- *Type:* string

---

##### `CpuSetMems`<sup>Required</sup> <a name="CpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems"></a>

```csharp
public string CpuSetMems { get; }
```

- *Type:* string

---

##### `CpuShares`<sup>Required</sup> <a name="CpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares"></a>

```csharp
public double CpuShares { get; }
```

- *Type:* double

---

##### `Dockerfile`<sup>Required</sup> <a name="Dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile"></a>

```csharp
public string Dockerfile { get; }
```

- *Type:* string

---

##### `ExtraHosts`<sup>Required</sup> <a name="ExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts"></a>

```csharp
public string[] ExtraHosts { get; }
```

- *Type:* string[]

---

##### `ForceRemove`<sup>Required</sup> <a name="ForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove"></a>

```csharp
public bool|IResolvable ForceRemove { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Isolation`<sup>Required</sup> <a name="Isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation"></a>

```csharp
public string Isolation { get; }
```

- *Type:* string

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Label { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Labels`<sup>Required</sup> <a name="Labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Labels { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Memory`<sup>Required</sup> <a name="Memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory"></a>

```csharp
public double Memory { get; }
```

- *Type:* double

---

##### `MemorySwap`<sup>Required</sup> <a name="MemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap"></a>

```csharp
public double MemorySwap { get; }
```

- *Type:* double

---

##### `NetworkMode`<sup>Required</sup> <a name="NetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode"></a>

```csharp
public string NetworkMode { get; }
```

- *Type:* string

---

##### `NoCache`<sup>Required</sup> <a name="NoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache"></a>

```csharp
public bool|IResolvable NoCache { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Platform`<sup>Required</sup> <a name="Platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform"></a>

```csharp
public string Platform { get; }
```

- *Type:* string

---

##### `Provenance`<sup>Required</sup> <a name="Provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance"></a>

```csharp
public string Provenance { get; }
```

- *Type:* string

---

##### `PullParent`<sup>Required</sup> <a name="PullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent"></a>

```csharp
public bool|IResolvable PullParent { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RemoteContext`<sup>Required</sup> <a name="RemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext"></a>

```csharp
public string RemoteContext { get; }
```

- *Type:* string

---

##### `Remove`<sup>Required</sup> <a name="Remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove"></a>

```csharp
public bool|IResolvable Remove { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Sbom`<sup>Required</sup> <a name="Sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom"></a>

```csharp
public string Sbom { get; }
```

- *Type:* string

---

##### `SecurityOpt`<sup>Required</sup> <a name="SecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt"></a>

```csharp
public string[] SecurityOpt { get; }
```

- *Type:* string[]

---

##### `SessionId`<sup>Required</sup> <a name="SessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId"></a>

```csharp
public string SessionId { get; }
```

- *Type:* string

---

##### `ShmSize`<sup>Required</sup> <a name="ShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize"></a>

```csharp
public double ShmSize { get; }
```

- *Type:* double

---

##### `Squash`<sup>Required</sup> <a name="Squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash"></a>

```csharp
public bool|IResolvable Squash { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SuppressOutput`<sup>Required</sup> <a name="SuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput"></a>

```csharp
public bool|IResolvable SuppressOutput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Tag`<sup>Required</sup> <a name="Tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag"></a>

```csharp
public string[] Tag { get; }
```

- *Type:* string[]

---

##### `Target`<sup>Required</sup> <a name="Target" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target"></a>

```csharp
public string Target { get; }
```

- *Type:* string

---

##### `UseLegacyBuilder`<sup>Required</sup> <a name="UseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder"></a>

```csharp
public bool|IResolvable UseLegacyBuilder { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Version`<sup>Required</sup> <a name="Version" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version"></a>

```csharp
public string Version { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue"></a>

```csharp
public RegistryImageBuild InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---


### RegistryImageBuildSecretsList <a name="RegistryImageBuildSecretsList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildSecretsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get"></a>

```csharp
private RegistryImageBuildSecretsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageBuildSecrets[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

---


### RegistryImageBuildSecretsOutputReference <a name="RegistryImageBuildSecretsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildSecretsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv">ResetEnv</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc">ResetSrc</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetEnv` <a name="ResetEnv" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv"></a>

```csharp
private void ResetEnv()
```

##### `ResetSrc` <a name="ResetSrc" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc"></a>

```csharp
private void ResetSrc()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput">EnvInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput">SrcInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env">Env</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src">Src</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `EnvInput`<sup>Optional</sup> <a name="EnvInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput"></a>

```csharp
public string EnvInput { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `SrcInput`<sup>Optional</sup> <a name="SrcInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput"></a>

```csharp
public string SrcInput { get; }
```

- *Type:* string

---

##### `Env`<sup>Required</sup> <a name="Env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env"></a>

```csharp
public string Env { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Src`<sup>Required</sup> <a name="Src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src"></a>

```csharp
public string Src { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageBuildSecrets InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>

---


### RegistryImageBuildUlimitList <a name="RegistryImageBuildUlimitList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildUlimitList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get"></a>

```csharp
private RegistryImageBuildUlimitOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageBuildUlimit[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

---


### RegistryImageBuildUlimitOutputReference <a name="RegistryImageBuildUlimitOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageBuildUlimitOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput">HardInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput">SoftInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard">Hard</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft">Soft</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `HardInput`<sup>Optional</sup> <a name="HardInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput"></a>

```csharp
public double HardInput { get; }
```

- *Type:* double

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `SoftInput`<sup>Optional</sup> <a name="SoftInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput"></a>

```csharp
public double SoftInput { get; }
```

- *Type:* double

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard"></a>

```csharp
public double Hard { get; }
```

- *Type:* double

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft"></a>

```csharp
public double Soft { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageBuildUlimit InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>

---


### RegistryImageTimeoutsOutputReference <a name="RegistryImageTimeoutsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new RegistryImageTimeoutsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate">ResetCreate</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete">ResetDelete</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate">ResetUpdate</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetCreate` <a name="ResetCreate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate"></a>

```csharp
private void ResetCreate()
```

##### `ResetDelete` <a name="ResetDelete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete"></a>

```csharp
private void ResetDelete()
```

##### `ResetUpdate` <a name="ResetUpdate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate"></a>

```csharp
private void ResetUpdate()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput">CreateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput">DeleteInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput">UpdateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create">Create</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete">Delete</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update">Update</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `CreateInput`<sup>Optional</sup> <a name="CreateInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput"></a>

```csharp
public string CreateInput { get; }
```

- *Type:* string

---

##### `DeleteInput`<sup>Optional</sup> <a name="DeleteInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput"></a>

```csharp
public string DeleteInput { get; }
```

- *Type:* string

---

##### `UpdateInput`<sup>Optional</sup> <a name="UpdateInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput"></a>

```csharp
public string UpdateInput { get; }
```

- *Type:* string

---

##### `Create`<sup>Required</sup> <a name="Create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create"></a>

```csharp
public string Create { get; }
```

- *Type:* string

---

##### `Delete`<sup>Required</sup> <a name="Delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete"></a>

```csharp
public string Delete { get; }
```

- *Type:* string

---

##### `Update`<sup>Required</sup> <a name="Update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update"></a>

```csharp
public string Update { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|RegistryImageTimeouts InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---



