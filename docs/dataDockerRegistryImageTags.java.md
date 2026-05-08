# `dataDockerRegistryImageTags` Submodule <a name="`dataDockerRegistryImageTags` Submodule" id="@cdktn/provider-docker.dataDockerRegistryImageTags"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataDockerRegistryImageTags <a name="DataDockerRegistryImageTags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags docker_registry_image_tags}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer"></a>

```java
import io.cdktn.providers.docker.data_docker_registry_image_tags.DataDockerRegistryImageTags;

DataDockerRegistryImageTags.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .name(java.lang.String)
//  .insecureSkipVerify(java.lang.Boolean|IResolvable)
//  .strictSemver(java.lang.Boolean|IResolvable)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.insecureSkipVerify">insecureSkipVerify</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.strictSemver">strictSemver</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, only stable semantic version tags are returned. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.name"></a>

- *Type:* java.lang.String

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `insecureSkipVerify`<sup>Optional</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.insecureSkipVerify"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `strictSemver`<sup>Optional</sup> <a name="strictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.strictSemver"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform">toHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify">resetInsecureSkipVerify</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver">resetStrictSemver</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `resetInsecureSkipVerify` <a name="resetInsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify"></a>

```java
public void resetInsecureSkipVerify()
```

##### `resetStrictSemver` <a name="resetStrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver"></a>

```java
public void resetStrictSemver()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct"></a>

```java
import io.cdktn.providers.docker.data_docker_registry_image_tags.DataDockerRegistryImageTags;

DataDockerRegistryImageTags.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement"></a>

```java
import io.cdktn.providers.docker.data_docker_registry_image_tags.DataDockerRegistryImageTags;

DataDockerRegistryImageTags.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource"></a>

```java
import io.cdktn.providers.docker.data_docker_registry_image_tags.DataDockerRegistryImageTags;

DataDockerRegistryImageTags.isTerraformDataSource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport"></a>

```java
import io.cdktn.providers.docker.data_docker_registry_image_tags.DataDockerRegistryImageTags;

DataDockerRegistryImageTags.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),DataDockerRegistryImageTags.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the DataDockerRegistryImageTags to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing DataDockerRegistryImageTags that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the DataDockerRegistryImageTags to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags">tags</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput">insecureSkipVerifyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput">strictSemverInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver">strictSemver</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `tags`<sup>Required</sup> <a name="tags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags"></a>

```java
public java.util.List<java.lang.String> getTags();
```

- *Type:* java.util.List<java.lang.String>

---

##### `insecureSkipVerifyInput`<sup>Optional</sup> <a name="insecureSkipVerifyInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput"></a>

```java
public java.lang.Boolean|IResolvable getInsecureSkipVerifyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `strictSemverInput`<sup>Optional</sup> <a name="strictSemverInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput"></a>

```java
public java.lang.Boolean|IResolvable getStrictSemverInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `insecureSkipVerify`<sup>Required</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify"></a>

```java
public java.lang.Boolean|IResolvable getInsecureSkipVerify();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `strictSemver`<sup>Required</sup> <a name="strictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver"></a>

```java
public java.lang.Boolean|IResolvable getStrictSemver();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### DataDockerRegistryImageTagsConfig <a name="DataDockerRegistryImageTagsConfig" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.data_docker_registry_image_tags.DataDockerRegistryImageTagsConfig;

DataDockerRegistryImageTagsConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .name(java.lang.String)
//  .insecureSkipVerify(java.lang.Boolean|IResolvable)
//  .strictSemver(java.lang.Boolean|IResolvable)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name">name</a></code> | <code>java.lang.String</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver">strictSemver</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, only stable semantic version tags are returned. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `insecureSkipVerify`<sup>Optional</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify"></a>

```java
public java.lang.Boolean|IResolvable getInsecureSkipVerify();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `strictSemver`<sup>Optional</sup> <a name="strictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver"></a>

```java
public java.lang.Boolean|IResolvable getStrictSemver();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.2.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---



