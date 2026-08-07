# `compose` Submodule <a name="`compose` Submodule" id="@cdktn/provider-docker.compose"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Compose <a name="Compose" id="@cdktn/provider-docker.compose.Compose"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose docker_compose}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.compose.Compose.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/compose"

compose.NewCompose(scope Construct, id *string, config ComposeConfig) Compose
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.compose.ComposeConfig">ComposeConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.config"></a>

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

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.compose.Compose.with"></a>

```go
func With(mixins ...IMixin) IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.compose.Compose.with.parameter.mixins"></a>

- *Type:* ...github.com/aws/constructs-go/constructs/v10.IMixin

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.compose.Compose.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.compose.Compose.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.compose.Compose.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.compose.Compose.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.compose.Compose.hasResourceMove"></a>

```go
func HasResourceMove() interface{}
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.compose.Compose.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.compose.Compose.moveFromId"></a>

```go
func MoveFromId(id *string)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveFromId.parameter.id"></a>

- *Type:* *string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.compose.Compose.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.compose.Compose.moveToId"></a>

```go
func MoveToId(id *string)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveToId.parameter.id"></a>

- *Type:* *string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `ResetEnvFiles` <a name="ResetEnvFiles" id="@cdktn/provider-docker.compose.Compose.resetEnvFiles"></a>

```go
func ResetEnvFiles()
```

##### `ResetProfiles` <a name="ResetProfiles" id="@cdktn/provider-docker.compose.Compose.resetProfiles"></a>

```go
func ResetProfiles()
```

##### `ResetProjectDirectory` <a name="ResetProjectDirectory" id="@cdktn/provider-docker.compose.Compose.resetProjectDirectory"></a>

```go
func ResetProjectDirectory()
```

##### `ResetProjectName` <a name="ResetProjectName" id="@cdktn/provider-docker.compose.Compose.resetProjectName"></a>

```go
func ResetProjectName()
```

##### `ResetRemoveOrphans` <a name="ResetRemoveOrphans" id="@cdktn/provider-docker.compose.Compose.resetRemoveOrphans"></a>

```go
func ResetRemoveOrphans()
```

##### `ResetWait` <a name="ResetWait" id="@cdktn/provider-docker.compose.Compose.resetWait"></a>

```go
func ResetWait()
```

##### `ResetWaitTimeout` <a name="ResetWaitTimeout" id="@cdktn/provider-docker.compose.Compose.resetWaitTimeout"></a>

```go
func ResetWaitTimeout()
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

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/compose"

compose.Compose_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.compose.Compose.isTerraformElement"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/compose"

compose.Compose_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.compose.Compose.isTerraformResource"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/compose"

compose.Compose_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/compose"

compose.Compose_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the Compose to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing Compose that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

? Optional instance of the provider where the Compose to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.cdktfStack">CdktfStack</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPathsInput">ConfigPathsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFilesInput">EnvFilesInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profilesInput">ProfilesInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput">ProjectDirectoryInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectNameInput">ProjectNameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphansInput">RemoveOrphansInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitInput">WaitInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput">WaitTimeoutInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPaths">ConfigPaths</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFiles">EnvFiles</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profiles">Profiles</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectory">ProjectDirectory</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectName">ProjectName</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphans">RemoveOrphans</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.wait">Wait</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeout">WaitTimeout</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.compose.Compose.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.compose.Compose.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.compose.Compose.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.compose.Compose.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.compose.Compose.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.compose.Compose.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.compose.Compose.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.compose.Compose.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.compose.Compose.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.compose.Compose.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.compose.Compose.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.compose.Compose.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `ConfigPathsInput`<sup>Optional</sup> <a name="ConfigPathsInput" id="@cdktn/provider-docker.compose.Compose.property.configPathsInput"></a>

```go
func ConfigPathsInput() *[]*string
```

- *Type:* *[]*string

---

##### `EnvFilesInput`<sup>Optional</sup> <a name="EnvFilesInput" id="@cdktn/provider-docker.compose.Compose.property.envFilesInput"></a>

```go
func EnvFilesInput() *[]*string
```

- *Type:* *[]*string

---

##### `ProfilesInput`<sup>Optional</sup> <a name="ProfilesInput" id="@cdktn/provider-docker.compose.Compose.property.profilesInput"></a>

```go
func ProfilesInput() *[]*string
```

- *Type:* *[]*string

---

##### `ProjectDirectoryInput`<sup>Optional</sup> <a name="ProjectDirectoryInput" id="@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput"></a>

```go
func ProjectDirectoryInput() *string
```

- *Type:* *string

---

##### `ProjectNameInput`<sup>Optional</sup> <a name="ProjectNameInput" id="@cdktn/provider-docker.compose.Compose.property.projectNameInput"></a>

```go
func ProjectNameInput() *string
```

- *Type:* *string

---

##### `RemoveOrphansInput`<sup>Optional</sup> <a name="RemoveOrphansInput" id="@cdktn/provider-docker.compose.Compose.property.removeOrphansInput"></a>

```go
func RemoveOrphansInput() interface{}
```

- *Type:* interface{}

---

##### `WaitInput`<sup>Optional</sup> <a name="WaitInput" id="@cdktn/provider-docker.compose.Compose.property.waitInput"></a>

```go
func WaitInput() interface{}
```

- *Type:* interface{}

---

##### `WaitTimeoutInput`<sup>Optional</sup> <a name="WaitTimeoutInput" id="@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput"></a>

```go
func WaitTimeoutInput() *string
```

- *Type:* *string

---

##### `ConfigPaths`<sup>Required</sup> <a name="ConfigPaths" id="@cdktn/provider-docker.compose.Compose.property.configPaths"></a>

```go
func ConfigPaths() *[]*string
```

- *Type:* *[]*string

---

##### `EnvFiles`<sup>Required</sup> <a name="EnvFiles" id="@cdktn/provider-docker.compose.Compose.property.envFiles"></a>

```go
func EnvFiles() *[]*string
```

- *Type:* *[]*string

---

##### `Profiles`<sup>Required</sup> <a name="Profiles" id="@cdktn/provider-docker.compose.Compose.property.profiles"></a>

```go
func Profiles() *[]*string
```

- *Type:* *[]*string

---

##### `ProjectDirectory`<sup>Required</sup> <a name="ProjectDirectory" id="@cdktn/provider-docker.compose.Compose.property.projectDirectory"></a>

```go
func ProjectDirectory() *string
```

- *Type:* *string

---

##### `ProjectName`<sup>Required</sup> <a name="ProjectName" id="@cdktn/provider-docker.compose.Compose.property.projectName"></a>

```go
func ProjectName() *string
```

- *Type:* *string

---

##### `RemoveOrphans`<sup>Required</sup> <a name="RemoveOrphans" id="@cdktn/provider-docker.compose.Compose.property.removeOrphans"></a>

```go
func RemoveOrphans() interface{}
```

- *Type:* interface{}

---

##### `Wait`<sup>Required</sup> <a name="Wait" id="@cdktn/provider-docker.compose.Compose.property.wait"></a>

```go
func Wait() interface{}
```

- *Type:* interface{}

---

##### `WaitTimeout`<sup>Required</sup> <a name="WaitTimeout" id="@cdktn/provider-docker.compose.Compose.property.waitTimeout"></a>

```go
func WaitTimeout() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.compose.Compose.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### ComposeConfig <a name="ComposeConfig" id="@cdktn/provider-docker.compose.ComposeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.compose.ComposeConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/compose"

