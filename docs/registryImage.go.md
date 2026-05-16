# `registryImage` Submodule <a name="`registryImage` Submodule" id="@cdktn/provider-docker.registryImage"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### RegistryImage <a name="RegistryImage" id="@cdktn/provider-docker.registryImage.RegistryImage"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image docker_registry_image}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImage(scope Construct, id *string, config RegistryImageConfig) RegistryImage
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig">RegistryImageConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.config"></a>

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

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.registryImage.RegistryImage.with"></a>

```go
func With(mixins ...IMixin) IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.registryImage.RegistryImage.with.parameter.mixins"></a>

- *Type:* ...github.com/aws/constructs-go/constructs/v10.IMixin

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove"></a>

```go
func HasResourceMove() interface{}
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId"></a>

```go
func MoveFromId(id *string)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId.parameter.id"></a>

- *Type:* *string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId"></a>

```go
func MoveToId(id *string)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId.parameter.id"></a>

- *Type:* *string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutAuthConfig` <a name="PutAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig"></a>

```go
func PutAuthConfig(value RegistryImageAuthConfig)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `PutBuildAttribute` <a name="PutBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute"></a>

```go
func PutBuildAttribute(value RegistryImageBuild)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `PutTimeouts` <a name="PutTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts"></a>

```go
func PutTimeouts(value RegistryImageTimeouts)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `ResetAuthConfig` <a name="ResetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig"></a>

```go
func ResetAuthConfig()
```

##### `ResetBuildAttribute` <a name="ResetBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute"></a>

```go
func ResetBuildAttribute()
```

##### `ResetId` <a name="ResetId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetId"></a>

```go
func ResetId()
```

##### `ResetInsecureSkipVerify` <a name="ResetInsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify"></a>

```go
func ResetInsecureSkipVerify()
```

##### `ResetKeepRemotely` <a name="ResetKeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely"></a>

```go
func ResetKeepRemotely()
```

##### `ResetTimeouts` <a name="ResetTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts"></a>

```go
func ResetTimeouts()
```

##### `ResetTriggers` <a name="ResetTriggers" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers"></a>

```go
func ResetTriggers()
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

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.RegistryImage_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.RegistryImage_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.RegistryImage_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.RegistryImage_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the RegistryImage to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing RegistryImage that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

? Optional instance of the provider where the RegistryImage to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack">CdktfStack</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute">BuildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest">Sha256Digest</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput">AuthConfigInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput">BuildAttributeInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput">InsecureSkipVerifyInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput">KeepRemotelyInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput">TimeoutsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput">TriggersInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely">KeepRemotely</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggers">Triggers</a></code> | <code>*map[string]*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.registryImage.RegistryImage.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.registryImage.RegistryImage.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.registryImage.RegistryImage.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.registryImage.RegistryImage.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `AuthConfig`<sup>Required</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig"></a>

```go
func AuthConfig() RegistryImageAuthConfigOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a>

---

##### `BuildAttribute`<sup>Required</sup> <a name="BuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute"></a>

```go
func BuildAttribute() RegistryImageBuildOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a>

---

##### `Sha256Digest`<sup>Required</sup> <a name="Sha256Digest" id="@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest"></a>

```go
func Sha256Digest() *string
```

- *Type:* *string

---

##### `Timeouts`<sup>Required</sup> <a name="Timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts"></a>

```go
func Timeouts() RegistryImageTimeoutsOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a>

---

##### `AuthConfigInput`<sup>Optional</sup> <a name="AuthConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput"></a>

```go
func AuthConfigInput() RegistryImageAuthConfig
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `BuildAttributeInput`<sup>Optional</sup> <a name="BuildAttributeInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput"></a>

```go
func BuildAttributeInput() RegistryImageBuild
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `InsecureSkipVerifyInput`<sup>Optional</sup> <a name="InsecureSkipVerifyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput"></a>

```go
func InsecureSkipVerifyInput() interface{}
```

- *Type:* interface{}

---

##### `KeepRemotelyInput`<sup>Optional</sup> <a name="KeepRemotelyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput"></a>

```go
func KeepRemotelyInput() interface{}
```

- *Type:* interface{}

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `TimeoutsInput`<sup>Optional</sup> <a name="TimeoutsInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput"></a>

```go
func TimeoutsInput() interface{}
```

- *Type:* interface{}

---

##### `TriggersInput`<sup>Optional</sup> <a name="TriggersInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput"></a>

```go
func TriggersInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImage.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `InsecureSkipVerify`<sup>Required</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify"></a>

```go
func InsecureSkipVerify() interface{}
```

- *Type:* interface{}

---

##### `KeepRemotely`<sup>Required</sup> <a name="KeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely"></a>

```go
func KeepRemotely() interface{}
```

- *Type:* interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImage.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Triggers`<sup>Required</sup> <a name="Triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggers"></a>

```go
func Triggers() *map[string]*string
```

- *Type:* *map[string]*string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### RegistryImageAuthConfig <a name="RegistryImageAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageAuthConfig {
	Address: *string,
	Password: *string,
	Username: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address">Address</a></code> | <code>*string</code> | The address of the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password">Password</a></code> | <code>*string</code> | The password for the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username">Username</a></code> | <code>*string</code> | The username for the Docker registry. |

---

##### `Address`<sup>Required</sup> <a name="Address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address"></a>

```go
Address *string
```

- *Type:* *string

The address of the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#address RegistryImage#address}

---

##### `Password`<sup>Optional</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password"></a>

```go
Password *string
```

- *Type:* *string

The password for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `Username`<sup>Optional</sup> <a name="Username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username"></a>

```go
Username *string
```

- *Type:* *string

The username for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#username RegistryImage#username}

---

