# `registryImage` Submodule <a name="`registryImage` Submodule" id="@cdktn/provider-docker.registryImage"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### RegistryImage <a name="RegistryImage" id="@cdktn/provider-docker.registryImage.RegistryImage"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image docker_registry_image}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImage(scope: Construct, id: string, config: RegistryImageConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig">RegistryImageConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktn/provider-docker.registryImage.RegistryImage.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig">RegistryImageConfig</a>

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

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.registryImage.RegistryImage.with"></a>

```typescript
public with(mixins: ...IMixin[]): IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.registryImage.RegistryImage.with.parameter.mixins"></a>

- *Type:* ...constructs.IMixin[]

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toHclTerraform"></a>

```typescript
public toHclTerraform(): any
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.registryImage.RegistryImage.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget"></a>

```typescript
public addMoveTarget(moveTarget: string): void
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.registryImage.RegistryImage.hasResourceMove"></a>

```typescript
public hasResourceMove(): TerraformResourceMoveByTarget | TerraformResourceMoveById
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom"></a>

```typescript
public importFrom(id: string, provider?: TerraformProvider): void
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.id"></a>

- *Type:* string

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.importFrom.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId"></a>

```typescript
public moveFromId(id: string): void
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using it's instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo"></a>

```typescript
public moveTo(moveTarget: string, index?: string | number): void
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImage.moveTo.parameter.index"></a>

- *Type:* string | number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId"></a>

```typescript
public moveToId(id: string): void
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `putAuthConfig` <a name="putAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig"></a>

```typescript
public putAuthConfig(value: RegistryImageAuthConfig): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putAuthConfig.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `putBuildAttribute` <a name="putBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute"></a>

```typescript
public putBuildAttribute(value: RegistryImageBuild): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putBuildAttribute.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `putTimeouts` <a name="putTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts"></a>

```typescript
public putTimeouts(value: RegistryImageTimeouts): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImage.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `resetAuthConfig` <a name="resetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.resetAuthConfig"></a>

```typescript
public resetAuthConfig(): void
```

##### `resetBuildAttribute` <a name="resetBuildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.resetBuildAttribute"></a>

```typescript
public resetBuildAttribute(): void
```

##### `resetId` <a name="resetId" id="@cdktn/provider-docker.registryImage.RegistryImage.resetId"></a>

```typescript
public resetId(): void
```

##### `resetInsecureSkipVerify` <a name="resetInsecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.resetInsecureSkipVerify"></a>

```typescript
public resetInsecureSkipVerify(): void
```

##### `resetKeepRemotely` <a name="resetKeepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.resetKeepRemotely"></a>

```typescript
public resetKeepRemotely(): void
```

##### `resetTimeouts` <a name="resetTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTimeouts"></a>

```typescript
public resetTimeouts(): void
```

##### `resetTriggers` <a name="resetTriggers" id="@cdktn/provider-docker.registryImage.RegistryImage.resetTriggers"></a>

```typescript
public resetTriggers(): void
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

```typescript
import { registryImage } from '@cdktn/provider-docker'

registryImage.RegistryImage.isConstruct(x: any)
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

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

registryImage.RegistryImage.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

registryImage.RegistryImage.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.registryImage.RegistryImage.isTerraformResource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

registryImage.RegistryImage.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTN code for importing a RegistryImage resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the RegistryImage to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing RegistryImage that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the RegistryImage to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack">cdktfStack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute">buildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest">sha256Digest</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput">authConfigInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput">buildAttributeInput</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput">insecureSkipVerifyInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput">keepRemotelyInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput">timeoutsInput</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput">triggersInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely">keepRemotely</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.triggers">triggers</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.registryImage.RegistryImage.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.registryImage.RegistryImage.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.registryImage.RegistryImage.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.registryImage.RegistryImage.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImage.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImage.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.registryImage.RegistryImage.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.registryImage.RegistryImage.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImage.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImage.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `authConfig`<sup>Required</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfig"></a>

```typescript
public readonly authConfig: RegistryImageAuthConfigOutputReference;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference">RegistryImageAuthConfigOutputReference</a>

---

##### `buildAttribute`<sup>Required</sup> <a name="buildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttribute"></a>

```typescript
public readonly buildAttribute: RegistryImageBuildOutputReference;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference">RegistryImageBuildOutputReference</a>

---

##### `sha256Digest`<sup>Required</sup> <a name="sha256Digest" id="@cdktn/provider-docker.registryImage.RegistryImage.property.sha256Digest"></a>

```typescript
public readonly sha256Digest: string;
```

- *Type:* string

---

##### `timeouts`<sup>Required</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeouts"></a>

```typescript
public readonly timeouts: RegistryImageTimeoutsOutputReference;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference">RegistryImageTimeoutsOutputReference</a>

---

##### `authConfigInput`<sup>Optional</sup> <a name="authConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.authConfigInput"></a>

```typescript
public readonly authConfigInput: RegistryImageAuthConfig;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---

##### `buildAttributeInput`<sup>Optional</sup> <a name="buildAttributeInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.buildAttributeInput"></a>

```typescript
public readonly buildAttributeInput: RegistryImageBuild;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `insecureSkipVerifyInput`<sup>Optional</sup> <a name="insecureSkipVerifyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerifyInput"></a>

```typescript
public readonly insecureSkipVerifyInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `keepRemotelyInput`<sup>Optional</sup> <a name="keepRemotelyInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotelyInput"></a>

```typescript
public readonly keepRemotelyInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `timeoutsInput`<sup>Optional</sup> <a name="timeoutsInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.timeoutsInput"></a>

```typescript
public readonly timeoutsInput: IResolvable | RegistryImageTimeouts;
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---

##### `triggersInput`<sup>Optional</sup> <a name="triggersInput" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggersInput"></a>

```typescript
public readonly triggersInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImage.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `insecureSkipVerify`<sup>Required</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImage.property.insecureSkipVerify"></a>

```typescript
public readonly insecureSkipVerify: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `keepRemotely`<sup>Required</sup> <a name="keepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImage.property.keepRemotely"></a>

```typescript
public readonly keepRemotely: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImage.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `triggers`<sup>Required</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImage.property.triggers"></a>

