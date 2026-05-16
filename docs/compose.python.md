# `compose` Submodule <a name="`compose` Submodule" id="@cdktn/provider-docker.compose"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Compose <a name="Compose" id="@cdktn/provider-docker.compose.Compose"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose docker_compose}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.compose.Compose.Initializer"></a>

```python
from cdktn_provider_docker import compose

compose.Compose(
  scope: Construct,
  id: str,
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  config_paths: typing.List[str],
  env_files: typing.List[str] = None,
  profiles: typing.List[str] = None,
  project_directory: str = None,
  project_name: str = None,
  remove_orphans: bool | IResolvable = None,
  wait: bool | IResolvable = None,
  wait_timeout: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.configPaths">config_paths</a></code> | <code>typing.List[str]</code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.envFiles">env_files</a></code> | <code>typing.List[str]</code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.profiles">profiles</a></code> | <code>typing.List[str]</code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectDirectory">project_directory</a></code> | <code>str</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectName">project_name</a></code> | <code>str</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.removeOrphans">remove_orphans</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.wait">wait</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.waitTimeout">wait_timeout</a></code> | <code>str</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.connection"></a>

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.count"></a>

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.forEach"></a>

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.lifecycle"></a>

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `config_paths`<sup>Required</sup> <a name="config_paths" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.configPaths"></a>

- *Type:* typing.List[str]

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `env_files`<sup>Optional</sup> <a name="env_files" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.envFiles"></a>

- *Type:* typing.List[str]

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#env_files Compose#env_files}

---

##### `profiles`<sup>Optional</sup> <a name="profiles" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.profiles"></a>

- *Type:* typing.List[str]

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#profiles Compose#profiles}

---

##### `project_directory`<sup>Optional</sup> <a name="project_directory" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectDirectory"></a>

- *Type:* str

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `project_name`<sup>Optional</sup> <a name="project_name" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectName"></a>

- *Type:* str

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#project_name Compose#project_name}

---

##### `remove_orphans`<sup>Optional</sup> <a name="remove_orphans" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.removeOrphans"></a>

- *Type:* bool | cdktn.IResolvable

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.wait"></a>

- *Type:* bool | cdktn.IResolvable

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#wait Compose#wait}

---

##### `wait_timeout`<sup>Optional</sup> <a name="wait_timeout" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.waitTimeout"></a>

- *Type:* str

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toHclTerraform">to_hcl_terraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.addMoveTarget">add_move_target</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.hasResourceMove">has_resource_move</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.importFrom">import_from</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveFromId">move_from_id</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveTo">move_to</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveToId">move_to_id</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetEnvFiles">reset_env_files</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProfiles">reset_profiles</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProjectDirectory">reset_project_directory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProjectName">reset_project_name</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetRemoveOrphans">reset_remove_orphans</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetWait">reset_wait</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetWaitTimeout">reset_wait_timeout</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="@cdktn/provider-docker.compose.Compose.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.compose.Compose.with"></a>

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

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.compose.Compose.with.parameter.mixins"></a>

- *Type:* *constructs.IMixin

The mixins to apply.

---

##### `add_override` <a name="add_override" id="@cdktn/provider-docker.compose.Compose.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_hcl_terraform` <a name="to_hcl_terraform" id="@cdktn/provider-docker.compose.Compose.toHclTerraform"></a>

```python
def to_hcl_terraform() -> typing.Any
```

##### `to_metadata` <a name="to_metadata" id="@cdktn/provider-docker.compose.Compose.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="@cdktn/provider-docker.compose.Compose.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `add_move_target` <a name="add_move_target" id="@cdktn/provider-docker.compose.Compose.addMoveTarget"></a>

```python
def add_move_target(
  move_target: str
) -> None
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktn/provider-docker.compose.Compose.addMoveTarget.parameter.moveTarget"></a>

- *Type:* str

The string move target that will correspond to this resource.

---

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `has_resource_move` <a name="has_resource_move" id="@cdktn/provider-docker.compose.Compose.hasResourceMove"></a>

```python
def has_resource_move() -> TerraformResourceMoveByTarget | TerraformResourceMoveById
```

##### `import_from` <a name="import_from" id="@cdktn/provider-docker.compose.Compose.importFrom"></a>

```python
def import_from(
  id: str,
  provider: TerraformProvider = None
) -> None
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.id"></a>

- *Type:* str

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `move_from_id` <a name="move_from_id" id="@cdktn/provider-docker.compose.Compose.moveFromId"></a>

```python
def move_from_id(
  id: str
) -> None
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveFromId.parameter.id"></a>

- *Type:* str

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `move_to` <a name="move_to" id="@cdktn/provider-docker.compose.Compose.moveTo"></a>

```python
def move_to(
  move_target: str,
  index: str | typing.Union[int, float] = None
) -> None
```

Moves this resource to the target resource given by moveTarget.

###### `move_target`<sup>Required</sup> <a name="move_target" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.moveTarget"></a>

- *Type:* str

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.index"></a>

- *Type:* str | typing.Union[int, float]

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `move_to_id` <a name="move_to_id" id="@cdktn/provider-docker.compose.Compose.moveToId"></a>

```python
def move_to_id(
  id: str
) -> None
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveToId.parameter.id"></a>

