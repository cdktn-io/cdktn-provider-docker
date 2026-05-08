# `volume` Submodule <a name="`volume` Submodule" id="@cdktn/provider-docker.volume"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Volume <a name="Volume" id="@cdktn/provider-docker.volume.Volume"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume docker_volume}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.Volume.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.NewVolume(scope Construct, id *string, config VolumeConfig) Volume
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeConfig">VolumeConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="config" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeConfig">VolumeConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.volume.Volume.putCluster">PutCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.putLabels">PutLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetCluster">ResetCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetDriver">ResetDriver</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetDriverOpts">ResetDriverOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetLabels">ResetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetName">ResetName</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.volume.Volume.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.volume.Volume.with"></a>

```go
func With(mixins ...IMixin) IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.volume.Volume.with.parameter.mixins"></a>

- *Type:* ...github.com/aws/constructs-go/constructs/v10.IMixin

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.volume.Volume.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.volume.Volume.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.volume.Volume.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.volume.Volume.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.volume.Volume.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.volume.Volume.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.volume.Volume.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.volume.Volume.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.volume.Volume.addMoveTarget"></a>

```go
func AddMoveTarget(moveTarget *string)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.volume.Volume.addMoveTarget.parameter.moveTarget"></a>

- *Type:* *string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.volume.Volume.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.volume.Volume.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.volume.Volume.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.volume.Volume.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.volume.Volume.hasResourceMove"></a>

