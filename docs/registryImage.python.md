# `registryImage` Submodule <a name="`registryImage` Submodule" id="@cdktn/provider-docker.registryImage"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### RegistryImage <a name="RegistryImage" id="@cdktn/provider-docker.registryImage.RegistryImage"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image docker_registry_image}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImage(
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
  auth_config: RegistryImageAuthConfig = None,
  build_attribute: RegistryImageBuild = None,
  id: str = None,
  insecure_skip_verify: bool | IResolvable = None,
  keep_remotely: bool | IResolvable = None,
  timeouts: RegistryImageTimeouts = None,
  triggers: typing.Mapping[str] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.name">name</a></code> | <code>str</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.authConfig">auth_config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.buildAttribute">build_attribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.insecureSkipVerify">insecure_skip_verify</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.keepRemotely">keep_remotely</a></code> | <code>bool \| cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.triggers">triggers</a></code> | <code>typing.Mapping[str]</code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.connection"></a>

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.count"></a>

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.forEach"></a>

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.lifecycle"></a>

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.name"></a>

- *Type:* str

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `auth_config`<sup>Optional</sup> <a name="auth_config" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.authConfig"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `build_attribute`<sup>Optional</sup> <a name="build_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.buildAttribute"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `insecure_skip_verify`<sup>Optional</sup> <a name="insecure_skip_verify" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.insecureSkipVerify"></a>

- *Type:* bool | cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `keep_remotely`<sup>Optional</sup> <a name="keep_remotely" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.keepRemotely"></a>

- *Type:* bool | cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.timeouts"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `triggers`<sup>Optional</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.triggers"></a>

- *Type:* typing.Mapping[str]

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform">to_hcl_terraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget">add_move_target</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove">has_resource_move</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.importFrom">import_from</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveFromId">move_from_id</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveTo">move_to</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveToId">move_to_id</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig">put_auth_config</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute">put_build_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts">put_timeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig">reset_auth_config</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute">reset_build_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify">reset_insecure_skip_verify</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely">reset_keep_remotely</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts">reset_timeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers">reset_triggers</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImage.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.registryImage.RegistryImage.with"></a>

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

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.registryImage.RegistryImage.with.parameter.mixins"></a>

- *Type:* *constructs.IMixin

The mixins to apply.

---

##### `add_override` <a name="add_override" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_hcl_terraform` <a name="to_hcl_terraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform"></a>

```python
def to_hcl_terraform() -> typing.Any
```

##### `to_metadata` <a name="to_metadata" id="@cdktn/provider-docker.registryImage.RegistryImage.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `add_move_target` <a name="add_move_target" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget"></a>

```python
def add_move_target(
  move_target: str
) -> None
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget.parameter.moveTarget"></a>

- *Type:* str

The string move target that will correspond to this resource.

---

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `has_resource_move` <a name="has_resource_move" id="@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove"></a>

```python
def has_resource_move() -> TerraformResourceMoveByTarget | TerraformResourceMoveById
```

##### `import_from` <a name="import_from" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom"></a>

```python
def import_from(
  id: str,
  provider: TerraformProvider = None
) -> None
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.id"></a>

- *Type:* str

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `move_from_id` <a name="move_from_id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId"></a>

```python
def move_from_id(
  id: str
) -> None
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId.parameter.id"></a>

- *Type:* str

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `move_to` <a name="move_to" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo"></a>

```python
def move_to(
  move_target: str,
  index: str | typing.Union[int, float] = None
) -> None
```

Moves this resource to the target resource given by moveTarget.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.moveTarget"></a>

- *Type:* str

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.index"></a>

- *Type:* str | typing.Union[int, float]

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `move_to_id` <a name="move_to_id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId"></a>

```python
def move_to_id(
  id: str
) -> None
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId.parameter.id"></a>

- *Type:* str

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `put_auth_config` <a name="put_auth_config" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig"></a>

```python
def put_auth_config(
  address: str,
  password: str = None,
  username: str = None
) -> None
```

###### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.address"></a>

- *Type:* str

The address of the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#address RegistryImage#address}

---

###### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.password"></a>

- *Type:* str

The password for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#password RegistryImage#password}

---

###### `username`<sup>Optional</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.username"></a>

- *Type:* str

The username for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#username RegistryImage#username}

---

##### `put_build_attribute` <a name="put_build_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute"></a>

```python
def put_build_attribute(
  context: str,
  additional_contexts: typing.List[str] = None,
  auth_config: IResolvable | typing.List[RegistryImageBuildAuthConfig] = None,
  build_args: typing.Mapping[str] = None,
  builder: str = None,
  build_id: str = None,
  build_log_file: str = None,
  cache_from: typing.List[str] = None,
  cache_to: typing.List[str] = None,
  cgroup_parent: str = None,
  cpu_period: typing.Union[int, float] = None,
  cpu_quota: typing.Union[int, float] = None,
  cpu_set_cpus: str = None,
  cpu_set_mems: str = None,
  cpu_shares: typing.Union[int, float] = None,
  dockerfile: str = None,
  extra_hosts: typing.List[str] = None,
  force_remove: bool | IResolvable = None,
  isolation: str = None,
  label: typing.Mapping[str] = None,
  labels: typing.Mapping[str] = None,
  memory: typing.Union[int, float] = None,
  memory_swap: typing.Union[int, float] = None,
  network_mode: str = None,
  no_cache: bool | IResolvable = None,
  platform: str = None,
  provenance: str = None,
  pull_parent: bool | IResolvable = None,
  remote_context: str = None,
  remove: bool | IResolvable = None,
  sbom: str = None,
  secrets: IResolvable | typing.List[RegistryImageBuildSecrets] = None,
  security_opt: typing.List[str] = None,
  session_id: str = None,
  shm_size: typing.Union[int, float] = None,
  squash: bool | IResolvable = None,
  suppress_output: bool | IResolvable = None,
  tag: typing.List[str] = None,
  target: str = None,
  ulimit: IResolvable | typing.List[RegistryImageBuildUlimit] = None,
  use_legacy_builder: bool | IResolvable = None,
  version: str = None
) -> None
```

###### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.context"></a>

- *Type:* str

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#context RegistryImage#context}

---

###### `additional_contexts`<sup>Optional</sup> <a name="additional_contexts" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.additionalContexts"></a>

- *Type:* typing.List[str]

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#additional_contexts RegistryImage#additional_contexts}

---

###### `auth_config`<sup>Optional</sup> <a name="auth_config" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.authConfig"></a>

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

###### `build_args`<sup>Optional</sup> <a name="build_args" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.buildArgs"></a>

- *Type:* typing.Mapping[str]

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build_args RegistryImage#build_args}

---

###### `builder`<sup>Optional</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.builder"></a>

- *Type:* str

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#builder RegistryImage#builder}

---

###### `build_id`<sup>Optional</sup> <a name="build_id" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.buildId"></a>

- *Type:* str

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build_id RegistryImage#build_id}

---

###### `build_log_file`<sup>Optional</sup> <a name="build_log_file" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.buildLogFile"></a>

- *Type:* str

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build_log_file RegistryImage#build_log_file}

---

###### `cache_from`<sup>Optional</sup> <a name="cache_from" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cacheFrom"></a>

- *Type:* typing.List[str]

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cache_from RegistryImage#cache_from}

---

###### `cache_to`<sup>Optional</sup> <a name="cache_to" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cacheTo"></a>

- *Type:* typing.List[str]

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cache_to RegistryImage#cache_to}

---

###### `cgroup_parent`<sup>Optional</sup> <a name="cgroup_parent" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cgroupParent"></a>

- *Type:* str

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cgroup_parent RegistryImage#cgroup_parent}

---

###### `cpu_period`<sup>Optional</sup> <a name="cpu_period" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cpuPeriod"></a>

- *Type:* typing.Union[int, float]

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_period RegistryImage#cpu_period}

---

###### `cpu_quota`<sup>Optional</sup> <a name="cpu_quota" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cpuQuota"></a>

- *Type:* typing.Union[int, float]

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_quota RegistryImage#cpu_quota}

