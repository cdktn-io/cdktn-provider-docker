# `volume` Submodule <a name="`volume` Submodule" id="@cdktn/provider-docker.volume"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Volume <a name="Volume" id="@cdktn/provider-docker.volume.Volume"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume docker_volume}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.Volume.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.Volume;

Volume.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
//  .cluster(VolumeCluster)
//  .driver(java.lang.String)
//  .driverOpts(java.util.Map<java.lang.String, java.lang.String>)
//  .id(java.lang.String)
//  .labels(IResolvable|java.util.List<VolumeLabels>)
//  .name(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.cluster">cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | cluster block. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.driver">driver</a></code> | <code>java.lang.String</code> | Driver type for the volume. Defaults to `local`. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.driverOpts">driverOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Options specific to the driver. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#id Volume#id}. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.labels">labels</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>></code> | labels block. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | The name of the Docker volume (will be generated if not provided). |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `cluster`<sup>Optional</sup> <a name="cluster" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.cluster"></a>

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

cluster block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#cluster Volume#cluster}

---

##### `driver`<sup>Optional</sup> <a name="driver" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.driver"></a>

- *Type:* java.lang.String

Driver type for the volume. Defaults to `local`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#driver Volume#driver}

---

##### `driverOpts`<sup>Optional</sup> <a name="driverOpts" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.driverOpts"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Options specific to the driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#driver_opts Volume#driver_opts}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#id Volume#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.labels"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>>

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#labels Volume#labels}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.name"></a>

- *Type:* java.lang.String

The name of the Docker volume (will be generated if not provided).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#name Volume#name}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toHclTerraform">toHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.hasResourceMove">hasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.moveFromId">moveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.moveToId">moveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.volume.Volume.putCluster">putCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.putLabels">putLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetCluster">resetCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetDriver">resetDriver</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetDriverOpts">resetDriverOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetId">resetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetLabels">resetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.resetName">resetName</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.Volume.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.volume.Volume.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.volume.Volume.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.volume.Volume.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.volume.Volume.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.volume.Volume.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.volume.Volume.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.volume.Volume.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.volume.Volume.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.volume.Volume.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.volume.Volume.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.volume.Volume.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.volume.Volume.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.volume.Volume.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.volume.Volume.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.volume.Volume.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.volume.Volume.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.volume.Volume.hasResourceMove"></a>