### RegistryImageBuild <a name="RegistryImageBuild" id="@cdktn/provider-docker.registryImage.RegistryImageBuild"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageBuild {
	Context: *string,
	AdditionalContexts: *[]*string,
	AuthConfig: interface{},
	BuildArgs: *map[string]*string,
	Builder: *string,
	BuildId: *string,
	BuildLogFile: *string,
	CacheFrom: *[]*string,
	CacheTo: *[]*string,
	CgroupParent: *string,
	CpuPeriod: *f64,
	CpuQuota: *f64,
	CpuSetCpus: *string,
	CpuSetMems: *string,
	CpuShares: *f64,
	Dockerfile: *string,
	ExtraHosts: *[]*string,
	ForceRemove: interface{},
	Isolation: *string,
	Label: *map[string]*string,
	Labels: *map[string]*string,
	Memory: *f64,
	MemorySwap: *f64,
	NetworkMode: *string,
	NoCache: interface{},
	Platform: *string,
	Provenance: *string,
	PullParent: interface{},
	RemoteContext: *string,
	Remove: interface{},
	Sbom: *string,
	Secrets: interface{},
	SecurityOpt: *[]*string,
	SessionId: *string,
	ShmSize: *f64,
	Squash: interface{},
	SuppressOutput: interface{},
	Tag: *[]*string,
	Target: *string,
	Ulimit: interface{},
	UseLegacyBuilder: interface{},
	Version: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context">Context</a></code> | <code>*string</code> | Value to specify the build context. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts">AdditionalContexts</a></code> | <code>*[]*string</code> | A list of additional build contexts. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig">AuthConfig</a></code> | <code>interface{}</code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs">BuildArgs</a></code> | <code>*map[string]*string</code> | Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder">Builder</a></code> | <code>*string</code> | The name of the buildx builder to use. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId">BuildId</a></code> | <code>*string</code> | BuildID is an optional identifier that can be passed together with the build request. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile">BuildLogFile</a></code> | <code>*string</code> | Path to a file where the buildx log are written to. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom">CacheFrom</a></code> | <code>*[]*string</code> | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo">CacheTo</a></code> | <code>*[]*string</code> | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent">CgroupParent</a></code> | <code>*string</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod">CpuPeriod</a></code> | <code>*f64</code> | The length of a CPU period in microseconds. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota">CpuQuota</a></code> | <code>*f64</code> | Microseconds of CPU time that the container can get in a CPU period. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus">CpuSetCpus</a></code> | <code>*string</code> | CPUs in which to allow execution (e.g., `0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems">CpuSetMems</a></code> | <code>*string</code> | MEMs in which to allow execution (`0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares">CpuShares</a></code> | <code>*f64</code> | CPU shares (relative weight). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile">Dockerfile</a></code> | <code>*string</code> | Name of the Dockerfile. Defaults to `Dockerfile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts">ExtraHosts</a></code> | <code>*[]*string</code> | A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"]. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove">ForceRemove</a></code> | <code>interface{}</code> | Always remove intermediate containers. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation">Isolation</a></code> | <code>*string</code> | Isolation represents the isolation technology of a container. The supported values are. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label">Label</a></code> | <code>*map[string]*string</code> | Set metadata for an image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels">Labels</a></code> | <code>*map[string]*string</code> | User-defined key/value metadata. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory">Memory</a></code> | <code>*f64</code> | Set memory limit for build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap">MemorySwap</a></code> | <code>*f64</code> | Total memory (memory + swap), -1 to enable unlimited swap. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode">NetworkMode</a></code> | <code>*string</code> | Set the networking mode for the RUN instructions during build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache">NoCache</a></code> | <code>interface{}</code> | Do not use the cache when building the image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform">Platform</a></code> | <code>*string</code> | Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance">Provenance</a></code> | <code>*string</code> | Set provenance attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent">PullParent</a></code> | <code>interface{}</code> | Attempt to pull the image even if an older image exists locally. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext">RemoteContext</a></code> | <code>*string</code> | A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove">Remove</a></code> | <code>interface{}</code> | Remove intermediate containers after a successful build. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom">Sbom</a></code> | <code>*string</code> | Set SBOM (Software Bill of Materials) attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets">Secrets</a></code> | <code>interface{}</code> | secrets block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt">SecurityOpt</a></code> | <code>*[]*string</code> | The security options. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId">SessionId</a></code> | <code>*string</code> | Set an ID for the build session. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize">ShmSize</a></code> | <code>*f64</code> | Size of /dev/shm in bytes. The size must be greater than 0. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash">Squash</a></code> | <code>interface{}</code> | If true the new layers are squashed into a new image with a single new layer. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput">SuppressOutput</a></code> | <code>interface{}</code> | Suppress the build output and print image ID on success. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag">Tag</a></code> | <code>*[]*string</code> | Name and optionally a tag in the 'name:tag' format. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target">Target</a></code> | <code>*string</code> | Set the target build stage to build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit">Ulimit</a></code> | <code>interface{}</code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder">UseLegacyBuilder</a></code> | <code>interface{}</code> | Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version">Version</a></code> | <code>*string</code> | Version of the underlying builder to use. |

---

##### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context"></a>

```go
Context *string
```

- *Type:* *string

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#context RegistryImage#context}

---

##### `AdditionalContexts`<sup>Optional</sup> <a name="AdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts"></a>

```go
AdditionalContexts *[]*string
```

- *Type:* *[]*string

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#additional_contexts RegistryImage#additional_contexts}

---

##### `AuthConfig`<sup>Optional</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig"></a>

```go
AuthConfig interface{}
```

- *Type:* interface{}

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `BuildArgs`<sup>Optional</sup> <a name="BuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs"></a>

```go
BuildArgs *map[string]*string
```

- *Type:* *map[string]*string

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build_args RegistryImage#build_args}

---

##### `Builder`<sup>Optional</sup> <a name="Builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder"></a>

```go
Builder *string
```

- *Type:* *string

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#builder RegistryImage#builder}

---

##### `BuildId`<sup>Optional</sup> <a name="BuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId"></a>

```go
BuildId *string
```

- *Type:* *string

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build_id RegistryImage#build_id}

---

##### `BuildLogFile`<sup>Optional</sup> <a name="BuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile"></a>

```go
BuildLogFile *string
```

- *Type:* *string

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build_log_file RegistryImage#build_log_file}

---

##### `CacheFrom`<sup>Optional</sup> <a name="CacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom"></a>

```go
CacheFrom *[]*string
```

- *Type:* *[]*string

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cache_from RegistryImage#cache_from}

---

##### `CacheTo`<sup>Optional</sup> <a name="CacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo"></a>

```go
CacheTo *[]*string
```

- *Type:* *[]*string

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cache_to RegistryImage#cache_to}

---

##### `CgroupParent`<sup>Optional</sup> <a name="CgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent"></a>

```go
CgroupParent *string
```

- *Type:* *string

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cgroup_parent RegistryImage#cgroup_parent}

---

##### `CpuPeriod`<sup>Optional</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod"></a>

```go
CpuPeriod *f64
```

- *Type:* *f64

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_period RegistryImage#cpu_period}

---

##### `CpuQuota`<sup>Optional</sup> <a name="CpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota"></a>

```go
CpuQuota *f64
```

- *Type:* *f64

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_quota RegistryImage#cpu_quota}

---

##### `CpuSetCpus`<sup>Optional</sup> <a name="CpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus"></a>

```go
CpuSetCpus *string
```

- *Type:* *string

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_set_cpus RegistryImage#cpu_set_cpus}

---

##### `CpuSetMems`<sup>Optional</sup> <a name="CpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems"></a>

```go
CpuSetMems *string
```

- *Type:* *string

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_set_mems RegistryImage#cpu_set_mems}

---

##### `CpuShares`<sup>Optional</sup> <a name="CpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares"></a>

```go
CpuShares *f64
```

- *Type:* *f64

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_shares RegistryImage#cpu_shares}

---

