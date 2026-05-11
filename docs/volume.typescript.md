# `volume` Submodule <a name="`volume` Submodule" id="@cdktn/provider-docker.volume"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Volume <a name="Volume" id="@cdktn/provider-docker.volume.Volume"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume docker_volume}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.Volume.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

new volume.Volume(scope: Construct, id: string, config?: VolumeConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeConfig">VolumeConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="config" id="@cdktn/provider-docker.volume.Volume.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeConfig">VolumeConfig</a>

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

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.volume.Volume.with"></a>

```typescript
public with(mixins: ...IMixin[]): IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.volume.Volume.with.parameter.mixins"></a>

- *Type:* ...constructs.IMixin[]

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.volume.Volume.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.volume.Volume.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.volume.Volume.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.volume.Volume.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.volume.Volume.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.volume.Volume.toHclTerraform"></a>

```typescript
public toHclTerraform(): any
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.volume.Volume.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.volume.Volume.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.volume.Volume.addMoveTarget"></a>

```typescript
public addMoveTarget(moveTarget: string): void
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.volume.Volume.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.volume.Volume.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.volume.Volume.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.volume.Volume.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.volume.Volume.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.volume.Volume.hasResourceMove"></a>

```typescript
public hasResourceMove(): TerraformResourceMoveByTarget | TerraformResourceMoveById
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.volume.Volume.importFrom"></a>

```typescript
public importFrom(id: string, provider?: TerraformProvider): void
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.importFrom.parameter.id"></a>

- *Type:* string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.importFrom.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.volume.Volume.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.Volume.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.volume.Volume.moveFromId"></a>

```typescript
public moveFromId(id: string): void
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.volume.Volume.moveTo"></a>

```typescript
public moveTo(moveTarget: string, index?: string | number): void
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.volume.Volume.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.volume.Volume.moveTo.parameter.index"></a>

- *Type:* string | number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.volume.Volume.moveToId"></a>

```typescript
public moveToId(id: string): void
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `putCluster` <a name="putCluster" id="@cdktn/provider-docker.volume.Volume.putCluster"></a>

```typescript
public putCluster(value: VolumeCluster): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.putCluster.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---

##### `putLabels` <a name="putLabels" id="@cdktn/provider-docker.volume.Volume.putLabels"></a>

```typescript
public putLabels(value: IResolvable | VolumeLabels[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.Volume.putLabels.parameter.value"></a>

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]

---

##### `resetCluster` <a name="resetCluster" id="@cdktn/provider-docker.volume.Volume.resetCluster"></a>

```typescript
public resetCluster(): void
```

##### `resetDriver` <a name="resetDriver" id="@cdktn/provider-docker.volume.Volume.resetDriver"></a>

```typescript
public resetDriver(): void
```

##### `resetDriverOpts` <a name="resetDriverOpts" id="@cdktn/provider-docker.volume.Volume.resetDriverOpts"></a>

```typescript
public resetDriverOpts(): void
```

##### `resetId` <a name="resetId" id="@cdktn/provider-docker.volume.Volume.resetId"></a>

```typescript
public resetId(): void
```

##### `resetLabels` <a name="resetLabels" id="@cdktn/provider-docker.volume.Volume.resetLabels"></a>

```typescript
public resetLabels(): void
```

##### `resetName` <a name="resetName" id="@cdktn/provider-docker.volume.Volume.resetName"></a>

```typescript
public resetName(): void
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

```typescript
import { volume } from '@cdktn/provider-docker'

volume.Volume.isConstruct(x: any)
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

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.volume.Volume.isTerraformElement"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

volume.Volume.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.volume.Volume.isTerraformResource"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

volume.Volume.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.volume.Volume.isTerraformResource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

volume.Volume.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTN code for importing a Volume resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Volume to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Volume that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the Volume to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.cdktfStack">cdktfStack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.cluster">cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference">VolumeClusterOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.labels">labels</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList">VolumeLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.mountpoint">mountpoint</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.clusterInput">clusterInput</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverInput">driverInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverOptsInput">driverOptsInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.labelsInput">labelsInput</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driver">driver</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.driverOpts">driverOpts</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.name">name</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.volume.Volume.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.volume.Volume.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.Volume.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.volume.Volume.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.volume.Volume.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.volume.Volume.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.volume.Volume.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.volume.Volume.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.volume.Volume.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.volume.Volume.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.volume.Volume.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.volume.Volume.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.Volume.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.volume.Volume.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `cluster`<sup>Required</sup> <a name="cluster" id="@cdktn/provider-docker.volume.Volume.property.cluster"></a>

```typescript
public readonly cluster: VolumeClusterOutputReference;
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference">VolumeClusterOutputReference</a>

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.volume.Volume.property.labels"></a>

```typescript
public readonly labels: VolumeLabelsList;
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeLabelsList">VolumeLabelsList</a>

---

##### `mountpoint`<sup>Required</sup> <a name="mountpoint" id="@cdktn/provider-docker.volume.Volume.property.mountpoint"></a>

```typescript
public readonly mountpoint: string;
```

- *Type:* string

---

##### `clusterInput`<sup>Optional</sup> <a name="clusterInput" id="@cdktn/provider-docker.volume.Volume.property.clusterInput"></a>

```typescript
public readonly clusterInput: VolumeCluster;
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---

##### `driverInput`<sup>Optional</sup> <a name="driverInput" id="@cdktn/provider-docker.volume.Volume.property.driverInput"></a>

```typescript
public readonly driverInput: string;
```

- *Type:* string

---

##### `driverOptsInput`<sup>Optional</sup> <a name="driverOptsInput" id="@cdktn/provider-docker.volume.Volume.property.driverOptsInput"></a>

```typescript
public readonly driverOptsInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.volume.Volume.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `labelsInput`<sup>Optional</sup> <a name="labelsInput" id="@cdktn/provider-docker.volume.Volume.property.labelsInput"></a>

```typescript
public readonly labelsInput: IResolvable | VolumeLabels[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.volume.Volume.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `driver`<sup>Required</sup> <a name="driver" id="@cdktn/provider-docker.volume.Volume.property.driver"></a>

```typescript
public readonly driver: string;
```

- *Type:* string

---

##### `driverOpts`<sup>Required</sup> <a name="driverOpts" id="@cdktn/provider-docker.volume.Volume.property.driverOpts"></a>

```typescript
public readonly driverOpts: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.Volume.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.volume.Volume.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.Volume.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.volume.Volume.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### VolumeCluster <a name="VolumeCluster" id="@cdktn/provider-docker.volume.VolumeCluster"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeCluster.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

const volumeCluster: volume.VolumeCluster = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.availability">availability</a></code> | <code>string</code> | Availability of the volume. Can be `active` (default), `pause`, or `drain`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.group">group</a></code> | <code>string</code> | Cluster Volume group. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.limitBytes">limitBytes</a></code> | <code>string</code> | Minimum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc). |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.requiredBytes">requiredBytes</a></code> | <code>string</code> | Maximum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc). |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.scope">scope</a></code> | <code>string</code> | The scope of the volume. Can be `single` (default) or `multi`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.sharing">sharing</a></code> | <code>string</code> | The sharing mode. Can be `none` (default), `readonly`, `onewriter` or `all`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.topologyPreferred">topologyPreferred</a></code> | <code>string</code> | A topology that the Cluster Volume would be preferred in. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.topologyRequired">topologyRequired</a></code> | <code>string</code> | A topology that the Cluster Volume must be accessible from. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeCluster.property.type">type</a></code> | <code>string</code> | Cluster Volume access type. Can be `mount` or `block` (default). |

---

##### `availability`<sup>Optional</sup> <a name="availability" id="@cdktn/provider-docker.volume.VolumeCluster.property.availability"></a>

```typescript
public readonly availability: string;
```

- *Type:* string

Availability of the volume. Can be `active` (default), `pause`, or `drain`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#availability Volume#availability}

---

##### `group`<sup>Optional</sup> <a name="group" id="@cdktn/provider-docker.volume.VolumeCluster.property.group"></a>

```typescript
public readonly group: string;
```

- *Type:* string

Cluster Volume group.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#group Volume#group}

---

##### `limitBytes`<sup>Optional</sup> <a name="limitBytes" id="@cdktn/provider-docker.volume.VolumeCluster.property.limitBytes"></a>

```typescript
public readonly limitBytes: string;
```

- *Type:* string

Minimum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc).