---

###### `cpu_set_cpus`<sup>Optional</sup> <a name="cpu_set_cpus" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cpuSetCpus"></a>

- *Type:* str

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_set_cpus RegistryImage#cpu_set_cpus}

---

###### `cpu_set_mems`<sup>Optional</sup> <a name="cpu_set_mems" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cpuSetMems"></a>

- *Type:* str

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_set_mems RegistryImage#cpu_set_mems}

---

###### `cpu_shares`<sup>Optional</sup> <a name="cpu_shares" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.cpuShares"></a>

- *Type:* typing.Union[int, float]

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_shares RegistryImage#cpu_shares}

---

###### `dockerfile`<sup>Optional</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.dockerfile"></a>

- *Type:* str

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#dockerfile RegistryImage#dockerfile}

---

###### `extra_hosts`<sup>Optional</sup> <a name="extra_hosts" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.extraHosts"></a>

- *Type:* typing.List[str]

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#extra_hosts RegistryImage#extra_hosts}

---

###### `force_remove`<sup>Optional</sup> <a name="force_remove" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.forceRemove"></a>

- *Type:* bool | cdktn.IResolvable

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#force_remove RegistryImage#force_remove}

---

###### `isolation`<sup>Optional</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.isolation"></a>

- *Type:* str

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#isolation RegistryImage#isolation}

---

###### `label`<sup>Optional</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.label"></a>

- *Type:* typing.Mapping[str]

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#label RegistryImage#label}

---

###### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.labels"></a>

- *Type:* typing.Mapping[str]

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#labels RegistryImage#labels}

---

###### `memory`<sup>Optional</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.memory"></a>

- *Type:* typing.Union[int, float]

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#memory RegistryImage#memory}

---

###### `memory_swap`<sup>Optional</sup> <a name="memory_swap" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.memorySwap"></a>

- *Type:* typing.Union[int, float]

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#memory_swap RegistryImage#memory_swap}

---

###### `network_mode`<sup>Optional</sup> <a name="network_mode" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.networkMode"></a>

- *Type:* str

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#network_mode RegistryImage#network_mode}

---

###### `no_cache`<sup>Optional</sup> <a name="no_cache" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.noCache"></a>

- *Type:* bool | cdktn.IResolvable

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#no_cache RegistryImage#no_cache}

---

###### `platform`<sup>Optional</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.platform"></a>

- *Type:* str

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#platform RegistryImage#platform}

---

###### `provenance`<sup>Optional</sup> <a name="provenance" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.provenance"></a>

- *Type:* str

Set provenance attestation for the build.

BuildKit v0.11+ adds provenance attestations by default, which creates OCI image manifests that some registries (like AWS Lambda) don't support. Set to `false` to disable. Valid values: `false`, `true`, `min`, `max`, `mode=min`, `mode=max`, or a full provenance specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#provenance RegistryImage#provenance}

---

###### `pull_parent`<sup>Optional</sup> <a name="pull_parent" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.pullParent"></a>

- *Type:* bool | cdktn.IResolvable

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#pull_parent RegistryImage#pull_parent}

---

###### `remote_context`<sup>Optional</sup> <a name="remote_context" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.remoteContext"></a>

- *Type:* str

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#remote_context RegistryImage#remote_context}

---

###### `remove`<sup>Optional</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.remove"></a>

- *Type:* bool | cdktn.IResolvable

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#remove RegistryImage#remove}

---

###### `sbom`<sup>Optional</sup> <a name="sbom" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.sbom"></a>

- *Type:* str

Set SBOM (Software Bill of Materials) attestation for the build.

Set to `false` to disable. Valid values: `false`, `true`, or a full SBOM specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#sbom RegistryImage#sbom}

---

###### `secrets`<sup>Optional</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.secrets"></a>

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#secrets RegistryImage#secrets}

---

###### `security_opt`<sup>Optional</sup> <a name="security_opt" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.securityOpt"></a>

- *Type:* typing.List[str]

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#security_opt RegistryImage#security_opt}

---

###### `session_id`<sup>Optional</sup> <a name="session_id" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.sessionId"></a>

- *Type:* str

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#session_id RegistryImage#session_id}

---

###### `shm_size`<sup>Optional</sup> <a name="shm_size" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.shmSize"></a>

- *Type:* typing.Union[int, float]

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#shm_size RegistryImage#shm_size}

---

###### `squash`<sup>Optional</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.squash"></a>

- *Type:* bool | cdktn.IResolvable

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#squash RegistryImage#squash}

---

###### `suppress_output`<sup>Optional</sup> <a name="suppress_output" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.suppressOutput"></a>

- *Type:* bool | cdktn.IResolvable

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#suppress_output RegistryImage#suppress_output}

---

###### `tag`<sup>Optional</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.tag"></a>

- *Type:* typing.List[str]

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#tag RegistryImage#tag}

---

###### `target`<sup>Optional</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.target"></a>

- *Type:* str

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#target RegistryImage#target}

---

###### `ulimit`<sup>Optional</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.ulimit"></a>

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#ulimit RegistryImage#ulimit}

---

###### `use_legacy_builder`<sup>Optional</sup> <a name="use_legacy_builder" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.useLegacyBuilder"></a>

- *Type:* bool | cdktn.IResolvable

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#use_legacy_builder RegistryImage#use_legacy_builder}

---

###### `version`<sup>Optional</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.version"></a>

- *Type:* str

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#version RegistryImage#version}

---

##### `put_timeouts` <a name="put_timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts"></a>

```python
def put_timeouts(
  create: str = None,
  delete: str = None,
  update: str = None
) -> None
```

###### `create`<sup>Optional</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.create"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#create RegistryImage#create}.

---

###### `delete`<sup>Optional</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.delete"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#delete RegistryImage#delete}.

---

###### `update`<sup>Optional</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.update"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#update RegistryImage#update}.

---

##### `reset_auth_config` <a name="reset_auth_config" id="@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig"></a>

```python
def reset_auth_config() -> None
```

##### `reset_build_attribute` <a name="reset_build_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute"></a>

```python
def reset_build_attribute() -> None
```

##### `reset_id` <a name="reset_id" id="@cdktn/provider-docker.registryImage.RegistryImage.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_insecure_skip_verify` <a name="reset_insecure_skip_verify" id="@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify"></a>

```python
def reset_insecure_skip_verify() -> None
```

##### `reset_keep_remotely` <a name="reset_keep_remotely" id="@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely"></a>

```python
def reset_keep_remotely() -> None
```

##### `reset_timeouts` <a name="reset_timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts"></a>

```python
def reset_timeouts() -> None
```

##### `reset_triggers` <a name="reset_triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers"></a>

```python
def reset_triggers() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource">is_terraform_resource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktn/provider-docker.registryImage.RegistryImage.isConstruct"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImage.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImage.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImage.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImage.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the RegistryImage to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

The id of the existing RegistryImage that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the RegistryImage to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack">cdktf_stack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig">auth_config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute">build_attribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest">sha256_digest</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput">auth_config_input</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput">build_attribute_input</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput">insecure_skip_verify_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput">keep_remotely_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput">timeouts_input</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput">triggers_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify">insecure_skip_verify</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely">keep_remotely</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggers">triggers</a></code> | <code>typing.Mapping[str]</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.registryImage.RegistryImage.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImage.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImage.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.registryImage.RegistryImage.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `auth_config`<sup>Required</sup> <a name="auth_config" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig"></a>

```python
auth_config: RegistryImageAuthConfigOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a>

---

##### `build_attribute`<sup>Required</sup> <a name="build_attribute" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute"></a>

```python
build_attribute: RegistryImageBuildOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a>

---

##### `sha256_digest`<sup>Required</sup> <a name="sha256_digest" id="@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest"></a>

```python
sha256_digest: str
```

- *Type:* str

---

##### `timeouts`<sup>Required</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts"></a>

```python
timeouts: RegistryImageTimeoutsOutputReference
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a>

---

##### `auth_config_input`<sup>Optional</sup> <a name="auth_config_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput"></a>