```go
func HasResourceMove() interface{}
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.volume.Volume.importFrom"></a>

```go
func ImportFrom(id *string, provider TerraformProvider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.importFrom.parameter.id"></a>

- *Type:* *string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.importFrom.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.volume.Volume.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.volume.Volume.moveFromId"></a>

```go
func MoveFromId(id *string)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.moveFromId.parameter.id"></a>

- *Type:* *string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.volume.Volume.moveTo"></a>

```go
func MoveTo(moveTarget *string, index interface{})
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.volume.Volume.moveTo.parameter.moveTarget"></a>

- *Type:* *string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.volume.Volume.moveTo.parameter.index"></a>

- *Type:* interface{}

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.volume.Volume.moveToId"></a>

```go
func MoveToId(id *string)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.moveToId.parameter.id"></a>

- *Type:* *string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutCluster` <a name="PutCluster" id="@cdktn/provider-docker.volume.Volume.putCluster"></a>

```go
func PutCluster(value VolumeCluster)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.putCluster.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---

##### `PutLabels` <a name="PutLabels" id="@cdktn/provider-docker.volume.Volume.putLabels"></a>

```go
func PutLabels(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.putLabels.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetCluster` <a name="ResetCluster" id="@cdktn/provider-docker.volume.Volume.resetCluster"></a>

```go
func ResetCluster()
```

##### `ResetDriver` <a name="ResetDriver" id="@cdktn/provider-docker.volume.Volume.resetDriver"></a>

```go
func ResetDriver()
```

##### `ResetDriverOpts` <a name="ResetDriverOpts" id="@cdktn/provider-docker.volume.Volume.resetDriverOpts"></a>

```go
func ResetDriverOpts()
```

##### `ResetId` <a name="ResetId" id="@cdktn/provider-docker.volume.Volume.resetId"></a>

```go
func ResetId()
```

##### `ResetLabels` <a name="ResetLabels" id="@cdktn/provider-docker.volume.Volume.resetLabels"></a>

```go
func ResetLabels()
```

##### `ResetName` <a name="ResetName" id="@cdktn/provider-docker.volume.Volume.resetName"></a>

```go
func ResetName()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a Volume resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.volume.Volume.isConstruct"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.Volume_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.volume.Volume.isTerraformElement"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.Volume_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.volume.Volume.isTerraformResource"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.Volume_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.Volume_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTN code for importing a Volume resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the Volume to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing Volume that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

? Optional instance of the provider where the Volume to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.cdktfStack">CdktfStack</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.cluster">Cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference">VolumeClusterOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.labels">Labels</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList">VolumeLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.mountpoint">Mountpoint</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.clusterInput">ClusterInput</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverInput">DriverInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverOptsInput">DriverOptsInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.labelsInput">LabelsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driver">Driver</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverOpts">DriverOpts</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.name">Name</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.volume.Volume.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.volume.Volume.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.volume.Volume.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.volume.Volume.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.volume.Volume.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.volume.Volume.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.volume.Volume.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.volume.Volume.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.volume.Volume.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.volume.Volume.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.volume.Volume.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.volume.Volume.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.volume.Volume.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.volume.Volume.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Cluster`<sup>Required</sup> <a name="Cluster" id="@cdktn/provider-docker.volume.Volume.property.cluster"></a>

```go
func Cluster() VolumeClusterOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference">VolumeClusterOutputReference</a>

---

##### `Labels`<sup>Required</sup> <a name="Labels" id="@cdktn/provider-docker.volume.Volume.property.labels"></a>

```go
func Labels() VolumeLabelsList
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeLabelsList">VolumeLabelsList</a>

---

##### `Mountpoint`<sup>Required</sup> <a name="Mountpoint" id="@cdktn/provider-docker.volume.Volume.property.mountpoint"></a>

```go
func Mountpoint() *string
```

- *Type:* *string

---

##### `ClusterInput`<sup>Optional</sup> <a name="ClusterInput" id="@cdktn/provider-docker.volume.Volume.property.clusterInput"></a>

```go
func ClusterInput() VolumeCluster
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---

##### `DriverInput`<sup>Optional</sup> <a name="DriverInput" id="@cdktn/provider-docker.volume.Volume.property.driverInput"></a>

```go
func DriverInput() *string
```

- *Type:* *string

---

##### `DriverOptsInput`<sup>Optional</sup> <a name="DriverOptsInput" id="@cdktn/provider-docker.volume.Volume.property.driverOptsInput"></a>

```go
func DriverOptsInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.volume.Volume.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `LabelsInput`<sup>Optional</sup> <a name="LabelsInput" id="@cdktn/provider-docker.volume.Volume.property.labelsInput"></a>

```go
func LabelsInput() interface{}
```

- *Type:* interface{}

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.volume.Volume.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `Driver`<sup>Required</sup> <a name="Driver" id="@cdktn/provider-docker.volume.Volume.property.driver"></a>

```go
func Driver() *string
```

- *Type:* *string

---

##### `DriverOpts`<sup>Required</sup> <a name="DriverOpts" id="@cdktn/provider-docker.volume.Volume.property.driverOpts"></a>

```go
func DriverOpts() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.volume.Volume.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.volume.Volume.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.volume.Volume.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### VolumeCluster <a name="VolumeCluster" id="@cdktn/provider-docker.volume.VolumeCluster"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeCluster.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

&volume.VolumeCluster {
	Availability: *string,
	Group: *string,
	LimitBytes: *string,
	RequiredBytes: *string,
	Scope: *string,
	Sharing: *string,
	TopologyPreferred: *string,
	TopologyRequired: *string,
	Type: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.availability">Availability</a></code> | <code>*string</code> | Availability of the volume. Can be `active` (default), `pause`, or `drain`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.group">Group</a></code> | <code>*string</code> | Cluster Volume group. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.limitBytes">LimitBytes</a></code> | <code>*string</code> | Minimum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc). |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.requiredBytes">RequiredBytes</a></code> | <code>*string</code> | Maximum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc). |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.scope">Scope</a></code> | <code>*string</code> | The scope of the volume. Can be `single` (default) or `multi`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.sharing">Sharing</a></code> | <code>*string</code> | The sharing mode. Can be `none` (default), `readonly`, `onewriter` or `all`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.topologyPreferred">TopologyPreferred</a></code> | <code>*string</code> | A topology that the Cluster Volume would be preferred in. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.topologyRequired">TopologyRequired</a></code> | <code>*string</code> | A topology that the Cluster Volume must be accessible from. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.type">Type</a></code> | <code>*string</code> | Cluster Volume access type. Can be `mount` or `block` (default). |

---

##### `Availability`<sup>Optional</sup> <a name="Availability" id="@cdktn/provider-docker.volume.VolumeCluster.property.availability"></a>

```go
Availability *string
```

- *Type:* *string

Availability of the volume. Can be `active` (default), `pause`, or `drain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#availability Volume#availability}

---

##### `Group`<sup>Optional</sup> <a name="Group" id="@cdktn/provider-docker.volume.VolumeCluster.property.group"></a>

```go
Group *string
```

- *Type:* *string

Cluster Volume group.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#group Volume#group}

---

##### `LimitBytes`<sup>Optional</sup> <a name="LimitBytes" id="@cdktn/provider-docker.volume.VolumeCluster.property.limitBytes"></a>

```go
LimitBytes *string
```

- *Type:* *string

Minimum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc).

Must be in format of KiB, MiB, Gib, Tib or PiB.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#limit_bytes Volume#limit_bytes}

---

##### `RequiredBytes`<sup>Optional</sup> <a name="RequiredBytes" id="@cdktn/provider-docker.volume.VolumeCluster.property.requiredBytes"></a>

```go
RequiredBytes *string
```

- *Type:* *string

Maximum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc).