Must be in format of KiB, MiB, Gib, Tib or PiB.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#limit_bytes Volume#limit_bytes}

---

##### `requiredBytes`<sup>Optional</sup> <a name="requiredBytes" id="@cdktn/provider-docker.volume.VolumeCluster.property.requiredBytes"></a>

```typescript
public readonly requiredBytes: string;
```

- *Type:* string

Maximum size of the Cluster Volume in human readable memory bytes (like 128MiB, 2GiB, etc).

Must be in format of KiB, MiB, Gib, Tib or PiB.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#required_bytes Volume#required_bytes}

---

##### `scope`<sup>Optional</sup> <a name="scope" id="@cdktn/provider-docker.volume.VolumeCluster.property.scope"></a>

```typescript
public readonly scope: string;
```

- *Type:* string

The scope of the volume. Can be `single` (default) or `multi`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#scope Volume#scope}

---

##### `sharing`<sup>Optional</sup> <a name="sharing" id="@cdktn/provider-docker.volume.VolumeCluster.property.sharing"></a>

```typescript
public readonly sharing: string;
```

- *Type:* string

The sharing mode. Can be `none` (default), `readonly`, `onewriter` or `all`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#sharing Volume#sharing}

---

##### `topologyPreferred`<sup>Optional</sup> <a name="topologyPreferred" id="@cdktn/provider-docker.volume.VolumeCluster.property.topologyPreferred"></a>