- *Type:* str

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `reset_env_files` <a name="reset_env_files" id="@cdktn/provider-docker.compose.Compose.resetEnvFiles"></a>

```python
def reset_env_files() -> None
```

##### `reset_profiles` <a name="reset_profiles" id="@cdktn/provider-docker.compose.Compose.resetProfiles"></a>

```python
def reset_profiles() -> None
```

##### `reset_project_directory` <a name="reset_project_directory" id="@cdktn/provider-docker.compose.Compose.resetProjectDirectory"></a>

```python
def reset_project_directory() -> None
```

##### `reset_project_name` <a name="reset_project_name" id="@cdktn/provider-docker.compose.Compose.resetProjectName"></a>

```python
def reset_project_name() -> None
```

##### `reset_remove_orphans` <a name="reset_remove_orphans" id="@cdktn/provider-docker.compose.Compose.resetRemoveOrphans"></a>

```python
def reset_remove_orphans() -> None
```

##### `reset_wait` <a name="reset_wait" id="@cdktn/provider-docker.compose.Compose.resetWait"></a>

```python
def reset_wait() -> None
```

##### `reset_wait_timeout` <a name="reset_wait_timeout" id="@cdktn/provider-docker.compose.Compose.resetWaitTimeout"></a>

```python
def reset_wait_timeout() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isTerraformResource">is_terraform_resource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.generateConfigForImport">generate_config_for_import</a></code> | Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>". |

---

##### `is_construct` <a name="is_construct" id="@cdktn/provider-docker.compose.Compose.isConstruct"></a>

```python
from cdktn_provider_docker import compose

compose.Compose.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="@cdktn/provider-docker.compose.Compose.isTerraformElement"></a>

```python
from cdktn_provider_docker import compose

compose.Compose.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="@cdktn/provider-docker.compose.Compose.isTerraformResource"></a>

```python
from cdktn_provider_docker import compose

compose.Compose.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

##### `generate_config_for_import` <a name="generate_config_for_import" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport"></a>

```python
from cdktn_provider_docker import compose

compose.Compose.generate_config_for_import(
  scope: Construct,
  import_to_id: str,
  import_from_id: str,
  provider: TerraformProvider = None
)
```

Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `import_to_id`<sup>Required</sup> <a name="import_to_id" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importToId"></a>

- *Type:* str

The construct id used in the generated config for the Compose to import.

---

###### `import_from_id`<sup>Required</sup> <a name="import_from_id" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importFromId"></a>

- *Type:* str

The id of the existing Compose that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the Compose to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.cdktfStack">cdktf_stack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPathsInput">config_paths_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFilesInput">env_files_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profilesInput">profiles_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput">project_directory_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectNameInput">project_name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphansInput">remove_orphans_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitInput">wait_input</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput">wait_timeout_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPaths">config_paths</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFiles">env_files</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profiles">profiles</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectory">project_directory</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectName">project_name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphans">remove_orphans</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.wait">wait</a></code> | <code>bool \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeout">wait_timeout</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.compose.Compose.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="@cdktn/provider-docker.compose.Compose.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.compose.Compose.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="@cdktn/provider-docker.compose.Compose.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.Compose.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.Compose.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.compose.Compose.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.compose.Compose.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.Compose.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.Compose.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `config_paths_input`<sup>Optional</sup> <a name="config_paths_input" id="@cdktn/provider-docker.compose.Compose.property.configPathsInput"></a>

```python
config_paths_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `env_files_input`<sup>Optional</sup> <a name="env_files_input" id="@cdktn/provider-docker.compose.Compose.property.envFilesInput"></a>

```python
env_files_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `profiles_input`<sup>Optional</sup> <a name="profiles_input" id="@cdktn/provider-docker.compose.Compose.property.profilesInput"></a>

```python
profiles_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `project_directory_input`<sup>Optional</sup> <a name="project_directory_input" id="@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput"></a>

```python
project_directory_input: str
```

- *Type:* str

---

##### `project_name_input`<sup>Optional</sup> <a name="project_name_input" id="@cdktn/provider-docker.compose.Compose.property.projectNameInput"></a>

```python
project_name_input: str
```

- *Type:* str

---

##### `remove_orphans_input`<sup>Optional</sup> <a name="remove_orphans_input" id="@cdktn/provider-docker.compose.Compose.property.removeOrphansInput"></a>

```python
remove_orphans_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `wait_input`<sup>Optional</sup> <a name="wait_input" id="@cdktn/provider-docker.compose.Compose.property.waitInput"></a>