&compose.ComposeConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable,
	ForEach: github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator,
	Lifecycle: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle,
	Provider: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider,
	Provisioners: *[]interface{},
	ConfigPaths: *[]*string,
	EnvFiles: *[]*string,
	Profiles: *[]*string,
	ProjectDirectory: *string,
	ProjectName: *string,
	RemoveOrphans: interface{},
	Wait: interface{},
	WaitTimeout: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.configPaths">ConfigPaths</a></code> | <code>*[]*string</code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.envFiles">EnvFiles</a></code> | <code>*[]*string</code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.profiles">Profiles</a></code> | <code>*[]*string</code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory">ProjectDirectory</a></code> | <code>*string</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectName">ProjectName</a></code> | <code>*string</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans">RemoveOrphans</a></code> | <code>interface{}</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.wait">Wait</a></code> | <code>interface{}</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout">WaitTimeout</a></code> | <code>*string</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.compose.ComposeConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.compose.ComposeConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.compose.ComposeConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.compose.ComposeConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.compose.ComposeConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `ConfigPaths`<sup>Required</sup> <a name="ConfigPaths" id="@cdktn/provider-docker.compose.ComposeConfig.property.configPaths"></a>

```go
ConfigPaths *[]*string
```

- *Type:* *[]*string

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `EnvFiles`<sup>Optional</sup> <a name="EnvFiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.envFiles"></a>

```go
EnvFiles *[]*string
```

- *Type:* *[]*string

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#env_files Compose#env_files}

---

##### `Profiles`<sup>Optional</sup> <a name="Profiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.profiles"></a>

```go
Profiles *[]*string
```

- *Type:* *[]*string

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#profiles Compose#profiles}

---

##### `ProjectDirectory`<sup>Optional</sup> <a name="ProjectDirectory" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory"></a>

```go
ProjectDirectory *string
```

- *Type:* *string

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `ProjectName`<sup>Optional</sup> <a name="ProjectName" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectName"></a>

```go
ProjectName *string
```

- *Type:* *string

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_name Compose#project_name}

---

##### `RemoveOrphans`<sup>Optional</sup> <a name="RemoveOrphans" id="@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans"></a>

```go
RemoveOrphans interface{}
```

- *Type:* interface{}

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `Wait`<sup>Optional</sup> <a name="Wait" id="@cdktn/provider-docker.compose.ComposeConfig.property.wait"></a>

```go
Wait interface{}
```

- *Type:* interface{}

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait Compose#wait}

---

##### `WaitTimeout`<sup>Optional</sup> <a name="WaitTimeout" id="@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout"></a>

```go
WaitTimeout *string
```

- *Type:* *string

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---