```python
auth_config_input: RegistryImageAuthConfig
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `build_attribute_input`<sup>Optional</sup> <a name="build_attribute_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput"></a>

```python
build_attribute_input: RegistryImageBuild
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `insecure_skip_verify_input`<sup>Optional</sup> <a name="insecure_skip_verify_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput"></a>

```python
insecure_skip_verify_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `keep_remotely_input`<sup>Optional</sup> <a name="keep_remotely_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput"></a>

```python
keep_remotely_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `timeouts_input`<sup>Optional</sup> <a name="timeouts_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput"></a>

```python
timeouts_input: IResolvable | RegistryImageTimeouts
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `triggers_input`<sup>Optional</sup> <a name="triggers_input" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput"></a>

```python
triggers_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `insecure_skip_verify`<sup>Required</sup> <a name="insecure_skip_verify" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify"></a>

```python
insecure_skip_verify: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `keep_remotely`<sup>Required</sup> <a name="keep_remotely" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely"></a>

```python
keep_remotely: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImage.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `triggers`<sup>Required</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggers"></a>

```python
triggers: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### RegistryImageAuthConfig <a name="RegistryImageAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageAuthConfig(
  address: str,
  password: str = None,
  username: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address">address</a></code> | <code>str</code> | The address of the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password">password</a></code> | <code>str</code> | The password for the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username">username</a></code> | <code>str</code> | The username for the Docker registry. |

---

##### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address"></a>

```python
address: str
```

- *Type:* str

The address of the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#address RegistryImage#address}

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password"></a>

```python
password: str
```

- *Type:* str

The password for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `username`<sup>Optional</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username"></a>

```python
username: str
```

- *Type:* str

The username for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#username RegistryImage#username}

---

### RegistryImageBuild <a name="RegistryImageBuild" id="@cdktn/provider-docker.registryImage.RegistryImageBuild"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuild(
  context: str,
  additional_contexts: typing.List[str] = None,
  auth_config: IResolvable | typing.List[RegistryImageBuildAuthConfig] = None,
  build_args: typing.Mapping[str] = None,
  builder: str = None,
  build_id: str = None,
  build_log_file: str = None,
  cache_from: typing.List[str] = None,
  cache_to: typing.List[str] = None,
  cgroup_parent: str = None,
  cpu_period: typing.Union[int, float] = None,
  cpu_quota: typing.Union[int, float] = None,
  cpu_set_cpus: str = None,
  cpu_set_mems: str = None,
  cpu_shares: typing.Union[int, float] = None,
  dockerfile: str = None,
  extra_hosts: typing.List[str] = None,
  force_remove: bool | IResolvable = None,
  isolation: str = None,
  label: typing.Mapping[str] = None,
  labels: typing.Mapping[str] = None,
  memory: typing.Union[int, float] = None,
  memory_swap: typing.Union[int, float] = None,
  network_mode: str = None,
  no_cache: bool | IResolvable = None,
  platform: str = None,
  provenance: str = None,
  pull_parent: bool | IResolvable = None,
  remote_context: str = None,
  remove: bool | IResolvable = None,
  sbom: str = None,
  secrets: IResolvable | typing.List[RegistryImageBuildSecrets] = None,
  security_opt: typing.List[str] = None,
  session_id: str = None,
  shm_size: typing.Union[int, float] = None,
  squash: bool | IResolvable = None,
  suppress_output: bool | IResolvable = None,
  tag: typing.List[str] = None,
  target: str = None,
  ulimit: IResolvable | typing.List[RegistryImageBuildUlimit] = None,
  use_legacy_builder: bool | IResolvable = None,
  version: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context">context</a></code> | <code>str</code> | Value to specify the build context. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts">additional_contexts</a></code> | <code>typing.List[str]</code> | A list of additional build contexts. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig">auth_config</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]</code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs">build_args</a></code> | <code>typing.Mapping[str]</code> | Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder">builder</a></code> | <code>str</code> | The name of the buildx builder to use. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId">build_id</a></code> | <code>str</code> | BuildID is an optional identifier that can be passed together with the build request. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile">build_log_file</a></code> | <code>str</code> | Path to a file where the buildx log are written to. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom">cache_from</a></code> | <code>typing.List[str]</code> | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo">cache_to</a></code> | <code>typing.List[str]</code> | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent">cgroup_parent</a></code> | <code>str</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod">cpu_period</a></code> | <code>typing.Union[int, float]</code> | The length of a CPU period in microseconds. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota">cpu_quota</a></code> | <code>typing.Union[int, float]</code> | Microseconds of CPU time that the container can get in a CPU period. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus">cpu_set_cpus</a></code> | <code>str</code> | CPUs in which to allow execution (e.g., `0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems">cpu_set_mems</a></code> | <code>str</code> | MEMs in which to allow execution (`0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares">cpu_shares</a></code> | <code>typing.Union[int, float]</code> | CPU shares (relative weight). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile">dockerfile</a></code> | <code>str</code> | Name of the Dockerfile. Defaults to `Dockerfile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts">extra_hosts</a></code> | <code>typing.List[str]</code> | A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"]. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove">force_remove</a></code> | <code>bool \| cdktn.IResolvable</code> | Always remove intermediate containers. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation">isolation</a></code> | <code>str</code> | Isolation represents the isolation technology of a container. The supported values are. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label">label</a></code> | <code>typing.Mapping[str]</code> | Set metadata for an image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels">labels</a></code> | <code>typing.Mapping[str]</code> | User-defined key/value metadata. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory">memory</a></code> | <code>typing.Union[int, float]</code> | Set memory limit for build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap">memory_swap</a></code> | <code>typing.Union[int, float]</code> | Total memory (memory + swap), -1 to enable unlimited swap. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode">network_mode</a></code> | <code>str</code> | Set the networking mode for the RUN instructions during build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache">no_cache</a></code> | <code>bool \| cdktn.IResolvable</code> | Do not use the cache when building the image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform">platform</a></code> | <code>str</code> | Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance">provenance</a></code> | <code>str</code> | Set provenance attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent">pull_parent</a></code> | <code>bool \| cdktn.IResolvable</code> | Attempt to pull the image even if an older image exists locally. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext">remote_context</a></code> | <code>str</code> | A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove">remove</a></code> | <code>bool \| cdktn.IResolvable</code> | Remove intermediate containers after a successful build. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom">sbom</a></code> | <code>str</code> | Set SBOM (Software Bill of Materials) attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets">secrets</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]</code> | secrets block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt">security_opt</a></code> | <code>typing.List[str]</code> | The security options. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId">session_id</a></code> | <code>str</code> | Set an ID for the build session. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize">shm_size</a></code> | <code>typing.Union[int, float]</code> | Size of /dev/shm in bytes. The size must be greater than 0. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash">squash</a></code> | <code>bool \| cdktn.IResolvable</code> | If true the new layers are squashed into a new image with a single new layer. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput">suppress_output</a></code> | <code>bool \| cdktn.IResolvable</code> | Suppress the build output and print image ID on success. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag">tag</a></code> | <code>typing.List[str]</code> | Name and optionally a tag in the 'name:tag' format. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target">target</a></code> | <code>str</code> | Set the target build stage to build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit">ulimit</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]</code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder">use_legacy_builder</a></code> | <code>bool \| cdktn.IResolvable</code> | Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version">version</a></code> | <code>str</code> | Version of the underlying builder to use. |

---

##### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context"></a>

```python
context: str
```

- *Type:* str

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#context RegistryImage#context}

---

##### `additional_contexts`<sup>Optional</sup> <a name="additional_contexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts"></a>

```python
additional_contexts: typing.List[str]
```

- *Type:* typing.List[str]

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#additional_contexts RegistryImage#additional_contexts}

---

##### `auth_config`<sup>Optional</sup> <a name="auth_config" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig"></a>

```python
auth_config: IResolvable | typing.List[RegistryImageBuildAuthConfig]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `build_args`<sup>Optional</sup> <a name="build_args" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs"></a>

```python
build_args: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build_args RegistryImage#build_args}

---

