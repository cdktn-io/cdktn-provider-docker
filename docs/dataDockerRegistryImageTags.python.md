# `dataDockerRegistryImageTags` Submodule <a name="`dataDockerRegistryImageTags` Submodule" id="@cdktn/provider-docker.dataDockerRegistryImageTags"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataDockerRegistryImageTags <a name="DataDockerRegistryImageTags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags docker_registry_image_tags}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer"></a>

```python
from cdktn_provider_docker import data_docker_registry_image_tags

dataDockerRegistryImageTags.DataDockerRegistryImageTags(
  scope: Construct,
  id: str,
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  name: str,
  insecure_skip_verify: bool | IResolvable = None,
  strict_semver: bool | IResolvable = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.name">name</a></code> | <code>str</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.insecureSkipVerify">insecure_skip_verify</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.strictSemver">strict_semver</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, only stable semantic version tags are returned. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.connection"></a>

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.count"></a>

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.forEach"></a>

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.lifecycle"></a>

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.name"></a>

- *Type:* str

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `insecure_skip_verify`<sup>Optional</sup> <a name="insecure_skip_verify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.insecureSkipVerify"></a>

- *Type:* bool | cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `strict_semver`<sup>Optional</sup> <a name="strict_semver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.strictSemver"></a>

- *Type:* bool | cdktn.IResolvable

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform">to_hcl_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify">reset_insecure_skip_verify</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver">reset_strict_semver</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with"></a>

```python
def with(
  mixins: *IMixin
) -> IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with.parameter.mixins"></a>

- *Type:* *constructs.IMixin

The mixins to apply.

---

##### `add_override` <a name="add_override" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_hcl_terraform` <a name="to_hcl_terraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform"></a>

```python
def to_hcl_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `to_metadata` <a name="to_metadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `reset_insecure_skip_verify` <a name="reset_insecure_skip_verify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify"></a>

```python
def reset_insecure_skip_verify() -> None
```

##### `reset_strict_semver` <a name="reset_strict_semver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver"></a>

```python
def reset_strict_semver() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct"></a>

```python
from cdktn_provider_docker import data_docker_registry_image_tags

dataDockerRegistryImageTags.DataDockerRegistryImageTags.is_construct(
  x: typing.Any
)
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

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement"></a>

```python
from cdktn_provider_docker import data_docker_registry_image_tags

dataDockerRegistryImageTags.DataDockerRegistryImageTags.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource"></a>

```python
from cdktn_provider_docker import data_docker_registry_image_tags

dataDockerRegistryImageTags.DataDockerRegistryImageTags.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport"></a>

```python
from cdktn_provider_docker import data_docker_registry_image_tags

dataDockerRegistryImageTags.DataDockerRegistryImageTags.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the DataDockerRegistryImageTags to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

The id of the existing DataDockerRegistryImageTags that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the DataDockerRegistryImageTags to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack">cdktf_stack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags">tags</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput">insecure_skip_verify_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput">strict_semver_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify">insecure_skip_verify</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver">strict_semver</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `tags`<sup>Required</sup> <a name="tags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `insecure_skip_verify_input`<sup>Optional</sup> <a name="insecure_skip_verify_input" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput"></a>

```python
insecure_skip_verify_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `strict_semver_input`<sup>Optional</sup> <a name="strict_semver_input" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput"></a>

```python
strict_semver_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `insecure_skip_verify`<sup>Required</sup> <a name="insecure_skip_verify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify"></a>

```python
insecure_skip_verify: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `strict_semver`<sup>Required</sup> <a name="strict_semver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver"></a>

```python
strict_semver: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataDockerRegistryImageTagsConfig <a name="DataDockerRegistryImageTagsConfig" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.Initializer"></a>

```python
from cdktn_provider_docker import data_docker_registry_image_tags

dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig(
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  name: str,
  insecure_skip_verify: bool | IResolvable = None,
  strict_semver: bool | IResolvable = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name">name</a></code> | <code>str</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify">insecure_skip_verify</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver">strict_semver</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, only stable semantic version tags are returned. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name"></a>

```python
name: str
```

- *Type:* str

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `insecure_skip_verify`<sup>Optional</sup> <a name="insecure_skip_verify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify"></a>

```python
insecure_skip_verify: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `strict_semver`<sup>Optional</sup> <a name="strict_semver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver"></a>

```python
strict_semver: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---