```java
public TerraformResourceMoveByTarget|TerraformResourceMoveById hasResourceMove()
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.volume.Volume.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.importFrom.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.volume.Volume.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.volume.Volume.moveFromId"></a>

```java
public void moveFromId(java.lang.String id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.moveFromId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.volume.Volume.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String|java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.volume.Volume.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.volume.Volume.moveTo.parameter.index"></a>

- *Type:* java.lang.String|java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.volume.Volume.moveToId"></a>

```java
public void moveToId(java.lang.String id)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.moveToId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `putCluster` <a name="putCluster" id="@cdktn/provider-docker.volume.Volume.putCluster"></a>

```java
public void putCluster(VolumeCluster value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.putCluster.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---

##### `putLabels` <a name="putLabels" id="@cdktn/provider-docker.volume.Volume.putLabels"></a>

```java
public void putLabels(IResolvable|java.util.List<VolumeLabels> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.putLabels.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>>

---

##### `resetCluster` <a name="resetCluster" id="@cdktn/provider-docker.volume.Volume.resetCluster"></a>

```java
public void resetCluster()
```

##### `resetDriver` <a name="resetDriver" id="@cdktn/provider-docker.volume.Volume.resetDriver"></a>

```java
public void resetDriver()
```

##### `resetDriverOpts` <a name="resetDriverOpts" id="@cdktn/provider-docker.volume.Volume.resetDriverOpts"></a>

```java
public void resetDriverOpts()
```

##### `resetId` <a name="resetId" id="@cdktn/provider-docker.volume.Volume.resetId"></a>

```java
public void resetId()
```

##### `resetLabels` <a name="resetLabels" id="@cdktn/provider-docker.volume.Volume.resetLabels"></a>

```java
public void resetLabels()
```

##### `resetName` <a name="resetName" id="@cdktn/provider-docker.volume.Volume.resetName"></a>

```java
public void resetName()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a Volume resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-docker.volume.Volume.isConstruct"></a>

```java
import io.cdktn.providers.docker.volume.Volume;

Volume.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.volume.Volume.isTerraformElement"></a>

```java
import io.cdktn.providers.docker.volume.Volume;

Volume.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.volume.Volume.isTerraformResource"></a>

```java
import io.cdktn.providers.docker.volume.Volume;

Volume.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport"></a>

```java
import io.cdktn.providers.docker.volume.Volume;

Volume.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),Volume.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a Volume resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the Volume to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing Volume that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the Volume to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.cluster">cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference">VolumeClusterOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.labels">labels</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList">VolumeLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.mountpoint">mountpoint</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.clusterInput">clusterInput</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverInput">driverInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverOptsInput">driverOptsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.labelsInput">labelsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driver">driver</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverOpts">driverOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.volume.Volume.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.volume.Volume.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.Volume.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.volume.Volume.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.volume.Volume.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.volume.Volume.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.volume.Volume.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.volume.Volume.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.volume.Volume.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.volume.Volume.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.volume.Volume.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.volume.Volume.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.volume.Volume.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `cluster`<sup>Required</sup> <a name="cluster" id="@cdktn/provider-docker.volume.Volume.property.cluster"></a>

```java
public VolumeClusterOutputReference getCluster();
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference">VolumeClusterOutputReference</a>

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.volume.Volume.property.labels"></a>

```java
public VolumeLabelsList getLabels();
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeLabelsList">VolumeLabelsList</a>

---

##### `mountpoint`<sup>Required</sup> <a name="mountpoint" id="@cdktn/provider-docker.volume.Volume.property.mountpoint"></a>

```java
public java.lang.String getMountpoint();
```

- *Type:* java.lang.String

---

##### `clusterInput`<sup>Optional</sup> <a name="clusterInput" id="@cdktn/provider-docker.volume.Volume.property.clusterInput"></a>

```java
public VolumeCluster getClusterInput();
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---

##### `driverInput`<sup>Optional</sup> <a name="driverInput" id="@cdktn/provider-docker.volume.Volume.property.driverInput"></a>

```java
public java.lang.String getDriverInput();
```

- *Type:* java.lang.String

---

##### `driverOptsInput`<sup>Optional</sup> <a name="driverOptsInput" id="@cdktn/provider-docker.volume.Volume.property.driverOptsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDriverOptsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.volume.Volume.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `labelsInput`<sup>Optional</sup> <a name="labelsInput" id="@cdktn/provider-docker.volume.Volume.property.labelsInput"></a>

```java
public IResolvable|java.util.List<VolumeLabels> getLabelsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>>

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.volume.Volume.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `driver`<sup>Required</sup> <a name="driver" id="@cdktn/provider-docker.volume.Volume.property.driver"></a>

```java
public java.lang.String getDriver();
```

- *Type:* java.lang.String

---

##### `driverOpts`<sup>Required</sup> <a name="driverOpts" id="@cdktn/provider-docker.volume.Volume.property.driverOpts"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDriverOpts();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.volume.Volume.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.volume.Volume.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### VolumeCluster <a name="VolumeCluster" id="@cdktn/provider-docker.volume.VolumeCluster"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeCluster.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.VolumeCluster;

VolumeCluster.builder()
//  .availability(java.lang.String)
//  .group(java.lang.String)
//  .limitBytes(java.lang.String)
//  .requiredBytes(java.lang.String)
//  .scope(java.lang.String)
//  .sharing(java.lang.String)
//  .topologyPreferred(java.lang.String)
//  .topologyRequired(java.lang.String)
//  .type(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.availability">availability</a></code> | <code>java.lang.String</code> | Availability of the volume. Can be `active` (default), `pause`, or `drain`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.group">group</a></code> | <code>java.lang.String</code> | Cluster Volume group. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.limitBytes">limitBytes</a></code> | <code>java.lang.String</code> | Minimum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc). |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.requiredBytes">requiredBytes</a></code> | <code>java.lang.String</code> | Maximum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc). |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.scope">scope</a></code> | <code>java.lang.String</code> | The scope of the volume. Can be `single` (default) or `multi`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.sharing">sharing</a></code> | <code>java.lang.String</code> | The sharing mode. Can be `none` (default), `readonly`, `onewriter` or `all`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.topologyPreferred">topologyPreferred</a></code> | <code>java.lang.String</code> | A topology that the Cluster Volume would be preferred in. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.topologyRequired">topologyRequired</a></code> | <code>java.lang.String</code> | A topology that the Cluster Volume must be accessible from. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.type">type</a></code> | <code>java.lang.String</code> | Cluster Volume access type. Can be `mount` or `block` (default). |

---

##### `availability`<sup>Optional</sup> <a name="availability" id="@cdktn/provider-docker.volume.VolumeCluster.property.availability"></a>

```java
public java.lang.String getAvailability();
```

- *Type:* java.lang.String

Availability of the volume. Can be `active` (default), `pause`, or `drain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#availability Volume#availability}

---

##### `group`<sup>Optional</sup> <a name="group" id="@cdktn/provider-docker.volume.VolumeCluster.property.group"></a>

```java
public java.lang.String getGroup();
```

- *Type:* java.lang.String

Cluster Volume group.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#group Volume#group}

---

##### `limitBytes`<sup>Optional</sup> <a name="limitBytes" id="@cdktn/provider-docker.volume.VolumeCluster.property.limitBytes"></a>

```java
public java.lang.String getLimitBytes();
```

- *Type:* java.lang.String

Minimum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc).

Must be in format of KiB, MiB, Gib, Tib or PiB.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#limit_bytes Volume#limit_bytes}

---

##### `requiredBytes`<sup>Optional</sup> <a name="requiredBytes" id="@cdktn/provider-docker.volume.VolumeCluster.property.requiredBytes"></a>

```java
public java.lang.String getRequiredBytes();
```

- *Type:* java.lang.String

Maximum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc).

Must be in format of KiB, MiB, Gib, Tib or PiB.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#required_bytes Volume#required_bytes}

---

##### `scope`<sup>Optional</sup> <a name="scope" id="@cdktn/provider-docker.volume.VolumeCluster.property.scope"></a>

```java
public java.lang.String getScope();
```

- *Type:* java.lang.String

The scope of the volume. Can be `single` (default) or `multi`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#scope Volume#scope}

---

##### `sharing`<sup>Optional</sup> <a name="sharing" id="@cdktn/provider-docker.volume.VolumeCluster.property.sharing"></a>

```java
public java.lang.String getSharing();
```

- *Type:* java.lang.String

The sharing mode. Can be `none` (default), `readonly`, `onewriter` or `all`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#sharing Volume#sharing}

---

##### `topologyPreferred`<sup>Optional</sup> <a name="topologyPreferred" id="@cdktn/provider-docker.volume.VolumeCluster.property.topologyPreferred"></a>

```java
public java.lang.String getTopologyPreferred();
```

- *Type:* java.lang.String

A topology that the Cluster Volume would be preferred in.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#topology_preferred Volume#topology_preferred}

---

##### `topologyRequired`<sup>Optional</sup> <a name="topologyRequired" id="@cdktn/provider-docker.volume.VolumeCluster.property.topologyRequired"></a>

```java
public java.lang.String getTopologyRequired();
```

- *Type:* java.lang.String

A topology that the Cluster Volume must be accessible from.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#topology_required Volume#topology_required}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktn/provider-docker.volume.VolumeCluster.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Cluster Volume access type. Can be `mount` or `block` (default).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#type Volume#type}

---

### VolumeConfig <a name="VolumeConfig" id="@cdktn/provider-docker.volume.VolumeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.VolumeConfig;

VolumeConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
//  .cluster(VolumeCluster)
//  .driver(java.lang.String)
//  .driverOpts(java.util.Map<java.lang.String, java.lang.String>)
//  .id(java.lang.String)
//  .labels(IResolvable|java.util.List<VolumeLabels>)
//  .name(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.cluster">cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | cluster block. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.driver">driver</a></code> | <code>java.lang.String</code> | Driver type for the volume. Defaults to `local`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.driverOpts">driverOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Options specific to the driver. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#id Volume#id}. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.labels">labels</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>></code> | labels block. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.name">name</a></code> | <code>java.lang.String</code> | The name of the Docker volume (will be generated if not provided). |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.volume.VolumeConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.volume.VolumeConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.volume.VolumeConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.volume.VolumeConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.volume.VolumeConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.VolumeConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.volume.VolumeConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `cluster`<sup>Optional</sup> <a name="cluster" id="@cdktn/provider-docker.volume.VolumeConfig.property.cluster"></a>

```java
public VolumeCluster getCluster();
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

cluster block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#cluster Volume#cluster}

---

##### `driver`<sup>Optional</sup> <a name="driver" id="@cdktn/provider-docker.volume.VolumeConfig.property.driver"></a>

```java
public java.lang.String getDriver();
```

- *Type:* java.lang.String

Driver type for the volume. Defaults to `local`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#driver Volume#driver}

---

##### `driverOpts`<sup>Optional</sup> <a name="driverOpts" id="@cdktn/provider-docker.volume.VolumeConfig.property.driverOpts"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDriverOpts();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Options specific to the driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#driver_opts Volume#driver_opts}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.volume.VolumeConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#id Volume#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.volume.VolumeConfig.property.labels"></a>

```java
public IResolvable|java.util.List<VolumeLabels> getLabels();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>>

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#labels Volume#labels}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktn/provider-docker.volume.VolumeConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The name of the Docker volume (will be generated if not provided).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#name Volume#name}

---

### VolumeLabels <a name="VolumeLabels" id="@cdktn/provider-docker.volume.VolumeLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeLabels.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.VolumeLabels;

VolumeLabels.builder()
    .label(java.lang.String)
    .value(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabels.property.label">label</a></code> | <code>java.lang.String</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabels.property.value">value</a></code> | <code>java.lang.String</code> | Value of the label. |

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.volume.VolumeLabels.property.label"></a>

```java
public java.lang.String getLabel();
```

- *Type:* java.lang.String

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#label Volume#label}

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.VolumeLabels.property.value"></a>

```java
public java.lang.String getValue();
```

- *Type:* java.lang.String

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/volume#value Volume#value}

---

## Classes <a name="Classes" id="Classes"></a>

### VolumeClusterOutputReference <a name="VolumeClusterOutputReference" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.VolumeClusterOutputReference;

new VolumeClusterOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetAvailability">resetAvailability</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetGroup">resetGroup</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetLimitBytes">resetLimitBytes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetRequiredBytes">resetRequiredBytes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetScope">resetScope</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetSharing">resetSharing</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyPreferred">resetTopologyPreferred</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyRequired">resetTopologyRequired</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetType">resetType</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAvailability` <a name="resetAvailability" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetAvailability"></a>

```java
public void resetAvailability()
```

##### `resetGroup` <a name="resetGroup" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetGroup"></a>

```java
public void resetGroup()
```

##### `resetLimitBytes` <a name="resetLimitBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetLimitBytes"></a>

```java
public void resetLimitBytes()
```

##### `resetRequiredBytes` <a name="resetRequiredBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetRequiredBytes"></a>

```java
public void resetRequiredBytes()
```

##### `resetScope` <a name="resetScope" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetScope"></a>

```java
public void resetScope()
```

##### `resetSharing` <a name="resetSharing" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetSharing"></a>

```java
public void resetSharing()
```

##### `resetTopologyPreferred` <a name="resetTopologyPreferred" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyPreferred"></a>

```java
public void resetTopologyPreferred()
```

##### `resetTopologyRequired` <a name="resetTopologyRequired" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyRequired"></a>

```java
public void resetTopologyRequired()
```

##### `resetType` <a name="resetType" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetType"></a>

```java
public void resetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availabilityInput">availabilityInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.groupInput">groupInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytesInput">limitBytesInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytesInput">requiredBytesInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scopeInput">scopeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharingInput">sharingInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferredInput">topologyPreferredInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequiredInput">topologyRequiredInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availability">availability</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.group">group</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytes">limitBytes</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytes">requiredBytes</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scope">scope</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharing">sharing</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferred">topologyPreferred</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequired">topologyRequired</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `availabilityInput`<sup>Optional</sup> <a name="availabilityInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availabilityInput"></a>

```java
public java.lang.String getAvailabilityInput();
```

- *Type:* java.lang.String

---

##### `groupInput`<sup>Optional</sup> <a name="groupInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.groupInput"></a>

```java
public java.lang.String getGroupInput();
```

- *Type:* java.lang.String

---

##### `limitBytesInput`<sup>Optional</sup> <a name="limitBytesInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytesInput"></a>

```java
public java.lang.String getLimitBytesInput();
```

- *Type:* java.lang.String

---

##### `requiredBytesInput`<sup>Optional</sup> <a name="requiredBytesInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytesInput"></a>

```java
public java.lang.String getRequiredBytesInput();
```

- *Type:* java.lang.String

---

##### `scopeInput`<sup>Optional</sup> <a name="scopeInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scopeInput"></a>

```java
public java.lang.String getScopeInput();
```

- *Type:* java.lang.String

---

##### `sharingInput`<sup>Optional</sup> <a name="sharingInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharingInput"></a>

```java
public java.lang.String getSharingInput();
```

- *Type:* java.lang.String

---

##### `topologyPreferredInput`<sup>Optional</sup> <a name="topologyPreferredInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferredInput"></a>

```java
public java.lang.String getTopologyPreferredInput();
```

- *Type:* java.lang.String

---

##### `topologyRequiredInput`<sup>Optional</sup> <a name="topologyRequiredInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequiredInput"></a>

```java
public java.lang.String getTopologyRequiredInput();
```

- *Type:* java.lang.String

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `availability`<sup>Required</sup> <a name="availability" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availability"></a>

```java
public java.lang.String getAvailability();
```

- *Type:* java.lang.String

---

##### `group`<sup>Required</sup> <a name="group" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.group"></a>

```java
public java.lang.String getGroup();
```

- *Type:* java.lang.String

---

##### `limitBytes`<sup>Required</sup> <a name="limitBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytes"></a>

```java
public java.lang.String getLimitBytes();
```

- *Type:* java.lang.String

---

##### `requiredBytes`<sup>Required</sup> <a name="requiredBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytes"></a>

```java
public java.lang.String getRequiredBytes();
```

- *Type:* java.lang.String

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scope"></a>

```java
public java.lang.String getScope();
```

- *Type:* java.lang.String

---

##### `sharing`<sup>Required</sup> <a name="sharing" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharing"></a>

```java
public java.lang.String getSharing();
```

- *Type:* java.lang.String

---

##### `topologyPreferred`<sup>Required</sup> <a name="topologyPreferred" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferred"></a>

```java
public java.lang.String getTopologyPreferred();
```

- *Type:* java.lang.String

---

##### `topologyRequired`<sup>Required</sup> <a name="topologyRequired" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequired"></a>

```java
public java.lang.String getTopologyRequired();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.internalValue"></a>

```java
public VolumeCluster getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---


### VolumeLabelsList <a name="VolumeLabelsList" id="@cdktn/provider-docker.volume.VolumeLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.VolumeLabelsList;

new VolumeLabelsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.volume.VolumeLabelsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.volume.VolumeLabelsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeLabelsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.VolumeLabelsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.volume.VolumeLabelsList.get"></a>

```java
public VolumeLabelsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.volume.VolumeLabelsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<VolumeLabels> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>>

---


### VolumeLabelsOutputReference <a name="VolumeLabelsOutputReference" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.volume.VolumeLabelsOutputReference;

new VolumeLabelsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.labelInput">labelInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.valueInput">valueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.label">label</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.value">value</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `labelInput`<sup>Optional</sup> <a name="labelInput" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.labelInput"></a>

```java
public java.lang.String getLabelInput();
```

- *Type:* java.lang.String

---

##### `valueInput`<sup>Optional</sup> <a name="valueInput" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.valueInput"></a>

```java
public java.lang.String getValueInput();
```

- *Type:* java.lang.String

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.label"></a>

```java
public java.lang.String getLabel();
```

- *Type:* java.lang.String

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.value"></a>

```java
public java.lang.String getValue();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.internalValue"></a>

```java
public IResolvable|VolumeLabels getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>

---