##### `builder`<sup>Optional</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder"></a>

```python
builder: str
```

- *Type:* str

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#builder RegistryImage#builder}

---

##### `build_id`<sup>Optional</sup> <a name="build_id" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId"></a>

```python
build_id: str
```

- *Type:* str

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build_id RegistryImage#build_id}

---

##### `build_log_file`<sup>Optional</sup> <a name="build_log_file" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile"></a>

```python
build_log_file: str
```

- *Type:* str

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build_log_file RegistryImage#build_log_file}

---

##### `cache_from`<sup>Optional</sup> <a name="cache_from" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom"></a>

```python
cache_from: typing.List[str]
```

- *Type:* typing.List[str]

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cache_from RegistryImage#cache_from}

---

##### `cache_to`<sup>Optional</sup> <a name="cache_to" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo"></a>

```python
cache_to: typing.List[str]
```

- *Type:* typing.List[str]

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cache_to RegistryImage#cache_to}

---

##### `cgroup_parent`<sup>Optional</sup> <a name="cgroup_parent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent"></a>

```python
cgroup_parent: str
```

- *Type:* str

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cgroup_parent RegistryImage#cgroup_parent}

---

##### `cpu_period`<sup>Optional</sup> <a name="cpu_period" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod"></a>

```python
cpu_period: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_period RegistryImage#cpu_period}

---

##### `cpu_quota`<sup>Optional</sup> <a name="cpu_quota" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota"></a>

```python
cpu_quota: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_quota RegistryImage#cpu_quota}

---

##### `cpu_set_cpus`<sup>Optional</sup> <a name="cpu_set_cpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus"></a>

```python
cpu_set_cpus: str
```

- *Type:* str

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_set_cpus RegistryImage#cpu_set_cpus}

---

##### `cpu_set_mems`<sup>Optional</sup> <a name="cpu_set_mems" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems"></a>

```python
cpu_set_mems: str
```

- *Type:* str

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_set_mems RegistryImage#cpu_set_mems}

---

##### `cpu_shares`<sup>Optional</sup> <a name="cpu_shares" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares"></a>

```python
cpu_shares: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#cpu_shares RegistryImage#cpu_shares}

---

##### `dockerfile`<sup>Optional</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile"></a>

```python
dockerfile: str
```

- *Type:* str

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#dockerfile RegistryImage#dockerfile}

---

##### `extra_hosts`<sup>Optional</sup> <a name="extra_hosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts"></a>

```python
extra_hosts: typing.List[str]
```

- *Type:* typing.List[str]

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#extra_hosts RegistryImage#extra_hosts}

---

##### `force_remove`<sup>Optional</sup> <a name="force_remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove"></a>

```python
force_remove: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#force_remove RegistryImage#force_remove}

---

##### `isolation`<sup>Optional</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation"></a>

```python
isolation: str
```

- *Type:* str

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#isolation RegistryImage#isolation}

---

##### `label`<sup>Optional</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label"></a>

```python
label: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#label RegistryImage#label}

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels"></a>

```python
labels: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#labels RegistryImage#labels}

---

##### `memory`<sup>Optional</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory"></a>

```python
memory: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#memory RegistryImage#memory}

---

##### `memory_swap`<sup>Optional</sup> <a name="memory_swap" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap"></a>

```python
memory_swap: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#memory_swap RegistryImage#memory_swap}

---

##### `network_mode`<sup>Optional</sup> <a name="network_mode" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode"></a>

```python
network_mode: str
```

- *Type:* str

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#network_mode RegistryImage#network_mode}

---

##### `no_cache`<sup>Optional</sup> <a name="no_cache" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache"></a>

```python
no_cache: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#no_cache RegistryImage#no_cache}

---

##### `platform`<sup>Optional</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform"></a>

```python
platform: str
```

- *Type:* str

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#platform RegistryImage#platform}

---

##### `provenance`<sup>Optional</sup> <a name="provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance"></a>

```python
provenance: str
```

- *Type:* str

Set provenance attestation for the build.

BuildKit v0.11+ adds provenance attestations by default, which creates OCI image manifests that some registries (like AWS Lambda) don't support. Set to `false` to disable. Valid values: `false`, `true`, `min`, `max`, `mode=min`, `mode=max`, or a full provenance specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#provenance RegistryImage#provenance}

---

##### `pull_parent`<sup>Optional</sup> <a name="pull_parent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent"></a>

```python
pull_parent: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#pull_parent RegistryImage#pull_parent}

---

##### `remote_context`<sup>Optional</sup> <a name="remote_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext"></a>

```python
remote_context: str
```

- *Type:* str

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#remote_context RegistryImage#remote_context}

---

##### `remove`<sup>Optional</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove"></a>

```python
remove: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#remove RegistryImage#remove}

---

##### `sbom`<sup>Optional</sup> <a name="sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom"></a>

```python
sbom: str
```

- *Type:* str

Set SBOM (Software Bill of Materials) attestation for the build.

Set to `false` to disable. Valid values: `false`, `true`, or a full SBOM specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#sbom RegistryImage#sbom}

---

##### `secrets`<sup>Optional</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets"></a>

```python
secrets: IResolvable | typing.List[RegistryImageBuildSecrets]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#secrets RegistryImage#secrets}

---

##### `security_opt`<sup>Optional</sup> <a name="security_opt" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt"></a>

```python
security_opt: typing.List[str]
```

- *Type:* typing.List[str]

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#security_opt RegistryImage#security_opt}

---

##### `session_id`<sup>Optional</sup> <a name="session_id" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId"></a>

```python
session_id: str
```

- *Type:* str

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#session_id RegistryImage#session_id}

---

##### `shm_size`<sup>Optional</sup> <a name="shm_size" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize"></a>

```python
shm_size: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#shm_size RegistryImage#shm_size}

---

##### `squash`<sup>Optional</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash"></a>

```python
squash: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#squash RegistryImage#squash}

---

##### `suppress_output`<sup>Optional</sup> <a name="suppress_output" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput"></a>

```python
suppress_output: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#suppress_output RegistryImage#suppress_output}

---

##### `tag`<sup>Optional</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag"></a>

```python
tag: typing.List[str]
```

- *Type:* typing.List[str]

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#tag RegistryImage#tag}

---

##### `target`<sup>Optional</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target"></a>

```python
target: str
```

- *Type:* str

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#target RegistryImage#target}

---

##### `ulimit`<sup>Optional</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit"></a>

```python
ulimit: IResolvable | typing.List[RegistryImageBuildUlimit]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#ulimit RegistryImage#ulimit}

---

##### `use_legacy_builder`<sup>Optional</sup> <a name="use_legacy_builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder"></a>