```python
wait_input: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `wait_timeout_input`<sup>Optional</sup> <a name="wait_timeout_input" id="@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput"></a>

```python
wait_timeout_input: str
```

- *Type:* str

---

##### `config_paths`<sup>Required</sup> <a name="config_paths" id="@cdktn/provider-docker.compose.Compose.property.configPaths"></a>

```python
config_paths: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `env_files`<sup>Required</sup> <a name="env_files" id="@cdktn/provider-docker.compose.Compose.property.envFiles"></a>

```python
env_files: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `profiles`<sup>Required</sup> <a name="profiles" id="@cdktn/provider-docker.compose.Compose.property.profiles"></a>

```python
profiles: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `project_directory`<sup>Required</sup> <a name="project_directory" id="@cdktn/provider-docker.compose.Compose.property.projectDirectory"></a>

```python
project_directory: str
```

- *Type:* str

---

##### `project_name`<sup>Required</sup> <a name="project_name" id="@cdktn/provider-docker.compose.Compose.property.projectName"></a>

```python
project_name: str
```

- *Type:* str

---

##### `remove_orphans`<sup>Required</sup> <a name="remove_orphans" id="@cdktn/provider-docker.compose.Compose.property.removeOrphans"></a>

```python
remove_orphans: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `wait`<sup>Required</sup> <a name="wait" id="@cdktn/provider-docker.compose.Compose.property.wait"></a>

```python
wait: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

---

##### `wait_timeout`<sup>Required</sup> <a name="wait_timeout" id="@cdktn/provider-docker.compose.Compose.property.waitTimeout"></a>

```python
wait_timeout: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.compose.Compose.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### ComposeConfig <a name="ComposeConfig" id="@cdktn/provider-docker.compose.ComposeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.compose.ComposeConfig.Initializer"></a>

```python
from cdktn_provider_docker import compose

compose.ComposeConfig(
  connection: SSHProvisionerConnection | WinrmProvisionerConnection = None,
  count: typing.Union[int, float] | TerraformCount = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner] = None,
  config_paths: typing.List[str],
  env_files: typing.List[str] = None,
  profiles: typing.List[str] = None,
  project_directory: str = None,
  project_name: str = None,
  remove_orphans: bool | IResolvable = None,
  wait: bool | IResolvable = None,
  wait_timeout: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.count">count</a></code> | <code>typing.Union[int, float] \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktn.ITerraformDependable]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.forEach">for_each</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provisioners">provisioners</a></code> | <code>typing.List[cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.configPaths">config_paths</a></code> | <code>typing.List[str]</code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.envFiles">env_files</a></code> | <code>typing.List[str]</code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.profiles">profiles</a></code> | <code>typing.List[str]</code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory">project_directory</a></code> | <code>str</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectName">project_name</a></code> | <code>str</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans">remove_orphans</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.wait">wait</a></code> | <code>bool \| cdktn.IResolvable</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout">wait_timeout</a></code> | <code>str</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.ComposeConfig.property.connection"></a>

```python
connection: SSHProvisionerConnection | WinrmProvisionerConnection
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.ComposeConfig.property.count"></a>

```python
count: typing.Union[int, float] | TerraformCount
```

- *Type:* typing.Union[int, float] | cdktn.TerraformCount

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktn.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="@cdktn/provider-docker.compose.ComposeConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.ComposeConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.ComposeConfig.property.provisioners"></a>

```python
provisioners: typing.List[FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner]
```

- *Type:* typing.List[cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner]

---

##### `config_paths`<sup>Required</sup> <a name="config_paths" id="@cdktn/provider-docker.compose.ComposeConfig.property.configPaths"></a>

```python
config_paths: typing.List[str]
```

- *Type:* typing.List[str]

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `env_files`<sup>Optional</sup> <a name="env_files" id="@cdktn/provider-docker.compose.ComposeConfig.property.envFiles"></a>

```python
env_files: typing.List[str]
```

- *Type:* typing.List[str]

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#env_files Compose#env_files}

---

##### `profiles`<sup>Optional</sup> <a name="profiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.profiles"></a>

```python
profiles: typing.List[str]
```

- *Type:* typing.List[str]

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#profiles Compose#profiles}

---

##### `project_directory`<sup>Optional</sup> <a name="project_directory" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory"></a>

```python
project_directory: str
```

- *Type:* str

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `project_name`<sup>Optional</sup> <a name="project_name" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectName"></a>

```python
project_name: str
```

- *Type:* str

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#project_name Compose#project_name}

---

##### `remove_orphans`<sup>Optional</sup> <a name="remove_orphans" id="@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans"></a>

```python
remove_orphans: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.compose.ComposeConfig.property.wait"></a>

```python
wait: bool | IResolvable
```

- *Type:* bool | cdktn.IResolvable

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#wait Compose#wait}

---

##### `wait_timeout`<sup>Optional</sup> <a name="wait_timeout" id="@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout"></a>

```python
wait_timeout: str
```

- *Type:* str

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---



