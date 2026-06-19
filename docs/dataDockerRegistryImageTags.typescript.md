# `dataDockerRegistryImageTags` Submodule <a name="`dataDockerRegistryImageTags` Submodule" id="@cdktn/provider-docker.dataDockerRegistryImageTags"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataDockerRegistryImageTags <a name="DataDockerRegistryImageTags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags docker_registry_image_tags}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer"></a>

```typescript
import { dataDockerRegistryImageTags } from '@cdktn/provider-docker'

new dataDockerRegistryImageTags.DataDockerRegistryImageTags(scope: Construct, id: string, config: DataDockerRegistryImageTagsConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.config">config</a></code> | <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig">DataDockerRegistryImageTagsConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig">DataDockerRegistryImageTagsConfig</a>

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

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with"></a>

```typescript
public with(mixins: ...IMixin[]): IConstruct
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.with.parameter.mixins"></a>

- *Type:* ...constructs.IMixin[]

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toHclTerraform"></a>

```typescript
public toHclTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `resetInsecureSkipVerify` <a name="resetInsecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetInsecureSkipVerify"></a>

```typescript
public resetInsecureSkipVerify(): void
```

##### `resetStrictSemver` <a name="resetStrictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.resetStrictSemver"></a>

```typescript
public resetStrictSemver(): void
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

```typescript
import { dataDockerRegistryImageTags } from '@cdktn/provider-docker'

dataDockerRegistryImageTags.DataDockerRegistryImageTags.isConstruct(x: any)
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

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement"></a>

```typescript
import { dataDockerRegistryImageTags } from '@cdktn/provider-docker'

dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource"></a>

```typescript
import { dataDockerRegistryImageTags } from '@cdktn/provider-docker'

dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.isTerraformDataSource.parameter.x"></a>

- *Type:* any

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport"></a>

```typescript
import { dataDockerRegistryImageTags } from '@cdktn/provider-docker'

dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport(scope: Construct, importToId: string, importFromId: string, provider?: TerraformProvider)
```

Generates CDKTN code for importing a DataDockerRegistryImageTags resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataDockerRegistryImageTags to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataDockerRegistryImageTags that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.generateConfigForImport.parameter.provider"></a>

- *Type:* cdktn.TerraformProvider

? Optional instance of the provider where the DataDockerRegistryImageTags to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack">cdktfStack</a></code> | <code>cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags">tags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput">insecureSkipVerifyInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput">strictSemverInput</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver">strictSemver</a></code> | <code>boolean \| cdktn.IResolvable</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktn.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `tags`<sup>Required</sup> <a name="tags" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tags"></a>

```typescript
public readonly tags: string[];
```

- *Type:* string[]

---

##### `insecureSkipVerifyInput`<sup>Optional</sup> <a name="insecureSkipVerifyInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerifyInput"></a>

```typescript
public readonly insecureSkipVerifyInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `strictSemverInput`<sup>Optional</sup> <a name="strictSemverInput" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemverInput"></a>

```typescript
public readonly strictSemverInput: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `insecureSkipVerify`<sup>Required</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.insecureSkipVerify"></a>

```typescript
public readonly insecureSkipVerify: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `strictSemver`<sup>Required</sup> <a name="strictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.strictSemver"></a>

```typescript
public readonly strictSemver: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTags.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataDockerRegistryImageTagsConfig <a name="DataDockerRegistryImageTagsConfig" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.Initializer"></a>

```typescript
import { dataDockerRegistryImageTags } from '@cdktn/provider-docker'

const dataDockerRegistryImageTagsConfig: dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection">connection</a></code> | <code>cdktn.SSHProvisionerConnection \| cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count">count</a></code> | <code>number \| cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn">dependsOn</a></code> | <code>cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach">forEach</a></code> | <code>cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle">lifecycle</a></code> | <code>cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider">provider</a></code> | <code>cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners">provisioners</a></code> | <code>cdktn.FileProvisioner \| cdktn.LocalExecProvisioner \| cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name">name</a></code> | <code>string</code> | The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify">insecureSkipVerify</a></code> | <code>boolean \| cdktn.IResolvable</code> | If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver">strictSemver</a></code> | <code>boolean \| cdktn.IResolvable</code> | If `true`, only stable semantic version tags are returned. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktn.SSHProvisionerConnection | cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktn.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.provisioners"></a>

```typescript
public readonly provisioners: (FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner)[];
```

- *Type:* cdktn.FileProvisioner | cdktn.LocalExecProvisioner | cdktn.RemoteExecProvisioner[]

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

The name of the Docker image repository, including any tag or digest. For example, `alpine:latest`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#name DataDockerRegistryImageTags#name}

---

##### `insecureSkipVerify`<sup>Optional</sup> <a name="insecureSkipVerify" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.insecureSkipVerify"></a>

```typescript
public readonly insecureSkipVerify: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If `true`, the verification of TLS certificates of the server/registry is disabled. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#insecure_skip_verify DataDockerRegistryImageTags#insecure_skip_verify}

---

##### `strictSemver`<sup>Optional</sup> <a name="strictSemver" id="@cdktn/provider-docker.dataDockerRegistryImageTags.DataDockerRegistryImageTagsConfig.property.strictSemver"></a>

```typescript
public readonly strictSemver: boolean | IResolvable;
```

- *Type:* boolean | cdktn.IResolvable

If `true`, only stable semantic version tags are returned.

Prerelease tags such as `1.2.3-rc.1` are excluded as well as any other tags that do not conform to the semantic versioning specification. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/data-sources/registry_image_tags#strict_semver DataDockerRegistryImageTags#strict_semver}

---