```typescript
public readonly topologyPreferred: string;
```

- *Type:* string

A topology that the Cluster Volume would be preferred in.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#topology_preferred Volume#topology_preferred}

---

##### `topologyRequired`<sup>Optional</sup> <a name="topologyRequired" id="@cdktn/provider-docker.volume.VolumeCluster.property.topologyRequired"></a>

```typescript
public readonly topologyRequired: string;
```

- *Type:* string

A topology that the Cluster Volume must be accessible from.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#topology_required Volume#topology_required}

---

##### `type`<sup>Optional</sup> <a name="type" id="@cdktn/provider-docker.volume.VolumeCluster.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Cluster Volume access type. Can be `mount` or `block` (default).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#type Volume#type}

---

### VolumeConfig <a name="VolumeConfig" id="@cdktn/provider-docker.volume.VolumeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeConfig.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

const volumeConfig: volume.VolumeConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.dependsOn">dependsOn</a></code> | <code>cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.cluster">cluster</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | cluster block. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.driver">driver</a></code> | <code>string</code> | Driver type for the volume. Defaults to `local`. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.driverOpts">driverOpts</a></code> | <code>{[ key: string ]: string}</code> | Options specific to the driver. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#id Volume#id}. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.labels">labels</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]</code> | labels block. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeConfig.property.name">name</a></code> | <code>string</code> | The name of the Docker volume (will be generated if not provided). |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.volume.VolumeConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.volume.VolumeConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.volume.VolumeConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktn.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.volume.VolumeConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.volume.VolumeConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.volume.VolumeConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.volume.VolumeConfig.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `cluster`<sup>Optional</sup> <a name="cluster" id="@cdktn/provider-docker.volume.VolumeConfig.property.cluster"></a>