```python
use_legacy_builder: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#use_legacy_builder RegistryImage#use_legacy_builder}

---

##### `version`<sup>Optional</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version"></a>

```python
version: str
```

- *Type:* str

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#version RegistryImage#version}

---

### RegistryImageBuildAuthConfig <a name="RegistryImageBuildAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildAuthConfig(
  host_name: str,
  auth: str = None,
  email: str = None,
  identity_token: str = None,
  password: str = None,
  registry_token: str = None,
  server_address: str = None,
  user_name: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName">host_name</a></code> | <code>str</code> | hostname of the registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth">auth</a></code> | <code>str</code> | the auth token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email">email</a></code> | <code>str</code> | the user emal. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken">identity_token</a></code> | <code>str</code> | the identity token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password">password</a></code> | <code>str</code> | the registry password. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken">registry_token</a></code> | <code>str</code> | the registry token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress">server_address</a></code> | <code>str</code> | the server address. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName">user_name</a></code> | <code>str</code> | the registry user name. |

---

##### `host_name`<sup>Required</sup> <a name="host_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName"></a>

```python
host_name: str
```

- *Type:* str

hostname of the registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#host_name RegistryImage#host_name}

---

##### `auth`<sup>Optional</sup> <a name="auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth"></a>

```python
auth: str
```

- *Type:* str

the auth token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#auth RegistryImage#auth}

---

##### `email`<sup>Optional</sup> <a name="email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email"></a>

```python
email: str
```

- *Type:* str

the user emal.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#email RegistryImage#email}

---

##### `identity_token`<sup>Optional</sup> <a name="identity_token" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken"></a>

```python
identity_token: str
```

- *Type:* str

the identity token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#identity_token RegistryImage#identity_token}

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password"></a>

```python
password: str
```

- *Type:* str

the registry password.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `registry_token`<sup>Optional</sup> <a name="registry_token" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken"></a>

```python
registry_token: str
```

- *Type:* str

the registry token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#registry_token RegistryImage#registry_token}

---

##### `server_address`<sup>Optional</sup> <a name="server_address" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress"></a>

```python
server_address: str
```

- *Type:* str

the server address.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#server_address RegistryImage#server_address}

---

##### `user_name`<sup>Optional</sup> <a name="user_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName"></a>

```python
user_name: str
```

- *Type:* str

the registry user name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#user_name RegistryImage#user_name}

---

### RegistryImageBuildSecrets <a name="RegistryImageBuildSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildSecrets(
  id: str,
  env: str = None,
  src: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id">id</a></code> | <code>str</code> | ID of the secret. By default, secrets are mounted to /run/secrets/<id>. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env">env</a></code> | <code>str</code> | Environment variable source of the secret. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src">src</a></code> | <code>str</code> | File source of the secret. Takes precedence over `env`. |

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id"></a>

```python
id: str
```

- *Type:* str

ID of the secret. By default, secrets are mounted to /run/secrets/<id>.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#id RegistryImage#id}

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `env`<sup>Optional</sup> <a name="env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env"></a>

```python
env: str
```

- *Type:* str

Environment variable source of the secret.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#env RegistryImage#env}

---

##### `src`<sup>Optional</sup> <a name="src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src"></a>

```python
src: str
```

- *Type:* str

File source of the secret. Takes precedence over `env`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#src RegistryImage#src}

---

### RegistryImageBuildUlimit <a name="RegistryImageBuildUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildUlimit(
  hard: typing.Union[int, float],
  name: str,
  soft: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard">hard</a></code> | <code>typing.Union[int, float]</code> | soft limit. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name">name</a></code> | <code>str</code> | type of ulimit, e.g. `nofile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft">soft</a></code> | <code>typing.Union[int, float]</code> | hard limit. |

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard"></a>

```python
hard: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#hard RegistryImage#hard}

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name"></a>

```python
name: str
```

- *Type:* str

type of ulimit, e.g. `nofile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft"></a>

```python
soft: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#soft RegistryImage#soft}

---

### RegistryImageConfig <a name="RegistryImageConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageConfig(
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  name: str,
  auth_config: RegistryImageAuthConfig = None,
  build_attribute: RegistryImageBuild = None,
  id: str = None,
  insecure_skip_verify: bool | IResolvable = None,
  keep_remotely: bool | IResolvable = None,
  timeouts: RegistryImageTimeouts = None,
  triggers: typing.Mapping[str] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name">name</a></code> | <code>str</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig">auth_config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute">build_attribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify">insecure_skip_verify</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely">keep_remotely</a></code> | <code>bool \| cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers">triggers</a></code> | <code>typing.Mapping[str]</code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name"></a>

```python
name: str
```

- *Type:* str

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `auth_config`<sup>Optional</sup> <a name="auth_config" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig"></a>

```python
auth_config: RegistryImageAuthConfig
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `build_attribute`<sup>Optional</sup> <a name="build_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute"></a>

```python
build_attribute: RegistryImageBuild
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `insecure_skip_verify`<sup>Optional</sup> <a name="insecure_skip_verify" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify"></a>

```python
insecure_skip_verify: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `keep_remotely`<sup>Optional</sup> <a name="keep_remotely" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely"></a>

```python
keep_remotely: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts"></a>

```python
timeouts: RegistryImageTimeouts
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `triggers`<sup>Optional</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers"></a>

```python
triggers: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

### RegistryImageTimeouts <a name="RegistryImageTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageTimeouts(
  create: str = None,
  delete: str = None,
  update: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create">create</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#create RegistryImage#create}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete">delete</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#delete RegistryImage#delete}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update">update</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#update RegistryImage#update}. |

---

##### `create`<sup>Optional</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create"></a>

```python
create: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#create RegistryImage#create}.

---

##### `delete`<sup>Optional</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete"></a>

```python
delete: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#delete RegistryImage#delete}.

---

##### `update`<sup>Optional</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update"></a>

```python
update: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/registry_image#update RegistryImage#update}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistryImageAuthConfigOutputReference <a name="RegistryImageAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageAuthConfigOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword">reset_password</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername">reset_username</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_password` <a name="reset_password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword"></a>

```python
def reset_password() -> None
```

##### `reset_username` <a name="reset_username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername"></a>

```python
def reset_username() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput">address_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput">password_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput">username_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address">address</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password">password</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username">username</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `address_input`<sup>Optional</sup> <a name="address_input" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput"></a>

```python
address_input: str
```

- *Type:* str

---

##### `password_input`<sup>Optional</sup> <a name="password_input" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput"></a>

```python
password_input: str
```

- *Type:* str

---

##### `username_input`<sup>Optional</sup> <a name="username_input" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput"></a>

```python
username_input: str
```

- *Type:* str

---

##### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address"></a>

```python
address: str
```

- *Type:* str

---

##### `password`<sup>Required</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password"></a>

```python
password: str
```

- *Type:* str

---

##### `username`<sup>Required</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username"></a>

```python
username: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue"></a>

```python
internal_value: RegistryImageAuthConfig
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---


### RegistryImageBuildAuthConfigList <a name="RegistryImageBuildAuthConfigList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildAuthConfigList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey">all_with_map_key</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get">get</a></code> | *No description.* |

---

##### `all_with_map_key` <a name="all_with_map_key" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey"></a>

```python
def all_with_map_key(
  map_key_attribute_name: str
) -> DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `map_key_attribute_name`<sup>Required</sup> <a name="map_key_attribute_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* str

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> RegistryImageBuildAuthConfigOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue"></a>

```python
internal_value: IResolvable | typing.List[RegistryImageBuildAuthConfig]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]

---


### RegistryImageBuildAuthConfigOutputReference <a name="RegistryImageBuildAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildAuthConfigOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth">reset_auth</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail">reset_email</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken">reset_identity_token</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword">reset_password</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken">reset_registry_token</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress">reset_server_address</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName">reset_user_name</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_auth` <a name="reset_auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth"></a>

```python
def reset_auth() -> None
```

##### `reset_email` <a name="reset_email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail"></a>

```python
def reset_email() -> None
```

##### `reset_identity_token` <a name="reset_identity_token" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken"></a>

```python
def reset_identity_token() -> None
```

##### `reset_password` <a name="reset_password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword"></a>

```python
def reset_password() -> None
```

##### `reset_registry_token` <a name="reset_registry_token" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken"></a>

```python
def reset_registry_token() -> None
```

##### `reset_server_address` <a name="reset_server_address" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress"></a>

```python
def reset_server_address() -> None
```

##### `reset_user_name` <a name="reset_user_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName"></a>

