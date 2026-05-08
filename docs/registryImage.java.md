# `registryImage` Submodule <a name="`registryImage` Submodule" id="@cdktn/provider-docker.registryImage"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### RegistryImage <a name="RegistryImage" id="@cdktn/provider-docker.registryImage.RegistryImage"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image docker_registry_image}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImage;

RegistryImage.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .name(java.lang.String)
//  .authConfig(RegistryImageAuthConfig)
//  .buildAttribute(RegistryImageBuild)
//  .id(java.lang.String)
//  .insecureSkipVerify(java.lang.Boolean|IResolvable)
//  .keepRemotely(java.lang.Boolean|IResolvable)
//  .timeouts(RegistryImageTimeouts)
//  .triggers(java.util.Map<java.lang.String, java.lang.String>)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.buildAttribute">buildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.insecureSkipVerify">insecureSkipVerify</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.keepRemotely">keepRemotely</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.triggers">triggers</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.name"></a>

- *Type:* java.lang.String

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `authConfig`<sup>Optional</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.authConfig"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `buildAttribute`<sup>Optional</sup> <a name="buildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.buildAttribute"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `insecureSkipVerify`<sup>Optional</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.insecureSkipVerify"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `keepRemotely`<sup>Optional</sup> <a name="keepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.keepRemotely"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.timeouts"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `triggers`<sup>Optional</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.triggers"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform">toHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove">hasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveFromId">moveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.moveToId">moveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig">putAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute">putBuildAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts">putTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig">resetAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute">resetBuildAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetId">resetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify">resetInsecureSkipVerify</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely">resetKeepRemotely</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts">resetTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers">resetTriggers</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImage.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.registryImage.RegistryImage.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.registryImage.RegistryImage.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove"></a>