##### `Dockerfile`<sup>Optional</sup> <a name="Dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile"></a>

```go
Dockerfile *string
```

- *Type:* *string

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#dockerfile RegistryImage#dockerfile}

---

##### `ExtraHosts`<sup>Optional</sup> <a name="ExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts"></a>

```go
ExtraHosts *[]*string
```

- *Type:* *[]*string

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#extra_hosts RegistryImage#extra_hosts}

---

##### `ForceRemove`<sup>Optional</sup> <a name="ForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove"></a>

```go
ForceRemove interface{}
```

- *Type:* interface{}

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#force_remove RegistryImage#force_remove}

---

##### `Isolation`<sup>Optional</sup> <a name="Isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation"></a>

```go
Isolation *string
```

- *Type:* *string

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#isolation RegistryImage#isolation}

---

##### `Label`<sup>Optional</sup> <a name="Label" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label"></a>

```go
Label *map[string]*string
```

- *Type:* *map[string]*string

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#label RegistryImage#label}

---

##### `Labels`<sup>Optional</sup> <a name="Labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels"></a>

```go
Labels *map[string]*string
```

- *Type:* *map[string]*string

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#labels RegistryImage#labels}

---

##### `Memory`<sup>Optional</sup> <a name="Memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory"></a>

```go
Memory *f64
```

- *Type:* *f64

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#memory RegistryImage#memory}

---

##### `MemorySwap`<sup>Optional</sup> <a name="MemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap"></a>

```go
MemorySwap *f64
```

- *Type:* *f64

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#memory_swap RegistryImage#memory_swap}

---

##### `NetworkMode`<sup>Optional</sup> <a name="NetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode"></a>

```go
NetworkMode *string
```

- *Type:* *string

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#network_mode RegistryImage#network_mode}

---

##### `NoCache`<sup>Optional</sup> <a name="NoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache"></a>

```go
NoCache interface{}
```

- *Type:* interface{}

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#no_cache RegistryImage#no_cache}

---

##### `Platform`<sup>Optional</sup> <a name="Platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform"></a>

```go
Platform *string
```

- *Type:* *string

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#platform RegistryImage#platform}

---

##### `Provenance`<sup>Optional</sup> <a name="Provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance"></a>

```go
Provenance *string
```

- *Type:* *string

Set provenance attestation for the build.

BuildKit v0.11+ adds provenance attestations by default, which creates OCI image manifests that some registries (like AWS Lambda) don't support. Set to `false` to disable. Valid values: `false`, `true`, `min`, `max`, `mode=min`, `mode=max`, or a full provenance specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#provenance RegistryImage#provenance}

---

##### `PullParent`<sup>Optional</sup> <a name="PullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent"></a>

```go
PullParent interface{}
```

- *Type:* interface{}

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#pull_parent RegistryImage#pull_parent}

---

##### `RemoteContext`<sup>Optional</sup> <a name="RemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext"></a>

```go
RemoteContext *string
```

- *Type:* *string

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#remote_context RegistryImage#remote_context}

---

##### `Remove`<sup>Optional</sup> <a name="Remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove"></a>

```go
Remove interface{}
```

- *Type:* interface{}

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#remove RegistryImage#remove}

---

##### `Sbom`<sup>Optional</sup> <a name="Sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom"></a>

```go
Sbom *string
```

- *Type:* *string

Set SBOM (Software Bill of Materials) attestation for the build.

Set to `false` to disable. Valid values: `false`, `true`, or a full SBOM specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#sbom RegistryImage#sbom}

---

##### `Secrets`<sup>Optional</sup> <a name="Secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets"></a>

```go
Secrets interface{}
```

- *Type:* interface{}

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#secrets RegistryImage#secrets}

---

##### `SecurityOpt`<sup>Optional</sup> <a name="SecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt"></a>

```go
SecurityOpt *[]*string
```

- *Type:* *[]*string

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#security_opt RegistryImage#security_opt}

---

##### `SessionId`<sup>Optional</sup> <a name="SessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId"></a>

```go
SessionId *string
```

- *Type:* *string

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#session_id RegistryImage#session_id}

---

##### `ShmSize`<sup>Optional</sup> <a name="ShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize"></a>

```go
ShmSize *f64
```

- *Type:* *f64

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#shm_size RegistryImage#shm_size}

---

##### `Squash`<sup>Optional</sup> <a name="Squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash"></a>

```go
Squash interface{}
```

- *Type:* interface{}

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#squash RegistryImage#squash}

---

##### `SuppressOutput`<sup>Optional</sup> <a name="SuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput"></a>

```go
SuppressOutput interface{}
```

- *Type:* interface{}

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#suppress_output RegistryImage#suppress_output}

---

##### `Tag`<sup>Optional</sup> <a name="Tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag"></a>

```go
Tag *[]*string
```

- *Type:* *[]*string

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#tag RegistryImage#tag}

---

##### `Target`<sup>Optional</sup> <a name="Target" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target"></a>

```go
Target *string
```

- *Type:* *string

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#target RegistryImage#target}

---

##### `Ulimit`<sup>Optional</sup> <a name="Ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit"></a>

```go
Ulimit interface{}
```

- *Type:* interface{}

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#ulimit RegistryImage#ulimit}

---

##### `UseLegacyBuilder`<sup>Optional</sup> <a name="UseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder"></a>

```go
UseLegacyBuilder interface{}
```

- *Type:* interface{}

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#use_legacy_builder RegistryImage#use_legacy_builder}

---

##### `Version`<sup>Optional</sup> <a name="Version" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version"></a>

```go
Version *string
```

- *Type:* *string

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#version RegistryImage#version}

---

### RegistryImageBuildAuthConfig <a name="RegistryImageBuildAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageBuildAuthConfig {
	HostName: *string,
	Auth: *string,
	Email: *string,
	IdentityToken: *string,
	Password: *string,
	RegistryToken: *string,
	ServerAddress: *string,
	UserName: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName">HostName</a></code> | <code>*string</code> | hostname of the registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth">Auth</a></code> | <code>*string</code> | the auth token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email">Email</a></code> | <code>*string</code> | the user emal. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken">IdentityToken</a></code> | <code>*string</code> | the identity token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password">Password</a></code> | <code>*string</code> | the registry password. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken">RegistryToken</a></code> | <code>*string</code> | the registry token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress">ServerAddress</a></code> | <code>*string</code> | the server address. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName">UserName</a></code> | <code>*string</code> | the registry user name. |

---

##### `HostName`<sup>Required</sup> <a name="HostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName"></a>

```go
HostName *string
```

- *Type:* *string

hostname of the registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#host_name RegistryImage#host_name}

---

##### `Auth`<sup>Optional</sup> <a name="Auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth"></a>

```go
Auth *string
```

- *Type:* *string

the auth token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#auth RegistryImage#auth}

---

##### `Email`<sup>Optional</sup> <a name="Email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email"></a>

