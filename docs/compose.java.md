# `compose` Submodule <a name="`compose` Submodule" id="@cdktn/provider-docker.compose"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Compose <a name="Compose" id="@cdktn/provider-docker.compose.Compose"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose docker_compose}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.compose.Compose.Initializer"></a>

```java
import io.cdktn.providers.docker.compose.Compose;

Compose.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .configPaths(java.util.List<java.lang.String>)
//  .envFiles(java.util.List<java.lang.String>)
//  .profiles(java.util.List<java.lang.String>)
//  .projectDirectory(java.lang.String)
//  .projectName(java.lang.String)
//  .removeOrphans(java.lang.Boolean|IResolvable)
//  .wait(java.lang.Boolean|IResolvable)
//  .waitTimeout(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.configPaths">configPaths</a></code> | <code>java.util.List<java.lang.String></code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.envFiles">envFiles</a></code> | <code>java.util.List<java.lang.String></code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.profiles">profiles</a></code> | <code>java.util.List<java.lang.String></code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectDirectory">projectDirectory</a></code> | <code>java.lang.String</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectName">projectName</a></code> | <code>java.lang.String</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.removeOrphans">removeOrphans</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.wait">wait</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.waitTimeout">waitTimeout</a></code> | <code>java.lang.String</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `configPaths`<sup>Required</sup> <a name="configPaths" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.configPaths"></a>

- *Type:* java.util.List<java.lang.String>

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `envFiles`<sup>Optional</sup> <a name="envFiles" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.envFiles"></a>

- *Type:* java.util.List<java.lang.String>

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#env_files Compose#env_files}

---

##### `profiles`<sup>Optional</sup> <a name="profiles" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.profiles"></a>

- *Type:* java.util.List<java.lang.String>

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#profiles Compose#profiles}

---

##### `projectDirectory`<sup>Optional</sup> <a name="projectDirectory" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectDirectory"></a>

- *Type:* java.lang.String

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `projectName`<sup>Optional</sup> <a name="projectName" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.projectName"></a>

- *Type:* java.lang.String

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_name Compose#project_name}

---

##### `removeOrphans`<sup>Optional</sup> <a name="removeOrphans" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.removeOrphans"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.wait"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait Compose#wait}

---

##### `waitTimeout`<sup>Optional</sup> <a name="waitTimeout" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.waitTimeout"></a>

- *Type:* java.lang.String

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toHclTerraform">toHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.hasResourceMove">hasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveFromId">moveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.moveToId">moveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetEnvFiles">resetEnvFiles</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProfiles">resetProfiles</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProjectDirectory">resetProjectDirectory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetProjectName">resetProjectName</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetRemoveOrphans">resetRemoveOrphans</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetWait">resetWait</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.resetWaitTimeout">resetWaitTimeout</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.compose.Compose.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.compose.Compose.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.compose.Compose.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.compose.Compose.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.compose.Compose.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.compose.Compose.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.compose.Compose.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.compose.Compose.hasResourceMove"></a>

```java
public TerraformResourceMoveByTarget|TerraformResourceMoveById hasResourceMove()
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.compose.Compose.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.compose.Compose.moveFromId"></a>

```java
public void moveFromId(java.lang.String id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveFromId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.compose.Compose.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String|java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.index"></a>

- *Type:* java.lang.String|java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.compose.Compose.moveToId"></a>

```java
public void moveToId(java.lang.String id)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveToId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `resetEnvFiles` <a name="resetEnvFiles" id="@cdktn/provider-docker.compose.Compose.resetEnvFiles"></a>

```java
public void resetEnvFiles()
```

##### `resetProfiles` <a name="resetProfiles" id="@cdktn/provider-docker.compose.Compose.resetProfiles"></a>

```java
public void resetProfiles()
```

##### `resetProjectDirectory` <a name="resetProjectDirectory" id="@cdktn/provider-docker.compose.Compose.resetProjectDirectory"></a>

```java
public void resetProjectDirectory()
```

##### `resetProjectName` <a name="resetProjectName" id="@cdktn/provider-docker.compose.Compose.resetProjectName"></a>

```java
public void resetProjectName()
```

