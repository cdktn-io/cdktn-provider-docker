# `dataDockerRegistryImageTags` Submodule <a name="`dataDockerRegistryImageTags` Submodule" id="@cdktn/provider-docker.dataDockerRegistryImageTags"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataDockerRegistryImageTags <a name="DataDockerRegistryImageTags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/data-sources/registry_image_tags docker_registry_image_tags}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/datadockerregistryimagetags"

datadockerregistryimagetags.NewDataDockerRegistryImageTags(scope Construct, id *string, config DataDockerRegistryImageTagsConfig) DataDockerRegistryImageTags
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig">DataDockerRegistryImageTagsConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.config"></a>

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

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with"></a>

```go
func With(mixins ...IMixin) IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with.parameter.mixins"></a>

- *Type:* ...github.com/aws/constructs-go/constructs/v10.IMixin

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform"></a>

```go
func ToHclTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `ResetInsecureSkipVerify` <a name="ResetInsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify"></a>

```go
func ResetInsecureSkipVerify()
```

##### `ResetStrictSemver` <a name="ResetStrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver"></a>

```go
func ResetStrictSemver()
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

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/datadockerregistryimagetags"

datadockerregistryimagetags.DataDockerRegistryImageTags_IsConstruct(x interface{}) *bool
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct.parameter.x"></a>

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/datadockerregistryimagetags"

datadockerregistryimagetags.DataDockerRegistryImageTags_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/datadockerregistryimagetags"

datadockerregistryimagetags.DataDockerRegistryImageTags_IsTerraformDataSource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource.parameter.x"></a>

- *Type:* interface{}

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/datadockerregistryimagetags"

datadockerregistryimagetags.DataDockerRegistryImageTags_GenerateConfigForImport(scope Construct, importToId *string, importFromId *string, provider TerraformProvider) ImportableResource
```

Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importToId"></a>

- *Type:* *string

The construct id used in the generated config for the DataDockerRegistryImageTags to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importFromId"></a>

- *Type:* *string

The id of the existing DataDockerRegistryImageTags that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/data-sources/registry_image_tags#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.provider"></a>

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

? Optional instance of the provider where the DataDockerRegistryImageTags to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack">CdktfStack</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags">Tags</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput">InsecureSkipVerifyInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput">StrictSemverInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver">StrictSemver</a></code> | <code>interface{}</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Tags`<sup>Required</sup> <a name="Tags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags"></a>

```go
func Tags() *[]*string
```

- *Type:* *[]*string

---

##### `InsecureSkipVerifyInput`<sup>Optional</sup> <a name="InsecureSkipVerifyInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput"></a>

```go
func InsecureSkipVerifyInput() interface{}
```

- *Type:* interface{}

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `StrictSemverInput`<sup>Optional</sup> <a name="StrictSemverInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput"></a>

```go
func StrictSemverInput() interface{}
```

- *Type:* interface{}

---

##### `InsecureSkipVerify`<sup>Required</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify"></a>

```go
func InsecureSkipVerify() interface{}
```

- *Type:* interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `StrictSemver`<sup>Required</sup> <a name="StrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver"></a>

```go
func StrictSemver() interface{}
```

- *Type:* interface{}

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### DataDockerRegistryImageTagsConfig <a name="DataDockerRegistryImageTagsConfig" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.Initializer"></a>

```go
import "github.com/cdktn-io/cdktn-provider-docker-go/docker/v15/datadockerregistryimagetags"

&datadockerregistryimagetags.DataDockerRegistryImageTagsConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable,
	ForEach: github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator,
	Lifecycle: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle,
	Provider: github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider,
	Provisioners: *[]interface{},
	Name: *string,
	InsecureSkipVerify: interface{},
	StrictSemver: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach">ForEach</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider">Provider</a></code> | <code>github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name">Name</a></code> | <code>*string</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify">InsecureSkipVerify</a></code> | <code>interface{}</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver">StrictSemver</a></code> | <code>interface{}</code> | If `true`, only stable semantic version tags are returned. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/open-constructs/cdk-terrain-go/cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `InsecureSkipVerify`<sup>Optional</sup> <a name="InsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify"></a>

```go
InsecureSkipVerify interface{}
```

- *Type:* interface{}

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `StrictSemver`<sup>Optional</sup> <a name="StrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver"></a>

```go
StrictSemver interface{}
```

- *Type:* interface{}

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---