```go
Email *string
```

- *Type:* *string

the user emal.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#email RegistryImage#email}

---

##### `IdentityToken`<sup>Optional</sup> <a name="IdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken"></a>

```go
IdentityToken *string
```

- *Type:* *string

the identity token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#identity_token RegistryImage#identity_token}

---

##### `Password`<sup>Optional</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password"></a>

```go
Password *string
```

- *Type:* *string

the registry password.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `RegistryToken`<sup>Optional</sup> <a name="RegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken"></a>

```go
RegistryToken *string
```

- *Type:* *string

the registry token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#registry_token RegistryImage#registry_token}

---

##### `ServerAddress`<sup>Optional</sup> <a name="ServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress"></a>

```go
ServerAddress *string
```

- *Type:* *string

the server address.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#server_address RegistryImage#server_address}

---

##### `UserName`<sup>Optional</sup> <a name="UserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName"></a>

```go
UserName *string
```

- *Type:* *string

the registry user name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#user_name RegistryImage#user_name}

---

### RegistryImageBuildSecrets <a name="RegistryImageBuildSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageBuildSecrets {
	Id: *string,
	Env: *string,
	Src: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id">Id</a></code> | <code>*string</code> | ID of the secret. By default, secrets are mounted to /run/secrets/<id>. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env">Env</a></code> | <code>*string</code> | Environment variable source of the secret. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src">Src</a></code> | <code>*string</code> | File source of the secret. Takes precedence over `env`. |

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id"></a>

```go
Id *string
```

- *Type:* *string

ID of the secret. By default, secrets are mounted to /run/secrets/<id>.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#id RegistryImage#id}

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Env`<sup>Optional</sup> <a name="Env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env"></a>

```go
Env *string
```

- *Type:* *string

Environment variable source of the secret.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#env RegistryImage#env}

---

##### `Src`<sup>Optional</sup> <a name="Src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src"></a>

```go
Src *string
```

- *Type:* *string

File source of the secret. Takes precedence over `env`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#src RegistryImage#src}

---

### RegistryImageBuildUlimit <a name="RegistryImageBuildUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageBuildUlimit {
	Hard: *f64,
	Name: *string,
	Soft: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard">Hard</a></code> | <code>*f64</code> | soft limit. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name">Name</a></code> | <code>*string</code> | type of ulimit, e.g. `nofile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft">Soft</a></code> | <code>*f64</code> | hard limit. |

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard"></a>

```go
Hard *f64
```

- *Type:* *f64

soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#hard RegistryImage#hard}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name"></a>

```go
Name *string
```

- *Type:* *string

type of ulimit, e.g. `nofile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft"></a>

```go
Soft *f64
```

- *Type:* *f64

hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#soft RegistryImage#soft}

---

### RegistryImageConfig <a name="RegistryImageConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable,
	ForEach: github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator,
	Lifecycle: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle,
	Provider: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider,
	Provisioners: *[]interface{},
	Name: *string,
	AuthConfig: github.com/cdktn-io/cdktn-provider-docker-go/docker/v15.registryImage.RegistryImageAuthConfig,
	BuildAttribute: github.com/cdktn-io/cdktn-provider-docker-go/docker/v15.registryImage.RegistryImageBuild,
	Id: *string,
	InsecureSkipVerify: interface{},
	KeepRemotely: interface{},
	Timeouts: github.com/cdktn-io/cdktn-provider-docker-go/docker/v15.registryImage.RegistryImageTimeouts,
	Triggers: *map[string]*string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name">Name</a></code> | <code>*string</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute">BuildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>interface{}</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely">KeepRemotely</a></code> | <code>interface{}</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers">Triggers</a></code> | <code>*map[string]*string</code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `AuthConfig`<sup>Optional</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig"></a>

```go
AuthConfig RegistryImageAuthConfig
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `BuildAttribute`<sup>Optional</sup> <a name="BuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute"></a>

```go
BuildAttribute RegistryImageBuild
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `InsecureSkipVerify`<sup>Optional</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify"></a>

```go
InsecureSkipVerify interface{}
```

- *Type:* interface{}

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `KeepRemotely`<sup>Optional</sup> <a name="KeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely"></a>

```go
KeepRemotely interface{}
```

- *Type:* interface{}

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `Timeouts`<sup>Optional</sup> <a name="Timeouts" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts"></a>

```go
Timeouts RegistryImageTimeouts
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `Triggers`<sup>Optional</sup> <a name="Triggers" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers"></a>

```go
Triggers *map[string]*string
```

- *Type:* *map[string]*string

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

### RegistryImageTimeouts <a name="RegistryImageTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