Must be in format of KiB, MiB, Gib, Tib or PiB.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#required_bytes Volume#required_bytes}

---

##### `Scope`<sup>Optional</sup> <a name="Scope" id="@cdktn/provider-docker.volume.VolumeCluster.property.scope"></a>

```go
Scope *string
```

- *Type:* *string

The scope of the volume. Can be `single` (default) or `multi`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#scope Volume#scope}

---

##### `Sharing`<sup>Optional</sup> <a name="Sharing" id="@cdktn/provider-docker.volume.VolumeCluster.property.sharing"></a>

```go
Sharing *string
```

- *Type:* *string

The sharing mode. Can be `none` (default), `readonly`, `onewriter` or `all`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#sharing Volume#sharing}

---

##### `TopologyPreferred`<sup>Optional</sup> <a name="TopologyPreferred" id="@cdktn/provider-docker.volume.VolumeCluster.property.topologyPreferred"></a>

```go
TopologyPreferred *string
```

- *Type:* *string

A topology that the Cluster Volume would be preferred in.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#topology_preferred Volume#topology_preferred}

---

##### `TopologyRequired`<sup>Optional</sup> <a name="TopologyRequired" id="@cdktn/provider-docker.volume.VolumeCluster.property.topologyRequired"></a>

```go
TopologyRequired *string
```

- *Type:* *string

A topology that the Cluster Volume must be accessible from.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#topology_required Volume#topology_required}

---

##### `Type`<sup>Optional</sup> <a name="Type" id="@cdktn/provider-docker.volume.VolumeCluster.property.type"></a>

```go
Type *string
```

- *Type:* *string

Cluster Volume access type. Can be `mount` or `block` (default).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#type Volume#type}

---

### VolumeConfig <a name="VolumeConfig" id="@cdktn/provider-docker.volume.VolumeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

&volume.VolumeConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable,
	ForEach: github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator,
	Lifecycle: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle,
	Provider: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider,
	Provisioners: *[]interface{},
	Cluster: github.com/cdktn-io/cdktn-provider-docker-go/docker/v15.volume.VolumeCluster,
	Driver: *string,
	DriverOpts: *map[string]*string,
	Id: *string,
	Labels: interface{},
	Name: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.cluster">Cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | cluster block. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.driver">Driver</a></code> | <code>*string</code> | Driver type for the volume. Defaults to `local`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.driverOpts">DriverOpts</a></code> | <code>*map[string]*string</code> | Options specific to the driver. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#id Volume#id}. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.labels">Labels</a></code> | <code>interface{}</code> | labels block. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.name">Name</a></code> | <code>*string</code> | The name of the Docker volume (will be generated if not provided). |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.volume.VolumeConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.volume.VolumeConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.volume.VolumeConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.volume.VolumeConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.volume.VolumeConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.volume.VolumeConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.volume.VolumeConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Cluster`<sup>Optional</sup> <a name="Cluster" id="@cdktn/provider-docker.volume.VolumeConfig.property.cluster"></a>

