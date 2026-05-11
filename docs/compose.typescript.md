# `compose` Submodule <a name="`compose` Submodule" id="@cdktn/provider-docker.compose"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Compose <a name="Compose" id="@cdktn/provider-docker.compose.Compose"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose docker_compose}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.compose.Compose.Initializer"></a>

```typescript
import { compose } from '@cdktn/provider-docker'

new compose.Compose(scope: Construct, id: string, config: ComposeConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.compose.ComposeConfig">ComposeConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktn/provider-docker.compose.Compose.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.compose.ComposeConfig">ComposeConfig</a>

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

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.compose.Compose.with"></a>

```typescript
public with(mixins: ...IMixin[]): IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.compose.Compose.with.parameter.mixins"></a>

- *Type:* ...constructs.IMixin[]

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.compose.Compose.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.compose.Compose.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.compose.Compose.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.compose.Compose.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.compose.Compose.toHclTerraform"></a>

```typescript
public toHclTerraform(): any
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.compose.Compose.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.compose.Compose.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget"></a>

```typescript
public addMoveTarget(moveTarget: string): void
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.compose.Compose.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.compose.Compose.hasResourceMove"></a>

```typescript
public hasResourceMove(): TerraformResourceMoveByTarget | TerraformResourceMoveById
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.compose.Compose.importFrom"></a>

```typescript
public importFrom(id: string, provider?: TerraformProvider): void
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.id"></a>

- *Type:* string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.importFrom.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.compose.Compose.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.compose.Compose.moveFromId"></a>

```typescript
public moveFromId(id: string): void
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.compose.Compose.moveTo"></a>

```typescript
public moveTo(moveTarget: string, index?: string | number): void
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.compose.Compose.moveTo.parameter.index"></a>

- *Type:* string | number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.compose.Compose.moveToId"></a>

```typescript
public moveToId(id: string): void
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `resetEnvFiles` <a name="resetEnvFiles" id="@cdktn/provider-docker.compose.Compose.resetEnvFiles"></a>

```typescript
public resetEnvFiles(): void
```

##### `resetProfiles` <a name="resetProfiles" id="@cdktn/provider-docker.compose.Compose.resetProfiles"></a>

```typescript
public resetProfiles(): void
```

##### `resetProjectDirectory` <a name="resetProjectDirectory" id="@cdktn/provider-docker.compose.Compose.resetProjectDirectory"></a>

```typescript
public resetProjectDirectory(): void
```

##### `resetProjectName` <a name="resetProjectName" id="@cdktn/provider-docker.compose.Compose.resetProjectName"></a>

```typescript
public resetProjectName(): void
```

##### `resetRemoveOrphans` <a name="resetRemoveOrphans" id="@cdktn/provider-docker.compose.Compose.resetRemoveOrphans"></a>

```typescript
public resetRemoveOrphans(): void
```

##### `resetWait` <a name="resetWait" id="@cdktn/provider-docker.compose.Compose.resetWait"></a>

```typescript
public resetWait(): void
```

##### `resetWaitTimeout` <a name="resetWaitTimeout" id="@cdktn/provider-docker.compose.Compose.resetWaitTimeout"></a>

```typescript
public resetWaitTimeout(): void
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

```typescript
import { compose } from '@cdktn/provider-docker'

compose.Compose.isConstruct(x: any)
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

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.compose.Compose.isTerraformElement"></a>

```typescript
import { compose } from '@cdktn/provider-docker'

compose.Compose.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.compose.Compose.isTerraformResource"></a>

```typescript
import { compose } from '@cdktn/provider-docker'

compose.Compose.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.compose.Compose.isTerraformResource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport"></a>

```typescript
import { compose } from '@cdktn/provider-docker'