```python
def reset_user_name() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput">auth_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput">email_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput">host_name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput">identity_token_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput">password_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput">registry_token_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput">server_address_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput">user_name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth">auth</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email">email</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName">host_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken">identity_token</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password">password</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken">registry_token</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress">server_address</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName">user_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `auth_input`<sup>Optional</sup> <a name="auth_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput"></a>

```python
auth_input: str
```

- *Type:* str

---

##### `email_input`<sup>Optional</sup> <a name="email_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput"></a>

```python
email_input: str
```

- *Type:* str

---

##### `host_name_input`<sup>Optional</sup> <a name="host_name_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput"></a>

```python
host_name_input: str
```

- *Type:* str

---

##### `identity_token_input`<sup>Optional</sup> <a name="identity_token_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput"></a>

```python
identity_token_input: str
```

- *Type:* str

---

##### `password_input`<sup>Optional</sup> <a name="password_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput"></a>

```python
password_input: str
```

- *Type:* str

---

##### `registry_token_input`<sup>Optional</sup> <a name="registry_token_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput"></a>

```python
registry_token_input: str
```

- *Type:* str

---

##### `server_address_input`<sup>Optional</sup> <a name="server_address_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput"></a>

```python
server_address_input: str
```

- *Type:* str

---

##### `user_name_input`<sup>Optional</sup> <a name="user_name_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput"></a>

```python
user_name_input: str
```

- *Type:* str

---

##### `auth`<sup>Required</sup> <a name="auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth"></a>

```python
auth: str
```

- *Type:* str

---

##### `email`<sup>Required</sup> <a name="email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email"></a>

```python
email: str
```

- *Type:* str

---

##### `host_name`<sup>Required</sup> <a name="host_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName"></a>

```python
host_name: str
```

- *Type:* str

---

##### `identity_token`<sup>Required</sup> <a name="identity_token" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken"></a>

```python
identity_token: str
```

- *Type:* str

---

##### `password`<sup>Required</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password"></a>

```python
password: str
```

- *Type:* str

---

##### `registry_token`<sup>Required</sup> <a name="registry_token" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken"></a>

```python
registry_token: str
```

- *Type:* str

---

##### `server_address`<sup>Required</sup> <a name="server_address" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress"></a>

```python
server_address: str
```

- *Type:* str

---

##### `user_name`<sup>Required</sup> <a name="user_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName"></a>

```python
user_name: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue"></a>

```python
internal_value: IResolvable | RegistryImageBuildAuthConfig
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>

---


### RegistryImageBuildOutputReference <a name="RegistryImageBuildOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig">put_auth_config</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets">put_secrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit">put_ulimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts">reset_additional_contexts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig">reset_auth_config</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs">reset_build_args</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder">reset_builder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId">reset_build_id</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile">reset_build_log_file</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom">reset_cache_from</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo">reset_cache_to</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent">reset_cgroup_parent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod">reset_cpu_period</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota">reset_cpu_quota</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus">reset_cpu_set_cpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems">reset_cpu_set_mems</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares">reset_cpu_shares</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile">reset_dockerfile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts">reset_extra_hosts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove">reset_force_remove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation">reset_isolation</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel">reset_label</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels">reset_labels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory">reset_memory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap">reset_memory_swap</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode">reset_network_mode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache">reset_no_cache</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform">reset_platform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance">reset_provenance</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent">reset_pull_parent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext">reset_remote_context</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove">reset_remove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom">reset_sbom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets">reset_secrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt">reset_security_opt</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId">reset_session_id</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize">reset_shm_size</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash">reset_squash</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput">reset_suppress_output</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag">reset_tag</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget">reset_target</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit">reset_ulimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder">reset_use_legacy_builder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion">reset_version</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_auth_config` <a name="put_auth_config" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig"></a>

```python
def put_auth_config(
  value: IResolvable | typing.List[RegistryImageBuildAuthConfig]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig.parameter.value"></a>

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]

---

##### `put_secrets` <a name="put_secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets"></a>

```python
def put_secrets(
  value: IResolvable | typing.List[RegistryImageBuildSecrets]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets.parameter.value"></a>

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]

---

##### `put_ulimit` <a name="put_ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit"></a>

```python
def put_ulimit(
  value: IResolvable | typing.List[RegistryImageBuildUlimit]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit.parameter.value"></a>

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]

---

##### `reset_additional_contexts` <a name="reset_additional_contexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts"></a>

```python
def reset_additional_contexts() -> None
```

##### `reset_auth_config` <a name="reset_auth_config" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig"></a>

```python
def reset_auth_config() -> None
```

##### `reset_build_args` <a name="reset_build_args" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs"></a>

```python
def reset_build_args() -> None
```

##### `reset_builder` <a name="reset_builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder"></a>

```python
def reset_builder() -> None
```

##### `reset_build_id` <a name="reset_build_id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId"></a>

```python
def reset_build_id() -> None
```

##### `reset_build_log_file` <a name="reset_build_log_file" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile"></a>

```python
def reset_build_log_file() -> None
```

##### `reset_cache_from` <a name="reset_cache_from" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom"></a>

```python
def reset_cache_from() -> None
```

##### `reset_cache_to` <a name="reset_cache_to" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo"></a>

```python
def reset_cache_to() -> None
```

##### `reset_cgroup_parent` <a name="reset_cgroup_parent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent"></a>

```python
def reset_cgroup_parent() -> None
```

##### `reset_cpu_period` <a name="reset_cpu_period" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod"></a>

```python
def reset_cpu_period() -> None
```

##### `reset_cpu_quota` <a name="reset_cpu_quota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota"></a>

```python
def reset_cpu_quota() -> None
```

##### `reset_cpu_set_cpus` <a name="reset_cpu_set_cpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus"></a>

```python
def reset_cpu_set_cpus() -> None
```

##### `reset_cpu_set_mems` <a name="reset_cpu_set_mems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems"></a>

```python
def reset_cpu_set_mems() -> None
```

##### `reset_cpu_shares` <a name="reset_cpu_shares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares"></a>

```python
def reset_cpu_shares() -> None
```

##### `reset_dockerfile` <a name="reset_dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile"></a>

```python
def reset_dockerfile() -> None
```

##### `reset_extra_hosts` <a name="reset_extra_hosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts"></a>

```python
def reset_extra_hosts() -> None
```

##### `reset_force_remove` <a name="reset_force_remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove"></a>

```python
def reset_force_remove() -> None
```

##### `reset_isolation` <a name="reset_isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation"></a>

```python
def reset_isolation() -> None
```

##### `reset_label` <a name="reset_label" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel"></a>

```python
def reset_label() -> None
```

##### `reset_labels` <a name="reset_labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels"></a>

```python
def reset_labels() -> None
```

##### `reset_memory` <a name="reset_memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory"></a>

```python
def reset_memory() -> None
```

##### `reset_memory_swap` <a name="reset_memory_swap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap"></a>

```python
def reset_memory_swap() -> None
```

##### `reset_network_mode` <a name="reset_network_mode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode"></a>

```python
def reset_network_mode() -> None
```

##### `reset_no_cache` <a name="reset_no_cache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache"></a>

```python
def reset_no_cache() -> None
```

##### `reset_platform` <a name="reset_platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform"></a>

```python
def reset_platform() -> None
```

##### `reset_provenance` <a name="reset_provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance"></a>

```python
def reset_provenance() -> None
```

##### `reset_pull_parent` <a name="reset_pull_parent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent"></a>

```python
def reset_pull_parent() -> None
```

##### `reset_remote_context` <a name="reset_remote_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext"></a>

```python
def reset_remote_context() -> None
```

##### `reset_remove` <a name="reset_remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove"></a>

```python
def reset_remove() -> None
```

##### `reset_sbom` <a name="reset_sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom"></a>

```python
def reset_sbom() -> None
```

##### `reset_secrets` <a name="reset_secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets"></a>

```python
def reset_secrets() -> None
```

##### `reset_security_opt` <a name="reset_security_opt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt"></a>

```python
def reset_security_opt() -> None
```

##### `reset_session_id` <a name="reset_session_id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId"></a>

```python
def reset_session_id() -> None
```

##### `reset_shm_size` <a name="reset_shm_size" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize"></a>

```python
def reset_shm_size() -> None
```

##### `reset_squash` <a name="reset_squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash"></a>

```python
def reset_squash() -> None
```

##### `reset_suppress_output` <a name="reset_suppress_output" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput"></a>

```python
def reset_suppress_output() -> None
```

##### `reset_tag` <a name="reset_tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag"></a>

```python
def reset_tag() -> None
```

##### `reset_target` <a name="reset_target" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget"></a>

```python
def reset_target() -> None
```

##### `reset_ulimit` <a name="reset_ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit"></a>

```python
def reset_ulimit() -> None
```

##### `reset_use_legacy_builder` <a name="reset_use_legacy_builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder"></a>

```python
def reset_use_legacy_builder() -> None
```

##### `reset_version` <a name="reset_version" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion"></a>

```python
def reset_version() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig">auth_config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets">secrets</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit">ulimit</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput">additional_contexts_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput">auth_config_input</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput">build_args_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput">builder_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput">build_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput">build_log_file_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput">cache_from_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput">cache_to_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput">cgroup_parent_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput">context_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput">cpu_period_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput">cpu_quota_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput">cpu_set_cpus_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput">cpu_set_mems_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput">cpu_shares_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput">dockerfile_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput">extra_hosts_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput">force_remove_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput">isolation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput">label_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput">labels_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput">memory_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput">memory_swap_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput">network_mode_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput">no_cache_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput">platform_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput">provenance_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput">pull_parent_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput">remote_context_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput">remove_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput">sbom_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput">secrets_input</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput">security_opt_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput">session_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput">shm_size_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput">squash_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput">suppress_output_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput">tag_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput">target_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput">ulimit_input</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput">use_legacy_builder_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput">version_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts">additional_contexts</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs">build_args</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder">builder</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId">build_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile">build_log_file</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom">cache_from</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo">cache_to</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent">cgroup_parent</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context">context</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod">cpu_period</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota">cpu_quota</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus">cpu_set_cpus</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems">cpu_set_mems</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares">cpu_shares</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile">dockerfile</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts">extra_hosts</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove">force_remove</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation">isolation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label">label</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels">labels</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory">memory</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap">memory_swap</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode">network_mode</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache">no_cache</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform">platform</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance">provenance</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent">pull_parent</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext">remote_context</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove">remove</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom">sbom</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt">security_opt</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId">session_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize">shm_size</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash">squash</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput">suppress_output</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag">tag</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target">target</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder">use_legacy_builder</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version">version</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue">internal_value</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `auth_config`<sup>Required</sup> <a name="auth_config" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig"></a>