```java
public TerraformResourceMoveByTarget|TerraformResourceMoveById hasResourceMove()
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId"></a>

```java
public void moveFromId(java.lang.String id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String|java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.index"></a>

- *Type:* java.lang.String|java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId"></a>

```java
public void moveToId(java.lang.String id)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `putAuthConfig` <a name="putAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig"></a>

```java
public void putAuthConfig(RegistryImageAuthConfig value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `putBuildAttribute` <a name="putBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute"></a>

```java
public void putBuildAttribute(RegistryImageBuild value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `putTimeouts` <a name="putTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts"></a>

```java
public void putTimeouts(RegistryImageTimeouts value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `resetAuthConfig` <a name="resetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig"></a>

```java
public void resetAuthConfig()
```

##### `resetBuildAttribute` <a name="resetBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute"></a>

```java
public void resetBuildAttribute()
```

##### `resetId` <a name="resetId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetId"></a>

```java
public void resetId()
```

##### `resetInsecureSkipVerify` <a name="resetInsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify"></a>

```java
public void resetInsecureSkipVerify()
```

##### `resetKeepRemotely` <a name="resetKeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely"></a>

```java
public void resetKeepRemotely()
```

##### `resetTimeouts` <a name="resetTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts"></a>

```java
public void resetTimeouts()
```

##### `resetTriggers` <a name="resetTriggers" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers"></a>

```java
public void resetTriggers()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-docker.registryImage.RegistryImage.isConstruct"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImage;

RegistryImage.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImage;

RegistryImage.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImage;

RegistryImage.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImage;

RegistryImage.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),RegistryImage.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the RegistryImage to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing RegistryImage that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the RegistryImage to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute">buildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest">sha256Digest</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput">authConfigInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput">buildAttributeInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput">insecureSkipVerifyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput">keepRemotelyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput">timeoutsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput">triggersInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely">keepRemotely</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggers">triggers</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.registryImage.RegistryImage.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImage.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImage.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.registryImage.RegistryImage.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `authConfig`<sup>Required</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig"></a>

```java
public RegistryImageAuthConfigOutputReference getAuthConfig();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a>

---

##### `buildAttribute`<sup>Required</sup> <a name="buildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute"></a>

```java
public RegistryImageBuildOutputReference getBuildAttribute();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a>

---

##### `sha256Digest`<sup>Required</sup> <a name="sha256Digest" id="@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest"></a>

```java
public java.lang.String getSha256Digest();
```

- *Type:* java.lang.String

---

##### `timeouts`<sup>Required</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts"></a>

```java
public RegistryImageTimeoutsOutputReference getTimeouts();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a>

---

##### `authConfigInput`<sup>Optional</sup> <a name="authConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput"></a>

```java
public RegistryImageAuthConfig getAuthConfigInput();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `buildAttributeInput`<sup>Optional</sup> <a name="buildAttributeInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput"></a>

```java
public RegistryImageBuild getBuildAttributeInput();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `insecureSkipVerifyInput`<sup>Optional</sup> <a name="insecureSkipVerifyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput"></a>

```java
public java.lang.Boolean|IResolvable getInsecureSkipVerifyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `keepRemotelyInput`<sup>Optional</sup> <a name="keepRemotelyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput"></a>

```java
public java.lang.Boolean|IResolvable getKeepRemotelyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `timeoutsInput`<sup>Optional</sup> <a name="timeoutsInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput"></a>

```java
public IResolvable|RegistryImageTimeouts getTimeoutsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `triggersInput`<sup>Optional</sup> <a name="triggersInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getTriggersInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `insecureSkipVerify`<sup>Required</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify"></a>

```java
public java.lang.Boolean|IResolvable getInsecureSkipVerify();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `keepRemotely`<sup>Required</sup> <a name="keepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely"></a>

```java
public java.lang.Boolean|IResolvable getKeepRemotely();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImage.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `triggers`<sup>Required</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggers"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getTriggers();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### RegistryImageAuthConfig <a name="RegistryImageAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageAuthConfig;

RegistryImageAuthConfig.builder()
    .address(java.lang.String)
//  .password(java.lang.String)
//  .username(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address">address</a></code> | <code>java.lang.String</code> | The address of the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password">password</a></code> | <code>java.lang.String</code> | The password for the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username">username</a></code> | <code>java.lang.String</code> | The username for the Docker registry. |

---

##### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address"></a>

```java
public java.lang.String getAddress();
```

- *Type:* java.lang.String

The address of the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#address RegistryImage#address}

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password"></a>

```java
public java.lang.String getPassword();
```

- *Type:* java.lang.String

The password for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `username`<sup>Optional</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username"></a>

```java
public java.lang.String getUsername();
```

- *Type:* java.lang.String

The username for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#username RegistryImage#username}

---

### RegistryImageBuild <a name="RegistryImageBuild" id="@cdktn/provider-docker.registryImage.RegistryImageBuild"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuild;

RegistryImageBuild.builder()
    .context(java.lang.String)
//  .additionalContexts(java.util.List<java.lang.String>)
//  .authConfig(IResolvable|java.util.List<RegistryImageBuildAuthConfig>)
//  .buildArgs(java.util.Map<java.lang.String, java.lang.String>)
//  .builder(java.lang.String)
//  .buildId(java.lang.String)
//  .buildLogFile(java.lang.String)
//  .cacheFrom(java.util.List<java.lang.String>)
//  .cacheTo(java.util.List<java.lang.String>)
//  .cgroupParent(java.lang.String)
//  .cpuPeriod(java.lang.Number)
//  .cpuQuota(java.lang.Number)
//  .cpuSetCpus(java.lang.String)
//  .cpuSetMems(java.lang.String)
//  .cpuShares(java.lang.Number)
//  .dockerfile(java.lang.String)
//  .extraHosts(java.util.List<java.lang.String>)
//  .forceRemove(java.lang.Boolean|IResolvable)
//  .isolation(java.lang.String)
//  .label(java.util.Map<java.lang.String, java.lang.String>)
//  .labels(java.util.Map<java.lang.String, java.lang.String>)
//  .memory(java.lang.Number)
//  .memorySwap(java.lang.Number)
//  .networkMode(java.lang.String)
//  .noCache(java.lang.Boolean|IResolvable)
//  .platform(java.lang.String)
//  .pullParent(java.lang.Boolean|IResolvable)
//  .remoteContext(java.lang.String)
//  .remove(java.lang.Boolean|IResolvable)
//  .secrets(IResolvable|java.util.List<RegistryImageBuildSecrets>)
//  .securityOpt(java.util.List<java.lang.String>)
//  .sessionId(java.lang.String)
//  .shmSize(java.lang.Number)
//  .squash(java.lang.Boolean|IResolvable)
//  .suppressOutput(java.lang.Boolean|IResolvable)
//  .tag(java.util.List<java.lang.String>)
//  .target(java.lang.String)
//  .ulimit(IResolvable|java.util.List<RegistryImageBuildUlimit>)
//  .useLegacyBuilder(java.lang.Boolean|IResolvable)
//  .version(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context">context</a></code> | <code>java.lang.String</code> | Value to specify the build context. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts">additionalContexts</a></code> | <code>java.util.List<java.lang.String></code> | A list of additional build contexts. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig">authConfig</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs">buildArgs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder">builder</a></code> | <code>java.lang.String</code> | The name of the buildx builder to use. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId">buildId</a></code> | <code>java.lang.String</code> | BuildID is an optional identifier that can be passed together with the build request. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile">buildLogFile</a></code> | <code>java.lang.String</code> | Path to a file where the buildx log are written to. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom">cacheFrom</a></code> | <code>java.util.List<java.lang.String></code> | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo">cacheTo</a></code> | <code>java.util.List<java.lang.String></code> | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent">cgroupParent</a></code> | <code>java.lang.String</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod">cpuPeriod</a></code> | <code>java.lang.Number</code> | The length of a CPU period in microseconds. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota">cpuQuota</a></code> | <code>java.lang.Number</code> | Microseconds of CPU time that the container can get in a CPU period. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus">cpuSetCpus</a></code> | <code>java.lang.String</code> | CPUs in which to allow execution (e.g., `0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems">cpuSetMems</a></code> | <code>java.lang.String</code> | MEMs in which to allow execution (`0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares">cpuShares</a></code> | <code>java.lang.Number</code> | CPU shares (relative weight). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile">dockerfile</a></code> | <code>java.lang.String</code> | Name of the Dockerfile. Defaults to `Dockerfile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts">extraHosts</a></code> | <code>java.util.List<java.lang.String></code> | A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"]. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove">forceRemove</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Always remove intermediate containers. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation">isolation</a></code> | <code>java.lang.String</code> | Isolation represents the isolation technology of a container. The supported values are. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label">label</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Set metadata for an image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels">labels</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | User-defined key/value metadata. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory">memory</a></code> | <code>java.lang.Number</code> | Set memory limit for build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap">memorySwap</a></code> | <code>java.lang.Number</code> | Total memory (memory + swap), -1 to enable unlimited swap. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode">networkMode</a></code> | <code>java.lang.String</code> | Set the networking mode for the RUN instructions during build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache">noCache</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Do not use the cache when building the image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform">platform</a></code> | <code>java.lang.String</code> | Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent">pullParent</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Attempt to pull the image even if an older image exists locally. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext">remoteContext</a></code> | <code>java.lang.String</code> | A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove">remove</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Remove intermediate containers after a successful build. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets">secrets</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>></code> | secrets block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt">securityOpt</a></code> | <code>java.util.List<java.lang.String></code> | The security options. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId">sessionId</a></code> | <code>java.lang.String</code> | Set an ID for the build session. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize">shmSize</a></code> | <code>java.lang.Number</code> | Size of /dev/shm in bytes. The size must be greater than 0. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash">squash</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If true the new layers are squashed into a new image with a single new layer. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput">suppressOutput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Suppress the build output and print image ID on success. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag">tag</a></code> | <code>java.util.List<java.lang.String></code> | Name and optionally a tag in the 'name:tag' format. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target">target</a></code> | <code>java.lang.String</code> | Set the target build stage to build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit">ulimit</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>></code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder">useLegacyBuilder</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version">version</a></code> | <code>java.lang.String</code> | Version of the underlying builder to use. |

---

##### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context"></a>

```java
public java.lang.String getContext();
```

- *Type:* java.lang.String

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#context RegistryImage#context}

---

##### `additionalContexts`<sup>Optional</sup> <a name="additionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts"></a>

```java
public java.util.List<java.lang.String> getAdditionalContexts();
```

- *Type:* java.util.List<java.lang.String>

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#additional_contexts RegistryImage#additional_contexts}

---

##### `authConfig`<sup>Optional</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildAuthConfig> getAuthConfig();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `buildArgs`<sup>Optional</sup> <a name="buildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getBuildArgs();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#build_args RegistryImage#build_args}

---

##### `builder`<sup>Optional</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder"></a>

```java
public java.lang.String getBuilder();
```

- *Type:* java.lang.String

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#builder RegistryImage#builder}

---

##### `buildId`<sup>Optional</sup> <a name="buildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId"></a>

```java
public java.lang.String getBuildId();
```

- *Type:* java.lang.String

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#build_id RegistryImage#build_id}

---

##### `buildLogFile`<sup>Optional</sup> <a name="buildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile"></a>

```java
public java.lang.String getBuildLogFile();
```

- *Type:* java.lang.String

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#build_log_file RegistryImage#build_log_file}

---

##### `cacheFrom`<sup>Optional</sup> <a name="cacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom"></a>

```java
public java.util.List<java.lang.String> getCacheFrom();
```

- *Type:* java.util.List<java.lang.String>

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cache_from RegistryImage#cache_from}

---

##### `cacheTo`<sup>Optional</sup> <a name="cacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo"></a>

```java
public java.util.List<java.lang.String> getCacheTo();
```

- *Type:* java.util.List<java.lang.String>

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cache_to RegistryImage#cache_to}

---

##### `cgroupParent`<sup>Optional</sup> <a name="cgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent"></a>

```java
public java.lang.String getCgroupParent();
```

- *Type:* java.lang.String

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cgroup_parent RegistryImage#cgroup_parent}

---

##### `cpuPeriod`<sup>Optional</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod"></a>

```java
public java.lang.Number getCpuPeriod();
```

- *Type:* java.lang.Number

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cpu_period RegistryImage#cpu_period}

---

##### `cpuQuota`<sup>Optional</sup> <a name="cpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota"></a>

```java
public java.lang.Number getCpuQuota();
```

- *Type:* java.lang.Number

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cpu_quota RegistryImage#cpu_quota}

---

##### `cpuSetCpus`<sup>Optional</sup> <a name="cpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus"></a>

```java
public java.lang.String getCpuSetCpus();
```

- *Type:* java.lang.String

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cpu_set_cpus RegistryImage#cpu_set_cpus}

---

##### `cpuSetMems`<sup>Optional</sup> <a name="cpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems"></a>

```java
public java.lang.String getCpuSetMems();
```

- *Type:* java.lang.String

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cpu_set_mems RegistryImage#cpu_set_mems}

---

##### `cpuShares`<sup>Optional</sup> <a name="cpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares"></a>

```java
public java.lang.Number getCpuShares();
```

- *Type:* java.lang.Number

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#cpu_shares RegistryImage#cpu_shares}

---

##### `dockerfile`<sup>Optional</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile"></a>

```java
public java.lang.String getDockerfile();
```

- *Type:* java.lang.String

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#dockerfile RegistryImage#dockerfile}

---

##### `extraHosts`<sup>Optional</sup> <a name="extraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts"></a>

```java
public java.util.List<java.lang.String> getExtraHosts();
```

- *Type:* java.util.List<java.lang.String>

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#extra_hosts RegistryImage#extra_hosts}

---

##### `forceRemove`<sup>Optional</sup> <a name="forceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove"></a>

```java
public java.lang.Boolean|IResolvable getForceRemove();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#force_remove RegistryImage#force_remove}

---

##### `isolation`<sup>Optional</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation"></a>

```java
public java.lang.String getIsolation();
```

- *Type:* java.lang.String

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#isolation RegistryImage#isolation}

---

##### `label`<sup>Optional</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLabel();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#label RegistryImage#label}

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLabels();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#labels RegistryImage#labels}

---

##### `memory`<sup>Optional</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory"></a>

```java
public java.lang.Number getMemory();
```

- *Type:* java.lang.Number

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#memory RegistryImage#memory}

---

##### `memorySwap`<sup>Optional</sup> <a name="memorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap"></a>

```java
public java.lang.Number getMemorySwap();
```

- *Type:* java.lang.Number

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#memory_swap RegistryImage#memory_swap}

---

##### `networkMode`<sup>Optional</sup> <a name="networkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode"></a>

```java
public java.lang.String getNetworkMode();
```

- *Type:* java.lang.String

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#network_mode RegistryImage#network_mode}

---

##### `noCache`<sup>Optional</sup> <a name="noCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache"></a>

```java
public java.lang.Boolean|IResolvable getNoCache();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#no_cache RegistryImage#no_cache}

---

##### `platform`<sup>Optional</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform"></a>

```java
public java.lang.String getPlatform();
```

- *Type:* java.lang.String

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#platform RegistryImage#platform}

---

##### `pullParent`<sup>Optional</sup> <a name="pullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent"></a>

```java
public java.lang.Boolean|IResolvable getPullParent();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#pull_parent RegistryImage#pull_parent}

---

##### `remoteContext`<sup>Optional</sup> <a name="remoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext"></a>

```java
public java.lang.String getRemoteContext();
```

- *Type:* java.lang.String

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#remote_context RegistryImage#remote_context}

---

##### `remove`<sup>Optional</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove"></a>

```java
public java.lang.Boolean|IResolvable getRemove();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#remove RegistryImage#remove}

---

##### `secrets`<sup>Optional</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildSecrets> getSecrets();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>>

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#secrets RegistryImage#secrets}

---

##### `securityOpt`<sup>Optional</sup> <a name="securityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt"></a>

```java
public java.util.List<java.lang.String> getSecurityOpt();
```

- *Type:* java.util.List<java.lang.String>

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#security_opt RegistryImage#security_opt}

---

##### `sessionId`<sup>Optional</sup> <a name="sessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId"></a>

```java
public java.lang.String getSessionId();
```

- *Type:* java.lang.String

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#session_id RegistryImage#session_id}

---

##### `shmSize`<sup>Optional</sup> <a name="shmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize"></a>

```java
public java.lang.Number getShmSize();
```

- *Type:* java.lang.Number

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#shm_size RegistryImage#shm_size}

---

##### `squash`<sup>Optional</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash"></a>

```java
public java.lang.Boolean|IResolvable getSquash();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#squash RegistryImage#squash}

---

##### `suppressOutput`<sup>Optional</sup> <a name="suppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput"></a>

```java
public java.lang.Boolean|IResolvable getSuppressOutput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#suppress_output RegistryImage#suppress_output}

---

##### `tag`<sup>Optional</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag"></a>

```java
public java.util.List<java.lang.String> getTag();
```

- *Type:* java.util.List<java.lang.String>

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#tag RegistryImage#tag}

---

##### `target`<sup>Optional</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target"></a>

```java
public java.lang.String getTarget();
```

- *Type:* java.lang.String

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#target RegistryImage#target}

---

##### `ulimit`<sup>Optional</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildUlimit> getUlimit();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>>

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#ulimit RegistryImage#ulimit}

---

##### `useLegacyBuilder`<sup>Optional</sup> <a name="useLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder"></a>

```java
public java.lang.Boolean|IResolvable getUseLegacyBuilder();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#use_legacy_builder RegistryImage#use_legacy_builder}

---

##### `version`<sup>Optional</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version"></a>

```java
public java.lang.String getVersion();
```

- *Type:* java.lang.String

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#version RegistryImage#version}

---

### RegistryImageBuildAuthConfig <a name="RegistryImageBuildAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildAuthConfig;

RegistryImageBuildAuthConfig.builder()
    .hostName(java.lang.String)
//  .auth(java.lang.String)
//  .email(java.lang.String)
//  .identityToken(java.lang.String)
//  .password(java.lang.String)
//  .registryToken(java.lang.String)
//  .serverAddress(java.lang.String)
//  .userName(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName">hostName</a></code> | <code>java.lang.String</code> | hostname of the registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth">auth</a></code> | <code>java.lang.String</code> | the auth token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email">email</a></code> | <code>java.lang.String</code> | the user emal. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken">identityToken</a></code> | <code>java.lang.String</code> | the identity token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password">password</a></code> | <code>java.lang.String</code> | the registry password. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken">registryToken</a></code> | <code>java.lang.String</code> | the registry token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress">serverAddress</a></code> | <code>java.lang.String</code> | the server address. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName">userName</a></code> | <code>java.lang.String</code> | the registry user name. |

---

##### `hostName`<sup>Required</sup> <a name="hostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName"></a>

```java
public java.lang.String getHostName();
```

- *Type:* java.lang.String

hostname of the registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#host_name RegistryImage#host_name}

---

##### `auth`<sup>Optional</sup> <a name="auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth"></a>

```java
public java.lang.String getAuth();
```

- *Type:* java.lang.String

the auth token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#auth RegistryImage#auth}

---

##### `email`<sup>Optional</sup> <a name="email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email"></a>

```java
public java.lang.String getEmail();
```

- *Type:* java.lang.String

the user emal.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#email RegistryImage#email}

---

##### `identityToken`<sup>Optional</sup> <a name="identityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken"></a>

```java
public java.lang.String getIdentityToken();
```

- *Type:* java.lang.String

the identity token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#identity_token RegistryImage#identity_token}

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password"></a>

```java
public java.lang.String getPassword();
```

- *Type:* java.lang.String

the registry password.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `registryToken`<sup>Optional</sup> <a name="registryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken"></a>

```java
public java.lang.String getRegistryToken();
```

- *Type:* java.lang.String

the registry token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#registry_token RegistryImage#registry_token}

---

##### `serverAddress`<sup>Optional</sup> <a name="serverAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress"></a>

```java
public java.lang.String getServerAddress();
```

- *Type:* java.lang.String

the server address.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#server_address RegistryImage#server_address}

---

##### `userName`<sup>Optional</sup> <a name="userName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName"></a>

```java
public java.lang.String getUserName();
```

- *Type:* java.lang.String

the registry user name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#user_name RegistryImage#user_name}

---

### RegistryImageBuildSecrets <a name="RegistryImageBuildSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildSecrets;

RegistryImageBuildSecrets.builder()
    .id(java.lang.String)
//  .env(java.lang.String)
//  .src(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id">id</a></code> | <code>java.lang.String</code> | ID of the secret. By default, secrets are mounted to /run/secrets/<id>. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env">env</a></code> | <code>java.lang.String</code> | Environment variable source of the secret. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src">src</a></code> | <code>java.lang.String</code> | File source of the secret. Takes precedence over `env`. |

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

ID of the secret. By default, secrets are mounted to /run/secrets/<id>.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#id RegistryImage#id}

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `env`<sup>Optional</sup> <a name="env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env"></a>

```java
public java.lang.String getEnv();
```

- *Type:* java.lang.String

Environment variable source of the secret.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#env RegistryImage#env}

---

##### `src`<sup>Optional</sup> <a name="src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src"></a>

```java
public java.lang.String getSrc();
```

- *Type:* java.lang.String

File source of the secret. Takes precedence over `env`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#src RegistryImage#src}

---

### RegistryImageBuildUlimit <a name="RegistryImageBuildUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildUlimit;

RegistryImageBuildUlimit.builder()
    .hard(java.lang.Number)
    .name(java.lang.String)
    .soft(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard">hard</a></code> | <code>java.lang.Number</code> | soft limit. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name">name</a></code> | <code>java.lang.String</code> | type of ulimit, e.g. `nofile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft">soft</a></code> | <code>java.lang.Number</code> | hard limit. |

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard"></a>

```java
public java.lang.Number getHard();
```

- *Type:* java.lang.Number

soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#hard RegistryImage#hard}

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

type of ulimit, e.g. `nofile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft"></a>

```java
public java.lang.Number getSoft();
```

- *Type:* java.lang.Number

hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#soft RegistryImage#soft}

---

### RegistryImageConfig <a name="RegistryImageConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageConfig;

RegistryImageConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .name(java.lang.String)
//  .authConfig(RegistryImageAuthConfig)
//  .buildAttribute(RegistryImageBuild)
//  .id(java.lang.String)
//  .insecureSkipVerify(java.lang.Boolean|IResolvable)
//  .keepRemotely(java.lang.Boolean|IResolvable)
//  .timeouts(RegistryImageTimeouts)
//  .triggers(java.util.Map<java.lang.String, java.lang.String>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name">name</a></code> | <code>java.lang.String</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute">buildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely">keepRemotely</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers">triggers</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `authConfig`<sup>Optional</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig"></a>

```java
public RegistryImageAuthConfig getAuthConfig();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `buildAttribute`<sup>Optional</sup> <a name="buildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute"></a>

```java
public RegistryImageBuild getBuildAttribute();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `insecureSkipVerify`<sup>Optional</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify"></a>

```java
public java.lang.Boolean|IResolvable getInsecureSkipVerify();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `keepRemotely`<sup>Optional</sup> <a name="keepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely"></a>

```java
public java.lang.Boolean|IResolvable getKeepRemotely();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts"></a>

```java
public RegistryImageTimeouts getTimeouts();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `triggers`<sup>Optional</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getTriggers();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

### RegistryImageTimeouts <a name="RegistryImageTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageTimeouts;

RegistryImageTimeouts.builder()
//  .create(java.lang.String)
//  .delete(java.lang.String)
//  .update(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create">create</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#create RegistryImage#create}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete">delete</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#delete RegistryImage#delete}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update">update</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#update RegistryImage#update}. |

---

##### `create`<sup>Optional</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create"></a>

```java
public java.lang.String getCreate();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#create RegistryImage#create}.

---

##### `delete`<sup>Optional</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete"></a>

```java
public java.lang.String getDelete();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#delete RegistryImage#delete}.

---

##### `update`<sup>Optional</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update"></a>

```java
public java.lang.String getUpdate();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/resources/registry_image#update RegistryImage#update}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistryImageAuthConfigOutputReference <a name="RegistryImageAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageAuthConfigOutputReference;

new RegistryImageAuthConfigOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword">resetPassword</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername">resetUsername</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetPassword` <a name="resetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword"></a>

```java
public void resetPassword()
```

##### `resetUsername` <a name="resetUsername" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername"></a>

```java
public void resetUsername()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput">addressInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput">passwordInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput">usernameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address">address</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password">password</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username">username</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `addressInput`<sup>Optional</sup> <a name="addressInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput"></a>

```java
public java.lang.String getAddressInput();
```

- *Type:* java.lang.String

---

##### `passwordInput`<sup>Optional</sup> <a name="passwordInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput"></a>

```java
public java.lang.String getPasswordInput();
```

- *Type:* java.lang.String

---

##### `usernameInput`<sup>Optional</sup> <a name="usernameInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput"></a>

```java
public java.lang.String getUsernameInput();
```

- *Type:* java.lang.String

---

##### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address"></a>

```java
public java.lang.String getAddress();
```

- *Type:* java.lang.String

---

##### `password`<sup>Required</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password"></a>

```java
public java.lang.String getPassword();
```

- *Type:* java.lang.String

---

##### `username`<sup>Required</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username"></a>

```java
public java.lang.String getUsername();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue"></a>

```java
public RegistryImageAuthConfig getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---


### RegistryImageBuildAuthConfigList <a name="RegistryImageBuildAuthConfigList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildAuthConfigList;

new RegistryImageBuildAuthConfigList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get"></a>

```java
public RegistryImageBuildAuthConfigOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildAuthConfig> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>>

---


### RegistryImageBuildAuthConfigOutputReference <a name="RegistryImageBuildAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildAuthConfigOutputReference;

new RegistryImageBuildAuthConfigOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth">resetAuth</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail">resetEmail</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken">resetIdentityToken</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword">resetPassword</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken">resetRegistryToken</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress">resetServerAddress</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName">resetUserName</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAuth` <a name="resetAuth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth"></a>

```java
public void resetAuth()
```

##### `resetEmail` <a name="resetEmail" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail"></a>

```java
public void resetEmail()
```

##### `resetIdentityToken` <a name="resetIdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken"></a>

```java
public void resetIdentityToken()
```

##### `resetPassword` <a name="resetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword"></a>

```java
public void resetPassword()
```

##### `resetRegistryToken` <a name="resetRegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken"></a>

```java
public void resetRegistryToken()
```

##### `resetServerAddress` <a name="resetServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress"></a>

```java
public void resetServerAddress()
```

##### `resetUserName` <a name="resetUserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName"></a>

```java
public void resetUserName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput">authInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput">emailInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput">hostNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput">identityTokenInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput">passwordInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput">registryTokenInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput">serverAddressInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput">userNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth">auth</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email">email</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName">hostName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken">identityToken</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password">password</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken">registryToken</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress">serverAddress</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName">userName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `authInput`<sup>Optional</sup> <a name="authInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput"></a>

```java
public java.lang.String getAuthInput();
```

- *Type:* java.lang.String

---

##### `emailInput`<sup>Optional</sup> <a name="emailInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput"></a>

```java
public java.lang.String getEmailInput();
```

- *Type:* java.lang.String

---

##### `hostNameInput`<sup>Optional</sup> <a name="hostNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput"></a>

```java
public java.lang.String getHostNameInput();
```

- *Type:* java.lang.String

---

##### `identityTokenInput`<sup>Optional</sup> <a name="identityTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput"></a>

```java
public java.lang.String getIdentityTokenInput();
```

- *Type:* java.lang.String

---

##### `passwordInput`<sup>Optional</sup> <a name="passwordInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput"></a>

```java
public java.lang.String getPasswordInput();
```

- *Type:* java.lang.String

---

##### `registryTokenInput`<sup>Optional</sup> <a name="registryTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput"></a>

```java
public java.lang.String getRegistryTokenInput();
```

- *Type:* java.lang.String

---

##### `serverAddressInput`<sup>Optional</sup> <a name="serverAddressInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput"></a>

```java
public java.lang.String getServerAddressInput();
```

- *Type:* java.lang.String

---

##### `userNameInput`<sup>Optional</sup> <a name="userNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput"></a>

```java
public java.lang.String getUserNameInput();
```

- *Type:* java.lang.String

---

##### `auth`<sup>Required</sup> <a name="auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth"></a>

```java
public java.lang.String getAuth();
```

- *Type:* java.lang.String

---

##### `email`<sup>Required</sup> <a name="email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email"></a>

```java
public java.lang.String getEmail();
```

- *Type:* java.lang.String

---

##### `hostName`<sup>Required</sup> <a name="hostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName"></a>

```java
public java.lang.String getHostName();
```

- *Type:* java.lang.String

---

##### `identityToken`<sup>Required</sup> <a name="identityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken"></a>

```java
public java.lang.String getIdentityToken();
```

- *Type:* java.lang.String

---

##### `password`<sup>Required</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password"></a>

```java
public java.lang.String getPassword();
```

- *Type:* java.lang.String

---

##### `registryToken`<sup>Required</sup> <a name="registryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken"></a>

```java
public java.lang.String getRegistryToken();
```

- *Type:* java.lang.String

---

##### `serverAddress`<sup>Required</sup> <a name="serverAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress"></a>

```java
public java.lang.String getServerAddress();
```

- *Type:* java.lang.String

---

##### `userName`<sup>Required</sup> <a name="userName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName"></a>

```java
public java.lang.String getUserName();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue"></a>

```java
public IResolvable|RegistryImageBuildAuthConfig getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>

---


### RegistryImageBuildOutputReference <a name="RegistryImageBuildOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildOutputReference;

new RegistryImageBuildOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig">putAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets">putSecrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit">putUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts">resetAdditionalContexts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig">resetAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs">resetBuildArgs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder">resetBuilder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId">resetBuildId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile">resetBuildLogFile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom">resetCacheFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo">resetCacheTo</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent">resetCgroupParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod">resetCpuPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota">resetCpuQuota</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus">resetCpuSetCpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems">resetCpuSetMems</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares">resetCpuShares</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile">resetDockerfile</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts">resetExtraHosts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove">resetForceRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation">resetIsolation</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel">resetLabel</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels">resetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory">resetMemory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap">resetMemorySwap</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode">resetNetworkMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache">resetNoCache</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform">resetPlatform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent">resetPullParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext">resetRemoteContext</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove">resetRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets">resetSecrets</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt">resetSecurityOpt</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId">resetSessionId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize">resetShmSize</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash">resetSquash</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput">resetSuppressOutput</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag">resetTag</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget">resetTarget</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit">resetUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder">resetUseLegacyBuilder</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion">resetVersion</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putAuthConfig` <a name="putAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig"></a>

```java
public void putAuthConfig(IResolvable|java.util.List<RegistryImageBuildAuthConfig> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>>

---

##### `putSecrets` <a name="putSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets"></a>

```java
public void putSecrets(IResolvable|java.util.List<RegistryImageBuildSecrets> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>>

---

##### `putUlimit` <a name="putUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit"></a>

```java
public void putUlimit(IResolvable|java.util.List<RegistryImageBuildUlimit> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>>

---

##### `resetAdditionalContexts` <a name="resetAdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts"></a>

```java
public void resetAdditionalContexts()
```

##### `resetAuthConfig` <a name="resetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig"></a>

```java
public void resetAuthConfig()
```

##### `resetBuildArgs` <a name="resetBuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs"></a>

```java
public void resetBuildArgs()
```

##### `resetBuilder` <a name="resetBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder"></a>

```java
public void resetBuilder()
```

##### `resetBuildId` <a name="resetBuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId"></a>

```java
public void resetBuildId()
```

##### `resetBuildLogFile` <a name="resetBuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile"></a>

```java
public void resetBuildLogFile()
```

##### `resetCacheFrom` <a name="resetCacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom"></a>

```java
public void resetCacheFrom()
```

##### `resetCacheTo` <a name="resetCacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo"></a>

```java
public void resetCacheTo()
```

##### `resetCgroupParent` <a name="resetCgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent"></a>

```java
public void resetCgroupParent()
```

##### `resetCpuPeriod` <a name="resetCpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod"></a>

```java
public void resetCpuPeriod()
```

##### `resetCpuQuota` <a name="resetCpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota"></a>

```java
public void resetCpuQuota()
```

##### `resetCpuSetCpus` <a name="resetCpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus"></a>

```java
public void resetCpuSetCpus()
```

##### `resetCpuSetMems` <a name="resetCpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems"></a>

```java
public void resetCpuSetMems()
```

##### `resetCpuShares` <a name="resetCpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares"></a>

```java
public void resetCpuShares()
```

##### `resetDockerfile` <a name="resetDockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile"></a>

```java
public void resetDockerfile()
```

##### `resetExtraHosts` <a name="resetExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts"></a>

```java
public void resetExtraHosts()
```

##### `resetForceRemove` <a name="resetForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove"></a>

```java
public void resetForceRemove()
```

##### `resetIsolation` <a name="resetIsolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation"></a>

```java
public void resetIsolation()
```

##### `resetLabel` <a name="resetLabel" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel"></a>

```java
public void resetLabel()
```

##### `resetLabels` <a name="resetLabels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels"></a>

```java
public void resetLabels()
```

##### `resetMemory` <a name="resetMemory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory"></a>

```java
public void resetMemory()
```

##### `resetMemorySwap` <a name="resetMemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap"></a>

```java
public void resetMemorySwap()
```

##### `resetNetworkMode` <a name="resetNetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode"></a>

```java
public void resetNetworkMode()
```

##### `resetNoCache` <a name="resetNoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache"></a>

```java
public void resetNoCache()
```

##### `resetPlatform` <a name="resetPlatform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform"></a>

```java
public void resetPlatform()
```

##### `resetPullParent` <a name="resetPullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent"></a>

```java
public void resetPullParent()
```

##### `resetRemoteContext` <a name="resetRemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext"></a>

```java
public void resetRemoteContext()
```

##### `resetRemove` <a name="resetRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove"></a>

```java
public void resetRemove()
```

##### `resetSecrets` <a name="resetSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets"></a>

```java
public void resetSecrets()
```

##### `resetSecurityOpt` <a name="resetSecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt"></a>

```java
public void resetSecurityOpt()
```

##### `resetSessionId` <a name="resetSessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId"></a>

```java
public void resetSessionId()
```

##### `resetShmSize` <a name="resetShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize"></a>

```java
public void resetShmSize()
```

##### `resetSquash` <a name="resetSquash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash"></a>

```java
public void resetSquash()
```

##### `resetSuppressOutput` <a name="resetSuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput"></a>

```java
public void resetSuppressOutput()
```

##### `resetTag` <a name="resetTag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag"></a>

```java
public void resetTag()
```

##### `resetTarget` <a name="resetTarget" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget"></a>

```java
public void resetTarget()
```

##### `resetUlimit` <a name="resetUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit"></a>

```java
public void resetUlimit()
```

##### `resetUseLegacyBuilder` <a name="resetUseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder"></a>

```java
public void resetUseLegacyBuilder()
```

##### `resetVersion` <a name="resetVersion" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion"></a>

```java
public void resetVersion()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets">secrets</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit">ulimit</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput">additionalContextsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput">authConfigInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput">buildArgsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput">builderInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput">buildIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput">buildLogFileInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput">cacheFromInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput">cacheToInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput">cgroupParentInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput">contextInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput">cpuPeriodInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput">cpuQuotaInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput">cpuSetCpusInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput">cpuSetMemsInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput">cpuSharesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput">dockerfileInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput">extraHostsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput">forceRemoveInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput">isolationInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput">labelInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput">labelsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput">memoryInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput">memorySwapInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput">networkModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput">noCacheInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput">platformInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput">pullParentInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput">remoteContextInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput">removeInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput">secretsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput">securityOptInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput">sessionIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput">shmSizeInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput">squashInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput">suppressOutputInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput">tagInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput">targetInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput">ulimitInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput">useLegacyBuilderInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput">versionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts">additionalContexts</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs">buildArgs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder">builder</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId">buildId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile">buildLogFile</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom">cacheFrom</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo">cacheTo</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent">cgroupParent</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context">context</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod">cpuPeriod</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota">cpuQuota</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus">cpuSetCpus</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems">cpuSetMems</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares">cpuShares</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile">dockerfile</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts">extraHosts</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove">forceRemove</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation">isolation</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label">label</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels">labels</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory">memory</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap">memorySwap</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode">networkMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache">noCache</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform">platform</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent">pullParent</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext">remoteContext</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove">remove</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt">securityOpt</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId">sessionId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize">shmSize</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash">squash</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput">suppressOutput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag">tag</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target">target</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder">useLegacyBuilder</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version">version</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `authConfig`<sup>Required</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig"></a>

```java
public RegistryImageBuildAuthConfigList getAuthConfig();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a>

---

##### `secrets`<sup>Required</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets"></a>

```java
public RegistryImageBuildSecretsList getSecrets();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a>

---

##### `ulimit`<sup>Required</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit"></a>

```java
public RegistryImageBuildUlimitList getUlimit();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a>

---

##### `additionalContextsInput`<sup>Optional</sup> <a name="additionalContextsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput"></a>

```java
public java.util.List<java.lang.String> getAdditionalContextsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `authConfigInput`<sup>Optional</sup> <a name="authConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildAuthConfig> getAuthConfigInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>>

---

##### `buildArgsInput`<sup>Optional</sup> <a name="buildArgsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getBuildArgsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `builderInput`<sup>Optional</sup> <a name="builderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput"></a>

```java
public java.lang.String getBuilderInput();
```

- *Type:* java.lang.String

---

##### `buildIdInput`<sup>Optional</sup> <a name="buildIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput"></a>

```java
public java.lang.String getBuildIdInput();
```

- *Type:* java.lang.String

---

##### `buildLogFileInput`<sup>Optional</sup> <a name="buildLogFileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput"></a>

```java
public java.lang.String getBuildLogFileInput();
```

- *Type:* java.lang.String

---

##### `cacheFromInput`<sup>Optional</sup> <a name="cacheFromInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput"></a>

```java
public java.util.List<java.lang.String> getCacheFromInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `cacheToInput`<sup>Optional</sup> <a name="cacheToInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput"></a>

```java
public java.util.List<java.lang.String> getCacheToInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `cgroupParentInput`<sup>Optional</sup> <a name="cgroupParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput"></a>

```java
public java.lang.String getCgroupParentInput();
```

- *Type:* java.lang.String

---

##### `contextInput`<sup>Optional</sup> <a name="contextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput"></a>

```java
public java.lang.String getContextInput();
```

- *Type:* java.lang.String

---

##### `cpuPeriodInput`<sup>Optional</sup> <a name="cpuPeriodInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput"></a>

```java
public java.lang.Number getCpuPeriodInput();
```

- *Type:* java.lang.Number

---

##### `cpuQuotaInput`<sup>Optional</sup> <a name="cpuQuotaInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput"></a>

```java
public java.lang.Number getCpuQuotaInput();
```

- *Type:* java.lang.Number

---

##### `cpuSetCpusInput`<sup>Optional</sup> <a name="cpuSetCpusInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput"></a>

```java
public java.lang.String getCpuSetCpusInput();
```

- *Type:* java.lang.String

---

##### `cpuSetMemsInput`<sup>Optional</sup> <a name="cpuSetMemsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput"></a>

```java
public java.lang.String getCpuSetMemsInput();
```

- *Type:* java.lang.String

---

##### `cpuSharesInput`<sup>Optional</sup> <a name="cpuSharesInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput"></a>

```java
public java.lang.Number getCpuSharesInput();
```

- *Type:* java.lang.Number

---

##### `dockerfileInput`<sup>Optional</sup> <a name="dockerfileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput"></a>

```java
public java.lang.String getDockerfileInput();
```

- *Type:* java.lang.String

---

##### `extraHostsInput`<sup>Optional</sup> <a name="extraHostsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput"></a>

```java
public java.util.List<java.lang.String> getExtraHostsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forceRemoveInput`<sup>Optional</sup> <a name="forceRemoveInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput"></a>

```java
public java.lang.Boolean|IResolvable getForceRemoveInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `isolationInput`<sup>Optional</sup> <a name="isolationInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput"></a>

```java
public java.lang.String getIsolationInput();
```

- *Type:* java.lang.String

---

##### `labelInput`<sup>Optional</sup> <a name="labelInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLabelInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `labelsInput`<sup>Optional</sup> <a name="labelsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLabelsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `memoryInput`<sup>Optional</sup> <a name="memoryInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput"></a>

```java
public java.lang.Number getMemoryInput();
```

- *Type:* java.lang.Number

---

##### `memorySwapInput`<sup>Optional</sup> <a name="memorySwapInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput"></a>

```java
public java.lang.Number getMemorySwapInput();
```

- *Type:* java.lang.Number

---

##### `networkModeInput`<sup>Optional</sup> <a name="networkModeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput"></a>

```java
public java.lang.String getNetworkModeInput();
```

- *Type:* java.lang.String

---

##### `noCacheInput`<sup>Optional</sup> <a name="noCacheInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput"></a>

```java
public java.lang.Boolean|IResolvable getNoCacheInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `platformInput`<sup>Optional</sup> <a name="platformInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput"></a>

```java
public java.lang.String getPlatformInput();
```

- *Type:* java.lang.String

---

##### `pullParentInput`<sup>Optional</sup> <a name="pullParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput"></a>

```java
public java.lang.Boolean|IResolvable getPullParentInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `remoteContextInput`<sup>Optional</sup> <a name="remoteContextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput"></a>

```java
public java.lang.String getRemoteContextInput();
```

- *Type:* java.lang.String

---

##### `removeInput`<sup>Optional</sup> <a name="removeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput"></a>

```java
public java.lang.Boolean|IResolvable getRemoveInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `secretsInput`<sup>Optional</sup> <a name="secretsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildSecrets> getSecretsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>>

---

##### `securityOptInput`<sup>Optional</sup> <a name="securityOptInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput"></a>

```java
public java.util.List<java.lang.String> getSecurityOptInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `sessionIdInput`<sup>Optional</sup> <a name="sessionIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput"></a>

```java
public java.lang.String getSessionIdInput();
```

- *Type:* java.lang.String

---

##### `shmSizeInput`<sup>Optional</sup> <a name="shmSizeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput"></a>

```java
public java.lang.Number getShmSizeInput();
```

- *Type:* java.lang.Number

---

##### `squashInput`<sup>Optional</sup> <a name="squashInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput"></a>

```java
public java.lang.Boolean|IResolvable getSquashInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `suppressOutputInput`<sup>Optional</sup> <a name="suppressOutputInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput"></a>

```java
public java.lang.Boolean|IResolvable getSuppressOutputInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `tagInput`<sup>Optional</sup> <a name="tagInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput"></a>

```java
public java.util.List<java.lang.String> getTagInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `targetInput`<sup>Optional</sup> <a name="targetInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput"></a>

```java
public java.lang.String getTargetInput();
```

- *Type:* java.lang.String

---

##### `ulimitInput`<sup>Optional</sup> <a name="ulimitInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildUlimit> getUlimitInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>>

---

##### `useLegacyBuilderInput`<sup>Optional</sup> <a name="useLegacyBuilderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput"></a>

```java
public java.lang.Boolean|IResolvable getUseLegacyBuilderInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `versionInput`<sup>Optional</sup> <a name="versionInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput"></a>

```java
public java.lang.String getVersionInput();
```

- *Type:* java.lang.String

---

##### `additionalContexts`<sup>Required</sup> <a name="additionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts"></a>

```java
public java.util.List<java.lang.String> getAdditionalContexts();
```

- *Type:* java.util.List<java.lang.String>

---

##### `buildArgs`<sup>Required</sup> <a name="buildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getBuildArgs();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `builder`<sup>Required</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder"></a>

```java
public java.lang.String getBuilder();
```

- *Type:* java.lang.String

---

##### `buildId`<sup>Required</sup> <a name="buildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId"></a>

```java
public java.lang.String getBuildId();
```

- *Type:* java.lang.String

---

##### `buildLogFile`<sup>Required</sup> <a name="buildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile"></a>

```java
public java.lang.String getBuildLogFile();
```

- *Type:* java.lang.String

---

##### `cacheFrom`<sup>Required</sup> <a name="cacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom"></a>

```java
public java.util.List<java.lang.String> getCacheFrom();
```

- *Type:* java.util.List<java.lang.String>

---

##### `cacheTo`<sup>Required</sup> <a name="cacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo"></a>

```java
public java.util.List<java.lang.String> getCacheTo();
```

- *Type:* java.util.List<java.lang.String>

---

##### `cgroupParent`<sup>Required</sup> <a name="cgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent"></a>

```java
public java.lang.String getCgroupParent();
```

- *Type:* java.lang.String

---

##### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context"></a>

```java
public java.lang.String getContext();
```

- *Type:* java.lang.String

---

##### `cpuPeriod`<sup>Required</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod"></a>

```java
public java.lang.Number getCpuPeriod();
```

- *Type:* java.lang.Number

---

##### `cpuQuota`<sup>Required</sup> <a name="cpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota"></a>

```java
public java.lang.Number getCpuQuota();
```

- *Type:* java.lang.Number

---

##### `cpuSetCpus`<sup>Required</sup> <a name="cpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus"></a>

```java
public java.lang.String getCpuSetCpus();
```

- *Type:* java.lang.String

---

##### `cpuSetMems`<sup>Required</sup> <a name="cpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems"></a>

```java
public java.lang.String getCpuSetMems();
```

- *Type:* java.lang.String

---

##### `cpuShares`<sup>Required</sup> <a name="cpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares"></a>

```java
public java.lang.Number getCpuShares();
```

- *Type:* java.lang.Number

---

##### `dockerfile`<sup>Required</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile"></a>

```java
public java.lang.String getDockerfile();
```

- *Type:* java.lang.String

---

##### `extraHosts`<sup>Required</sup> <a name="extraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts"></a>

```java
public java.util.List<java.lang.String> getExtraHosts();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forceRemove`<sup>Required</sup> <a name="forceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove"></a>

```java
public java.lang.Boolean|IResolvable getForceRemove();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `isolation`<sup>Required</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation"></a>

```java
public java.lang.String getIsolation();
```

- *Type:* java.lang.String

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLabel();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLabels();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `memory`<sup>Required</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory"></a>

```java
public java.lang.Number getMemory();
```

- *Type:* java.lang.Number

---

##### `memorySwap`<sup>Required</sup> <a name="memorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap"></a>

```java
public java.lang.Number getMemorySwap();
```

- *Type:* java.lang.Number

---

##### `networkMode`<sup>Required</sup> <a name="networkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode"></a>

```java
public java.lang.String getNetworkMode();
```

- *Type:* java.lang.String

---

##### `noCache`<sup>Required</sup> <a name="noCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache"></a>

```java
public java.lang.Boolean|IResolvable getNoCache();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `platform`<sup>Required</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform"></a>

```java
public java.lang.String getPlatform();
```

- *Type:* java.lang.String

---

##### `pullParent`<sup>Required</sup> <a name="pullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent"></a>

```java
public java.lang.Boolean|IResolvable getPullParent();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `remoteContext`<sup>Required</sup> <a name="remoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext"></a>

```java
public java.lang.String getRemoteContext();
```

- *Type:* java.lang.String

---

##### `remove`<sup>Required</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove"></a>

```java
public java.lang.Boolean|IResolvable getRemove();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `securityOpt`<sup>Required</sup> <a name="securityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt"></a>

```java
public java.util.List<java.lang.String> getSecurityOpt();
```

- *Type:* java.util.List<java.lang.String>

---

##### `sessionId`<sup>Required</sup> <a name="sessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId"></a>

```java
public java.lang.String getSessionId();
```

- *Type:* java.lang.String

---

##### `shmSize`<sup>Required</sup> <a name="shmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize"></a>

```java
public java.lang.Number getShmSize();
```

- *Type:* java.lang.Number

---

##### `squash`<sup>Required</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash"></a>

```java
public java.lang.Boolean|IResolvable getSquash();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `suppressOutput`<sup>Required</sup> <a name="suppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput"></a>

```java
public java.lang.Boolean|IResolvable getSuppressOutput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `tag`<sup>Required</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag"></a>

```java
public java.util.List<java.lang.String> getTag();
```

- *Type:* java.util.List<java.lang.String>

---

##### `target`<sup>Required</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target"></a>

```java
public java.lang.String getTarget();
```

- *Type:* java.lang.String

---

##### `useLegacyBuilder`<sup>Required</sup> <a name="useLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder"></a>

```java
public java.lang.Boolean|IResolvable getUseLegacyBuilder();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `version`<sup>Required</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version"></a>

```java
public java.lang.String getVersion();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue"></a>

```java
public RegistryImageBuild getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---


### RegistryImageBuildSecretsList <a name="RegistryImageBuildSecretsList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildSecretsList;

new RegistryImageBuildSecretsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get"></a>

```java
public RegistryImageBuildSecretsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildSecrets> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>>

---


### RegistryImageBuildSecretsOutputReference <a name="RegistryImageBuildSecretsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildSecretsOutputReference;

new RegistryImageBuildSecretsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv">resetEnv</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc">resetSrc</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetEnv` <a name="resetEnv" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv"></a>

```java
public void resetEnv()
```

##### `resetSrc` <a name="resetSrc" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc"></a>

```java
public void resetSrc()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput">envInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput">srcInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env">env</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src">src</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `envInput`<sup>Optional</sup> <a name="envInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput"></a>

```java
public java.lang.String getEnvInput();
```

- *Type:* java.lang.String

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `srcInput`<sup>Optional</sup> <a name="srcInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput"></a>

```java
public java.lang.String getSrcInput();
```

- *Type:* java.lang.String

---

##### `env`<sup>Required</sup> <a name="env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env"></a>

```java
public java.lang.String getEnv();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `src`<sup>Required</sup> <a name="src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src"></a>

```java
public java.lang.String getSrc();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue"></a>

```java
public IResolvable|RegistryImageBuildSecrets getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>

---


### RegistryImageBuildUlimitList <a name="RegistryImageBuildUlimitList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildUlimitList;

new RegistryImageBuildUlimitList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get"></a>

```java
public RegistryImageBuildUlimitOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue"></a>

```java
public IResolvable|java.util.List<RegistryImageBuildUlimit> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>>

---


### RegistryImageBuildUlimitOutputReference <a name="RegistryImageBuildUlimitOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageBuildUlimitOutputReference;

new RegistryImageBuildUlimitOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput">hardInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput">softInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard">hard</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft">soft</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `hardInput`<sup>Optional</sup> <a name="hardInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput"></a>

```java
public java.lang.Number getHardInput();
```

- *Type:* java.lang.Number

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `softInput`<sup>Optional</sup> <a name="softInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput"></a>

```java
public java.lang.Number getSoftInput();
```

- *Type:* java.lang.Number

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard"></a>

```java
public java.lang.Number getHard();
```

- *Type:* java.lang.Number

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft"></a>

```java
public java.lang.Number getSoft();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue"></a>

```java
public IResolvable|RegistryImageBuildUlimit getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>

---


### RegistryImageTimeoutsOutputReference <a name="RegistryImageTimeoutsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.registry_image.RegistryImageTimeoutsOutputReference;

new RegistryImageTimeoutsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate">resetCreate</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete">resetDelete</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate">resetUpdate</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetCreate` <a name="resetCreate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate"></a>

```java
public void resetCreate()
```

##### `resetDelete` <a name="resetDelete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete"></a>

```java
public void resetDelete()
```

##### `resetUpdate` <a name="resetUpdate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate"></a>

```java
public void resetUpdate()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput">createInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput">deleteInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput">updateInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create">create</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete">delete</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update">update</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `createInput`<sup>Optional</sup> <a name="createInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput"></a>

```java
public java.lang.String getCreateInput();
```

- *Type:* java.lang.String

---

##### `deleteInput`<sup>Optional</sup> <a name="deleteInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput"></a>

```java
public java.lang.String getDeleteInput();
```

- *Type:* java.lang.String

---

##### `updateInput`<sup>Optional</sup> <a name="updateInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput"></a>

```java
public java.lang.String getUpdateInput();
```

- *Type:* java.lang.String

---

##### `create`<sup>Required</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create"></a>

```java
public java.lang.String getCreate();
```

- *Type:* java.lang.String

---

##### `delete`<sup>Required</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete"></a>

```java
public java.lang.String getDelete();
```

- *Type:* java.lang.String

---

##### `update`<sup>Required</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update"></a>

```java
public java.lang.String getUpdate();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue"></a>

```java
public IResolvable|RegistryImageTimeouts getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---