compose.Compose.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTN code for importing a Compose resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Compose to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Compose that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the Compose to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.cdktfStack">cdktfStack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPathsInput">configPathsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFilesInput">envFilesInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profilesInput">profilesInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput">projectDirectoryInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectNameInput">projectNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphansInput">removeOrphansInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitInput">waitInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput">waitTimeoutInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.configPaths">configPaths</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.envFiles">envFiles</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.profiles">profiles</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectDirectory">projectDirectory</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.projectName">projectName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.removeOrphans">removeOrphans</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.wait">wait</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.waitTimeout">waitTimeout</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.compose.Compose.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.compose.Compose.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.compose.Compose.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.compose.Compose.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.compose.Compose.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.compose.Compose.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.compose.Compose.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.Compose.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.Compose.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.compose.Compose.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.compose.Compose.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.Compose.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.Compose.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.Compose.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.compose.Compose.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `configPathsInput`<sup>Optional</sup> <a name="configPathsInput" id="@cdktn/provider-docker.compose.Compose.property.configPathsInput"></a>

```typescript
public readonly configPathsInput: string[];
```

- *Type:* string[]

---

##### `envFilesInput`<sup>Optional</sup> <a name="envFilesInput" id="@cdktn/provider-docker.compose.Compose.property.envFilesInput"></a>

```typescript
public readonly envFilesInput: string[];
```

- *Type:* string[]

---

##### `profilesInput`<sup>Optional</sup> <a name="profilesInput" id="@cdktn/provider-docker.compose.Compose.property.profilesInput"></a>

```typescript
public readonly profilesInput: string[];
```

- *Type:* string[]

---

##### `projectDirectoryInput`<sup>Optional</sup> <a name="projectDirectoryInput" id="@cdktn/provider-docker.compose.Compose.property.projectDirectoryInput"></a>

```typescript
public readonly projectDirectoryInput: string;
```

- *Type:* string

---

##### `projectNameInput`<sup>Optional</sup> <a name="projectNameInput" id="@cdktn/provider-docker.compose.Compose.property.projectNameInput"></a>

```typescript
public readonly projectNameInput: string;
```

- *Type:* string

---

##### `removeOrphansInput`<sup>Optional</sup> <a name="removeOrphansInput" id="@cdktn/provider-docker.compose.Compose.property.removeOrphansInput"></a>

```typescript
public readonly removeOrphansInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `waitInput`<sup>Optional</sup> <a name="waitInput" id="@cdktn/provider-docker.compose.Compose.property.waitInput"></a>

```typescript
public readonly waitInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `waitTimeoutInput`<sup>Optional</sup> <a name="waitTimeoutInput" id="@cdktn/provider-docker.compose.Compose.property.waitTimeoutInput"></a>

```typescript
public readonly waitTimeoutInput: string;
```

- *Type:* string

---

##### `configPaths`<sup>Required</sup> <a name="configPaths" id="@cdktn/provider-docker.compose.Compose.property.configPaths"></a>

```typescript
public readonly configPaths: string[];
```

- *Type:* string[]

---

##### `envFiles`<sup>Required</sup> <a name="envFiles" id="@cdktn/provider-docker.compose.Compose.property.envFiles"></a>

```typescript
public readonly envFiles: string[];
```

- *Type:* string[]

---

##### `profiles`<sup>Required</sup> <a name="profiles" id="@cdktn/provider-docker.compose.Compose.property.profiles"></a>

```typescript
public readonly profiles: string[];
```

- *Type:* string[]

---

##### `projectDirectory`<sup>Required</sup> <a name="projectDirectory" id="@cdktn/provider-docker.compose.Compose.property.projectDirectory"></a>

```typescript
public readonly projectDirectory: string;
```

- *Type:* string

---

##### `projectName`<sup>Required</sup> <a name="projectName" id="@cdktn/provider-docker.compose.Compose.property.projectName"></a>

```typescript
public readonly projectName: string;
```

- *Type:* string

---

##### `removeOrphans`<sup>Required</sup> <a name="removeOrphans" id="@cdktn/provider-docker.compose.Compose.property.removeOrphans"></a>

```typescript
public readonly removeOrphans: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `wait`<sup>Required</sup> <a name="wait" id="@cdktn/provider-docker.compose.Compose.property.wait"></a>

```typescript
public readonly wait: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `waitTimeout`<sup>Required</sup> <a name="waitTimeout" id="@cdktn/provider-docker.compose.Compose.property.waitTimeout"></a>