```go
Cluster VolumeCluster
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

cluster block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#cluster Volume#cluster}

---

##### `Driver`<sup>Optional</sup> <a name="Driver" id="@cdktn/provider-docker.volume.VolumeConfig.property.driver"></a>

```go
Driver *string
```

- *Type:* *string

Driver type for the volume. Defaults to `local`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#driver Volume#driver}

---

##### `DriverOpts`<sup>Optional</sup> <a name="DriverOpts" id="@cdktn/provider-docker.volume.VolumeConfig.property.driverOpts"></a>

```go
DriverOpts *map[string]*string
```

- *Type:* *map[string]*string

Options specific to the driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#driver_opts Volume#driver_opts}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktn/provider-docker.volume.VolumeConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#id Volume#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Labels`<sup>Optional</sup> <a name="Labels" id="@cdktn/provider-docker.volume.VolumeConfig.property.labels"></a>

```go
Labels interface{}
```

- *Type:* interface{}

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#labels Volume#labels}

---

##### `Name`<sup>Optional</sup> <a name="Name" id="@cdktn/provider-docker.volume.VolumeConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

The name of the Docker volume (will be generated if not provided).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#name Volume#name}

---

### VolumeLabels <a name="VolumeLabels" id="@cdktn/provider-docker.volume.VolumeLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeLabels.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