&registryimage.RegistryImageTimeouts {
	Create: *string,
	Delete: *string,
	Update: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create">Create</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#create RegistryImage#create}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete">Delete</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#delete RegistryImage#delete}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update">Update</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#update RegistryImage#update}. |

---

##### `Create`<sup>Optional</sup> <a name="Create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create"></a>

```go
Create *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#create RegistryImage#create}.

---

##### `Delete`<sup>Optional</sup> <a name="Delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete"></a>

```go
Delete *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#delete RegistryImage#delete}.

---

##### `Update`<sup>Optional</sup> <a name="Update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update"></a>

```go
Update *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#update RegistryImage#update}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistryImageAuthConfigOutputReference <a name="RegistryImageAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageAuthConfigOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) RegistryImageAuthConfigOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetPassword` <a name="ResetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword"></a>

```go
func ResetPassword()
```

##### `ResetUsername` <a name="ResetUsername" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername"></a>

```go
func ResetUsername()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput">AddressInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput">PasswordInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput">UsernameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address">Address</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password">Password</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username">Username</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `AddressInput`<sup>Optional</sup> <a name="AddressInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput"></a>

```go
func AddressInput() *string
```

- *Type:* *string

---

##### `PasswordInput`<sup>Optional</sup> <a name="PasswordInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput"></a>

```go
func PasswordInput() *string
```

- *Type:* *string

---

##### `UsernameInput`<sup>Optional</sup> <a name="UsernameInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput"></a>

```go
func UsernameInput() *string
```

- *Type:* *string

---

##### `Address`<sup>Required</sup> <a name="Address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address"></a>

```go
func Address() *string
```

- *Type:* *string

---

##### `Password`<sup>Required</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password"></a>

```go
func Password() *string
```

- *Type:* *string

---

##### `Username`<sup>Required</sup> <a name="Username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username"></a>

```go
func Username() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue"></a>

```go
func InternalValue() RegistryImageAuthConfig
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---


### RegistryImageBuildAuthConfigList <a name="RegistryImageBuildAuthConfigList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildAuthConfigList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) RegistryImageBuildAuthConfigList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

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

```go
func AllWithMapKey(mapKeyAttributeName *string) DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* *string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get"></a>

```go
func Get(index *f64) RegistryImageBuildAuthConfigOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### RegistryImageBuildAuthConfigOutputReference <a name="RegistryImageBuildAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildAuthConfigOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) RegistryImageBuildAuthConfigOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAuth` <a name="ResetAuth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth"></a>

```go
func ResetAuth()
```

##### `ResetEmail` <a name="ResetEmail" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail"></a>

```go
func ResetEmail()
```

##### `ResetIdentityToken` <a name="ResetIdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken"></a>

```go
func ResetIdentityToken()
```

##### `ResetPassword` <a name="ResetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword"></a>

```go
func ResetPassword()
```

##### `ResetRegistryToken` <a name="ResetRegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken"></a>

```go
func ResetRegistryToken()
```

##### `ResetServerAddress` <a name="ResetServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress"></a>

```go
func ResetServerAddress()
```

##### `ResetUserName` <a name="ResetUserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName"></a>

```go
func ResetUserName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput">AuthInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput">EmailInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput">HostNameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput">IdentityTokenInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput">PasswordInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput">RegistryTokenInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput">ServerAddressInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput">UserNameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth">Auth</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email">Email</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName">HostName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken">IdentityToken</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password">Password</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken">RegistryToken</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress">ServerAddress</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName">UserName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `AuthInput`<sup>Optional</sup> <a name="AuthInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput"></a>

```go
func AuthInput() *string
```

- *Type:* *string

---

##### `EmailInput`<sup>Optional</sup> <a name="EmailInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput"></a>

```go
func EmailInput() *string
```

- *Type:* *string

---

##### `HostNameInput`<sup>Optional</sup> <a name="HostNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput"></a>

```go
func HostNameInput() *string
```

- *Type:* *string

---

##### `IdentityTokenInput`<sup>Optional</sup> <a name="IdentityTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput"></a>

```go
func IdentityTokenInput() *string
```

- *Type:* *string

---

##### `PasswordInput`<sup>Optional</sup> <a name="PasswordInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput"></a>

```go
func PasswordInput() *string
```

- *Type:* *string

---

##### `RegistryTokenInput`<sup>Optional</sup> <a name="RegistryTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput"></a>

```go
func RegistryTokenInput() *string
```

- *Type:* *string

---

##### `ServerAddressInput`<sup>Optional</sup> <a name="ServerAddressInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput"></a>

```go
func ServerAddressInput() *string
```

- *Type:* *string

---

##### `UserNameInput`<sup>Optional</sup> <a name="UserNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput"></a>

```go
func UserNameInput() *string
```

- *Type:* *string

---

##### `Auth`<sup>Required</sup> <a name="Auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth"></a>

```go
func Auth() *string
```

- *Type:* *string

---

##### `Email`<sup>Required</sup> <a name="Email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email"></a>

```go
func Email() *string
```

- *Type:* *string

---

##### `HostName`<sup>Required</sup> <a name="HostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName"></a>

```go
func HostName() *string
```

- *Type:* *string

---

##### `IdentityToken`<sup>Required</sup> <a name="IdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken"></a>

```go
func IdentityToken() *string
```

- *Type:* *string

---

##### `Password`<sup>Required</sup> <a name="Password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password"></a>

```go
func Password() *string
```

- *Type:* *string

---

##### `RegistryToken`<sup>Required</sup> <a name="RegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken"></a>

```go
func RegistryToken() *string
```

- *Type:* *string

---

##### `ServerAddress`<sup>Required</sup> <a name="ServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress"></a>

```go
func ServerAddress() *string
```

- *Type:* *string

---

##### `UserName`<sup>Required</sup> <a name="UserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName"></a>

```go
func UserName() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### RegistryImageBuildOutputReference <a name="RegistryImageBuildOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) RegistryImageBuildOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutAuthConfig` <a name="PutAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig"></a>

```go
func PutAuthConfig(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig.parameter.value"></a>

- *Type:* interface{}

---

##### `PutSecrets` <a name="PutSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets"></a>

```go
func PutSecrets(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets.parameter.value"></a>

- *Type:* interface{}

---

##### `PutUlimit` <a name="PutUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit"></a>

```go
func PutUlimit(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetAdditionalContexts` <a name="ResetAdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts"></a>

```go
func ResetAdditionalContexts()
```

##### `ResetAuthConfig` <a name="ResetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig"></a>

```go
func ResetAuthConfig()
```

##### `ResetBuildArgs` <a name="ResetBuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs"></a>

```go
func ResetBuildArgs()
```

##### `ResetBuilder` <a name="ResetBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder"></a>

```go
func ResetBuilder()
```

##### `ResetBuildId` <a name="ResetBuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId"></a>

```go
func ResetBuildId()
```

##### `ResetBuildLogFile` <a name="ResetBuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile"></a>

```go
func ResetBuildLogFile()
```

##### `ResetCacheFrom` <a name="ResetCacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom"></a>

```go
func ResetCacheFrom()
```

##### `ResetCacheTo` <a name="ResetCacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo"></a>

```go
func ResetCacheTo()
```

##### `ResetCgroupParent` <a name="ResetCgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent"></a>

```go
func ResetCgroupParent()
```

##### `ResetCpuPeriod` <a name="ResetCpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod"></a>

```go
func ResetCpuPeriod()
```

##### `ResetCpuQuota` <a name="ResetCpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota"></a>

```go
func ResetCpuQuota()
```

##### `ResetCpuSetCpus` <a name="ResetCpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus"></a>

```go
func ResetCpuSetCpus()
```

##### `ResetCpuSetMems` <a name="ResetCpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems"></a>

```go
func ResetCpuSetMems()
```

##### `ResetCpuShares` <a name="ResetCpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares"></a>

```go
func ResetCpuShares()
```

##### `ResetDockerfile` <a name="ResetDockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile"></a>

```go
func ResetDockerfile()
```

##### `ResetExtraHosts` <a name="ResetExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts"></a>

```go
func ResetExtraHosts()
```

##### `ResetForceRemove` <a name="ResetForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove"></a>

```go
func ResetForceRemove()
```

##### `ResetIsolation` <a name="ResetIsolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation"></a>

```go
func ResetIsolation()
```

##### `ResetLabel` <a name="ResetLabel" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel"></a>

```go
func ResetLabel()
```

##### `ResetLabels` <a name="ResetLabels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels"></a>

```go
func ResetLabels()
```

##### `ResetMemory` <a name="ResetMemory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory"></a>

```go
func ResetMemory()
```

##### `ResetMemorySwap` <a name="ResetMemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap"></a>

```go
func ResetMemorySwap()
```

##### `ResetNetworkMode` <a name="ResetNetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode"></a>

```go
func ResetNetworkMode()
```

##### `ResetNoCache` <a name="ResetNoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache"></a>

```go
func ResetNoCache()
```

##### `ResetPlatform` <a name="ResetPlatform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform"></a>

```go
func ResetPlatform()
```

##### `ResetProvenance` <a name="ResetProvenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance"></a>

```go
func ResetProvenance()
```

##### `ResetPullParent` <a name="ResetPullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent"></a>

```go
func ResetPullParent()
```

##### `ResetRemoteContext` <a name="ResetRemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext"></a>

```go
func ResetRemoteContext()
```

##### `ResetRemove` <a name="ResetRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove"></a>

```go
func ResetRemove()
```

##### `ResetSbom` <a name="ResetSbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom"></a>

```go
func ResetSbom()
```

##### `ResetSecrets` <a name="ResetSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets"></a>

```go
func ResetSecrets()
```

##### `ResetSecurityOpt` <a name="ResetSecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt"></a>

```go
func ResetSecurityOpt()
```

##### `ResetSessionId` <a name="ResetSessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId"></a>

```go
func ResetSessionId()
```

##### `ResetShmSize` <a name="ResetShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize"></a>

```go
func ResetShmSize()
```

##### `ResetSquash` <a name="ResetSquash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash"></a>

```go
func ResetSquash()
```

##### `ResetSuppressOutput` <a name="ResetSuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput"></a>

```go
func ResetSuppressOutput()
```

##### `ResetTag` <a name="ResetTag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag"></a>

```go
func ResetTag()
```

##### `ResetTarget` <a name="ResetTarget" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget"></a>

```go
func ResetTarget()
```

##### `ResetUlimit` <a name="ResetUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit"></a>

```go
func ResetUlimit()
```

##### `ResetUseLegacyBuilder` <a name="ResetUseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder"></a>

```go
func ResetUseLegacyBuilder()
```

##### `ResetVersion` <a name="ResetVersion" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion"></a>

```go
func ResetVersion()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig">AuthConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets">Secrets</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit">Ulimit</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput">AdditionalContextsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput">AuthConfigInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput">BuildArgsInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput">BuilderInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput">BuildIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput">BuildLogFileInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput">CacheFromInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput">CacheToInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput">CgroupParentInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput">ContextInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput">CpuPeriodInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput">CpuQuotaInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput">CpuSetCpusInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput">CpuSetMemsInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput">CpuSharesInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput">DockerfileInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput">ExtraHostsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput">ForceRemoveInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput">IsolationInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput">LabelInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput">LabelsInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput">MemoryInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput">MemorySwapInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput">NetworkModeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput">NoCacheInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput">PlatformInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput">ProvenanceInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput">PullParentInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput">RemoteContextInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput">RemoveInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput">SbomInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput">SecretsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput">SecurityOptInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput">SessionIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput">ShmSizeInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput">SquashInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput">SuppressOutputInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput">TagInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput">TargetInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput">UlimitInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput">UseLegacyBuilderInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput">VersionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts">AdditionalContexts</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs">BuildArgs</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder">Builder</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId">BuildId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile">BuildLogFile</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom">CacheFrom</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo">CacheTo</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent">CgroupParent</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context">Context</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod">CpuPeriod</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota">CpuQuota</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus">CpuSetCpus</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems">CpuSetMems</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares">CpuShares</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile">Dockerfile</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts">ExtraHosts</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove">ForceRemove</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation">Isolation</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label">Label</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels">Labels</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory">Memory</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap">MemorySwap</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode">NetworkMode</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache">NoCache</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform">Platform</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance">Provenance</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent">PullParent</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext">RemoteContext</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove">Remove</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom">Sbom</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt">SecurityOpt</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId">SessionId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize">ShmSize</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash">Squash</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput">SuppressOutput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag">Tag</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target">Target</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder">UseLegacyBuilder</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version">Version</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `AuthConfig`<sup>Required</sup> <a name="AuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig"></a>

```go
func AuthConfig() RegistryImageBuildAuthConfigList
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a>

---

##### `Secrets`<sup>Required</sup> <a name="Secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets"></a>

```go
func Secrets() RegistryImageBuildSecretsList
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a>

---

##### `Ulimit`<sup>Required</sup> <a name="Ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit"></a>

```go
func Ulimit() RegistryImageBuildUlimitList
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a>

---

##### `AdditionalContextsInput`<sup>Optional</sup> <a name="AdditionalContextsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput"></a>

```go
func AdditionalContextsInput() *[]*string
```

- *Type:* *[]*string

---

##### `AuthConfigInput`<sup>Optional</sup> <a name="AuthConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput"></a>

```go
func AuthConfigInput() interface{}
```

- *Type:* interface{}

---

##### `BuildArgsInput`<sup>Optional</sup> <a name="BuildArgsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput"></a>

```go
func BuildArgsInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `BuilderInput`<sup>Optional</sup> <a name="BuilderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput"></a>

```go
func BuilderInput() *string
```

- *Type:* *string

---

##### `BuildIdInput`<sup>Optional</sup> <a name="BuildIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput"></a>

```go
func BuildIdInput() *string
```

- *Type:* *string

---

##### `BuildLogFileInput`<sup>Optional</sup> <a name="BuildLogFileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput"></a>

```go
func BuildLogFileInput() *string
```

- *Type:* *string

---

##### `CacheFromInput`<sup>Optional</sup> <a name="CacheFromInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput"></a>

```go
func CacheFromInput() *[]*string
```

- *Type:* *[]*string

---

##### `CacheToInput`<sup>Optional</sup> <a name="CacheToInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput"></a>

```go
func CacheToInput() *[]*string
```

- *Type:* *[]*string

---

##### `CgroupParentInput`<sup>Optional</sup> <a name="CgroupParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput"></a>

```go
func CgroupParentInput() *string
```

- *Type:* *string

---

##### `ContextInput`<sup>Optional</sup> <a name="ContextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput"></a>

```go
func ContextInput() *string
```

- *Type:* *string

---

##### `CpuPeriodInput`<sup>Optional</sup> <a name="CpuPeriodInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput"></a>

```go
func CpuPeriodInput() *f64
```

- *Type:* *f64

---

##### `CpuQuotaInput`<sup>Optional</sup> <a name="CpuQuotaInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput"></a>

```go
func CpuQuotaInput() *f64
```

- *Type:* *f64

---

##### `CpuSetCpusInput`<sup>Optional</sup> <a name="CpuSetCpusInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput"></a>

```go
func CpuSetCpusInput() *string
```

- *Type:* *string

---

##### `CpuSetMemsInput`<sup>Optional</sup> <a name="CpuSetMemsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput"></a>

```go
func CpuSetMemsInput() *string
```

- *Type:* *string

---

##### `CpuSharesInput`<sup>Optional</sup> <a name="CpuSharesInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput"></a>

```go
func CpuSharesInput() *f64
```

- *Type:* *f64

---

##### `DockerfileInput`<sup>Optional</sup> <a name="DockerfileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput"></a>

```go
func DockerfileInput() *string
```

- *Type:* *string

---

##### `ExtraHostsInput`<sup>Optional</sup> <a name="ExtraHostsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput"></a>

```go
func ExtraHostsInput() *[]*string
```

- *Type:* *[]*string

---

##### `ForceRemoveInput`<sup>Optional</sup> <a name="ForceRemoveInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput"></a>

```go
func ForceRemoveInput() interface{}
```

- *Type:* interface{}

---

##### `IsolationInput`<sup>Optional</sup> <a name="IsolationInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput"></a>

```go
func IsolationInput() *string
```

- *Type:* *string

---

##### `LabelInput`<sup>Optional</sup> <a name="LabelInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput"></a>

```go
func LabelInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `LabelsInput`<sup>Optional</sup> <a name="LabelsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput"></a>

```go
func LabelsInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `MemoryInput`<sup>Optional</sup> <a name="MemoryInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput"></a>

```go
func MemoryInput() *f64
```

- *Type:* *f64

---

##### `MemorySwapInput`<sup>Optional</sup> <a name="MemorySwapInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput"></a>

```go
func MemorySwapInput() *f64
```

- *Type:* *f64

---

##### `NetworkModeInput`<sup>Optional</sup> <a name="NetworkModeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput"></a>

```go
func NetworkModeInput() *string
```

- *Type:* *string

---

##### `NoCacheInput`<sup>Optional</sup> <a name="NoCacheInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput"></a>

```go
func NoCacheInput() interface{}
```

- *Type:* interface{}

---

##### `PlatformInput`<sup>Optional</sup> <a name="PlatformInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput"></a>

```go
func PlatformInput() *string
```

- *Type:* *string

---

##### `ProvenanceInput`<sup>Optional</sup> <a name="ProvenanceInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput"></a>

```go
func ProvenanceInput() *string
```

- *Type:* *string

---

##### `PullParentInput`<sup>Optional</sup> <a name="PullParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput"></a>

```go
func PullParentInput() interface{}
```

- *Type:* interface{}

---

##### `RemoteContextInput`<sup>Optional</sup> <a name="RemoteContextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput"></a>

```go
func RemoteContextInput() *string
```

- *Type:* *string

---

##### `RemoveInput`<sup>Optional</sup> <a name="RemoveInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput"></a>

```go
func RemoveInput() interface{}
```

- *Type:* interface{}

---

##### `SbomInput`<sup>Optional</sup> <a name="SbomInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput"></a>

```go
func SbomInput() *string
```

- *Type:* *string

---

##### `SecretsInput`<sup>Optional</sup> <a name="SecretsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput"></a>

```go
func SecretsInput() interface{}
```

- *Type:* interface{}

---

##### `SecurityOptInput`<sup>Optional</sup> <a name="SecurityOptInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput"></a>

```go
func SecurityOptInput() *[]*string
```

- *Type:* *[]*string

---

##### `SessionIdInput`<sup>Optional</sup> <a name="SessionIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput"></a>

```go
func SessionIdInput() *string
```

- *Type:* *string

---

##### `ShmSizeInput`<sup>Optional</sup> <a name="ShmSizeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput"></a>

```go
func ShmSizeInput() *f64
```

- *Type:* *f64

---

##### `SquashInput`<sup>Optional</sup> <a name="SquashInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput"></a>

```go
func SquashInput() interface{}
```

- *Type:* interface{}

---

##### `SuppressOutputInput`<sup>Optional</sup> <a name="SuppressOutputInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput"></a>

```go
func SuppressOutputInput() interface{}
```

- *Type:* interface{}

---

##### `TagInput`<sup>Optional</sup> <a name="TagInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput"></a>

```go
func TagInput() *[]*string
```

- *Type:* *[]*string

---

##### `TargetInput`<sup>Optional</sup> <a name="TargetInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput"></a>

```go
func TargetInput() *string
```

- *Type:* *string

---

##### `UlimitInput`<sup>Optional</sup> <a name="UlimitInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput"></a>

```go
func UlimitInput() interface{}
```

- *Type:* interface{}

---

##### `UseLegacyBuilderInput`<sup>Optional</sup> <a name="UseLegacyBuilderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput"></a>

```go
func UseLegacyBuilderInput() interface{}
```

- *Type:* interface{}

---

##### `VersionInput`<sup>Optional</sup> <a name="VersionInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput"></a>

```go
func VersionInput() *string
```

- *Type:* *string

---

##### `AdditionalContexts`<sup>Required</sup> <a name="AdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts"></a>

```go
func AdditionalContexts() *[]*string
```

- *Type:* *[]*string

---

##### `BuildArgs`<sup>Required</sup> <a name="BuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs"></a>

```go
func BuildArgs() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Builder`<sup>Required</sup> <a name="Builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder"></a>

```go
func Builder() *string
```

- *Type:* *string

---

##### `BuildId`<sup>Required</sup> <a name="BuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId"></a>

```go
func BuildId() *string
```

- *Type:* *string

---

##### `BuildLogFile`<sup>Required</sup> <a name="BuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile"></a>

```go
func BuildLogFile() *string
```

- *Type:* *string

---

##### `CacheFrom`<sup>Required</sup> <a name="CacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom"></a>

```go
func CacheFrom() *[]*string
```

- *Type:* *[]*string

---

##### `CacheTo`<sup>Required</sup> <a name="CacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo"></a>

```go
func CacheTo() *[]*string
```

- *Type:* *[]*string

---

##### `CgroupParent`<sup>Required</sup> <a name="CgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent"></a>

```go
func CgroupParent() *string
```

- *Type:* *string

---

##### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context"></a>

```go
func Context() *string
```

- *Type:* *string

---

##### `CpuPeriod`<sup>Required</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod"></a>

```go
func CpuPeriod() *f64
```

- *Type:* *f64

---

##### `CpuQuota`<sup>Required</sup> <a name="CpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota"></a>

```go
func CpuQuota() *f64
```

- *Type:* *f64

---

##### `CpuSetCpus`<sup>Required</sup> <a name="CpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus"></a>

```go
func CpuSetCpus() *string
```

- *Type:* *string

---

##### `CpuSetMems`<sup>Required</sup> <a name="CpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems"></a>

```go
func CpuSetMems() *string
```

- *Type:* *string

---

##### `CpuShares`<sup>Required</sup> <a name="CpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares"></a>

```go
func CpuShares() *f64
```

- *Type:* *f64

---

##### `Dockerfile`<sup>Required</sup> <a name="Dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile"></a>

```go
func Dockerfile() *string
```

- *Type:* *string

---

##### `ExtraHosts`<sup>Required</sup> <a name="ExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts"></a>

```go
func ExtraHosts() *[]*string
```

- *Type:* *[]*string

---

##### `ForceRemove`<sup>Required</sup> <a name="ForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove"></a>

```go
func ForceRemove() interface{}
```

- *Type:* interface{}

---

##### `Isolation`<sup>Required</sup> <a name="Isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation"></a>

```go
func Isolation() *string
```

- *Type:* *string

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label"></a>

```go
func Label() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Labels`<sup>Required</sup> <a name="Labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels"></a>

```go
func Labels() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Memory`<sup>Required</sup> <a name="Memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory"></a>

```go
func Memory() *f64
```

- *Type:* *f64

---

##### `MemorySwap`<sup>Required</sup> <a name="MemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap"></a>

```go
func MemorySwap() *f64
```

- *Type:* *f64

---

##### `NetworkMode`<sup>Required</sup> <a name="NetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode"></a>

```go
func NetworkMode() *string
```

- *Type:* *string

---

##### `NoCache`<sup>Required</sup> <a name="NoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache"></a>

```go
func NoCache() interface{}
```

- *Type:* interface{}

---

##### `Platform`<sup>Required</sup> <a name="Platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform"></a>

```go
func Platform() *string
```

- *Type:* *string

---

##### `Provenance`<sup>Required</sup> <a name="Provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance"></a>

```go
func Provenance() *string
```

- *Type:* *string

---

##### `PullParent`<sup>Required</sup> <a name="PullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent"></a>

```go
func PullParent() interface{}
```

- *Type:* interface{}

---

##### `RemoteContext`<sup>Required</sup> <a name="RemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext"></a>

```go
func RemoteContext() *string
```

- *Type:* *string

---

##### `Remove`<sup>Required</sup> <a name="Remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove"></a>

```go
func Remove() interface{}
```

- *Type:* interface{}

---

##### `Sbom`<sup>Required</sup> <a name="Sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom"></a>

```go
func Sbom() *string
```

- *Type:* *string

---

##### `SecurityOpt`<sup>Required</sup> <a name="SecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt"></a>

```go
func SecurityOpt() *[]*string
```

- *Type:* *[]*string

---

##### `SessionId`<sup>Required</sup> <a name="SessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId"></a>

```go
func SessionId() *string
```

- *Type:* *string

---

##### `ShmSize`<sup>Required</sup> <a name="ShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize"></a>

```go
func ShmSize() *f64
```

- *Type:* *f64

---

##### `Squash`<sup>Required</sup> <a name="Squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash"></a>

```go
func Squash() interface{}
```

- *Type:* interface{}

---

##### `SuppressOutput`<sup>Required</sup> <a name="SuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput"></a>

```go
func SuppressOutput() interface{}
```

- *Type:* interface{}

---

##### `Tag`<sup>Required</sup> <a name="Tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag"></a>

```go
func Tag() *[]*string
```

- *Type:* *[]*string

---

##### `Target`<sup>Required</sup> <a name="Target" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target"></a>

```go
func Target() *string
```

- *Type:* *string

---

##### `UseLegacyBuilder`<sup>Required</sup> <a name="UseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder"></a>

```go
func UseLegacyBuilder() interface{}
```

- *Type:* interface{}

---

##### `Version`<sup>Required</sup> <a name="Version" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version"></a>

```go
func Version() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue"></a>

```go
func InternalValue() RegistryImageBuild
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---


### RegistryImageBuildSecretsList <a name="RegistryImageBuildSecretsList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildSecretsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) RegistryImageBuildSecretsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

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

```go
func AllWithMapKey(mapKeyAttributeName *string) DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* *string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get"></a>

```go
func Get(index *f64) RegistryImageBuildSecretsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### RegistryImageBuildSecretsOutputReference <a name="RegistryImageBuildSecretsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildSecretsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) RegistryImageBuildSecretsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetEnv` <a name="ResetEnv" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv"></a>

```go
func ResetEnv()
```

##### `ResetSrc` <a name="ResetSrc" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc"></a>

```go
func ResetSrc()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput">EnvInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput">SrcInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env">Env</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src">Src</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `EnvInput`<sup>Optional</sup> <a name="EnvInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput"></a>

```go
func EnvInput() *string
```

- *Type:* *string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `SrcInput`<sup>Optional</sup> <a name="SrcInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput"></a>

```go
func SrcInput() *string
```

- *Type:* *string

---

##### `Env`<sup>Required</sup> <a name="Env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env"></a>

```go
func Env() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Src`<sup>Required</sup> <a name="Src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src"></a>

```go
func Src() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### RegistryImageBuildUlimitList <a name="RegistryImageBuildUlimitList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildUlimitList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) RegistryImageBuildUlimitList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

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

```go
func AllWithMapKey(mapKeyAttributeName *string) DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* *string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get"></a>

```go
func Get(index *f64) RegistryImageBuildUlimitOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### RegistryImageBuildUlimitOutputReference <a name="RegistryImageBuildUlimitOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageBuildUlimitOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) RegistryImageBuildUlimitOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput">HardInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput">SoftInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard">Hard</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft">Soft</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `HardInput`<sup>Optional</sup> <a name="HardInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput"></a>

```go
func HardInput() *f64
```

- *Type:* *f64

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `SoftInput`<sup>Optional</sup> <a name="SoftInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput"></a>

```go
func SoftInput() *f64
```

- *Type:* *f64

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard"></a>

```go
func Hard() *f64
```

- *Type:* *f64

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft"></a>

```go
func Soft() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### RegistryImageTimeoutsOutputReference <a name="RegistryImageTimeoutsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/registryimage"

registryimage.NewRegistryImageTimeoutsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) RegistryImageTimeoutsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

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

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetCreate` <a name="ResetCreate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate"></a>

```go
func ResetCreate()
```

##### `ResetDelete` <a name="ResetDelete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete"></a>

```go
func ResetDelete()
```

##### `ResetUpdate` <a name="ResetUpdate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate"></a>

```go
func ResetUpdate()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput">CreateInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput">DeleteInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput">UpdateInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create">Create</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete">Delete</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update">Update</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `CreateInput`<sup>Optional</sup> <a name="CreateInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput"></a>

```go
func CreateInput() *string
```

- *Type:* *string

---

##### `DeleteInput`<sup>Optional</sup> <a name="DeleteInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput"></a>

```go
func DeleteInput() *string
```

- *Type:* *string

---

##### `UpdateInput`<sup>Optional</sup> <a name="UpdateInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput"></a>

```go
func UpdateInput() *string
```

- *Type:* *string

---

##### `Create`<sup>Required</sup> <a name="Create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create"></a>

```go
func Create() *string
```

- *Type:* *string

---

##### `Delete`<sup>Required</sup> <a name="Delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete"></a>

```go
func Delete() *string
```

- *Type:* *string

---

##### `Update`<sup>Required</sup> <a name="Update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update"></a>

```go
func Update() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