```typescript
public readonly cluster: VolumeCluster;
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

cluster block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#cluster Volume#cluster}

---

##### `driver`<sup>Optional</sup> <a name="driver" id="@cdktn/provider-docker.volume.VolumeConfig.property.driver"></a>

```typescript
public readonly driver: string;
```

- *Type:* string

Driver type for the volume. Defaults to `local`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#driver Volume#driver}

---

##### `driverOpts`<sup>Optional</sup> <a name="driverOpts" id="@cdktn/provider-docker.volume.VolumeConfig.property.driverOpts"></a>

```typescript
public readonly driverOpts: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

Options specific to the driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#driver_opts Volume#driver_opts}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.volume.VolumeConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#id Volume#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.volume.VolumeConfig.property.labels"></a>

```typescript
public readonly labels: IResolvable | VolumeLabels[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#labels Volume#labels}

---

##### `name`<sup>Optional</sup> <a name="name" id="@cdktn/provider-docker.volume.VolumeConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

The name of the Docker volume (will be generated if not provided).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#name Volume#name}

---

### VolumeLabels <a name="VolumeLabels" id="@cdktn/provider-docker.volume.VolumeLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.volume.VolumeLabels.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

const volumeLabels: volume.VolumeLabels = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabels.property.label">label</a></code> | <code>string</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabels.property.value">value</a></code> | <code>string</code> | Value of the label. |

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.volume.VolumeLabels.property.label"></a>

```typescript
public readonly label: string;
```

- *Type:* string

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#label Volume#label}

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.VolumeLabels.property.value"></a>

```typescript
public readonly value: string;
```

- *Type:* string

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/volume#value Volume#value}

---

## Classes <a name="Classes" id="Classes"></a>

### VolumeClusterOutputReference <a name="VolumeClusterOutputReference" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

new volume.VolumeClusterOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAvailability` <a name="resetAvailability" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetAvailability"></a>

```typescript
public resetAvailability(): void
```

##### `resetGroup` <a name="resetGroup" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetGroup"></a>

```typescript
public resetGroup(): void
```

##### `resetLimitBytes` <a name="resetLimitBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetLimitBytes"></a>

```typescript
public resetLimitBytes(): void
```

##### `resetRequiredBytes` <a name="resetRequiredBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetRequiredBytes"></a>

```typescript
public resetRequiredBytes(): void
```

##### `resetScope` <a name="resetScope" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetScope"></a>

```typescript
public resetScope(): void
```

##### `resetSharing` <a name="resetSharing" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetSharing"></a>

```typescript
public resetSharing(): void
```

##### `resetTopologyPreferred` <a name="resetTopologyPreferred" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyPreferred"></a>

```typescript
public resetTopologyPreferred(): void
```

##### `resetTopologyRequired` <a name="resetTopologyRequired" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetTopologyRequired"></a>

```typescript
public resetTopologyRequired(): void
```

##### `resetType` <a name="resetType" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.resetType"></a>