##### `resetRemoveOrphans` <a name="resetRemoveOrphans" id="@cdktn/provider-docker.compose.Compose.resetRemoveOrphans"></a>

```java
public void resetRemoveOrphans()
```

##### `resetWait` <a name="resetWait" id="@cdktn/provider-docker.compose.Compose.resetWait"></a>

```java
public void resetWait()
```

##### `resetWaitTimeout` <a name="resetWaitTimeout" id="@cdktn/provider-docker.compose.Compose.resetWaitTimeout"></a>

```java
public void resetWaitTimeout()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-docker.compose.Compose.isConstruct"></a>

```java
import io.cdktn.providers.docker.compose.Compose;

Compose.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.compose.Compose.isTerraformElement"></a>

```java
import io.cdktn.providers.docker.compose.Compose;

Compose.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.compose.Compose.isTerraformResource"></a>

```java
import io.cdktn.providers.docker.compose.Compose;

Compose.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport"></a>

```java
import io.cdktn.providers.docker.compose.Compose;

Compose.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),Compose.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the Compose to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing Compose that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the Compose to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPathsInput">configPathsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFilesInput">envFilesInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profilesInput">profilesInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput">projectDirectoryInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectNameInput">projectNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphansInput">removeOrphansInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitInput">waitInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput">waitTimeoutInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPaths">configPaths</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFiles">envFiles</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profiles">profiles</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectory">projectDirectory</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectName">projectName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphans">removeOrphans</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.wait">wait</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeout">waitTimeout</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.compose.Compose.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.compose.Compose.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.compose.Compose.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.compose.Compose.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.Compose.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.Compose.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.compose.Compose.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.compose.Compose.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.Compose.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.Compose.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `configPathsInput`<sup>Optional</sup> <a name="configPathsInput" id="@cdktn/provider-docker.compose.Compose.property.configPathsInput"></a>

```java
public java.util.List<java.lang.String> getConfigPathsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `envFilesInput`<sup>Optional</sup> <a name="envFilesInput" id="@cdktn/provider-docker.compose.Compose.property.envFilesInput"></a>

```java
public java.util.List<java.lang.String> getEnvFilesInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `profilesInput`<sup>Optional</sup> <a name="profilesInput" id="@cdktn/provider-docker.compose.Compose.property.profilesInput"></a>

```java
public java.util.List<java.lang.String> getProfilesInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `projectDirectoryInput`<sup>Optional</sup> <a name="projectDirectoryInput" id="@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput"></a>

```java
public java.lang.String getProjectDirectoryInput();
```

- *Type:* java.lang.String

---

##### `projectNameInput`<sup>Optional</sup> <a name="projectNameInput" id="@cdktn/provider-docker.compose.Compose.property.projectNameInput"></a>

```java
public java.lang.String getProjectNameInput();
```

- *Type:* java.lang.String

---

##### `removeOrphansInput`<sup>Optional</sup> <a name="removeOrphansInput" id="@cdktn/provider-docker.compose.Compose.property.removeOrphansInput"></a>

```java
public java.lang.Boolean|IResolvable getRemoveOrphansInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `waitInput`<sup>Optional</sup> <a name="waitInput" id="@cdktn/provider-docker.compose.Compose.property.waitInput"></a>

```java
public java.lang.Boolean|IResolvable getWaitInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `waitTimeoutInput`<sup>Optional</sup> <a name="waitTimeoutInput" id="@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput"></a>

```java
public java.lang.String getWaitTimeoutInput();
```

- *Type:* java.lang.String

---

##### `configPaths`<sup>Required</sup> <a name="configPaths" id="@cdktn/provider-docker.compose.Compose.property.configPaths"></a>

```java
public java.util.List<java.lang.String> getConfigPaths();
```

- *Type:* java.util.List<java.lang.String>

---

##### `envFiles`<sup>Required</sup> <a name="envFiles" id="@cdktn/provider-docker.compose.Compose.property.envFiles"></a>

```java
public java.util.List<java.lang.String> getEnvFiles();
```

- *Type:* java.util.List<java.lang.String>

---

##### `profiles`<sup>Required</sup> <a name="profiles" id="@cdktn/provider-docker.compose.Compose.property.profiles"></a>