&volume.VolumeLabels {
	Label: *string,
	Value: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabels.property.label">Label</a></code> | <code>*string</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabels.property.value">Value</a></code> | <code>*string</code> | Value of the label. |

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.volume.VolumeLabels.property.label"></a>

```go
Label *string
```

- *Type:* *string

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#label Volume#label}

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.volume.VolumeLabels.property.value"></a>

```go
Value *string
```

- *Type:* *string

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/volume#value Volume#value}

---

## Classes <a name="Classes" id="Classes"></a>

### VolumeClusterOutputReference <a name="VolumeClusterOutputReference" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.NewVolumeClusterOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string) VolumeClusterOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetAvailability">ResetAvailability</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetGroup">ResetGroup</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetLimitBytes">ResetLimitBytes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetRequiredBytes">ResetRequiredBytes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetScope">ResetScope</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetSharing">ResetSharing</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyPreferred">ResetTopologyPreferred</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyRequired">ResetTopologyRequired</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetType">ResetType</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAvailability` <a name="ResetAvailability" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetAvailability"></a>

```go
func ResetAvailability()
```

##### `ResetGroup` <a name="ResetGroup" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetGroup"></a>

```go
func ResetGroup()
```

##### `ResetLimitBytes` <a name="ResetLimitBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetLimitBytes"></a>

```go
func ResetLimitBytes()
```

##### `ResetRequiredBytes` <a name="ResetRequiredBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetRequiredBytes"></a>

```go
func ResetRequiredBytes()
```

##### `ResetScope` <a name="ResetScope" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetScope"></a>

```go
func ResetScope()
```

##### `ResetSharing` <a name="ResetSharing" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetSharing"></a>

```go
func ResetSharing()
```

##### `ResetTopologyPreferred` <a name="ResetTopologyPreferred" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyPreferred"></a>

```go
func ResetTopologyPreferred()
```

##### `ResetTopologyRequired` <a name="ResetTopologyRequired" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyRequired"></a>

```go
func ResetTopologyRequired()
```

##### `ResetType` <a name="ResetType" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetType"></a>

```go
func ResetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availabilityInput">AvailabilityInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.groupInput">GroupInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytesInput">LimitBytesInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytesInput">RequiredBytesInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scopeInput">ScopeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharingInput">SharingInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferredInput">TopologyPreferredInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequiredInput">TopologyRequiredInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availability">Availability</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.group">Group</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytes">LimitBytes</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytes">RequiredBytes</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scope">Scope</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharing">Sharing</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferred">TopologyPreferred</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequired">TopologyRequired</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `AvailabilityInput`<sup>Optional</sup> <a name="AvailabilityInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availabilityInput"></a>

```go
func AvailabilityInput() *string
```

- *Type:* *string

---

##### `GroupInput`<sup>Optional</sup> <a name="GroupInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.groupInput"></a>

```go
func GroupInput() *string
```

- *Type:* *string

---

##### `LimitBytesInput`<sup>Optional</sup> <a name="LimitBytesInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytesInput"></a>

```go
func LimitBytesInput() *string
```

- *Type:* *string

---

##### `RequiredBytesInput`<sup>Optional</sup> <a name="RequiredBytesInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytesInput"></a>

```go
func RequiredBytesInput() *string
```

- *Type:* *string

---

##### `ScopeInput`<sup>Optional</sup> <a name="ScopeInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scopeInput"></a>

```go
func ScopeInput() *string
```

- *Type:* *string

---

##### `SharingInput`<sup>Optional</sup> <a name="SharingInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharingInput"></a>

```go
func SharingInput() *string
```

- *Type:* *string

---

##### `TopologyPreferredInput`<sup>Optional</sup> <a name="TopologyPreferredInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferredInput"></a>

```go
func TopologyPreferredInput() *string
```

- *Type:* *string

---

##### `TopologyRequiredInput`<sup>Optional</sup> <a name="TopologyRequiredInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequiredInput"></a>

```go
func TopologyRequiredInput() *string
```

- *Type:* *string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Availability`<sup>Required</sup> <a name="Availability" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availability"></a>

```go
func Availability() *string
```

- *Type:* *string

---

##### `Group`<sup>Required</sup> <a name="Group" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.group"></a>

```go
func Group() *string
```

- *Type:* *string

---

##### `LimitBytes`<sup>Required</sup> <a name="LimitBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytes"></a>

```go
func LimitBytes() *string
```

- *Type:* *string

---

##### `RequiredBytes`<sup>Required</sup> <a name="RequiredBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytes"></a>

```go
func RequiredBytes() *string
```

- *Type:* *string

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scope"></a>

```go
func Scope() *string
```

- *Type:* *string

---

##### `Sharing`<sup>Required</sup> <a name="Sharing" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharing"></a>

```go
func Sharing() *string
```

- *Type:* *string

---

##### `TopologyPreferred`<sup>Required</sup> <a name="TopologyPreferred" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferred"></a>

```go
func TopologyPreferred() *string
```

- *Type:* *string

---

##### `TopologyRequired`<sup>Required</sup> <a name="TopologyRequired" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequired"></a>

```go
func TopologyRequired() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.internalValue"></a>

```go
func InternalValue() VolumeCluster
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---


### VolumeLabelsList <a name="VolumeLabelsList" id="@cdktn/provider-docker.volume.VolumeLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.NewVolumeLabelsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) VolumeLabelsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey"></a>

```go
func AllWithMapKey(mapKeyAttributeName *string) DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* *string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.volume.VolumeLabelsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.volume.VolumeLabelsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeLabelsList.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.volume.VolumeLabelsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.volume.VolumeLabelsList.get"></a>

```go
func Get(index *f64) VolumeLabelsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.volume.VolumeLabelsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### VolumeLabelsOutputReference <a name="VolumeLabelsOutputReference" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/volume"

volume.NewVolumeLabelsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) VolumeLabelsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.labelInput">LabelInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.valueInput">ValueInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.label">Label</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.value">Value</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `LabelInput`<sup>Optional</sup> <a name="LabelInput" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.labelInput"></a>

```go
func LabelInput() *string
```

- *Type:* *string

---

##### `ValueInput`<sup>Optional</sup> <a name="ValueInput" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.valueInput"></a>

```go
func ValueInput() *string
```

- *Type:* *string

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.label"></a>

```go
func Label() *string
```

- *Type:* *string

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.value"></a>

```go
func Value() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