```python
auth_config: RegistryImageBuildAuthConfigList
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a>

---

##### `secrets`<sup>Required</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets"></a>

```python
secrets: RegistryImageBuildSecretsList
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a>

---

##### `ulimit`<sup>Required</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit"></a>

```python
ulimit: RegistryImageBuildUlimitList
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a>

---

##### `additional_contexts_input`<sup>Optional</sup> <a name="additional_contexts_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput"></a>

```python
additional_contexts_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `auth_config_input`<sup>Optional</sup> <a name="auth_config_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput"></a>

```python
auth_config_input: IResolvable | typing.List[RegistryImageBuildAuthConfig]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>]

---

##### `build_args_input`<sup>Optional</sup> <a name="build_args_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput"></a>

```python
build_args_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `builder_input`<sup>Optional</sup> <a name="builder_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput"></a>

```python
builder_input: str
```

- *Type:* str

---

##### `build_id_input`<sup>Optional</sup> <a name="build_id_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput"></a>

```python
build_id_input: str
```

- *Type:* str

---

##### `build_log_file_input`<sup>Optional</sup> <a name="build_log_file_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput"></a>

```python
build_log_file_input: str
```

- *Type:* str

---

##### `cache_from_input`<sup>Optional</sup> <a name="cache_from_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput"></a>

```python
cache_from_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `cache_to_input`<sup>Optional</sup> <a name="cache_to_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput"></a>

```python
cache_to_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `cgroup_parent_input`<sup>Optional</sup> <a name="cgroup_parent_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput"></a>

```python
cgroup_parent_input: str
```

- *Type:* str

---

##### `context_input`<sup>Optional</sup> <a name="context_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput"></a>

```python
context_input: str
```

- *Type:* str

---

##### `cpu_period_input`<sup>Optional</sup> <a name="cpu_period_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput"></a>

```python
cpu_period_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `cpu_quota_input`<sup>Optional</sup> <a name="cpu_quota_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput"></a>

```python
cpu_quota_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `cpu_set_cpus_input`<sup>Optional</sup> <a name="cpu_set_cpus_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput"></a>

```python
cpu_set_cpus_input: str
```

- *Type:* str

---

##### `cpu_set_mems_input`<sup>Optional</sup> <a name="cpu_set_mems_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput"></a>

```python
cpu_set_mems_input: str
```

- *Type:* str

---

##### `cpu_shares_input`<sup>Optional</sup> <a name="cpu_shares_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput"></a>

```python
cpu_shares_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `dockerfile_input`<sup>Optional</sup> <a name="dockerfile_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput"></a>

```python
dockerfile_input: str
```

- *Type:* str

---

##### `extra_hosts_input`<sup>Optional</sup> <a name="extra_hosts_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput"></a>

```python
extra_hosts_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `force_remove_input`<sup>Optional</sup> <a name="force_remove_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput"></a>

```python
force_remove_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `isolation_input`<sup>Optional</sup> <a name="isolation_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput"></a>

```python
isolation_input: str
```

- *Type:* str

---

##### `label_input`<sup>Optional</sup> <a name="label_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput"></a>

```python
label_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `labels_input`<sup>Optional</sup> <a name="labels_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput"></a>

```python
labels_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `memory_input`<sup>Optional</sup> <a name="memory_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput"></a>

```python
memory_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `memory_swap_input`<sup>Optional</sup> <a name="memory_swap_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput"></a>

```python
memory_swap_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `network_mode_input`<sup>Optional</sup> <a name="network_mode_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput"></a>

```python
network_mode_input: str
```

- *Type:* str

---

##### `no_cache_input`<sup>Optional</sup> <a name="no_cache_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput"></a>

```python
no_cache_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `platform_input`<sup>Optional</sup> <a name="platform_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput"></a>

```python
platform_input: str
```

- *Type:* str

---

##### `provenance_input`<sup>Optional</sup> <a name="provenance_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput"></a>

```python
provenance_input: str
```

- *Type:* str

---

##### `pull_parent_input`<sup>Optional</sup> <a name="pull_parent_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput"></a>

```python
pull_parent_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `remote_context_input`<sup>Optional</sup> <a name="remote_context_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput"></a>

```python
remote_context_input: str
```

- *Type:* str

---

##### `remove_input`<sup>Optional</sup> <a name="remove_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput"></a>

```python
remove_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `sbom_input`<sup>Optional</sup> <a name="sbom_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput"></a>

```python
sbom_input: str
```

- *Type:* str

---

##### `secrets_input`<sup>Optional</sup> <a name="secrets_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput"></a>

```python
secrets_input: IResolvable | typing.List[RegistryImageBuildSecrets]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]

---

##### `security_opt_input`<sup>Optional</sup> <a name="security_opt_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput"></a>

```python
security_opt_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `session_id_input`<sup>Optional</sup> <a name="session_id_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput"></a>

```python
session_id_input: str
```

- *Type:* str

---

##### `shm_size_input`<sup>Optional</sup> <a name="shm_size_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput"></a>

```python
shm_size_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `squash_input`<sup>Optional</sup> <a name="squash_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput"></a>

```python
squash_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `suppress_output_input`<sup>Optional</sup> <a name="suppress_output_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput"></a>

```python
suppress_output_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `tag_input`<sup>Optional</sup> <a name="tag_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput"></a>

```python
tag_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `target_input`<sup>Optional</sup> <a name="target_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput"></a>

```python
target_input: str
```

- *Type:* str

---

##### `ulimit_input`<sup>Optional</sup> <a name="ulimit_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput"></a>

```python
ulimit_input: IResolvable | typing.List[RegistryImageBuildUlimit]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]

---

##### `use_legacy_builder_input`<sup>Optional</sup> <a name="use_legacy_builder_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput"></a>

```python
use_legacy_builder_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `version_input`<sup>Optional</sup> <a name="version_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput"></a>

```python
version_input: str
```

- *Type:* str

---

##### `additional_contexts`<sup>Required</sup> <a name="additional_contexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts"></a>