```typescript
public resetType(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availabilityInput">availabilityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.groupInput">groupInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytesInput">limitBytesInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytesInput">requiredBytesInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scopeInput">scopeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharingInput">sharingInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferredInput">topologyPreferredInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequiredInput">topologyRequiredInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availability">availability</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.group">group</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytes">limitBytes</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytes">requiredBytes</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scope">scope</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharing">sharing</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferred">topologyPreferred</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequired">topologyRequired</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `availabilityInput`<sup>Optional</sup> <a name="availabilityInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availabilityInput"></a>

```typescript
public readonly availabilityInput: string;
```

- *Type:* string

---

##### `groupInput`<sup>Optional</sup> <a name="groupInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.groupInput"></a>

```typescript
public readonly groupInput: string;
```

- *Type:* string

---

##### `limitBytesInput`<sup>Optional</sup> <a name="limitBytesInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytesInput"></a>

```typescript
public readonly limitBytesInput: string;
```

- *Type:* string

---

##### `requiredBytesInput`<sup>Optional</sup> <a name="requiredBytesInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytesInput"></a>

```typescript
public readonly requiredBytesInput: string;
```

- *Type:* string

---

##### `scopeInput`<sup>Optional</sup> <a name="scopeInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scopeInput"></a>

```typescript
public readonly scopeInput: string;
```

- *Type:* string

---

##### `sharingInput`<sup>Optional</sup> <a name="sharingInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharingInput"></a>

```typescript
public readonly sharingInput: string;
```

- *Type:* string

---

##### `topologyPreferredInput`<sup>Optional</sup> <a name="topologyPreferredInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferredInput"></a>

```typescript
public readonly topologyPreferredInput: string;
```

- *Type:* string

---

##### `topologyRequiredInput`<sup>Optional</sup> <a name="topologyRequiredInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequiredInput"></a>

```typescript
public readonly topologyRequiredInput: string;
```

- *Type:* string

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `availability`<sup>Required</sup> <a name="availability" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.availability"></a>

```typescript
public readonly availability: string;
```

- *Type:* string

---

##### `group`<sup>Required</sup> <a name="group" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.group"></a>

```typescript
public readonly group: string;
```

- *Type:* string

---

##### `limitBytes`<sup>Required</sup> <a name="limitBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.limitBytes"></a>

```typescript
public readonly limitBytes: string;
```

- *Type:* string

---

##### `requiredBytes`<sup>Required</sup> <a name="requiredBytes" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.requiredBytes"></a>

```typescript
public readonly requiredBytes: string;
```

- *Type:* string

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.scope"></a>

```typescript
public readonly scope: string;
```

- *Type:* string

---

##### `sharing`<sup>Required</sup> <a name="sharing" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.sharing"></a>

```typescript
public readonly sharing: string;
```

- *Type:* string

---

##### `topologyPreferred`<sup>Required</sup> <a name="topologyPreferred" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyPreferred"></a>

```typescript
public readonly topologyPreferred: string;
```

- *Type:* string

---

##### `topologyRequired`<sup>Required</sup> <a name="topologyRequired" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.topologyRequired"></a>

```typescript
public readonly topologyRequired: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.volume.VolumeClusterOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: VolumeCluster;
```

- *Type:* <a href="#@cdktn/provider-docker.volume.VolumeCluster">VolumeCluster</a>

---


### VolumeLabelsList <a name="VolumeLabelsList" id="@cdktn/provider-docker.volume.VolumeLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

new volume.VolumeLabelsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.volume.VolumeLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

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

```typescript
public allWithMapKey(mapKeyAttributeName: string): DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.volume.VolumeLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.volume.VolumeLabelsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.volume.VolumeLabelsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeLabelsList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.VolumeLabelsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.volume.VolumeLabelsList.get"></a>

```typescript
public get(index: number): VolumeLabelsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.volume.VolumeLabelsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsList.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.volume.VolumeLabelsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | VolumeLabels[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>[]

---


### VolumeLabelsOutputReference <a name="VolumeLabelsOutputReference" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer"></a>

```typescript
import { volume } from '@cdktn/provider-docker'

new volume.VolumeLabelsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.labelInput">labelInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.valueInput">valueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.label">label</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.value">value</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `labelInput`<sup>Optional</sup> <a name="labelInput" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.labelInput"></a>

```typescript
public readonly labelInput: string;
```

- *Type:* string

---

##### `valueInput`<sup>Optional</sup> <a name="valueInput" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.valueInput"></a>

```typescript
public readonly valueInput: string;
```

- *Type:* string

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.label"></a>

```typescript
public readonly label: string;
```

- *Type:* string

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.value"></a>

```typescript
public readonly value: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.volume.VolumeLabelsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | VolumeLabels;
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.volume.VolumeLabels">VolumeLabels</a>

---