```typescript
public readonly waitTimeout: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.Compose.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.compose.Compose.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ComposeConfig <a name="ComposeConfig" id="@cdktn/provider-docker.compose.ComposeConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.compose.ComposeConfig.Initializer"></a>

```typescript
import { compose } from '@cdktn/provider-docker'

const composeConfig: compose.ComposeConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn">dependsOn</a></code> | <code>cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.configPaths">configPaths</a></code> | <code>string[]</code> | One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.envFiles">envFiles</a></code> | <code>string[]</code> | Optional list of env files to load before parsing the Compose configuration. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.profiles">profiles</a></code> | <code>string[]</code> | Optional list of Compose profiles to enable. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory">projectDirectory</a></code> | <code>string</code> | Optional project directory used as the Compose working directory. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.projectName">projectName</a></code> | <code>string</code> | Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans">removeOrphans</a></code> | <code>boolean \| cdktn.IResolvable</code> | If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.wait">wait</a></code> | <code>boolean \| cdktn.IResolvable</code> | If `true`, wait until services reach the running or healthy state before returning from apply. |
| <code><a href="#@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout">waitTimeout</a></code> | <code>string</code> | Optional duration for `wait`, for example `30s` or `2m`. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.compose.ComposeConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.compose.ComposeConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.compose.ComposeConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktn.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.compose.ComposeConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.compose.ComposeConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.compose.ComposeConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.compose.ComposeConfig.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `configPaths`<sup>Required</sup> <a name="configPaths" id="@cdktn/provider-docker.compose.ComposeConfig.property.configPaths"></a>

```typescript
public readonly configPaths: string[];
```

- *Type:* string[]

One or more Compose file paths, equivalent to repeating the `-f` flag with `docker compose`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#config_paths Compose#config_paths}

---

##### `envFiles`<sup>Optional</sup> <a name="envFiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.envFiles"></a>

```typescript
public readonly envFiles: string[];
```

- *Type:* string[]

Optional list of env files to load before parsing the Compose configuration.

If omitted, Compose uses the default `.env` behavior.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#env_files Compose#env_files}

---

##### `profiles`<sup>Optional</sup> <a name="profiles" id="@cdktn/provider-docker.compose.ComposeConfig.property.profiles"></a>

```typescript
public readonly profiles: string[];
```

- *Type:* string[]

Optional list of Compose profiles to enable.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#profiles Compose#profiles}

---

##### `projectDirectory`<sup>Optional</sup> <a name="projectDirectory" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectDirectory"></a>

```typescript
public readonly projectDirectory: string;
```

- *Type:* string

Optional project directory used as the Compose working directory.

If omitted, Compose uses the directory of the first file in `config_paths`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#project_directory Compose#project_directory}

---

##### `projectName`<sup>Optional</sup> <a name="projectName" id="@cdktn/provider-docker.compose.ComposeConfig.property.projectName"></a>

```typescript
public readonly projectName: string;
```

- *Type:* string

Optional Compose project name. If omitted, Compose derives the project name the same way as the CLI.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#project_name Compose#project_name}

---

##### `removeOrphans`<sup>Optional</sup> <a name="removeOrphans" id="@cdktn/provider-docker.compose.ComposeConfig.property.removeOrphans"></a>

```typescript
public readonly removeOrphans: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If `true`, remove containers for services that are no longer present in the Compose configuration during apply and destroy.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#remove_orphans Compose#remove_orphans}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.compose.ComposeConfig.property.wait"></a>

```typescript
public readonly wait: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If `true`, wait until services reach the running or healthy state before returning from apply.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#wait Compose#wait}

---

##### `waitTimeout`<sup>Optional</sup> <a name="waitTimeout" id="@cdktn/provider-docker.compose.ComposeConfig.property.waitTimeout"></a>

```typescript
public readonly waitTimeout: string;
```

- *Type:* string

Optional duration for `wait`, for example `30s` or `2m`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.3.0/docs/resources/compose#wait_timeout Compose#wait_timeout}

---