```python
additional_contexts: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `build_args`<sup>Required</sup> <a name="build_args" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs"></a>

```python
build_args: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `builder`<sup>Required</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder"></a>

```python
builder: str
```

- *Type:* str

---

##### `build_id`<sup>Required</sup> <a name="build_id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId"></a>

```python
build_id: str
```

- *Type:* str

---

##### `build_log_file`<sup>Required</sup> <a name="build_log_file" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile"></a>

```python
build_log_file: str
```

- *Type:* str

---

##### `cache_from`<sup>Required</sup> <a name="cache_from" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom"></a>

```python
cache_from: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `cache_to`<sup>Required</sup> <a name="cache_to" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo"></a>

```python
cache_to: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `cgroup_parent`<sup>Required</sup> <a name="cgroup_parent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent"></a>

```python
cgroup_parent: str
```

- *Type:* str

---

##### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context"></a>

```python
context: str
```

- *Type:* str

---

##### `cpu_period`<sup>Required</sup> <a name="cpu_period" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod"></a>

```python
cpu_period: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `cpu_quota`<sup>Required</sup> <a name="cpu_quota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota"></a>

```python
cpu_quota: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `cpu_set_cpus`<sup>Required</sup> <a name="cpu_set_cpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus"></a>

```python
cpu_set_cpus: str
```

- *Type:* str

---

##### `cpu_set_mems`<sup>Required</sup> <a name="cpu_set_mems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems"></a>

```python
cpu_set_mems: str
```

- *Type:* str

---

##### `cpu_shares`<sup>Required</sup> <a name="cpu_shares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares"></a>

```python
cpu_shares: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `dockerfile`<sup>Required</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile"></a>

```python
dockerfile: str
```

- *Type:* str

---

##### `extra_hosts`<sup>Required</sup> <a name="extra_hosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts"></a>

```python
extra_hosts: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `force_remove`<sup>Required</sup> <a name="force_remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove"></a>

```python
force_remove: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `isolation`<sup>Required</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation"></a>

```python
isolation: str
```

- *Type:* str

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label"></a>

```python
label: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels"></a>

```python
labels: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `memory`<sup>Required</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory"></a>

```python
memory: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `memory_swap`<sup>Required</sup> <a name="memory_swap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap"></a>

```python
memory_swap: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `network_mode`<sup>Required</sup> <a name="network_mode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode"></a>

```python
network_mode: str
```

- *Type:* str

---

##### `no_cache`<sup>Required</sup> <a name="no_cache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache"></a>

```python
no_cache: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `platform`<sup>Required</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform"></a>

```python
platform: str
```

- *Type:* str

---

##### `provenance`<sup>Required</sup> <a name="provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance"></a>

```python
provenance: str
```

- *Type:* str

---

##### `pull_parent`<sup>Required</sup> <a name="pull_parent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent"></a>

```python
pull_parent: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `remote_context`<sup>Required</sup> <a name="remote_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext"></a>

```python
remote_context: str
```

- *Type:* str

---

##### `remove`<sup>Required</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove"></a>

```python
remove: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `sbom`<sup>Required</sup> <a name="sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom"></a>

```python
sbom: str
```

- *Type:* str

---

##### `security_opt`<sup>Required</sup> <a name="security_opt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt"></a>

```python
security_opt: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `session_id`<sup>Required</sup> <a name="session_id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId"></a>

```python
session_id: str
```

- *Type:* str

---

##### `shm_size`<sup>Required</sup> <a name="shm_size" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize"></a>

```python
shm_size: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `squash`<sup>Required</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash"></a>

```python
squash: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `suppress_output`<sup>Required</sup> <a name="suppress_output" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput"></a>

```python
suppress_output: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `tag`<sup>Required</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag"></a>

```python
tag: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `target`<sup>Required</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target"></a>

```python
target: str
```

- *Type:* str

---

##### `use_legacy_builder`<sup>Required</sup> <a name="use_legacy_builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder"></a>

```python
use_legacy_builder: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `version`<sup>Required</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version"></a>

```python
version: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue"></a>

```python
internal_value: RegistryImageBuild
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---


### RegistryImageBuildSecretsList <a name="RegistryImageBuildSecretsList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildSecretsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey">all_with_map_key</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get">get</a></code> | *No description.* |

---

##### `all_with_map_key` <a name="all_with_map_key" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey"></a>

```python
def all_with_map_key(
  map_key_attribute_name: str
) -> DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `map_key_attribute_name`<sup>Required</sup> <a name="map_key_attribute_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* str

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> RegistryImageBuildSecretsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue"></a>

```python
internal_value: IResolvable | typing.List[RegistryImageBuildSecrets]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>]

---


### RegistryImageBuildSecretsOutputReference <a name="RegistryImageBuildSecretsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildSecretsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv">reset_env</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc">reset_src</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_env` <a name="reset_env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv"></a>

```python
def reset_env() -> None
```

##### `reset_src` <a name="reset_src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc"></a>

```python
def reset_src() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput">env_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput">src_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env">env</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src">src</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `env_input`<sup>Optional</sup> <a name="env_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput"></a>

```python
env_input: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `src_input`<sup>Optional</sup> <a name="src_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput"></a>

```python
src_input: str
```

- *Type:* str

---

##### `env`<sup>Required</sup> <a name="env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env"></a>

```python
env: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `src`<sup>Required</sup> <a name="src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src"></a>

```python
src: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue"></a>

```python
internal_value: IResolvable | RegistryImageBuildSecrets
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>

---


### RegistryImageBuildUlimitList <a name="RegistryImageBuildUlimitList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildUlimitList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey">all_with_map_key</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get">get</a></code> | *No description.* |

---

##### `all_with_map_key` <a name="all_with_map_key" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey"></a>

```python
def all_with_map_key(
  map_key_attribute_name: str
) -> DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `map_key_attribute_name`<sup>Required</sup> <a name="map_key_attribute_name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* str

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> RegistryImageBuildUlimitOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue"></a>

```python
internal_value: IResolvable | typing.List[RegistryImageBuildUlimit]
```

- *Type:* cdktn.IResolvable | typing.List[<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>]

---


### RegistryImageBuildUlimitOutputReference <a name="RegistryImageBuildUlimitOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageBuildUlimitOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput">hard_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput">soft_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard">hard</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft">soft</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `hard_input`<sup>Optional</sup> <a name="hard_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput"></a>

```python
hard_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `soft_input`<sup>Optional</sup> <a name="soft_input" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput"></a>

```python
soft_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard"></a>

```python
hard: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft"></a>

```python
soft: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue"></a>

```python
internal_value: IResolvable | RegistryImageBuildUlimit
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>

---


### RegistryImageTimeoutsOutputReference <a name="RegistryImageTimeoutsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer"></a>

```python
from cdktn_provider_docker import registry_image

registryImage.RegistryImageTimeoutsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate">reset_create</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete">reset_delete</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate">reset_update</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_create` <a name="reset_create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate"></a>

```python
def reset_create() -> None
```

##### `reset_delete` <a name="reset_delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete"></a>

```python
def reset_delete() -> None
```

##### `reset_update` <a name="reset_update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate"></a>

```python
def reset_update() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput">create_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput">delete_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput">update_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create">create</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete">delete</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update">update</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue">internal_value</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `create_input`<sup>Optional</sup> <a name="create_input" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput"></a>

```python
create_input: str
```

- *Type:* str

---

##### `delete_input`<sup>Optional</sup> <a name="delete_input" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput"></a>

```python
delete_input: str
```

- *Type:* str

---

##### `update_input`<sup>Optional</sup> <a name="update_input" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput"></a>

```python
update_input: str
```

- *Type:* str

---

##### `create`<sup>Required</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create"></a>

```python
create: str
```

- *Type:* str

---

##### `delete`<sup>Required</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete"></a>

```python
delete: str
```

- *Type:* str

---

##### `update`<sup>Required</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update"></a>

```python
update: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue"></a>

```python
internal_value: IResolvable | RegistryImageTimeouts
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---