```java
public java.util.List<java.lang.String> getProfiles();
```

- *Type:* java.util.List<java.lang.String>

---

##### `projectDirectory`<sup>Required</sup> <a name="projectDirectory" id="@cdktn/provider-docker.compose.Compose.property.projectDirectory"></a>

```java
public java.lang.String getProjectDirectory();
```

- *Type:* java.lang.String

---

##### `projectName`<sup>Required</sup> <a name="projectName" id="@cdktn/provider-docker.compose.Compose.property.projectName"></a>

```java
public java.lang.String getProjectName();
```

- *Type:* java.lang.String

---

##### `removeOrphans`<sup>Required</sup> <a name="removeOrphans" id="@cdktn/provider-docker.compose.Compose.property.removeOrphans"></a>

```java
public java.lang.Boolean|IResolvable getRemoveOrphans();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `wait`<sup>Required</sup> <a name="wait" id="@cdktn/provider-docker.compose.Compose.property.wait"></a>

```java
public java.lang.Boolean|IResolvable getWait();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `waitTimeout`<sup>Required</sup> <a name="waitTimeout" id="@cdktn/provider-docker.compose.Compose.property.waitTimeout"></a>

```java
public java.lang.String getWaitTimeout();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.compose.Compose.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### ComposeConfig <a name="ComposeConfig" id="@cdktn/provider-docker.compose.ComposeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.compose.ComposeConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.compose.ComposeConfig;

ComposeConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .configPaths(java.util.List<java.lang.String>)
//  .envFiles(java.util.List<java.lang.String>)
//  .profiles(java.util.List<java.lang.String>)
//  .projectDirectory(java.lang.String)
//  .projectName(java.lang.String)
//  .removeOrphans(java.lang.Boolean|IResolvable)
//  .wait(java.lang.Boolean|IResolvable)
//  .waitTimeout(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.configPaths">configPaths</a></code> | <code>java.util.List<java.lang.String></code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.envFiles">envFiles</a></code> | <code>java.util.List<java.lang.String></code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.profiles">profiles</a></code> | <code>java.util.List<java.lang.String></code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory">projectDirectory</a></code> | <code>java.lang.String</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectName">projectName</a></code> | <code>java.lang.String</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans">removeOrphans</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.wait">wait</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout">waitTimeout</a></code> | <code>java.lang.String</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.ComposeConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.ComposeConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.compose.ComposeConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.ComposeConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.ComposeConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `configPaths`<sup>Required</sup> <a name="configPaths" id="@cdktn/provider-docker.compose.ComposeConfig.property.configPaths"></a>

```java
public java.util.List<java.lang.String> getConfigPaths();
```

- *Type:* java.util.List<java.lang.String>

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `envFiles`<sup>Optional</sup> <a name="envFiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.envFiles"></a>

```java
public java.util.List<java.lang.String> getEnvFiles();
```

- *Type:* java.util.List<java.lang.String>

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#env_files Compose#env_files}

---

##### `profiles`<sup>Optional</sup> <a name="profiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.profiles"></a>

```java
public java.util.List<java.lang.String> getProfiles();
```

- *Type:* java.util.List<java.lang.String>

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#profiles Compose#profiles}

---

##### `projectDirectory`<sup>Optional</sup> <a name="projectDirectory" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory"></a>

```java
public java.lang.String getProjectDirectory();
```

- *Type:* java.lang.String

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `projectName`<sup>Optional</sup> <a name="projectName" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectName"></a>

```java
public java.lang.String getProjectName();
```

- *Type:* java.lang.String

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#project_name Compose#project_name}

---

##### `removeOrphans`<sup>Optional</sup> <a name="removeOrphans" id="@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans"></a>

```java
public java.lang.Boolean|IResolvable getRemoveOrphans();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.compose.ComposeConfig.property.wait"></a>

```java
public java.lang.Boolean|IResolvable getWait();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait Compose#wait}

---

##### `waitTimeout`<sup>Optional</sup> <a name="waitTimeout" id="@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout"></a>

```java
public java.lang.String getWaitTimeout();
```

- *Type:* java.lang.String

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---