```typescript
public readonly triggers: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.registryImage.RegistryImage.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### RegistryImageAuthConfig <a name="RegistryImageAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageAuthConfig: registryImage.RegistryImageAuthConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address">address</a></code> | <code>string</code> | The address of the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password">password</a></code> | <code>string</code> | The password for the Docker registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username">username</a></code> | <code>string</code> | The username for the Docker registry. |

---

##### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.address"></a>

```typescript
public readonly address: string;
```

- *Type:* string

The address of the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#address RegistryImage#address}

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.password"></a>

```typescript
public readonly password: string;
```

- *Type:* string

The password for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `username`<sup>Optional</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfig.property.username"></a>

```typescript
public readonly username: string;
```

- *Type:* string

The username for the Docker registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#username RegistryImage#username}

---

### RegistryImageBuild <a name="RegistryImageBuild" id="@cdktn/provider-docker.registryImage.RegistryImageBuild"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageBuild: registryImage.RegistryImageBuild = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context">context</a></code> | <code>string</code> | Value to specify the build context. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts">additionalContexts</a></code> | <code>string[]</code> | A list of additional build contexts. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig">authConfig</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]</code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs">buildArgs</a></code> | <code>{[ key: string ]: string}</code> | Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder">builder</a></code> | <code>string</code> | The name of the buildx builder to use. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId">buildId</a></code> | <code>string</code> | BuildID is an optional identifier that can be passed together with the build request. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile">buildLogFile</a></code> | <code>string</code> | Path to a file where the buildx log are written to. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom">cacheFrom</a></code> | <code>string[]</code> | External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo">cacheTo</a></code> | <code>string[]</code> | Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent">cgroupParent</a></code> | <code>string</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod">cpuPeriod</a></code> | <code>number</code> | The length of a CPU period in microseconds. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota">cpuQuota</a></code> | <code>number</code> | Microseconds of CPU time that the container can get in a CPU period. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus">cpuSetCpus</a></code> | <code>string</code> | CPUs in which to allow execution (e.g., `0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems">cpuSetMems</a></code> | <code>string</code> | MEMs in which to allow execution (`0-3`, `0`, `1`). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares">cpuShares</a></code> | <code>number</code> | CPU shares (relative weight). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile">dockerfile</a></code> | <code>string</code> | Name of the Dockerfile. Defaults to `Dockerfile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts">extraHosts</a></code> | <code>string[]</code> | A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"]. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove">forceRemove</a></code> | <code>boolean \| cdktn.IResolvable</code> | Always remove intermediate containers. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation">isolation</a></code> | <code>string</code> | Isolation represents the isolation technology of a container. The supported values are. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label">label</a></code> | <code>{[ key: string ]: string}</code> | Set metadata for an image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels">labels</a></code> | <code>{[ key: string ]: string}</code> | User-defined key/value metadata. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory">memory</a></code> | <code>number</code> | Set memory limit for build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap">memorySwap</a></code> | <code>number</code> | Total memory (memory + swap), -1 to enable unlimited swap. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode">networkMode</a></code> | <code>string</code> | Set the networking mode for the RUN instructions during build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache">noCache</a></code> | <code>boolean \| cdktn.IResolvable</code> | Do not use the cache when building the image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform">platform</a></code> | <code>string</code> | Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform). |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance">provenance</a></code> | <code>string</code> | Set provenance attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent">pullParent</a></code> | <code>boolean \| cdktn.IResolvable</code> | Attempt to pull the image even if an older image exists locally. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext">remoteContext</a></code> | <code>string</code> | A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove">remove</a></code> | <code>boolean \| cdktn.IResolvable</code> | Remove intermediate containers after a successful build. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom">sbom</a></code> | <code>string</code> | Set SBOM (Software Bill of Materials) attestation for the build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets">secrets</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]</code> | secrets block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt">securityOpt</a></code> | <code>string[]</code> | The security options. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId">sessionId</a></code> | <code>string</code> | Set an ID for the build session. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize">shmSize</a></code> | <code>number</code> | Size of /dev/shm in bytes. The size must be greater than 0. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash">squash</a></code> | <code>boolean \| cdktn.IResolvable</code> | If true the new layers are squashed into a new image with a single new layer. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput">suppressOutput</a></code> | <code>boolean \| cdktn.IResolvable</code> | Suppress the build output and print image ID on success. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag">tag</a></code> | <code>string[]</code> | Name and optionally a tag in the 'name:tag' format. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target">target</a></code> | <code>string</code> | Set the target build stage to build. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit">ulimit</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]</code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder">useLegacyBuilder</a></code> | <code>boolean \| cdktn.IResolvable</code> | Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version">version</a></code> | <code>string</code> | Version of the underlying builder to use. |

---

##### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.context"></a>

```typescript
public readonly context: string;
```

- *Type:* string

Value to specify the build context.

Currently, only a `PATH` context is supported. You can use the helper function '${path.cwd}/context-dir'. This always refers to the local working directory, even when building images on remote hosts. Please see https://docs.docker.com/build/building/context/ for more information about build contexts.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#context RegistryImage#context}

---

##### `additionalContexts`<sup>Optional</sup> <a name="additionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.additionalContexts"></a>

```typescript
public readonly additionalContexts: string[];
```

- *Type:* string[]

A list of additional build contexts.

Only supported when using a buildx builder. Example: `["name=path", "src = https://example.org"}`. Please see https://docs.docker.com/reference/cli/docker/buildx/build/#build-context for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#additional_contexts RegistryImage#additional_contexts}

---

##### `authConfig`<sup>Optional</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.authConfig"></a>

```typescript
public readonly authConfig: IResolvable | RegistryImageBuildAuthConfig[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `buildArgs`<sup>Optional</sup> <a name="buildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildArgs"></a>

```typescript
public readonly buildArgs: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

Pairs for build-time variables in the form of `ENDPOINT : "https://example.com"`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build_args RegistryImage#build_args}

---

##### `builder`<sup>Optional</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.builder"></a>

```typescript
public readonly builder: string;
```

- *Type:* string

The name of the buildx builder to use.

If BUILDX_BUILDER environment variable is set, it will be used. If left empty, the provider tries to resolve to the default builder - which might not always work. If you are in Windows, the legacy builder is used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#builder RegistryImage#builder}

---

##### `buildId`<sup>Optional</sup> <a name="buildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildId"></a>

```typescript
public readonly buildId: string;
```

- *Type:* string

BuildID is an optional identifier that can be passed together with the build request.

The same identifier can be used to gracefully cancel the build with the cancel request.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build_id RegistryImage#build_id}

---

##### `buildLogFile`<sup>Optional</sup> <a name="buildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.buildLogFile"></a>

```typescript
public readonly buildLogFile: string;
```

- *Type:* string

Path to a file where the buildx log are written to.

Only available when `builder` is set. If not set, no logs are available. The path is taken as is, so make sure to use a path that is available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build_log_file RegistryImage#build_log_file}

---

##### `cacheFrom`<sup>Optional</sup> <a name="cacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheFrom"></a>

```typescript
public readonly cacheFrom: string[];
```

- *Type:* string[]

External cache sources (e.g., `user/app:cache`, `type=local,src=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cache_from RegistryImage#cache_from}

---

##### `cacheTo`<sup>Optional</sup> <a name="cacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cacheTo"></a>

```typescript
public readonly cacheTo: string[];
```

- *Type:* string[]

Cache export destinations (e.g., `user/app:cache`, `type=local,dest=path/to/dir`). Only supported when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cache_to RegistryImage#cache_to}

---

##### `cgroupParent`<sup>Optional</sup> <a name="cgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cgroupParent"></a>

```typescript
public readonly cgroupParent: string;
```

- *Type:* string

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cgroup_parent RegistryImage#cgroup_parent}

---

##### `cpuPeriod`<sup>Optional</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuPeriod"></a>

```typescript
public readonly cpuPeriod: number;
```

- *Type:* number

The length of a CPU period in microseconds.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_period RegistryImage#cpu_period}

---

##### `cpuQuota`<sup>Optional</sup> <a name="cpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuQuota"></a>

```typescript
public readonly cpuQuota: number;
```

- *Type:* number

Microseconds of CPU time that the container can get in a CPU period.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_quota RegistryImage#cpu_quota}

---

##### `cpuSetCpus`<sup>Optional</sup> <a name="cpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetCpus"></a>

```typescript
public readonly cpuSetCpus: string;
```

- *Type:* string

CPUs in which to allow execution (e.g., `0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_set_cpus RegistryImage#cpu_set_cpus}

---

##### `cpuSetMems`<sup>Optional</sup> <a name="cpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuSetMems"></a>

```typescript
public readonly cpuSetMems: string;
```

- *Type:* string

MEMs in which to allow execution (`0-3`, `0`, `1`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_set_mems RegistryImage#cpu_set_mems}

---

##### `cpuShares`<sup>Optional</sup> <a name="cpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.cpuShares"></a>

```typescript
public readonly cpuShares: number;
```

- *Type:* number

CPU shares (relative weight).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#cpu_shares RegistryImage#cpu_shares}

---

##### `dockerfile`<sup>Optional</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.dockerfile"></a>

```typescript
public readonly dockerfile: string;
```

- *Type:* string

Name of the Dockerfile. Defaults to `Dockerfile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#dockerfile RegistryImage#dockerfile}

---

##### `extraHosts`<sup>Optional</sup> <a name="extraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.extraHosts"></a>

```typescript
public readonly extraHosts: string[];
```

- *Type:* string[]

A list of hostnames/IP mappings to add to the container’s /etc/hosts file. Specified in the form ["hostname:IP"].

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#extra_hosts RegistryImage#extra_hosts}

---

##### `forceRemove`<sup>Optional</sup> <a name="forceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.forceRemove"></a>

```typescript
public readonly forceRemove: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

Always remove intermediate containers.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#force_remove RegistryImage#force_remove}

---

##### `isolation`<sup>Optional</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.isolation"></a>

```typescript
public readonly isolation: string;
```

- *Type:* string

Isolation represents the isolation technology of a container. The supported values are.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#isolation RegistryImage#isolation}

---

##### `label`<sup>Optional</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.label"></a>

```typescript
public readonly label: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

Set metadata for an image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#label RegistryImage#label}

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.labels"></a>

```typescript
public readonly labels: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

User-defined key/value metadata.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#labels RegistryImage#labels}

---

##### `memory`<sup>Optional</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memory"></a>

```typescript
public readonly memory: number;
```

- *Type:* number

Set memory limit for build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#memory RegistryImage#memory}

---

##### `memorySwap`<sup>Optional</sup> <a name="memorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.memorySwap"></a>

```typescript
public readonly memorySwap: number;
```

- *Type:* number

Total memory (memory + swap), -1 to enable unlimited swap.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#memory_swap RegistryImage#memory_swap}

---

##### `networkMode`<sup>Optional</sup> <a name="networkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.networkMode"></a>

```typescript
public readonly networkMode: string;
```

- *Type:* string

Set the networking mode for the RUN instructions during build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#network_mode RegistryImage#network_mode}

---

##### `noCache`<sup>Optional</sup> <a name="noCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.noCache"></a>

```typescript
public readonly noCache: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

Do not use the cache when building the image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#no_cache RegistryImage#no_cache}

---

##### `platform`<sup>Optional</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.platform"></a>

```typescript
public readonly platform: string;
```

- *Type:* string

Set the target platform for the build. Defaults to `GOOS/GOARCH`. For more information see the [docker documentation](https://github.com/docker/buildx/blob/master/docs/reference/buildx.md#-set-the-target-platforms-for-the-build---platform).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#platform RegistryImage#platform}

---

##### `provenance`<sup>Optional</sup> <a name="provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.provenance"></a>

```typescript
public readonly provenance: string;
```

- *Type:* string

Set provenance attestation for the build.

BuildKit v0.11+ adds provenance attestations by default, which creates OCI image manifests that some registries (like AWS Lambda) don't support. Set to `false` to disable. Valid values: `false`, `true`, `min`, `max`, `mode=min`, `mode=max`, or a full provenance specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#provenance RegistryImage#provenance}

---

##### `pullParent`<sup>Optional</sup> <a name="pullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.pullParent"></a>

```typescript
public readonly pullParent: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

Attempt to pull the image even if an older image exists locally.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#pull_parent RegistryImage#pull_parent}

---

##### `remoteContext`<sup>Optional</sup> <a name="remoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remoteContext"></a>

```typescript
public readonly remoteContext: string;
```

- *Type:* string

A Git repository URI or HTTP/HTTPS context URI. Will be ignored if `builder` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#remote_context RegistryImage#remote_context}

---

##### `remove`<sup>Optional</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.remove"></a>

```typescript
public readonly remove: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

Remove intermediate containers after a successful build. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#remove RegistryImage#remove}

---

##### `sbom`<sup>Optional</sup> <a name="sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sbom"></a>

```typescript
public readonly sbom: string;
```

- *Type:* string

Set SBOM (Software Bill of Materials) attestation for the build.

Set to `false` to disable. Valid values: `false`, `true`, or a full SBOM specification. Only available when using a buildx builder.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#sbom RegistryImage#sbom}

---

##### `secrets`<sup>Optional</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.secrets"></a>

```typescript
public readonly secrets: IResolvable | RegistryImageBuildSecrets[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

secrets block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#secrets RegistryImage#secrets}

---

##### `securityOpt`<sup>Optional</sup> <a name="securityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.securityOpt"></a>

```typescript
public readonly securityOpt: string[];
```

- *Type:* string[]

The security options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#security_opt RegistryImage#security_opt}

---

##### `sessionId`<sup>Optional</sup> <a name="sessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.sessionId"></a>

```typescript
public readonly sessionId: string;
```

- *Type:* string

Set an ID for the build session.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#session_id RegistryImage#session_id}

---

##### `shmSize`<sup>Optional</sup> <a name="shmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.shmSize"></a>

```typescript
public readonly shmSize: number;
```

- *Type:* number

Size of /dev/shm in bytes. The size must be greater than 0.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#shm_size RegistryImage#shm_size}

---

##### `squash`<sup>Optional</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.squash"></a>

```typescript
public readonly squash: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If true the new layers are squashed into a new image with a single new layer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#squash RegistryImage#squash}

---

##### `suppressOutput`<sup>Optional</sup> <a name="suppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.suppressOutput"></a>

```typescript
public readonly suppressOutput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

Suppress the build output and print image ID on success.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#suppress_output RegistryImage#suppress_output}

---

##### `tag`<sup>Optional</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.tag"></a>

```typescript
public readonly tag: string[];
```

- *Type:* string[]

Name and optionally a tag in the 'name:tag' format.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#tag RegistryImage#tag}

---

##### `target`<sup>Optional</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.target"></a>

```typescript
public readonly target: string;
```

- *Type:* string

Set the target build stage to build.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#target RegistryImage#target}

---

##### `ulimit`<sup>Optional</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.ulimit"></a>

```typescript
public readonly ulimit: IResolvable | RegistryImageBuildUlimit[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#ulimit RegistryImage#ulimit}

---

##### `useLegacyBuilder`<sup>Optional</sup> <a name="useLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.useLegacyBuilder"></a>

```typescript
public readonly useLegacyBuilder: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

Force using the legacy Docker builder for image builds, even if buildx/buildkit would be available.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#use_legacy_builder RegistryImage#use_legacy_builder}

---

##### `version`<sup>Optional</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImageBuild.property.version"></a>

```typescript
public readonly version: string;
```

- *Type:* string

Version of the underlying builder to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#version RegistryImage#version}

---

### RegistryImageBuildAuthConfig <a name="RegistryImageBuildAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageBuildAuthConfig: registryImage.RegistryImageBuildAuthConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName">hostName</a></code> | <code>string</code> | hostname of the registry. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth">auth</a></code> | <code>string</code> | the auth token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email">email</a></code> | <code>string</code> | the user emal. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken">identityToken</a></code> | <code>string</code> | the identity token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password">password</a></code> | <code>string</code> | the registry password. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken">registryToken</a></code> | <code>string</code> | the registry token. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress">serverAddress</a></code> | <code>string</code> | the server address. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName">userName</a></code> | <code>string</code> | the registry user name. |

---

##### `hostName`<sup>Required</sup> <a name="hostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.hostName"></a>

```typescript
public readonly hostName: string;
```

- *Type:* string

hostname of the registry.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#host_name RegistryImage#host_name}

---

##### `auth`<sup>Optional</sup> <a name="auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.auth"></a>

```typescript
public readonly auth: string;
```

- *Type:* string

the auth token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#auth RegistryImage#auth}

---

##### `email`<sup>Optional</sup> <a name="email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.email"></a>

```typescript
public readonly email: string;
```

- *Type:* string

the user emal.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#email RegistryImage#email}

---

##### `identityToken`<sup>Optional</sup> <a name="identityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.identityToken"></a>

```typescript
public readonly identityToken: string;
```

- *Type:* string

the identity token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#identity_token RegistryImage#identity_token}

---

##### `password`<sup>Optional</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.password"></a>

```typescript
public readonly password: string;
```

- *Type:* string

the registry password.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#password RegistryImage#password}

---

##### `registryToken`<sup>Optional</sup> <a name="registryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.registryToken"></a>

```typescript
public readonly registryToken: string;
```

- *Type:* string

the registry token.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#registry_token RegistryImage#registry_token}

---

##### `serverAddress`<sup>Optional</sup> <a name="serverAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.serverAddress"></a>

```typescript
public readonly serverAddress: string;
```

- *Type:* string

the server address.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#server_address RegistryImage#server_address}

---

##### `userName`<sup>Optional</sup> <a name="userName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig.property.userName"></a>

```typescript
public readonly userName: string;
```

- *Type:* string

the registry user name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#user_name RegistryImage#user_name}

---

### RegistryImageBuildSecrets <a name="RegistryImageBuildSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageBuildSecrets: registryImage.RegistryImageBuildSecrets = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id">id</a></code> | <code>string</code> | ID of the secret. By default, secrets are mounted to /run/secrets/<id>. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env">env</a></code> | <code>string</code> | Environment variable source of the secret. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src">src</a></code> | <code>string</code> | File source of the secret. Takes precedence over `env`. |

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

ID of the secret. By default, secrets are mounted to /run/secrets/<id>.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#id RegistryImage#id}

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `env`<sup>Optional</sup> <a name="env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.env"></a>

```typescript
public readonly env: string;
```

- *Type:* string

Environment variable source of the secret.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#env RegistryImage#env}

---

##### `src`<sup>Optional</sup> <a name="src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets.property.src"></a>

```typescript
public readonly src: string;
```

- *Type:* string

File source of the secret. Takes precedence over `env`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#src RegistryImage#src}

---

### RegistryImageBuildUlimit <a name="RegistryImageBuildUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageBuildUlimit: registryImage.RegistryImageBuildUlimit = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard">hard</a></code> | <code>number</code> | soft limit. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name">name</a></code> | <code>string</code> | type of ulimit, e.g. `nofile`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft">soft</a></code> | <code>number</code> | hard limit. |

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.hard"></a>

```typescript
public readonly hard: number;
```

- *Type:* number

soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#hard RegistryImage#hard}

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

type of ulimit, e.g. `nofile`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit.property.soft"></a>

```typescript
public readonly soft: number;
```

- *Type:* number

hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#soft RegistryImage#soft}

---

### RegistryImageConfig <a name="RegistryImageConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageConfig: registryImage.RegistryImageConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn">dependsOn</a></code> | <code>cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name">name</a></code> | <code>string</code> | The name of the Docker image. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | auth_config block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute">buildAttribute</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | build block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#id RegistryImage#id}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>boolean \| cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely">keepRemotely</a></code> | <code>boolean \| cdktn.IResolvable</code> | If true, then the Docker image won't be deleted on destroy operation. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers">triggers</a></code> | <code>{[ key: string ]: string}</code> | A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktn.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

The name of the Docker image.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#name RegistryImage#name}

---

##### `authConfig`<sup>Optional</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.authConfig"></a>

```typescript
public readonly authConfig: RegistryImageAuthConfig;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

auth_config block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#auth_config RegistryImage#auth_config}

---

##### `buildAttribute`<sup>Optional</sup> <a name="buildAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.buildAttribute"></a>

```typescript
public readonly buildAttribute: RegistryImageBuild;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

build block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#build RegistryImage#build}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#id RegistryImage#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `insecureSkipVerify`<sup>Optional</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.insecureSkipVerify"></a>

```typescript
public readonly insecureSkipVerify: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#insecure_skip_verify RegistryImage#insecure_skip_verify}

---

##### `keepRemotely`<sup>Optional</sup> <a name="keepRemotely" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.keepRemotely"></a>

```typescript
public readonly keepRemotely: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If true, then the Docker image won't be deleted on destroy operation.

If this is false, it will delete the image from the docker registry on destroy operation. Defaults to `false`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#keep_remotely RegistryImage#keep_remotely}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.timeouts"></a>

```typescript
public readonly timeouts: RegistryImageTimeouts;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#timeouts RegistryImage#timeouts}

---

##### `triggers`<sup>Optional</sup> <a name="triggers" id="@cdktn/provider-docker.registryImage.RegistryImageConfig.property.triggers"></a>

```typescript
public readonly triggers: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

A map of arbitrary strings that, when changed, will force the `docker_registry_image` resource to be replaced.

This can be used to repush a local image

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#triggers RegistryImage#triggers}

---

### RegistryImageTimeouts <a name="RegistryImageTimeouts" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

const registryImageTimeouts: registryImage.RegistryImageTimeouts = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create">create</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#create RegistryImage#create}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete">delete</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#delete RegistryImage#delete}. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update">update</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#update RegistryImage#update}. |

---

##### `create`<sup>Optional</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.create"></a>

```typescript
public readonly create: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#create RegistryImage#create}.

---

##### `delete`<sup>Optional</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.delete"></a>

```typescript
public readonly delete: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#delete RegistryImage#delete}.

---

##### `update`<sup>Optional</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeouts.property.update"></a>

```typescript
public readonly update: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.4.0/docs/resources/registry_image#update RegistryImage#update}.

---

## Classes <a name="Classes" id="Classes"></a>

### RegistryImageAuthConfigOutputReference <a name="RegistryImageAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageAuthConfigOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetPassword` <a name="resetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetPassword"></a>

```typescript
public resetPassword(): void
```

##### `resetUsername` <a name="resetUsername" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.resetUsername"></a>

```typescript
public resetUsername(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput">addressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput">passwordInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput">usernameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address">address</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password">password</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username">username</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `addressInput`<sup>Optional</sup> <a name="addressInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.addressInput"></a>

```typescript
public readonly addressInput: string;
```

- *Type:* string

---

##### `passwordInput`<sup>Optional</sup> <a name="passwordInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.passwordInput"></a>

```typescript
public readonly passwordInput: string;
```

- *Type:* string

---

##### `usernameInput`<sup>Optional</sup> <a name="usernameInput" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.usernameInput"></a>

```typescript
public readonly usernameInput: string;
```

- *Type:* string

---

##### `address`<sup>Required</sup> <a name="address" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.address"></a>

```typescript
public readonly address: string;
```

- *Type:* string

---

##### `password`<sup>Required</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.password"></a>

```typescript
public readonly password: string;
```

- *Type:* string

---

##### `username`<sup>Required</sup> <a name="username" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.username"></a>

```typescript
public readonly username: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageAuthConfigOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: RegistryImageAuthConfig;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageAuthConfig">RegistryImageAuthConfig</a>

---


### RegistryImageBuildAuthConfigList <a name="RegistryImageBuildAuthConfigList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildAuthConfigList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

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

```typescript
public allWithMapKey(mapKeyAttributeName: string): DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get"></a>

```typescript
public get(index: number): RegistryImageBuildAuthConfigOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageBuildAuthConfig[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

---


### RegistryImageBuildAuthConfigOutputReference <a name="RegistryImageBuildAuthConfigOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildAuthConfigOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAuth` <a name="resetAuth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetAuth"></a>

```typescript
public resetAuth(): void
```

##### `resetEmail` <a name="resetEmail" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetEmail"></a>

```typescript
public resetEmail(): void
```

##### `resetIdentityToken` <a name="resetIdentityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetIdentityToken"></a>

```typescript
public resetIdentityToken(): void
```

##### `resetPassword` <a name="resetPassword" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetPassword"></a>

```typescript
public resetPassword(): void
```

##### `resetRegistryToken` <a name="resetRegistryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetRegistryToken"></a>

```typescript
public resetRegistryToken(): void
```

##### `resetServerAddress` <a name="resetServerAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetServerAddress"></a>

```typescript
public resetServerAddress(): void
```

##### `resetUserName` <a name="resetUserName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.resetUserName"></a>

```typescript
public resetUserName(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput">authInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput">emailInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput">hostNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput">identityTokenInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput">passwordInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput">registryTokenInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput">serverAddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput">userNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth">auth</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email">email</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName">hostName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken">identityToken</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password">password</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken">registryToken</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress">serverAddress</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName">userName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `authInput`<sup>Optional</sup> <a name="authInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.authInput"></a>

```typescript
public readonly authInput: string;
```

- *Type:* string

---

##### `emailInput`<sup>Optional</sup> <a name="emailInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.emailInput"></a>

```typescript
public readonly emailInput: string;
```

- *Type:* string

---

##### `hostNameInput`<sup>Optional</sup> <a name="hostNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostNameInput"></a>

```typescript
public readonly hostNameInput: string;
```

- *Type:* string

---

##### `identityTokenInput`<sup>Optional</sup> <a name="identityTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityTokenInput"></a>

```typescript
public readonly identityTokenInput: string;
```

- *Type:* string

---

##### `passwordInput`<sup>Optional</sup> <a name="passwordInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.passwordInput"></a>

```typescript
public readonly passwordInput: string;
```

- *Type:* string

---

##### `registryTokenInput`<sup>Optional</sup> <a name="registryTokenInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryTokenInput"></a>

```typescript
public readonly registryTokenInput: string;
```

- *Type:* string

---

##### `serverAddressInput`<sup>Optional</sup> <a name="serverAddressInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddressInput"></a>

```typescript
public readonly serverAddressInput: string;
```

- *Type:* string

---

##### `userNameInput`<sup>Optional</sup> <a name="userNameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userNameInput"></a>

```typescript
public readonly userNameInput: string;
```

- *Type:* string

---

##### `auth`<sup>Required</sup> <a name="auth" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.auth"></a>

```typescript
public readonly auth: string;
```

- *Type:* string

---

##### `email`<sup>Required</sup> <a name="email" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.email"></a>

```typescript
public readonly email: string;
```

- *Type:* string

---

##### `hostName`<sup>Required</sup> <a name="hostName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.hostName"></a>

```typescript
public readonly hostName: string;
```

- *Type:* string

---

##### `identityToken`<sup>Required</sup> <a name="identityToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.identityToken"></a>

```typescript
public readonly identityToken: string;
```

- *Type:* string

---

##### `password`<sup>Required</sup> <a name="password" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.password"></a>

```typescript
public readonly password: string;
```

- *Type:* string

---

##### `registryToken`<sup>Required</sup> <a name="registryToken" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.registryToken"></a>

```typescript
public readonly registryToken: string;
```

- *Type:* string

---

##### `serverAddress`<sup>Required</sup> <a name="serverAddress" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.serverAddress"></a>

```typescript
public readonly serverAddress: string;
```

- *Type:* string

---

##### `userName`<sup>Required</sup> <a name="userName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.userName"></a>

```typescript
public readonly userName: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageBuildAuthConfig;
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>

---


### RegistryImageBuildOutputReference <a name="RegistryImageBuildOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

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
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance">resetProvenance</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent">resetPullParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext">resetRemoteContext</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove">resetRemove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom">resetSbom</a></code> | *No description.* |
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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putAuthConfig` <a name="putAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig"></a>

```typescript
public putAuthConfig(value: IResolvable | RegistryImageBuildAuthConfig[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putAuthConfig.parameter.value"></a>

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

---

##### `putSecrets` <a name="putSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets"></a>

```typescript
public putSecrets(value: IResolvable | RegistryImageBuildSecrets[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putSecrets.parameter.value"></a>

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

---

##### `putUlimit` <a name="putUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit"></a>

```typescript
public putUlimit(value: IResolvable | RegistryImageBuildUlimit[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.putUlimit.parameter.value"></a>

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

---

##### `resetAdditionalContexts` <a name="resetAdditionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAdditionalContexts"></a>

```typescript
public resetAdditionalContexts(): void
```

##### `resetAuthConfig` <a name="resetAuthConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetAuthConfig"></a>

```typescript
public resetAuthConfig(): void
```

##### `resetBuildArgs` <a name="resetBuildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildArgs"></a>

```typescript
public resetBuildArgs(): void
```

##### `resetBuilder` <a name="resetBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuilder"></a>

```typescript
public resetBuilder(): void
```

##### `resetBuildId` <a name="resetBuildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildId"></a>

```typescript
public resetBuildId(): void
```

##### `resetBuildLogFile` <a name="resetBuildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetBuildLogFile"></a>

```typescript
public resetBuildLogFile(): void
```

##### `resetCacheFrom` <a name="resetCacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheFrom"></a>

```typescript
public resetCacheFrom(): void
```

##### `resetCacheTo` <a name="resetCacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCacheTo"></a>

```typescript
public resetCacheTo(): void
```

##### `resetCgroupParent` <a name="resetCgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCgroupParent"></a>

```typescript
public resetCgroupParent(): void
```

##### `resetCpuPeriod` <a name="resetCpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuPeriod"></a>

```typescript
public resetCpuPeriod(): void
```

##### `resetCpuQuota` <a name="resetCpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuQuota"></a>

```typescript
public resetCpuQuota(): void
```

##### `resetCpuSetCpus` <a name="resetCpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetCpus"></a>

```typescript
public resetCpuSetCpus(): void
```

##### `resetCpuSetMems` <a name="resetCpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuSetMems"></a>

```typescript
public resetCpuSetMems(): void
```

##### `resetCpuShares` <a name="resetCpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetCpuShares"></a>

```typescript
public resetCpuShares(): void
```

##### `resetDockerfile` <a name="resetDockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetDockerfile"></a>

```typescript
public resetDockerfile(): void
```

##### `resetExtraHosts` <a name="resetExtraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetExtraHosts"></a>

```typescript
public resetExtraHosts(): void
```

##### `resetForceRemove` <a name="resetForceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetForceRemove"></a>

```typescript
public resetForceRemove(): void
```

##### `resetIsolation` <a name="resetIsolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetIsolation"></a>

```typescript
public resetIsolation(): void
```

##### `resetLabel` <a name="resetLabel" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabel"></a>

```typescript
public resetLabel(): void
```

##### `resetLabels` <a name="resetLabels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetLabels"></a>

```typescript
public resetLabels(): void
```

##### `resetMemory` <a name="resetMemory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemory"></a>

```typescript
public resetMemory(): void
```

##### `resetMemorySwap` <a name="resetMemorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetMemorySwap"></a>

```typescript
public resetMemorySwap(): void
```

##### `resetNetworkMode` <a name="resetNetworkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNetworkMode"></a>

```typescript
public resetNetworkMode(): void
```

##### `resetNoCache` <a name="resetNoCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetNoCache"></a>

```typescript
public resetNoCache(): void
```

##### `resetPlatform` <a name="resetPlatform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPlatform"></a>

```typescript
public resetPlatform(): void
```

##### `resetProvenance` <a name="resetProvenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetProvenance"></a>

```typescript
public resetProvenance(): void
```

##### `resetPullParent` <a name="resetPullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetPullParent"></a>

```typescript
public resetPullParent(): void
```

##### `resetRemoteContext` <a name="resetRemoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemoteContext"></a>

```typescript
public resetRemoteContext(): void
```

##### `resetRemove` <a name="resetRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetRemove"></a>

```typescript
public resetRemove(): void
```

##### `resetSbom` <a name="resetSbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSbom"></a>

```typescript
public resetSbom(): void
```

##### `resetSecrets` <a name="resetSecrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecrets"></a>

```typescript
public resetSecrets(): void
```

##### `resetSecurityOpt` <a name="resetSecurityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSecurityOpt"></a>

```typescript
public resetSecurityOpt(): void
```

##### `resetSessionId` <a name="resetSessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSessionId"></a>

```typescript
public resetSessionId(): void
```

##### `resetShmSize` <a name="resetShmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetShmSize"></a>

```typescript
public resetShmSize(): void
```

##### `resetSquash` <a name="resetSquash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSquash"></a>

```typescript
public resetSquash(): void
```

##### `resetSuppressOutput` <a name="resetSuppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetSuppressOutput"></a>

```typescript
public resetSuppressOutput(): void
```

##### `resetTag` <a name="resetTag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTag"></a>

```typescript
public resetTag(): void
```

##### `resetTarget` <a name="resetTarget" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetTarget"></a>

```typescript
public resetTarget(): void
```

##### `resetUlimit` <a name="resetUlimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUlimit"></a>

```typescript
public resetUlimit(): void
```

##### `resetUseLegacyBuilder` <a name="resetUseLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetUseLegacyBuilder"></a>

```typescript
public resetUseLegacyBuilder(): void
```

##### `resetVersion` <a name="resetVersion" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.resetVersion"></a>

```typescript
public resetVersion(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig">authConfig</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets">secrets</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit">ulimit</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput">additionalContextsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput">authConfigInput</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput">buildArgsInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput">builderInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput">buildIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput">buildLogFileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput">cacheFromInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput">cacheToInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput">cgroupParentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput">contextInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput">cpuPeriodInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput">cpuQuotaInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput">cpuSetCpusInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput">cpuSetMemsInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput">cpuSharesInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput">dockerfileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput">extraHostsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput">forceRemoveInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput">isolationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput">labelInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput">labelsInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput">memoryInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput">memorySwapInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput">networkModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput">noCacheInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput">platformInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput">provenanceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput">pullParentInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput">remoteContextInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput">removeInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput">sbomInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput">secretsInput</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput">securityOptInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput">sessionIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput">shmSizeInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput">squashInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput">suppressOutputInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput">tagInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput">targetInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput">ulimitInput</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput">useLegacyBuilderInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput">versionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts">additionalContexts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs">buildArgs</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder">builder</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId">buildId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile">buildLogFile</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom">cacheFrom</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo">cacheTo</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent">cgroupParent</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context">context</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod">cpuPeriod</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota">cpuQuota</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus">cpuSetCpus</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems">cpuSetMems</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares">cpuShares</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile">dockerfile</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts">extraHosts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove">forceRemove</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation">isolation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label">label</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels">labels</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory">memory</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap">memorySwap</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode">networkMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache">noCache</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform">platform</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance">provenance</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent">pullParent</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext">remoteContext</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove">remove</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom">sbom</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt">securityOpt</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId">sessionId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize">shmSize</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash">squash</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput">suppressOutput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag">tag</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target">target</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder">useLegacyBuilder</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version">version</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `authConfig`<sup>Required</sup> <a name="authConfig" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfig"></a>

```typescript
public readonly authConfig: RegistryImageBuildAuthConfigList;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfigList">RegistryImageBuildAuthConfigList</a>

---

##### `secrets`<sup>Required</sup> <a name="secrets" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secrets"></a>

```typescript
public readonly secrets: RegistryImageBuildSecretsList;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList">RegistryImageBuildSecretsList</a>

---

##### `ulimit`<sup>Required</sup> <a name="ulimit" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimit"></a>

```typescript
public readonly ulimit: RegistryImageBuildUlimitList;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList">RegistryImageBuildUlimitList</a>

---

##### `additionalContextsInput`<sup>Optional</sup> <a name="additionalContextsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContextsInput"></a>

```typescript
public readonly additionalContextsInput: string[];
```

- *Type:* string[]

---

##### `authConfigInput`<sup>Optional</sup> <a name="authConfigInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.authConfigInput"></a>

```typescript
public readonly authConfigInput: IResolvable | RegistryImageBuildAuthConfig[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildAuthConfig">RegistryImageBuildAuthConfig</a>[]

---

##### `buildArgsInput`<sup>Optional</sup> <a name="buildArgsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgsInput"></a>

```typescript
public readonly buildArgsInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `builderInput`<sup>Optional</sup> <a name="builderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builderInput"></a>

```typescript
public readonly builderInput: string;
```

- *Type:* string

---

##### `buildIdInput`<sup>Optional</sup> <a name="buildIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildIdInput"></a>

```typescript
public readonly buildIdInput: string;
```

- *Type:* string

---

##### `buildLogFileInput`<sup>Optional</sup> <a name="buildLogFileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFileInput"></a>

```typescript
public readonly buildLogFileInput: string;
```

- *Type:* string

---

##### `cacheFromInput`<sup>Optional</sup> <a name="cacheFromInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFromInput"></a>

```typescript
public readonly cacheFromInput: string[];
```

- *Type:* string[]

---

##### `cacheToInput`<sup>Optional</sup> <a name="cacheToInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheToInput"></a>

```typescript
public readonly cacheToInput: string[];
```

- *Type:* string[]

---

##### `cgroupParentInput`<sup>Optional</sup> <a name="cgroupParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParentInput"></a>

```typescript
public readonly cgroupParentInput: string;
```

- *Type:* string

---

##### `contextInput`<sup>Optional</sup> <a name="contextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.contextInput"></a>

```typescript
public readonly contextInput: string;
```

- *Type:* string

---

##### `cpuPeriodInput`<sup>Optional</sup> <a name="cpuPeriodInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriodInput"></a>

```typescript
public readonly cpuPeriodInput: number;
```

- *Type:* number

---

##### `cpuQuotaInput`<sup>Optional</sup> <a name="cpuQuotaInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuotaInput"></a>

```typescript
public readonly cpuQuotaInput: number;
```

- *Type:* number

---

##### `cpuSetCpusInput`<sup>Optional</sup> <a name="cpuSetCpusInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpusInput"></a>

```typescript
public readonly cpuSetCpusInput: string;
```

- *Type:* string

---

##### `cpuSetMemsInput`<sup>Optional</sup> <a name="cpuSetMemsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMemsInput"></a>

```typescript
public readonly cpuSetMemsInput: string;
```

- *Type:* string

---

##### `cpuSharesInput`<sup>Optional</sup> <a name="cpuSharesInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSharesInput"></a>

```typescript
public readonly cpuSharesInput: number;
```

- *Type:* number

---

##### `dockerfileInput`<sup>Optional</sup> <a name="dockerfileInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfileInput"></a>

```typescript
public readonly dockerfileInput: string;
```

- *Type:* string

---

##### `extraHostsInput`<sup>Optional</sup> <a name="extraHostsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHostsInput"></a>

```typescript
public readonly extraHostsInput: string[];
```

- *Type:* string[]

---

##### `forceRemoveInput`<sup>Optional</sup> <a name="forceRemoveInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemoveInput"></a>

```typescript
public readonly forceRemoveInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `isolationInput`<sup>Optional</sup> <a name="isolationInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolationInput"></a>

```typescript
public readonly isolationInput: string;
```

- *Type:* string

---

##### `labelInput`<sup>Optional</sup> <a name="labelInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelInput"></a>

```typescript
public readonly labelInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `labelsInput`<sup>Optional</sup> <a name="labelsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labelsInput"></a>

```typescript
public readonly labelsInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `memoryInput`<sup>Optional</sup> <a name="memoryInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memoryInput"></a>

```typescript
public readonly memoryInput: number;
```

- *Type:* number

---

##### `memorySwapInput`<sup>Optional</sup> <a name="memorySwapInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwapInput"></a>

```typescript
public readonly memorySwapInput: number;
```

- *Type:* number

---

##### `networkModeInput`<sup>Optional</sup> <a name="networkModeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkModeInput"></a>

```typescript
public readonly networkModeInput: string;
```

- *Type:* string

---

##### `noCacheInput`<sup>Optional</sup> <a name="noCacheInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCacheInput"></a>

```typescript
public readonly noCacheInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `platformInput`<sup>Optional</sup> <a name="platformInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platformInput"></a>

```typescript
public readonly platformInput: string;
```

- *Type:* string

---

##### `provenanceInput`<sup>Optional</sup> <a name="provenanceInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenanceInput"></a>

```typescript
public readonly provenanceInput: string;
```

- *Type:* string

---

##### `pullParentInput`<sup>Optional</sup> <a name="pullParentInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParentInput"></a>

```typescript
public readonly pullParentInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `remoteContextInput`<sup>Optional</sup> <a name="remoteContextInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContextInput"></a>

```typescript
public readonly remoteContextInput: string;
```

- *Type:* string

---

##### `removeInput`<sup>Optional</sup> <a name="removeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.removeInput"></a>

```typescript
public readonly removeInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `sbomInput`<sup>Optional</sup> <a name="sbomInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbomInput"></a>

```typescript
public readonly sbomInput: string;
```

- *Type:* string

---

##### `secretsInput`<sup>Optional</sup> <a name="secretsInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.secretsInput"></a>

```typescript
public readonly secretsInput: IResolvable | RegistryImageBuildSecrets[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

---

##### `securityOptInput`<sup>Optional</sup> <a name="securityOptInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOptInput"></a>

```typescript
public readonly securityOptInput: string[];
```

- *Type:* string[]

---

##### `sessionIdInput`<sup>Optional</sup> <a name="sessionIdInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionIdInput"></a>

```typescript
public readonly sessionIdInput: string;
```

- *Type:* string

---

##### `shmSizeInput`<sup>Optional</sup> <a name="shmSizeInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSizeInput"></a>

```typescript
public readonly shmSizeInput: number;
```

- *Type:* number

---

##### `squashInput`<sup>Optional</sup> <a name="squashInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squashInput"></a>

```typescript
public readonly squashInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `suppressOutputInput`<sup>Optional</sup> <a name="suppressOutputInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutputInput"></a>

```typescript
public readonly suppressOutputInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `tagInput`<sup>Optional</sup> <a name="tagInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tagInput"></a>

```typescript
public readonly tagInput: string[];
```

- *Type:* string[]

---

##### `targetInput`<sup>Optional</sup> <a name="targetInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.targetInput"></a>

```typescript
public readonly targetInput: string;
```

- *Type:* string

---

##### `ulimitInput`<sup>Optional</sup> <a name="ulimitInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.ulimitInput"></a>

```typescript
public readonly ulimitInput: IResolvable | RegistryImageBuildUlimit[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

---

##### `useLegacyBuilderInput`<sup>Optional</sup> <a name="useLegacyBuilderInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilderInput"></a>

```typescript
public readonly useLegacyBuilderInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `versionInput`<sup>Optional</sup> <a name="versionInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.versionInput"></a>

```typescript
public readonly versionInput: string;
```

- *Type:* string

---

##### `additionalContexts`<sup>Required</sup> <a name="additionalContexts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.additionalContexts"></a>

```typescript
public readonly additionalContexts: string[];
```

- *Type:* string[]

---

##### `buildArgs`<sup>Required</sup> <a name="buildArgs" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildArgs"></a>

```typescript
public readonly buildArgs: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `builder`<sup>Required</sup> <a name="builder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.builder"></a>

```typescript
public readonly builder: string;
```

- *Type:* string

---

##### `buildId`<sup>Required</sup> <a name="buildId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildId"></a>

```typescript
public readonly buildId: string;
```

- *Type:* string

---

##### `buildLogFile`<sup>Required</sup> <a name="buildLogFile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.buildLogFile"></a>

```typescript
public readonly buildLogFile: string;
```

- *Type:* string

---

##### `cacheFrom`<sup>Required</sup> <a name="cacheFrom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheFrom"></a>

```typescript
public readonly cacheFrom: string[];
```

- *Type:* string[]

---

##### `cacheTo`<sup>Required</sup> <a name="cacheTo" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cacheTo"></a>

```typescript
public readonly cacheTo: string[];
```

- *Type:* string[]

---

##### `cgroupParent`<sup>Required</sup> <a name="cgroupParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cgroupParent"></a>

```typescript
public readonly cgroupParent: string;
```

- *Type:* string

---

##### `context`<sup>Required</sup> <a name="context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.context"></a>

```typescript
public readonly context: string;
```

- *Type:* string

---

##### `cpuPeriod`<sup>Required</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuPeriod"></a>

```typescript
public readonly cpuPeriod: number;
```

- *Type:* number

---

##### `cpuQuota`<sup>Required</sup> <a name="cpuQuota" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuQuota"></a>

```typescript
public readonly cpuQuota: number;
```

- *Type:* number

---

##### `cpuSetCpus`<sup>Required</sup> <a name="cpuSetCpus" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetCpus"></a>

```typescript
public readonly cpuSetCpus: string;
```

- *Type:* string

---

##### `cpuSetMems`<sup>Required</sup> <a name="cpuSetMems" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuSetMems"></a>

```typescript
public readonly cpuSetMems: string;
```

- *Type:* string

---

##### `cpuShares`<sup>Required</sup> <a name="cpuShares" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.cpuShares"></a>

```typescript
public readonly cpuShares: number;
```

- *Type:* number

---

##### `dockerfile`<sup>Required</sup> <a name="dockerfile" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.dockerfile"></a>

```typescript
public readonly dockerfile: string;
```

- *Type:* string

---

##### `extraHosts`<sup>Required</sup> <a name="extraHosts" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.extraHosts"></a>

```typescript
public readonly extraHosts: string[];
```

- *Type:* string[]

---

##### `forceRemove`<sup>Required</sup> <a name="forceRemove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.forceRemove"></a>

```typescript
public readonly forceRemove: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `isolation`<sup>Required</sup> <a name="isolation" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.isolation"></a>

```typescript
public readonly isolation: string;
```

- *Type:* string

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.label"></a>

```typescript
public readonly label: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.labels"></a>

```typescript
public readonly labels: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `memory`<sup>Required</sup> <a name="memory" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memory"></a>

```typescript
public readonly memory: number;
```

- *Type:* number

---

##### `memorySwap`<sup>Required</sup> <a name="memorySwap" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.memorySwap"></a>

```typescript
public readonly memorySwap: number;
```

- *Type:* number

---

##### `networkMode`<sup>Required</sup> <a name="networkMode" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.networkMode"></a>

```typescript
public readonly networkMode: string;
```

- *Type:* string

---

##### `noCache`<sup>Required</sup> <a name="noCache" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.noCache"></a>

```typescript
public readonly noCache: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `platform`<sup>Required</sup> <a name="platform" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.platform"></a>

```typescript
public readonly platform: string;
```

- *Type:* string

---

##### `provenance`<sup>Required</sup> <a name="provenance" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.provenance"></a>

```typescript
public readonly provenance: string;
```

- *Type:* string

---

##### `pullParent`<sup>Required</sup> <a name="pullParent" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.pullParent"></a>

```typescript
public readonly pullParent: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `remoteContext`<sup>Required</sup> <a name="remoteContext" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remoteContext"></a>

```typescript
public readonly remoteContext: string;
```

- *Type:* string

---

##### `remove`<sup>Required</sup> <a name="remove" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.remove"></a>

```typescript
public readonly remove: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `sbom`<sup>Required</sup> <a name="sbom" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sbom"></a>

```typescript
public readonly sbom: string;
```

- *Type:* string

---

##### `securityOpt`<sup>Required</sup> <a name="securityOpt" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.securityOpt"></a>

```typescript
public readonly securityOpt: string[];
```

- *Type:* string[]

---

##### `sessionId`<sup>Required</sup> <a name="sessionId" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.sessionId"></a>

```typescript
public readonly sessionId: string;
```

- *Type:* string

---

##### `shmSize`<sup>Required</sup> <a name="shmSize" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.shmSize"></a>

```typescript
public readonly shmSize: number;
```

- *Type:* number

---

##### `squash`<sup>Required</sup> <a name="squash" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.squash"></a>

```typescript
public readonly squash: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `suppressOutput`<sup>Required</sup> <a name="suppressOutput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.suppressOutput"></a>

```typescript
public readonly suppressOutput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `tag`<sup>Required</sup> <a name="tag" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.tag"></a>

```typescript
public readonly tag: string[];
```

- *Type:* string[]

---

##### `target`<sup>Required</sup> <a name="target" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.target"></a>

```typescript
public readonly target: string;
```

- *Type:* string

---

##### `useLegacyBuilder`<sup>Required</sup> <a name="useLegacyBuilder" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.useLegacyBuilder"></a>

```typescript
public readonly useLegacyBuilder: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `version`<sup>Required</sup> <a name="version" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.version"></a>

```typescript
public readonly version: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: RegistryImageBuild;
```

- *Type:* <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuild">RegistryImageBuild</a>

---


### RegistryImageBuildSecretsList <a name="RegistryImageBuildSecretsList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildSecretsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

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

```typescript
public allWithMapKey(mapKeyAttributeName: string): DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get"></a>

```typescript
public get(index: number): RegistryImageBuildSecretsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageBuildSecrets[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>[]

---


### RegistryImageBuildSecretsOutputReference <a name="RegistryImageBuildSecretsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildSecretsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetEnv` <a name="resetEnv" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetEnv"></a>

```typescript
public resetEnv(): void
```

##### `resetSrc` <a name="resetSrc" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.resetSrc"></a>

```typescript
public resetSrc(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput">envInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput">srcInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env">env</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src">src</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `envInput`<sup>Optional</sup> <a name="envInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.envInput"></a>

```typescript
public readonly envInput: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `srcInput`<sup>Optional</sup> <a name="srcInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.srcInput"></a>

```typescript
public readonly srcInput: string;
```

- *Type:* string

---

##### `env`<sup>Required</sup> <a name="env" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.env"></a>

```typescript
public readonly env: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `src`<sup>Required</sup> <a name="src" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.src"></a>

```typescript
public readonly src: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildSecretsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageBuildSecrets;
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildSecrets">RegistryImageBuildSecrets</a>

---


### RegistryImageBuildUlimitList <a name="RegistryImageBuildUlimitList" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildUlimitList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

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

```typescript
public allWithMapKey(mapKeyAttributeName: string): DynamicListTerraformIterator
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get"></a>

```typescript
public get(index: number): RegistryImageBuildUlimitOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageBuildUlimit[];
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>[]

---


### RegistryImageBuildUlimitOutputReference <a name="RegistryImageBuildUlimitOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageBuildUlimitOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput">hardInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput">softInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard">hard</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft">soft</a></code> | <code>number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `hardInput`<sup>Optional</sup> <a name="hardInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hardInput"></a>

```typescript
public readonly hardInput: number;
```

- *Type:* number

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `softInput`<sup>Optional</sup> <a name="softInput" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.softInput"></a>

```typescript
public readonly softInput: number;
```

- *Type:* number

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.hard"></a>

```typescript
public readonly hard: number;
```

- *Type:* number

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.soft"></a>

```typescript
public readonly soft: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageBuildUlimitOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageBuildUlimit;
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageBuildUlimit">RegistryImageBuildUlimit</a>

---


### RegistryImageTimeoutsOutputReference <a name="RegistryImageTimeoutsOutputReference" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer"></a>

```typescript
import { registryImage } from '@cdktn/provider-docker'

new registryImage.RegistryImageTimeoutsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

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

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetCreate` <a name="resetCreate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetCreate"></a>

```typescript
public resetCreate(): void
```

##### `resetDelete` <a name="resetDelete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetDelete"></a>

```typescript
public resetDelete(): void
```

##### `resetUpdate` <a name="resetUpdate" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.resetUpdate"></a>

```typescript
public resetUpdate(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput">createInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput">deleteInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput">updateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create">create</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete">delete</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update">update</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktn.IResolvable \| <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `createInput`<sup>Optional</sup> <a name="createInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.createInput"></a>

```typescript
public readonly createInput: string;
```

- *Type:* string

---

##### `deleteInput`<sup>Optional</sup> <a name="deleteInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.deleteInput"></a>

```typescript
public readonly deleteInput: string;
```

- *Type:* string

---

##### `updateInput`<sup>Optional</sup> <a name="updateInput" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.updateInput"></a>

```typescript
public readonly updateInput: string;
```

- *Type:* string

---

##### `create`<sup>Required</sup> <a name="create" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.create"></a>

```typescript
public readonly create: string;
```

- *Type:* string

---

##### `delete`<sup>Required</sup> <a name="delete" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.delete"></a>

```typescript
public readonly delete: string;
```

- *Type:* string

---

##### `update`<sup>Required</sup> <a name="update" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.update"></a>

```typescript
public readonly update: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.registryImage.RegistryImageTimeoutsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | RegistryImageTimeouts;
```

- *Type:* cdktn.IResolvable | <a href="#@cdktn/provider-docker.registryImage.RegistryImageTimeouts">RegistryImageTimeouts</a>

---



