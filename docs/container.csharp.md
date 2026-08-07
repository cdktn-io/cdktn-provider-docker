# `container` Submodule <a name="`container` Submodule" id="@cdktn/provider-docker.container"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Container <a name="Container" id="@cdktn/provider-docker.container.Container"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container docker_container}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.Container.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new Container(Construct Scope, string Id, ContainerConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerConfig">ContainerConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.container.Container.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.container.Container.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="@cdktn/provider-docker.container.Container.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerConfig">ContainerConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.container.Container.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.container.Container.toHclTerraform">ToHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.container.Container.addMoveTarget">AddMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.container.Container.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.hasResourceMove">HasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.importFrom">ImportFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.moveFromId">MoveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.container.Container.moveTo">MoveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.container.Container.moveToId">MoveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.container.Container.putCapabilities">PutCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceReadBps">PutDeviceReadBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceReadIops">PutDeviceReadIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceRequests">PutDeviceRequests</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDevices">PutDevices</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceWriteBps">PutDeviceWriteBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceWriteIops">PutDeviceWriteIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putHealthcheck">PutHealthcheck</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putHost">PutHost</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putLabels">PutLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putMounts">PutMounts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putNetworksAdvanced">PutNetworksAdvanced</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putPorts">PutPorts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putTimeouts">PutTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putUlimit">PutUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putUpload">PutUpload</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putVolumes">PutVolumes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetAttach">ResetAttach</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCapabilities">ResetCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCgroupnsMode">ResetCgroupnsMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCgroupParent">ResetCgroupParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCommand">ResetCommand</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetContainerReadRefreshTimeoutMilliseconds">ResetContainerReadRefreshTimeoutMilliseconds</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuPeriod">ResetCpuPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuQuota">ResetCpuQuota</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpus">ResetCpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuSet">ResetCpuSet</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuShares">ResetCpuShares</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDestroyGraceSeconds">ResetDestroyGraceSeconds</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceReadBps">ResetDeviceReadBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceReadIops">ResetDeviceReadIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceRequests">ResetDeviceRequests</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDevices">ResetDevices</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceWriteBps">ResetDeviceWriteBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceWriteIops">ResetDeviceWriteIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDns">ResetDns</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDnsOpts">ResetDnsOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDnsSearch">ResetDnsSearch</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDomainname">ResetDomainname</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetEntrypoint">ResetEntrypoint</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetEnv">ResetEnv</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetGpus">ResetGpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetGroupAdd">ResetGroupAdd</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetHealthcheck">ResetHealthcheck</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetHost">ResetHost</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetHostname">ResetHostname</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetInit">ResetInit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetIpcMode">ResetIpcMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLabels">ResetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLogDriver">ResetLogDriver</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLogOpts">ResetLogOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLogs">ResetLogs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMaxRetryCount">ResetMaxRetryCount</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMemory">ResetMemory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMemoryReservation">ResetMemoryReservation</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMemorySwap">ResetMemorySwap</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMounts">ResetMounts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMustRun">ResetMustRun</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetNetworkMode">ResetNetworkMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetNetworksAdvanced">ResetNetworksAdvanced</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPidMode">ResetPidMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPlatform">ResetPlatform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPorts">ResetPorts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPrivileged">ResetPrivileged</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPublishAllPorts">ResetPublishAllPorts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetReadOnly">ResetReadOnly</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRemoveVolumes">ResetRemoveVolumes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRestart">ResetRestart</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRm">ResetRm</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRuntime">ResetRuntime</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetSecurityOpts">ResetSecurityOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetShmSize">ResetShmSize</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStart">ResetStart</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStdinOpen">ResetStdinOpen</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStopSignal">ResetStopSignal</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStopTimeout">ResetStopTimeout</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStorageOpts">ResetStorageOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetSysctls">ResetSysctls</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetTimeouts">ResetTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetTmpfs">ResetTmpfs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetTty">ResetTty</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUlimit">ResetUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUpload">ResetUpload</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUser">ResetUser</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUsernsMode">ResetUsernsMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetVolumes">ResetVolumes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetWait">ResetWait</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetWaitTimeout">ResetWaitTimeout</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetWorkingDir">ResetWorkingDir</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.Container.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-docker.container.Container.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-docker.container.Container.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-docker.container.Container.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.Container.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-docker.container.Container.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-docker.container.Container.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-docker.container.Container.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-docker.container.Container.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-docker.container.Container.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-docker.container.Container.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `AddMoveTarget` <a name="AddMoveTarget" id="@cdktn/provider-docker.container.Container.addMoveTarget"></a>

```csharp
private void AddMoveTarget(string MoveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.container.Container.addMoveTarget.parameter.moveTarget"></a>

- *Type:* string

The string move target that will correspond to this resource.

---

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.Container.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.Container.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.Container.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.Container.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.Container.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.Container.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.Container.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.Container.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.Container.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `HasResourceMove` <a name="HasResourceMove" id="@cdktn/provider-docker.container.Container.hasResourceMove"></a>

```csharp
private TerraformResourceMoveByTarget|TerraformResourceMoveById HasResourceMove()
```

##### `ImportFrom` <a name="ImportFrom" id="@cdktn/provider-docker.container.Container.importFrom"></a>

```csharp
private void ImportFrom(string Id, TerraformProvider Provider = null)
```

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.container.Container.importFrom.parameter.id"></a>

- *Type:* string

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.container.Container.importFrom.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.Container.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.Container.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `MoveFromId` <a name="MoveFromId" id="@cdktn/provider-docker.container.Container.moveFromId"></a>

```csharp
private void MoveFromId(string Id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.container.Container.moveFromId.parameter.id"></a>

- *Type:* string

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `MoveTo` <a name="MoveTo" id="@cdktn/provider-docker.container.Container.moveTo"></a>

```csharp
private void MoveTo(string MoveTarget, string|double Index = null)
```

Moves this resource to the target resource given by moveTarget.

###### `MoveTarget`<sup>Required</sup> <a name="MoveTarget" id="@cdktn/provider-docker.container.Container.moveTo.parameter.moveTarget"></a>

- *Type:* string

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `Index`<sup>Optional</sup> <a name="Index" id="@cdktn/provider-docker.container.Container.moveTo.parameter.index"></a>

- *Type:* string|double

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `MoveToId` <a name="MoveToId" id="@cdktn/provider-docker.container.Container.moveToId"></a>

```csharp
private void MoveToId(string Id)
```

Moves this resource to the resource corresponding to "id".

###### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.container.Container.moveToId.parameter.id"></a>

- *Type:* string

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `PutCapabilities` <a name="PutCapabilities" id="@cdktn/provider-docker.container.Container.putCapabilities"></a>

```csharp
private void PutCapabilities(ContainerCapabilities Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putCapabilities.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

---

##### `PutDeviceReadBps` <a name="PutDeviceReadBps" id="@cdktn/provider-docker.container.Container.putDeviceReadBps"></a>

```csharp
private void PutDeviceReadBps(IResolvable|ContainerDeviceReadBps[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putDeviceReadBps.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]

---

##### `PutDeviceReadIops` <a name="PutDeviceReadIops" id="@cdktn/provider-docker.container.Container.putDeviceReadIops"></a>

```csharp
private void PutDeviceReadIops(IResolvable|ContainerDeviceReadIops[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putDeviceReadIops.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]

---

##### `PutDeviceRequests` <a name="PutDeviceRequests" id="@cdktn/provider-docker.container.Container.putDeviceRequests"></a>

```csharp
private void PutDeviceRequests(IResolvable|ContainerDeviceRequests[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putDeviceRequests.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]

---

##### `PutDevices` <a name="PutDevices" id="@cdktn/provider-docker.container.Container.putDevices"></a>

```csharp
private void PutDevices(IResolvable|ContainerDevices[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putDevices.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]

---

##### `PutDeviceWriteBps` <a name="PutDeviceWriteBps" id="@cdktn/provider-docker.container.Container.putDeviceWriteBps"></a>

```csharp
private void PutDeviceWriteBps(IResolvable|ContainerDeviceWriteBps[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putDeviceWriteBps.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]

---

##### `PutDeviceWriteIops` <a name="PutDeviceWriteIops" id="@cdktn/provider-docker.container.Container.putDeviceWriteIops"></a>

```csharp
private void PutDeviceWriteIops(IResolvable|ContainerDeviceWriteIops[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putDeviceWriteIops.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]

---

##### `PutHealthcheck` <a name="PutHealthcheck" id="@cdktn/provider-docker.container.Container.putHealthcheck"></a>

```csharp
private void PutHealthcheck(ContainerHealthcheck Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putHealthcheck.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

---

##### `PutHost` <a name="PutHost" id="@cdktn/provider-docker.container.Container.putHost"></a>

```csharp
private void PutHost(IResolvable|ContainerHost[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putHost.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]

---

##### `PutLabels` <a name="PutLabels" id="@cdktn/provider-docker.container.Container.putLabels"></a>

```csharp
private void PutLabels(IResolvable|ContainerLabels[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putLabels.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]

---

##### `PutMounts` <a name="PutMounts" id="@cdktn/provider-docker.container.Container.putMounts"></a>

```csharp
private void PutMounts(IResolvable|ContainerMounts[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putMounts.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]

---

##### `PutNetworksAdvanced` <a name="PutNetworksAdvanced" id="@cdktn/provider-docker.container.Container.putNetworksAdvanced"></a>

```csharp
private void PutNetworksAdvanced(IResolvable|ContainerNetworksAdvanced[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putNetworksAdvanced.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]

---

##### `PutPorts` <a name="PutPorts" id="@cdktn/provider-docker.container.Container.putPorts"></a>

```csharp
private void PutPorts(IResolvable|ContainerPorts[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putPorts.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]

---

##### `PutTimeouts` <a name="PutTimeouts" id="@cdktn/provider-docker.container.Container.putTimeouts"></a>

```csharp
private void PutTimeouts(ContainerTimeouts Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

---

##### `PutUlimit` <a name="PutUlimit" id="@cdktn/provider-docker.container.Container.putUlimit"></a>

```csharp
private void PutUlimit(IResolvable|ContainerUlimit[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putUlimit.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]

---

##### `PutUpload` <a name="PutUpload" id="@cdktn/provider-docker.container.Container.putUpload"></a>

```csharp
private void PutUpload(IResolvable|ContainerUpload[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putUpload.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]

---

##### `PutVolumes` <a name="PutVolumes" id="@cdktn/provider-docker.container.Container.putVolumes"></a>

```csharp
private void PutVolumes(IResolvable|ContainerVolumes[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.Container.putVolumes.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]

---

##### `ResetAttach` <a name="ResetAttach" id="@cdktn/provider-docker.container.Container.resetAttach"></a>

```csharp
private void ResetAttach()
```

##### `ResetCapabilities` <a name="ResetCapabilities" id="@cdktn/provider-docker.container.Container.resetCapabilities"></a>

```csharp
private void ResetCapabilities()
```

##### `ResetCgroupnsMode` <a name="ResetCgroupnsMode" id="@cdktn/provider-docker.container.Container.resetCgroupnsMode"></a>

```csharp
private void ResetCgroupnsMode()
```

##### `ResetCgroupParent` <a name="ResetCgroupParent" id="@cdktn/provider-docker.container.Container.resetCgroupParent"></a>

```csharp
private void ResetCgroupParent()
```

##### `ResetCommand` <a name="ResetCommand" id="@cdktn/provider-docker.container.Container.resetCommand"></a>

```csharp
private void ResetCommand()
```

##### `ResetContainerReadRefreshTimeoutMilliseconds` <a name="ResetContainerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.Container.resetContainerReadRefreshTimeoutMilliseconds"></a>

```csharp
private void ResetContainerReadRefreshTimeoutMilliseconds()
```

##### `ResetCpuPeriod` <a name="ResetCpuPeriod" id="@cdktn/provider-docker.container.Container.resetCpuPeriod"></a>

```csharp
private void ResetCpuPeriod()
```

##### `ResetCpuQuota` <a name="ResetCpuQuota" id="@cdktn/provider-docker.container.Container.resetCpuQuota"></a>

```csharp
private void ResetCpuQuota()
```

##### `ResetCpus` <a name="ResetCpus" id="@cdktn/provider-docker.container.Container.resetCpus"></a>

```csharp
private void ResetCpus()
```

##### `ResetCpuSet` <a name="ResetCpuSet" id="@cdktn/provider-docker.container.Container.resetCpuSet"></a>

```csharp
private void ResetCpuSet()
```

##### `ResetCpuShares` <a name="ResetCpuShares" id="@cdktn/provider-docker.container.Container.resetCpuShares"></a>

```csharp
private void ResetCpuShares()
```

##### `ResetDestroyGraceSeconds` <a name="ResetDestroyGraceSeconds" id="@cdktn/provider-docker.container.Container.resetDestroyGraceSeconds"></a>

```csharp
private void ResetDestroyGraceSeconds()
```

##### `ResetDeviceReadBps` <a name="ResetDeviceReadBps" id="@cdktn/provider-docker.container.Container.resetDeviceReadBps"></a>

```csharp
private void ResetDeviceReadBps()
```

##### `ResetDeviceReadIops` <a name="ResetDeviceReadIops" id="@cdktn/provider-docker.container.Container.resetDeviceReadIops"></a>

```csharp
private void ResetDeviceReadIops()
```

##### `ResetDeviceRequests` <a name="ResetDeviceRequests" id="@cdktn/provider-docker.container.Container.resetDeviceRequests"></a>

```csharp
private void ResetDeviceRequests()
```

##### `ResetDevices` <a name="ResetDevices" id="@cdktn/provider-docker.container.Container.resetDevices"></a>

```csharp
private void ResetDevices()
```

##### `ResetDeviceWriteBps` <a name="ResetDeviceWriteBps" id="@cdktn/provider-docker.container.Container.resetDeviceWriteBps"></a>

```csharp
private void ResetDeviceWriteBps()
```

##### `ResetDeviceWriteIops` <a name="ResetDeviceWriteIops" id="@cdktn/provider-docker.container.Container.resetDeviceWriteIops"></a>

```csharp
private void ResetDeviceWriteIops()
```

##### `ResetDns` <a name="ResetDns" id="@cdktn/provider-docker.container.Container.resetDns"></a>

```csharp
private void ResetDns()
```

##### `ResetDnsOpts` <a name="ResetDnsOpts" id="@cdktn/provider-docker.container.Container.resetDnsOpts"></a>

```csharp
private void ResetDnsOpts()
```

##### `ResetDnsSearch` <a name="ResetDnsSearch" id="@cdktn/provider-docker.container.Container.resetDnsSearch"></a>

```csharp
private void ResetDnsSearch()
```

##### `ResetDomainname` <a name="ResetDomainname" id="@cdktn/provider-docker.container.Container.resetDomainname"></a>

```csharp
private void ResetDomainname()
```

##### `ResetEntrypoint` <a name="ResetEntrypoint" id="@cdktn/provider-docker.container.Container.resetEntrypoint"></a>

```csharp
private void ResetEntrypoint()
```

##### `ResetEnv` <a name="ResetEnv" id="@cdktn/provider-docker.container.Container.resetEnv"></a>

```csharp
private void ResetEnv()
```

##### `ResetGpus` <a name="ResetGpus" id="@cdktn/provider-docker.container.Container.resetGpus"></a>

```csharp
private void ResetGpus()
```

##### `ResetGroupAdd` <a name="ResetGroupAdd" id="@cdktn/provider-docker.container.Container.resetGroupAdd"></a>

```csharp
private void ResetGroupAdd()
```

##### `ResetHealthcheck` <a name="ResetHealthcheck" id="@cdktn/provider-docker.container.Container.resetHealthcheck"></a>

```csharp
private void ResetHealthcheck()
```

##### `ResetHost` <a name="ResetHost" id="@cdktn/provider-docker.container.Container.resetHost"></a>

```csharp
private void ResetHost()
```

##### `ResetHostname` <a name="ResetHostname" id="@cdktn/provider-docker.container.Container.resetHostname"></a>

```csharp
private void ResetHostname()
```

##### `ResetId` <a name="ResetId" id="@cdktn/provider-docker.container.Container.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetInit` <a name="ResetInit" id="@cdktn/provider-docker.container.Container.resetInit"></a>

```csharp
private void ResetInit()
```

##### `ResetIpcMode` <a name="ResetIpcMode" id="@cdktn/provider-docker.container.Container.resetIpcMode"></a>

```csharp
private void ResetIpcMode()
```

##### `ResetLabels` <a name="ResetLabels" id="@cdktn/provider-docker.container.Container.resetLabels"></a>

```csharp
private void ResetLabels()
```

##### `ResetLogDriver` <a name="ResetLogDriver" id="@cdktn/provider-docker.container.Container.resetLogDriver"></a>

```csharp
private void ResetLogDriver()
```

##### `ResetLogOpts` <a name="ResetLogOpts" id="@cdktn/provider-docker.container.Container.resetLogOpts"></a>

```csharp
private void ResetLogOpts()
```

##### `ResetLogs` <a name="ResetLogs" id="@cdktn/provider-docker.container.Container.resetLogs"></a>

```csharp
private void ResetLogs()
```

##### `ResetMaxRetryCount` <a name="ResetMaxRetryCount" id="@cdktn/provider-docker.container.Container.resetMaxRetryCount"></a>

```csharp
private void ResetMaxRetryCount()
```

##### `ResetMemory` <a name="ResetMemory" id="@cdktn/provider-docker.container.Container.resetMemory"></a>

```csharp
private void ResetMemory()
```

##### `ResetMemoryReservation` <a name="ResetMemoryReservation" id="@cdktn/provider-docker.container.Container.resetMemoryReservation"></a>

```csharp
private void ResetMemoryReservation()
```

##### `ResetMemorySwap` <a name="ResetMemorySwap" id="@cdktn/provider-docker.container.Container.resetMemorySwap"></a>

```csharp
private void ResetMemorySwap()
```

##### `ResetMounts` <a name="ResetMounts" id="@cdktn/provider-docker.container.Container.resetMounts"></a>

```csharp
private void ResetMounts()
```

##### `ResetMustRun` <a name="ResetMustRun" id="@cdktn/provider-docker.container.Container.resetMustRun"></a>

```csharp
private void ResetMustRun()
```

##### `ResetNetworkMode` <a name="ResetNetworkMode" id="@cdktn/provider-docker.container.Container.resetNetworkMode"></a>

```csharp
private void ResetNetworkMode()
```

##### `ResetNetworksAdvanced` <a name="ResetNetworksAdvanced" id="@cdktn/provider-docker.container.Container.resetNetworksAdvanced"></a>

```csharp
private void ResetNetworksAdvanced()
```

##### `ResetPidMode` <a name="ResetPidMode" id="@cdktn/provider-docker.container.Container.resetPidMode"></a>

```csharp
private void ResetPidMode()
```

##### `ResetPlatform` <a name="ResetPlatform" id="@cdktn/provider-docker.container.Container.resetPlatform"></a>

```csharp
private void ResetPlatform()
```

##### `ResetPorts` <a name="ResetPorts" id="@cdktn/provider-docker.container.Container.resetPorts"></a>

```csharp
private void ResetPorts()
```

##### `ResetPrivileged` <a name="ResetPrivileged" id="@cdktn/provider-docker.container.Container.resetPrivileged"></a>

```csharp
private void ResetPrivileged()
```

##### `ResetPublishAllPorts` <a name="ResetPublishAllPorts" id="@cdktn/provider-docker.container.Container.resetPublishAllPorts"></a>

```csharp
private void ResetPublishAllPorts()
```

##### `ResetReadOnly` <a name="ResetReadOnly" id="@cdktn/provider-docker.container.Container.resetReadOnly"></a>

```csharp
private void ResetReadOnly()
```

##### `ResetRemoveVolumes` <a name="ResetRemoveVolumes" id="@cdktn/provider-docker.container.Container.resetRemoveVolumes"></a>

```csharp
private void ResetRemoveVolumes()
```

##### `ResetRestart` <a name="ResetRestart" id="@cdktn/provider-docker.container.Container.resetRestart"></a>

```csharp
private void ResetRestart()
```

##### `ResetRm` <a name="ResetRm" id="@cdktn/provider-docker.container.Container.resetRm"></a>

```csharp
private void ResetRm()
```

##### `ResetRuntime` <a name="ResetRuntime" id="@cdktn/provider-docker.container.Container.resetRuntime"></a>

```csharp
private void ResetRuntime()
```

##### `ResetSecurityOpts` <a name="ResetSecurityOpts" id="@cdktn/provider-docker.container.Container.resetSecurityOpts"></a>

```csharp
private void ResetSecurityOpts()
```

##### `ResetShmSize` <a name="ResetShmSize" id="@cdktn/provider-docker.container.Container.resetShmSize"></a>

```csharp
private void ResetShmSize()
```

##### `ResetStart` <a name="ResetStart" id="@cdktn/provider-docker.container.Container.resetStart"></a>

```csharp
private void ResetStart()
```

##### `ResetStdinOpen` <a name="ResetStdinOpen" id="@cdktn/provider-docker.container.Container.resetStdinOpen"></a>

```csharp
private void ResetStdinOpen()
```

##### `ResetStopSignal` <a name="ResetStopSignal" id="@cdktn/provider-docker.container.Container.resetStopSignal"></a>

```csharp
private void ResetStopSignal()
```

##### `ResetStopTimeout` <a name="ResetStopTimeout" id="@cdktn/provider-docker.container.Container.resetStopTimeout"></a>

```csharp
private void ResetStopTimeout()
```

##### `ResetStorageOpts` <a name="ResetStorageOpts" id="@cdktn/provider-docker.container.Container.resetStorageOpts"></a>

```csharp
private void ResetStorageOpts()
```

##### `ResetSysctls` <a name="ResetSysctls" id="@cdktn/provider-docker.container.Container.resetSysctls"></a>

```csharp
private void ResetSysctls()
```

##### `ResetTimeouts` <a name="ResetTimeouts" id="@cdktn/provider-docker.container.Container.resetTimeouts"></a>

```csharp
private void ResetTimeouts()
```

##### `ResetTmpfs` <a name="ResetTmpfs" id="@cdktn/provider-docker.container.Container.resetTmpfs"></a>

```csharp
private void ResetTmpfs()
```

##### `ResetTty` <a name="ResetTty" id="@cdktn/provider-docker.container.Container.resetTty"></a>

```csharp
private void ResetTty()
```

##### `ResetUlimit` <a name="ResetUlimit" id="@cdktn/provider-docker.container.Container.resetUlimit"></a>

```csharp
private void ResetUlimit()
```

##### `ResetUpload` <a name="ResetUpload" id="@cdktn/provider-docker.container.Container.resetUpload"></a>

```csharp
private void ResetUpload()
```

##### `ResetUser` <a name="ResetUser" id="@cdktn/provider-docker.container.Container.resetUser"></a>

```csharp
private void ResetUser()
```

##### `ResetUsernsMode` <a name="ResetUsernsMode" id="@cdktn/provider-docker.container.Container.resetUsernsMode"></a>

```csharp
private void ResetUsernsMode()
```

##### `ResetVolumes` <a name="ResetVolumes" id="@cdktn/provider-docker.container.Container.resetVolumes"></a>

```csharp
private void ResetVolumes()
```

##### `ResetWait` <a name="ResetWait" id="@cdktn/provider-docker.container.Container.resetWait"></a>

```csharp
private void ResetWait()
```

##### `ResetWaitTimeout` <a name="ResetWaitTimeout" id="@cdktn/provider-docker.container.Container.resetWaitTimeout"></a>

```csharp
private void ResetWaitTimeout()
```

##### `ResetWorkingDir` <a name="ResetWorkingDir" id="@cdktn/provider-docker.container.Container.resetWorkingDir"></a>

```csharp
private void ResetWorkingDir()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.isTerraformResource">IsTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a Container resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-docker.container.Container.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Container.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.container.Container.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-docker.container.Container.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Container.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.container.Container.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="@cdktn/provider-docker.container.Container.isTerraformResource"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Container.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-docker.container.Container.isTerraformResource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-docker.container.Container.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Docker;

Container.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a Container resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the Container to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing Container that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the Container to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.bridge">Bridge</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.capabilities">Capabilities</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference">ContainerCapabilitiesOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.containerLogs">ContainerLogs</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadBps">DeviceReadBps</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList">ContainerDeviceReadBpsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadIops">DeviceReadIops</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList">ContainerDeviceReadIopsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceRequests">DeviceRequests</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList">ContainerDeviceRequestsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.devices">Devices</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList">ContainerDevicesList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteBps">DeviceWriteBps</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList">ContainerDeviceWriteBpsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteIops">DeviceWriteIops</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList">ContainerDeviceWriteIopsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.exitCode">ExitCode</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.healthcheck">Healthcheck</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference">ContainerHealthcheckOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.host">Host</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHostList">ContainerHostList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.labels">Labels</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList">ContainerLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mounts">Mounts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsList">ContainerMountsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networkData">NetworkData</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList">ContainerNetworkDataList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networksAdvanced">NetworksAdvanced</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList">ContainerNetworksAdvancedList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ports">Ports</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerPortsList">ContainerPortsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference">ContainerTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ulimit">Ulimit</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList">ContainerUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.upload">Upload</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerUploadList">ContainerUploadList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.volumes">Volumes</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList">ContainerVolumesList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.attachInput">AttachInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.capabilitiesInput">CapabilitiesInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupnsModeInput">CgroupnsModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupParentInput">CgroupParentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.commandInput">CommandInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMillisecondsInput">ContainerReadRefreshTimeoutMillisecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuPeriodInput">CpuPeriodInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuQuotaInput">CpuQuotaInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuSetInput">CpuSetInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuSharesInput">CpuSharesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpusInput">CpusInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.destroyGraceSecondsInput">DestroyGraceSecondsInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadBpsInput">DeviceReadBpsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadIopsInput">DeviceReadIopsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceRequestsInput">DeviceRequestsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.devicesInput">DevicesInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteBpsInput">DeviceWriteBpsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteIopsInput">DeviceWriteIopsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsInput">DnsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsOptsInput">DnsOptsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsSearchInput">DnsSearchInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.domainnameInput">DomainnameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.entrypointInput">EntrypointInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.envInput">EnvInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.gpusInput">GpusInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.groupAddInput">GroupAddInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.healthcheckInput">HealthcheckInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.hostInput">HostInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.hostnameInput">HostnameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.imageInput">ImageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.initInput">InitInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ipcModeInput">IpcModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.labelsInput">LabelsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logDriverInput">LogDriverInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logOptsInput">LogOptsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logsInput">LogsInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.maxRetryCountInput">MaxRetryCountInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memoryInput">MemoryInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memoryReservationInput">MemoryReservationInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memorySwapInput">MemorySwapInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mountsInput">MountsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mustRunInput">MustRunInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networkModeInput">NetworkModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networksAdvancedInput">NetworksAdvancedInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.pidModeInput">PidModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.platformInput">PlatformInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.portsInput">PortsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.privilegedInput">PrivilegedInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.publishAllPortsInput">PublishAllPortsInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.readOnlyInput">ReadOnlyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.removeVolumesInput">RemoveVolumesInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.restartInput">RestartInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.rmInput">RmInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.runtimeInput">RuntimeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.securityOptsInput">SecurityOptsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.shmSizeInput">ShmSizeInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.startInput">StartInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stdinOpenInput">StdinOpenInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopSignalInput">StopSignalInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopTimeoutInput">StopTimeoutInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.storageOptsInput">StorageOptsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.sysctlsInput">SysctlsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.timeoutsInput">TimeoutsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tmpfsInput">TmpfsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ttyInput">TtyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ulimitInput">UlimitInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.uploadInput">UploadInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.userInput">UserInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.usernsModeInput">UsernsModeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.volumesInput">VolumesInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.waitInput">WaitInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.waitTimeoutInput">WaitTimeoutInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.workingDirInput">WorkingDirInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.attach">Attach</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupnsMode">CgroupnsMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupParent">CgroupParent</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.command">Command</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMilliseconds">ContainerReadRefreshTimeoutMilliseconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuPeriod">CpuPeriod</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuQuota">CpuQuota</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpus">Cpus</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuSet">CpuSet</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuShares">CpuShares</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.destroyGraceSeconds">DestroyGraceSeconds</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dns">Dns</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsOpts">DnsOpts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsSearch">DnsSearch</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.domainname">Domainname</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.entrypoint">Entrypoint</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.env">Env</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.gpus">Gpus</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.groupAdd">GroupAdd</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.hostname">Hostname</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.image">Image</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.init">Init</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ipcMode">IpcMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logDriver">LogDriver</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logOpts">LogOpts</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logs">Logs</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.maxRetryCount">MaxRetryCount</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memory">Memory</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memoryReservation">MemoryReservation</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memorySwap">MemorySwap</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mustRun">MustRun</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networkMode">NetworkMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.pidMode">PidMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.platform">Platform</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.privileged">Privileged</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.publishAllPorts">PublishAllPorts</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.readOnly">ReadOnly</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.removeVolumes">RemoveVolumes</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.restart">Restart</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.rm">Rm</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.runtime">Runtime</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.securityOpts">SecurityOpts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.shmSize">ShmSize</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.start">Start</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stdinOpen">StdinOpen</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopSignal">StopSignal</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopTimeout">StopTimeout</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.storageOpts">StorageOpts</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.sysctls">Sysctls</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tmpfs">Tmpfs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tty">Tty</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.user">User</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.usernsMode">UsernsMode</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.wait">Wait</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.waitTimeout">WaitTimeout</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.workingDir">WorkingDir</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-docker.container.Container.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-docker.container.Container.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.Container.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-docker.container.Container.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-docker.container.Container.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-docker.container.Container.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-docker.container.Container.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.container.Container.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.container.Container.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.container.Container.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.container.Container.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.container.Container.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.container.Container.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.container.Container.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Bridge`<sup>Required</sup> <a name="Bridge" id="@cdktn/provider-docker.container.Container.property.bridge"></a>

```csharp
public string Bridge { get; }
```

- *Type:* string

---

##### `Capabilities`<sup>Required</sup> <a name="Capabilities" id="@cdktn/provider-docker.container.Container.property.capabilities"></a>

```csharp
public ContainerCapabilitiesOutputReference Capabilities { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference">ContainerCapabilitiesOutputReference</a>

---

##### `ContainerLogs`<sup>Required</sup> <a name="ContainerLogs" id="@cdktn/provider-docker.container.Container.property.containerLogs"></a>

```csharp
public string ContainerLogs { get; }
```

- *Type:* string

---

##### `DeviceReadBps`<sup>Required</sup> <a name="DeviceReadBps" id="@cdktn/provider-docker.container.Container.property.deviceReadBps"></a>

```csharp
public ContainerDeviceReadBpsList DeviceReadBps { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList">ContainerDeviceReadBpsList</a>

---

##### `DeviceReadIops`<sup>Required</sup> <a name="DeviceReadIops" id="@cdktn/provider-docker.container.Container.property.deviceReadIops"></a>

```csharp
public ContainerDeviceReadIopsList DeviceReadIops { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList">ContainerDeviceReadIopsList</a>

---

##### `DeviceRequests`<sup>Required</sup> <a name="DeviceRequests" id="@cdktn/provider-docker.container.Container.property.deviceRequests"></a>

```csharp
public ContainerDeviceRequestsList DeviceRequests { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList">ContainerDeviceRequestsList</a>

---

##### `Devices`<sup>Required</sup> <a name="Devices" id="@cdktn/provider-docker.container.Container.property.devices"></a>

```csharp
public ContainerDevicesList Devices { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDevicesList">ContainerDevicesList</a>

---

##### `DeviceWriteBps`<sup>Required</sup> <a name="DeviceWriteBps" id="@cdktn/provider-docker.container.Container.property.deviceWriteBps"></a>

```csharp
public ContainerDeviceWriteBpsList DeviceWriteBps { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList">ContainerDeviceWriteBpsList</a>

---

##### `DeviceWriteIops`<sup>Required</sup> <a name="DeviceWriteIops" id="@cdktn/provider-docker.container.Container.property.deviceWriteIops"></a>

```csharp
public ContainerDeviceWriteIopsList DeviceWriteIops { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList">ContainerDeviceWriteIopsList</a>

---

##### `ExitCode`<sup>Required</sup> <a name="ExitCode" id="@cdktn/provider-docker.container.Container.property.exitCode"></a>

```csharp
public double ExitCode { get; }
```

- *Type:* double

---

##### `Healthcheck`<sup>Required</sup> <a name="Healthcheck" id="@cdktn/provider-docker.container.Container.property.healthcheck"></a>

```csharp
public ContainerHealthcheckOutputReference Healthcheck { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference">ContainerHealthcheckOutputReference</a>

---

##### `Host`<sup>Required</sup> <a name="Host" id="@cdktn/provider-docker.container.Container.property.host"></a>

```csharp
public ContainerHostList Host { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHostList">ContainerHostList</a>

---

##### `Labels`<sup>Required</sup> <a name="Labels" id="@cdktn/provider-docker.container.Container.property.labels"></a>

```csharp
public ContainerLabelsList Labels { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerLabelsList">ContainerLabelsList</a>

---

##### `Mounts`<sup>Required</sup> <a name="Mounts" id="@cdktn/provider-docker.container.Container.property.mounts"></a>

```csharp
public ContainerMountsList Mounts { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsList">ContainerMountsList</a>

---

##### `NetworkData`<sup>Required</sup> <a name="NetworkData" id="@cdktn/provider-docker.container.Container.property.networkData"></a>

```csharp
public ContainerNetworkDataList NetworkData { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerNetworkDataList">ContainerNetworkDataList</a>

---

##### `NetworksAdvanced`<sup>Required</sup> <a name="NetworksAdvanced" id="@cdktn/provider-docker.container.Container.property.networksAdvanced"></a>

```csharp
public ContainerNetworksAdvancedList NetworksAdvanced { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList">ContainerNetworksAdvancedList</a>

---

##### `Ports`<sup>Required</sup> <a name="Ports" id="@cdktn/provider-docker.container.Container.property.ports"></a>

```csharp
public ContainerPortsList Ports { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerPortsList">ContainerPortsList</a>

---

##### `Timeouts`<sup>Required</sup> <a name="Timeouts" id="@cdktn/provider-docker.container.Container.property.timeouts"></a>

```csharp
public ContainerTimeoutsOutputReference Timeouts { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference">ContainerTimeoutsOutputReference</a>

---

##### `Ulimit`<sup>Required</sup> <a name="Ulimit" id="@cdktn/provider-docker.container.Container.property.ulimit"></a>

```csharp
public ContainerUlimitList Ulimit { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerUlimitList">ContainerUlimitList</a>

---

##### `Upload`<sup>Required</sup> <a name="Upload" id="@cdktn/provider-docker.container.Container.property.upload"></a>

```csharp
public ContainerUploadList Upload { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerUploadList">ContainerUploadList</a>

---

##### `Volumes`<sup>Required</sup> <a name="Volumes" id="@cdktn/provider-docker.container.Container.property.volumes"></a>

```csharp
public ContainerVolumesList Volumes { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerVolumesList">ContainerVolumesList</a>

---

##### `AttachInput`<sup>Optional</sup> <a name="AttachInput" id="@cdktn/provider-docker.container.Container.property.attachInput"></a>

```csharp
public bool|IResolvable AttachInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `CapabilitiesInput`<sup>Optional</sup> <a name="CapabilitiesInput" id="@cdktn/provider-docker.container.Container.property.capabilitiesInput"></a>

```csharp
public ContainerCapabilities CapabilitiesInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

---

##### `CgroupnsModeInput`<sup>Optional</sup> <a name="CgroupnsModeInput" id="@cdktn/provider-docker.container.Container.property.cgroupnsModeInput"></a>

```csharp
public string CgroupnsModeInput { get; }
```

- *Type:* string

---

##### `CgroupParentInput`<sup>Optional</sup> <a name="CgroupParentInput" id="@cdktn/provider-docker.container.Container.property.cgroupParentInput"></a>

```csharp
public string CgroupParentInput { get; }
```

- *Type:* string

---

##### `CommandInput`<sup>Optional</sup> <a name="CommandInput" id="@cdktn/provider-docker.container.Container.property.commandInput"></a>

```csharp
public string[] CommandInput { get; }
```

- *Type:* string[]

---

##### `ContainerReadRefreshTimeoutMillisecondsInput`<sup>Optional</sup> <a name="ContainerReadRefreshTimeoutMillisecondsInput" id="@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMillisecondsInput"></a>

```csharp
public double ContainerReadRefreshTimeoutMillisecondsInput { get; }
```

- *Type:* double

---

##### `CpuPeriodInput`<sup>Optional</sup> <a name="CpuPeriodInput" id="@cdktn/provider-docker.container.Container.property.cpuPeriodInput"></a>

```csharp
public double CpuPeriodInput { get; }
```

- *Type:* double

---

##### `CpuQuotaInput`<sup>Optional</sup> <a name="CpuQuotaInput" id="@cdktn/provider-docker.container.Container.property.cpuQuotaInput"></a>

```csharp
public double CpuQuotaInput { get; }
```

- *Type:* double

---

##### `CpuSetInput`<sup>Optional</sup> <a name="CpuSetInput" id="@cdktn/provider-docker.container.Container.property.cpuSetInput"></a>

```csharp
public string CpuSetInput { get; }
```

- *Type:* string

---

##### `CpuSharesInput`<sup>Optional</sup> <a name="CpuSharesInput" id="@cdktn/provider-docker.container.Container.property.cpuSharesInput"></a>

```csharp
public double CpuSharesInput { get; }
```

- *Type:* double

---

##### `CpusInput`<sup>Optional</sup> <a name="CpusInput" id="@cdktn/provider-docker.container.Container.property.cpusInput"></a>

```csharp
public string CpusInput { get; }
```

- *Type:* string

---

##### `DestroyGraceSecondsInput`<sup>Optional</sup> <a name="DestroyGraceSecondsInput" id="@cdktn/provider-docker.container.Container.property.destroyGraceSecondsInput"></a>

```csharp
public double DestroyGraceSecondsInput { get; }
```

- *Type:* double

---

##### `DeviceReadBpsInput`<sup>Optional</sup> <a name="DeviceReadBpsInput" id="@cdktn/provider-docker.container.Container.property.deviceReadBpsInput"></a>

```csharp
public IResolvable|ContainerDeviceReadBps[] DeviceReadBpsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]

---

##### `DeviceReadIopsInput`<sup>Optional</sup> <a name="DeviceReadIopsInput" id="@cdktn/provider-docker.container.Container.property.deviceReadIopsInput"></a>

```csharp
public IResolvable|ContainerDeviceReadIops[] DeviceReadIopsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]

---

##### `DeviceRequestsInput`<sup>Optional</sup> <a name="DeviceRequestsInput" id="@cdktn/provider-docker.container.Container.property.deviceRequestsInput"></a>

```csharp
public IResolvable|ContainerDeviceRequests[] DeviceRequestsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]

---

##### `DevicesInput`<sup>Optional</sup> <a name="DevicesInput" id="@cdktn/provider-docker.container.Container.property.devicesInput"></a>

```csharp
public IResolvable|ContainerDevices[] DevicesInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]

---

##### `DeviceWriteBpsInput`<sup>Optional</sup> <a name="DeviceWriteBpsInput" id="@cdktn/provider-docker.container.Container.property.deviceWriteBpsInput"></a>

```csharp
public IResolvable|ContainerDeviceWriteBps[] DeviceWriteBpsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]

---

##### `DeviceWriteIopsInput`<sup>Optional</sup> <a name="DeviceWriteIopsInput" id="@cdktn/provider-docker.container.Container.property.deviceWriteIopsInput"></a>

```csharp
public IResolvable|ContainerDeviceWriteIops[] DeviceWriteIopsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]

---

##### `DnsInput`<sup>Optional</sup> <a name="DnsInput" id="@cdktn/provider-docker.container.Container.property.dnsInput"></a>

```csharp
public string[] DnsInput { get; }
```

- *Type:* string[]

---

##### `DnsOptsInput`<sup>Optional</sup> <a name="DnsOptsInput" id="@cdktn/provider-docker.container.Container.property.dnsOptsInput"></a>

```csharp
public string[] DnsOptsInput { get; }
```

- *Type:* string[]

---

##### `DnsSearchInput`<sup>Optional</sup> <a name="DnsSearchInput" id="@cdktn/provider-docker.container.Container.property.dnsSearchInput"></a>

```csharp
public string[] DnsSearchInput { get; }
```

- *Type:* string[]

---

##### `DomainnameInput`<sup>Optional</sup> <a name="DomainnameInput" id="@cdktn/provider-docker.container.Container.property.domainnameInput"></a>

```csharp
public string DomainnameInput { get; }
```

- *Type:* string

---

##### `EntrypointInput`<sup>Optional</sup> <a name="EntrypointInput" id="@cdktn/provider-docker.container.Container.property.entrypointInput"></a>

```csharp
public string[] EntrypointInput { get; }
```

- *Type:* string[]

---

##### `EnvInput`<sup>Optional</sup> <a name="EnvInput" id="@cdktn/provider-docker.container.Container.property.envInput"></a>

```csharp
public string[] EnvInput { get; }
```

- *Type:* string[]

---

##### `GpusInput`<sup>Optional</sup> <a name="GpusInput" id="@cdktn/provider-docker.container.Container.property.gpusInput"></a>

```csharp
public string GpusInput { get; }
```

- *Type:* string

---

##### `GroupAddInput`<sup>Optional</sup> <a name="GroupAddInput" id="@cdktn/provider-docker.container.Container.property.groupAddInput"></a>

```csharp
public string[] GroupAddInput { get; }
```

- *Type:* string[]

---

##### `HealthcheckInput`<sup>Optional</sup> <a name="HealthcheckInput" id="@cdktn/provider-docker.container.Container.property.healthcheckInput"></a>

```csharp
public ContainerHealthcheck HealthcheckInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

---

##### `HostInput`<sup>Optional</sup> <a name="HostInput" id="@cdktn/provider-docker.container.Container.property.hostInput"></a>

```csharp
public IResolvable|ContainerHost[] HostInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]

---

##### `HostnameInput`<sup>Optional</sup> <a name="HostnameInput" id="@cdktn/provider-docker.container.Container.property.hostnameInput"></a>

```csharp
public string HostnameInput { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="@cdktn/provider-docker.container.Container.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `ImageInput`<sup>Optional</sup> <a name="ImageInput" id="@cdktn/provider-docker.container.Container.property.imageInput"></a>

```csharp
public string ImageInput { get; }
```

- *Type:* string

---

##### `InitInput`<sup>Optional</sup> <a name="InitInput" id="@cdktn/provider-docker.container.Container.property.initInput"></a>

```csharp
public bool|IResolvable InitInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `IpcModeInput`<sup>Optional</sup> <a name="IpcModeInput" id="@cdktn/provider-docker.container.Container.property.ipcModeInput"></a>

```csharp
public string IpcModeInput { get; }
```

- *Type:* string

---

##### `LabelsInput`<sup>Optional</sup> <a name="LabelsInput" id="@cdktn/provider-docker.container.Container.property.labelsInput"></a>

```csharp
public IResolvable|ContainerLabels[] LabelsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]

---

##### `LogDriverInput`<sup>Optional</sup> <a name="LogDriverInput" id="@cdktn/provider-docker.container.Container.property.logDriverInput"></a>

```csharp
public string LogDriverInput { get; }
```

- *Type:* string

---

##### `LogOptsInput`<sup>Optional</sup> <a name="LogOptsInput" id="@cdktn/provider-docker.container.Container.property.logOptsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LogOptsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `LogsInput`<sup>Optional</sup> <a name="LogsInput" id="@cdktn/provider-docker.container.Container.property.logsInput"></a>

```csharp
public bool|IResolvable LogsInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `MaxRetryCountInput`<sup>Optional</sup> <a name="MaxRetryCountInput" id="@cdktn/provider-docker.container.Container.property.maxRetryCountInput"></a>

```csharp
public double MaxRetryCountInput { get; }
```

- *Type:* double

---

##### `MemoryInput`<sup>Optional</sup> <a name="MemoryInput" id="@cdktn/provider-docker.container.Container.property.memoryInput"></a>

```csharp
public double MemoryInput { get; }
```

- *Type:* double

---

##### `MemoryReservationInput`<sup>Optional</sup> <a name="MemoryReservationInput" id="@cdktn/provider-docker.container.Container.property.memoryReservationInput"></a>

```csharp
public double MemoryReservationInput { get; }
```

- *Type:* double

---

##### `MemorySwapInput`<sup>Optional</sup> <a name="MemorySwapInput" id="@cdktn/provider-docker.container.Container.property.memorySwapInput"></a>

```csharp
public double MemorySwapInput { get; }
```

- *Type:* double

---

##### `MountsInput`<sup>Optional</sup> <a name="MountsInput" id="@cdktn/provider-docker.container.Container.property.mountsInput"></a>

```csharp
public IResolvable|ContainerMounts[] MountsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]

---

##### `MustRunInput`<sup>Optional</sup> <a name="MustRunInput" id="@cdktn/provider-docker.container.Container.property.mustRunInput"></a>

```csharp
public bool|IResolvable MustRunInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.container.Container.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `NetworkModeInput`<sup>Optional</sup> <a name="NetworkModeInput" id="@cdktn/provider-docker.container.Container.property.networkModeInput"></a>

```csharp
public string NetworkModeInput { get; }
```

- *Type:* string

---

##### `NetworksAdvancedInput`<sup>Optional</sup> <a name="NetworksAdvancedInput" id="@cdktn/provider-docker.container.Container.property.networksAdvancedInput"></a>

```csharp
public IResolvable|ContainerNetworksAdvanced[] NetworksAdvancedInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]

---

##### `PidModeInput`<sup>Optional</sup> <a name="PidModeInput" id="@cdktn/provider-docker.container.Container.property.pidModeInput"></a>

```csharp
public string PidModeInput { get; }
```

- *Type:* string

---

##### `PlatformInput`<sup>Optional</sup> <a name="PlatformInput" id="@cdktn/provider-docker.container.Container.property.platformInput"></a>

```csharp
public string PlatformInput { get; }
```

- *Type:* string

---

##### `PortsInput`<sup>Optional</sup> <a name="PortsInput" id="@cdktn/provider-docker.container.Container.property.portsInput"></a>

```csharp
public IResolvable|ContainerPorts[] PortsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]

---

##### `PrivilegedInput`<sup>Optional</sup> <a name="PrivilegedInput" id="@cdktn/provider-docker.container.Container.property.privilegedInput"></a>

```csharp
public bool|IResolvable PrivilegedInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `PublishAllPortsInput`<sup>Optional</sup> <a name="PublishAllPortsInput" id="@cdktn/provider-docker.container.Container.property.publishAllPortsInput"></a>

```csharp
public bool|IResolvable PublishAllPortsInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `ReadOnlyInput`<sup>Optional</sup> <a name="ReadOnlyInput" id="@cdktn/provider-docker.container.Container.property.readOnlyInput"></a>

```csharp
public bool|IResolvable ReadOnlyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RemoveVolumesInput`<sup>Optional</sup> <a name="RemoveVolumesInput" id="@cdktn/provider-docker.container.Container.property.removeVolumesInput"></a>

```csharp
public bool|IResolvable RemoveVolumesInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RestartInput`<sup>Optional</sup> <a name="RestartInput" id="@cdktn/provider-docker.container.Container.property.restartInput"></a>

```csharp
public string RestartInput { get; }
```

- *Type:* string

---

##### `RmInput`<sup>Optional</sup> <a name="RmInput" id="@cdktn/provider-docker.container.Container.property.rmInput"></a>

```csharp
public bool|IResolvable RmInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RuntimeInput`<sup>Optional</sup> <a name="RuntimeInput" id="@cdktn/provider-docker.container.Container.property.runtimeInput"></a>

```csharp
public string RuntimeInput { get; }
```

- *Type:* string

---

##### `SecurityOptsInput`<sup>Optional</sup> <a name="SecurityOptsInput" id="@cdktn/provider-docker.container.Container.property.securityOptsInput"></a>

```csharp
public string[] SecurityOptsInput { get; }
```

- *Type:* string[]

---

##### `ShmSizeInput`<sup>Optional</sup> <a name="ShmSizeInput" id="@cdktn/provider-docker.container.Container.property.shmSizeInput"></a>

```csharp
public double ShmSizeInput { get; }
```

- *Type:* double

---

##### `StartInput`<sup>Optional</sup> <a name="StartInput" id="@cdktn/provider-docker.container.Container.property.startInput"></a>

```csharp
public bool|IResolvable StartInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `StdinOpenInput`<sup>Optional</sup> <a name="StdinOpenInput" id="@cdktn/provider-docker.container.Container.property.stdinOpenInput"></a>

```csharp
public bool|IResolvable StdinOpenInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `StopSignalInput`<sup>Optional</sup> <a name="StopSignalInput" id="@cdktn/provider-docker.container.Container.property.stopSignalInput"></a>

```csharp
public string StopSignalInput { get; }
```

- *Type:* string

---

##### `StopTimeoutInput`<sup>Optional</sup> <a name="StopTimeoutInput" id="@cdktn/provider-docker.container.Container.property.stopTimeoutInput"></a>

```csharp
public double StopTimeoutInput { get; }
```

- *Type:* double

---

##### `StorageOptsInput`<sup>Optional</sup> <a name="StorageOptsInput" id="@cdktn/provider-docker.container.Container.property.storageOptsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> StorageOptsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `SysctlsInput`<sup>Optional</sup> <a name="SysctlsInput" id="@cdktn/provider-docker.container.Container.property.sysctlsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> SysctlsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `TimeoutsInput`<sup>Optional</sup> <a name="TimeoutsInput" id="@cdktn/provider-docker.container.Container.property.timeoutsInput"></a>

```csharp
public IResolvable|ContainerTimeouts TimeoutsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

---

##### `TmpfsInput`<sup>Optional</sup> <a name="TmpfsInput" id="@cdktn/provider-docker.container.Container.property.tmpfsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> TmpfsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `TtyInput`<sup>Optional</sup> <a name="TtyInput" id="@cdktn/provider-docker.container.Container.property.ttyInput"></a>

```csharp
public bool|IResolvable TtyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `UlimitInput`<sup>Optional</sup> <a name="UlimitInput" id="@cdktn/provider-docker.container.Container.property.ulimitInput"></a>

```csharp
public IResolvable|ContainerUlimit[] UlimitInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]

---

##### `UploadInput`<sup>Optional</sup> <a name="UploadInput" id="@cdktn/provider-docker.container.Container.property.uploadInput"></a>

```csharp
public IResolvable|ContainerUpload[] UploadInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]

---

##### `UserInput`<sup>Optional</sup> <a name="UserInput" id="@cdktn/provider-docker.container.Container.property.userInput"></a>

```csharp
public string UserInput { get; }
```

- *Type:* string

---

##### `UsernsModeInput`<sup>Optional</sup> <a name="UsernsModeInput" id="@cdktn/provider-docker.container.Container.property.usernsModeInput"></a>

```csharp
public string UsernsModeInput { get; }
```

- *Type:* string

---

##### `VolumesInput`<sup>Optional</sup> <a name="VolumesInput" id="@cdktn/provider-docker.container.Container.property.volumesInput"></a>

```csharp
public IResolvable|ContainerVolumes[] VolumesInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]

---

##### `WaitInput`<sup>Optional</sup> <a name="WaitInput" id="@cdktn/provider-docker.container.Container.property.waitInput"></a>

```csharp
public bool|IResolvable WaitInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `WaitTimeoutInput`<sup>Optional</sup> <a name="WaitTimeoutInput" id="@cdktn/provider-docker.container.Container.property.waitTimeoutInput"></a>

```csharp
public double WaitTimeoutInput { get; }
```

- *Type:* double

---

##### `WorkingDirInput`<sup>Optional</sup> <a name="WorkingDirInput" id="@cdktn/provider-docker.container.Container.property.workingDirInput"></a>

```csharp
public string WorkingDirInput { get; }
```

- *Type:* string

---

##### `Attach`<sup>Required</sup> <a name="Attach" id="@cdktn/provider-docker.container.Container.property.attach"></a>

```csharp
public bool|IResolvable Attach { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `CgroupnsMode`<sup>Required</sup> <a name="CgroupnsMode" id="@cdktn/provider-docker.container.Container.property.cgroupnsMode"></a>

```csharp
public string CgroupnsMode { get; }
```

- *Type:* string

---

##### `CgroupParent`<sup>Required</sup> <a name="CgroupParent" id="@cdktn/provider-docker.container.Container.property.cgroupParent"></a>

```csharp
public string CgroupParent { get; }
```

- *Type:* string

---

##### `Command`<sup>Required</sup> <a name="Command" id="@cdktn/provider-docker.container.Container.property.command"></a>

```csharp
public string[] Command { get; }
```

- *Type:* string[]

---

##### `ContainerReadRefreshTimeoutMilliseconds`<sup>Required</sup> <a name="ContainerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMilliseconds"></a>

```csharp
public double ContainerReadRefreshTimeoutMilliseconds { get; }
```

- *Type:* double

---

##### `CpuPeriod`<sup>Required</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.container.Container.property.cpuPeriod"></a>

```csharp
public double CpuPeriod { get; }
```

- *Type:* double

---

##### `CpuQuota`<sup>Required</sup> <a name="CpuQuota" id="@cdktn/provider-docker.container.Container.property.cpuQuota"></a>

```csharp
public double CpuQuota { get; }
```

- *Type:* double

---

##### `Cpus`<sup>Required</sup> <a name="Cpus" id="@cdktn/provider-docker.container.Container.property.cpus"></a>

```csharp
public string Cpus { get; }
```

- *Type:* string

---

##### `CpuSet`<sup>Required</sup> <a name="CpuSet" id="@cdktn/provider-docker.container.Container.property.cpuSet"></a>

```csharp
public string CpuSet { get; }
```

- *Type:* string

---

##### `CpuShares`<sup>Required</sup> <a name="CpuShares" id="@cdktn/provider-docker.container.Container.property.cpuShares"></a>

```csharp
public double CpuShares { get; }
```

- *Type:* double

---

##### `DestroyGraceSeconds`<sup>Required</sup> <a name="DestroyGraceSeconds" id="@cdktn/provider-docker.container.Container.property.destroyGraceSeconds"></a>

```csharp
public double DestroyGraceSeconds { get; }
```

- *Type:* double

---

##### `Dns`<sup>Required</sup> <a name="Dns" id="@cdktn/provider-docker.container.Container.property.dns"></a>

```csharp
public string[] Dns { get; }
```

- *Type:* string[]

---

##### `DnsOpts`<sup>Required</sup> <a name="DnsOpts" id="@cdktn/provider-docker.container.Container.property.dnsOpts"></a>

```csharp
public string[] DnsOpts { get; }
```

- *Type:* string[]

---

##### `DnsSearch`<sup>Required</sup> <a name="DnsSearch" id="@cdktn/provider-docker.container.Container.property.dnsSearch"></a>

```csharp
public string[] DnsSearch { get; }
```

- *Type:* string[]

---

##### `Domainname`<sup>Required</sup> <a name="Domainname" id="@cdktn/provider-docker.container.Container.property.domainname"></a>

```csharp
public string Domainname { get; }
```

- *Type:* string

---

##### `Entrypoint`<sup>Required</sup> <a name="Entrypoint" id="@cdktn/provider-docker.container.Container.property.entrypoint"></a>

```csharp
public string[] Entrypoint { get; }
```

- *Type:* string[]

---

##### `Env`<sup>Required</sup> <a name="Env" id="@cdktn/provider-docker.container.Container.property.env"></a>

```csharp
public string[] Env { get; }
```

- *Type:* string[]

---

##### `Gpus`<sup>Required</sup> <a name="Gpus" id="@cdktn/provider-docker.container.Container.property.gpus"></a>

```csharp
public string Gpus { get; }
```

- *Type:* string

---

##### `GroupAdd`<sup>Required</sup> <a name="GroupAdd" id="@cdktn/provider-docker.container.Container.property.groupAdd"></a>

```csharp
public string[] GroupAdd { get; }
```

- *Type:* string[]

---

##### `Hostname`<sup>Required</sup> <a name="Hostname" id="@cdktn/provider-docker.container.Container.property.hostname"></a>

```csharp
public string Hostname { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-docker.container.Container.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Image`<sup>Required</sup> <a name="Image" id="@cdktn/provider-docker.container.Container.property.image"></a>

```csharp
public string Image { get; }
```

- *Type:* string

---

##### `Init`<sup>Required</sup> <a name="Init" id="@cdktn/provider-docker.container.Container.property.init"></a>

```csharp
public bool|IResolvable Init { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `IpcMode`<sup>Required</sup> <a name="IpcMode" id="@cdktn/provider-docker.container.Container.property.ipcMode"></a>

```csharp
public string IpcMode { get; }
```

- *Type:* string

---

##### `LogDriver`<sup>Required</sup> <a name="LogDriver" id="@cdktn/provider-docker.container.Container.property.logDriver"></a>

```csharp
public string LogDriver { get; }
```

- *Type:* string

---

##### `LogOpts`<sup>Required</sup> <a name="LogOpts" id="@cdktn/provider-docker.container.Container.property.logOpts"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LogOpts { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Logs`<sup>Required</sup> <a name="Logs" id="@cdktn/provider-docker.container.Container.property.logs"></a>

```csharp
public bool|IResolvable Logs { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `MaxRetryCount`<sup>Required</sup> <a name="MaxRetryCount" id="@cdktn/provider-docker.container.Container.property.maxRetryCount"></a>

```csharp
public double MaxRetryCount { get; }
```

- *Type:* double

---

##### `Memory`<sup>Required</sup> <a name="Memory" id="@cdktn/provider-docker.container.Container.property.memory"></a>

```csharp
public double Memory { get; }
```

- *Type:* double

---

##### `MemoryReservation`<sup>Required</sup> <a name="MemoryReservation" id="@cdktn/provider-docker.container.Container.property.memoryReservation"></a>

```csharp
public double MemoryReservation { get; }
```

- *Type:* double

---

##### `MemorySwap`<sup>Required</sup> <a name="MemorySwap" id="@cdktn/provider-docker.container.Container.property.memorySwap"></a>

```csharp
public double MemorySwap { get; }
```

- *Type:* double

---

##### `MustRun`<sup>Required</sup> <a name="MustRun" id="@cdktn/provider-docker.container.Container.property.mustRun"></a>

```csharp
public bool|IResolvable MustRun { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.container.Container.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `NetworkMode`<sup>Required</sup> <a name="NetworkMode" id="@cdktn/provider-docker.container.Container.property.networkMode"></a>

```csharp
public string NetworkMode { get; }
```

- *Type:* string

---

##### `PidMode`<sup>Required</sup> <a name="PidMode" id="@cdktn/provider-docker.container.Container.property.pidMode"></a>

```csharp
public string PidMode { get; }
```

- *Type:* string

---

##### `Platform`<sup>Required</sup> <a name="Platform" id="@cdktn/provider-docker.container.Container.property.platform"></a>

```csharp
public string Platform { get; }
```

- *Type:* string

---

##### `Privileged`<sup>Required</sup> <a name="Privileged" id="@cdktn/provider-docker.container.Container.property.privileged"></a>

```csharp
public bool|IResolvable Privileged { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `PublishAllPorts`<sup>Required</sup> <a name="PublishAllPorts" id="@cdktn/provider-docker.container.Container.property.publishAllPorts"></a>

```csharp
public bool|IResolvable PublishAllPorts { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `ReadOnly`<sup>Required</sup> <a name="ReadOnly" id="@cdktn/provider-docker.container.Container.property.readOnly"></a>

```csharp
public bool|IResolvable ReadOnly { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `RemoveVolumes`<sup>Required</sup> <a name="RemoveVolumes" id="@cdktn/provider-docker.container.Container.property.removeVolumes"></a>

```csharp
public bool|IResolvable RemoveVolumes { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Restart`<sup>Required</sup> <a name="Restart" id="@cdktn/provider-docker.container.Container.property.restart"></a>

```csharp
public string Restart { get; }
```

- *Type:* string

---

##### `Rm`<sup>Required</sup> <a name="Rm" id="@cdktn/provider-docker.container.Container.property.rm"></a>

```csharp
public bool|IResolvable Rm { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Runtime`<sup>Required</sup> <a name="Runtime" id="@cdktn/provider-docker.container.Container.property.runtime"></a>

```csharp
public string Runtime { get; }
```

- *Type:* string

---

##### `SecurityOpts`<sup>Required</sup> <a name="SecurityOpts" id="@cdktn/provider-docker.container.Container.property.securityOpts"></a>

```csharp
public string[] SecurityOpts { get; }
```

- *Type:* string[]

---

##### `ShmSize`<sup>Required</sup> <a name="ShmSize" id="@cdktn/provider-docker.container.Container.property.shmSize"></a>

```csharp
public double ShmSize { get; }
```

- *Type:* double

---

##### `Start`<sup>Required</sup> <a name="Start" id="@cdktn/provider-docker.container.Container.property.start"></a>

```csharp
public bool|IResolvable Start { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `StdinOpen`<sup>Required</sup> <a name="StdinOpen" id="@cdktn/provider-docker.container.Container.property.stdinOpen"></a>

```csharp
public bool|IResolvable StdinOpen { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `StopSignal`<sup>Required</sup> <a name="StopSignal" id="@cdktn/provider-docker.container.Container.property.stopSignal"></a>

```csharp
public string StopSignal { get; }
```

- *Type:* string

---

##### `StopTimeout`<sup>Required</sup> <a name="StopTimeout" id="@cdktn/provider-docker.container.Container.property.stopTimeout"></a>

```csharp
public double StopTimeout { get; }
```

- *Type:* double

---

##### `StorageOpts`<sup>Required</sup> <a name="StorageOpts" id="@cdktn/provider-docker.container.Container.property.storageOpts"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> StorageOpts { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Sysctls`<sup>Required</sup> <a name="Sysctls" id="@cdktn/provider-docker.container.Container.property.sysctls"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Sysctls { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Tmpfs`<sup>Required</sup> <a name="Tmpfs" id="@cdktn/provider-docker.container.Container.property.tmpfs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Tmpfs { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Tty`<sup>Required</sup> <a name="Tty" id="@cdktn/provider-docker.container.Container.property.tty"></a>

```csharp
public bool|IResolvable Tty { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `User`<sup>Required</sup> <a name="User" id="@cdktn/provider-docker.container.Container.property.user"></a>

```csharp
public string User { get; }
```

- *Type:* string

---

##### `UsernsMode`<sup>Required</sup> <a name="UsernsMode" id="@cdktn/provider-docker.container.Container.property.usernsMode"></a>

```csharp
public string UsernsMode { get; }
```

- *Type:* string

---

##### `Wait`<sup>Required</sup> <a name="Wait" id="@cdktn/provider-docker.container.Container.property.wait"></a>

```csharp
public bool|IResolvable Wait { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `WaitTimeout`<sup>Required</sup> <a name="WaitTimeout" id="@cdktn/provider-docker.container.Container.property.waitTimeout"></a>

```csharp
public double WaitTimeout { get; }
```

- *Type:* double

---

##### `WorkingDir`<sup>Required</sup> <a name="WorkingDir" id="@cdktn/provider-docker.container.Container.property.workingDir"></a>

```csharp
public string WorkingDir { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-docker.container.Container.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ContainerCapabilities <a name="ContainerCapabilities" id="@cdktn/provider-docker.container.ContainerCapabilities"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerCapabilities.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerCapabilities {
    string[] Add = null,
    string[] Drop = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities.property.add">Add</a></code> | <code>string[]</code> | List of linux capabilities to add. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities.property.drop">Drop</a></code> | <code>string[]</code> | List of linux capabilities to drop. |

---

##### `Add`<sup>Optional</sup> <a name="Add" id="@cdktn/provider-docker.container.ContainerCapabilities.property.add"></a>

```csharp
public string[] Add { get; set; }
```

- *Type:* string[]

List of linux capabilities to add.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#add Container#add}

---

##### `Drop`<sup>Optional</sup> <a name="Drop" id="@cdktn/provider-docker.container.ContainerCapabilities.property.drop"></a>

```csharp
public string[] Drop { get; set; }
```

- *Type:* string[]

List of linux capabilities to drop.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#drop Container#drop}

---

### ContainerConfig <a name="ContainerConfig" id="@cdktn/provider-docker.container.ContainerConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string Image,
    string Name,
    bool|IResolvable Attach = null,
    ContainerCapabilities Capabilities = null,
    string CgroupnsMode = null,
    string CgroupParent = null,
    string[] Command = null,
    double ContainerReadRefreshTimeoutMilliseconds = null,
    double CpuPeriod = null,
    double CpuQuota = null,
    string Cpus = null,
    string CpuSet = null,
    double CpuShares = null,
    double DestroyGraceSeconds = null,
    IResolvable|ContainerDeviceReadBps[] DeviceReadBps = null,
    IResolvable|ContainerDeviceReadIops[] DeviceReadIops = null,
    IResolvable|ContainerDeviceRequests[] DeviceRequests = null,
    IResolvable|ContainerDevices[] Devices = null,
    IResolvable|ContainerDeviceWriteBps[] DeviceWriteBps = null,
    IResolvable|ContainerDeviceWriteIops[] DeviceWriteIops = null,
    string[] Dns = null,
    string[] DnsOpts = null,
    string[] DnsSearch = null,
    string Domainname = null,
    string[] Entrypoint = null,
    string[] Env = null,
    string Gpus = null,
    string[] GroupAdd = null,
    ContainerHealthcheck Healthcheck = null,
    IResolvable|ContainerHost[] Host = null,
    string Hostname = null,
    string Id = null,
    bool|IResolvable Init = null,
    string IpcMode = null,
    IResolvable|ContainerLabels[] Labels = null,
    string LogDriver = null,
    System.Collections.Generic.IDictionary<string, string> LogOpts = null,
    bool|IResolvable Logs = null,
    double MaxRetryCount = null,
    double Memory = null,
    double MemoryReservation = null,
    double MemorySwap = null,
    IResolvable|ContainerMounts[] Mounts = null,
    bool|IResolvable MustRun = null,
    string NetworkMode = null,
    IResolvable|ContainerNetworksAdvanced[] NetworksAdvanced = null,
    string PidMode = null,
    string Platform = null,
    IResolvable|ContainerPorts[] Ports = null,
    bool|IResolvable Privileged = null,
    bool|IResolvable PublishAllPorts = null,
    bool|IResolvable ReadOnly = null,
    bool|IResolvable RemoveVolumes = null,
    string Restart = null,
    bool|IResolvable Rm = null,
    string Runtime = null,
    string[] SecurityOpts = null,
    double ShmSize = null,
    bool|IResolvable Start = null,
    bool|IResolvable StdinOpen = null,
    string StopSignal = null,
    double StopTimeout = null,
    System.Collections.Generic.IDictionary<string, string> StorageOpts = null,
    System.Collections.Generic.IDictionary<string, string> Sysctls = null,
    ContainerTimeouts Timeouts = null,
    System.Collections.Generic.IDictionary<string, string> Tmpfs = null,
    bool|IResolvable Tty = null,
    IResolvable|ContainerUlimit[] Ulimit = null,
    IResolvable|ContainerUpload[] Upload = null,
    string User = null,
    string UsernsMode = null,
    IResolvable|ContainerVolumes[] Volumes = null,
    bool|IResolvable Wait = null,
    double WaitTimeout = null,
    string WorkingDir = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.image">Image</a></code> | <code>string</code> | The ID of the image to back this container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.name">Name</a></code> | <code>string</code> | The name of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.attach">Attach</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true` attach to the container after its creation and waits the end of its execution. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.capabilities">Capabilities</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | capabilities block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cgroupnsMode">CgroupnsMode</a></code> | <code>string</code> | Cgroup namespace mode to use for the container. Possible values are: `private`, `host`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cgroupParent">CgroupParent</a></code> | <code>string</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.command">Command</a></code> | <code>string[]</code> | The command to use to start the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.containerReadRefreshTimeoutMilliseconds">ContainerReadRefreshTimeoutMilliseconds</a></code> | <code>double</code> | The total number of milliseconds to wait for the container to reach status 'running'. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuPeriod">CpuPeriod</a></code> | <code>double</code> | Specify the CPU CFS scheduler period (in microseconds), which is used alongside `cpu-quota`. Is ignored if `cpus` is set. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuQuota">CpuQuota</a></code> | <code>double</code> | Impose a CPU CFS quota on the container (in microseconds). |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpus">Cpus</a></code> | <code>string</code> | Specify how much of the available CPU resources a container can use. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuSet">CpuSet</a></code> | <code>string</code> | A comma-separated list or hyphen-separated range of CPUs a container can use, e.g. `0-1`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuShares">CpuShares</a></code> | <code>double</code> | CPU shares (relative weight) for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.destroyGraceSeconds">DestroyGraceSeconds</a></code> | <code>double</code> | If defined will attempt to stop the container before destroying. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceReadBps">DeviceReadBps</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]</code> | device_read_bps block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceReadIops">DeviceReadIops</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]</code> | device_read_iops block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceRequests">DeviceRequests</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]</code> | device_requests block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.devices">Devices</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]</code> | devices block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteBps">DeviceWriteBps</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]</code> | device_write_bps block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteIops">DeviceWriteIops</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]</code> | device_write_iops block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dns">Dns</a></code> | <code>string[]</code> | DNS servers to use. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dnsOpts">DnsOpts</a></code> | <code>string[]</code> | DNS options used by the DNS provider(s), see `resolv.conf` documentation for valid list of options. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dnsSearch">DnsSearch</a></code> | <code>string[]</code> | DNS search domains that are used when bare unqualified hostnames are used inside of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.domainname">Domainname</a></code> | <code>string</code> | Domain name of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.entrypoint">Entrypoint</a></code> | <code>string[]</code> | The command to use as the Entrypoint for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.env">Env</a></code> | <code>string[]</code> | Environment variables to set in the form of `KEY=VALUE`, e.g. `DEBUG=0`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.gpus">Gpus</a></code> | <code>string</code> | GPU devices to add to the container. Supported values are `all` or `device=<id[,id...]>`, for example `device=0,2` or `device=GPU-3a23c669-1f69-c64e-cf85-44e9b07e7a2a`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.groupAdd">GroupAdd</a></code> | <code>string[]</code> | Additional groups for the container user. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.healthcheck">Healthcheck</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | healthcheck block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.host">Host</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]</code> | host block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.hostname">Hostname</a></code> | <code>string</code> | Hostname of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#id Container#id}. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.init">Init</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Configured whether an init process should be injected for this container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.ipcMode">IpcMode</a></code> | <code>string</code> | IPC sharing mode for the container. Possible values are: `none`, `private`, `shareable`, `container:<name\|id>` or `host`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.labels">Labels</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]</code> | labels block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.logDriver">LogDriver</a></code> | <code>string</code> | The logging driver to use for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.logOpts">LogOpts</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Key/value pairs to use as options for the logging driver. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.logs">Logs</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Save the container logs (`attach` must be enabled). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.maxRetryCount">MaxRetryCount</a></code> | <code>double</code> | The maximum amount of times to an attempt a restart when `restart` is set to 'on-failure'. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.memory">Memory</a></code> | <code>double</code> | The memory limit for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.memoryReservation">MemoryReservation</a></code> | <code>double</code> | The memory-resveration for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.memorySwap">MemorySwap</a></code> | <code>double</code> | The total memory limit (memory + swap) for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.mounts">Mounts</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]</code> | mounts block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.mustRun">MustRun</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, then the Docker container will be kept running. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.networkMode">NetworkMode</a></code> | <code>string</code> | Network mode of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.networksAdvanced">NetworksAdvanced</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]</code> | networks_advanced block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.pidMode">PidMode</a></code> | <code>string</code> | The PID (Process) Namespace mode for the container. Either `container:<name\|id>` or `host`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.platform">Platform</a></code> | <code>string</code> | Platform in the format `os[/arch[/variant]]` used for image lookup and container runtime, for example `linux/amd64`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.ports">Ports</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]</code> | ports block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.privileged">Privileged</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, the container runs in privileged mode. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.publishAllPorts">PublishAllPorts</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Publish all ports of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.readOnly">ReadOnly</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, the container will be started as readonly. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.removeVolumes">RemoveVolumes</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, it will remove anonymous volumes associated with the container. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.restart">Restart</a></code> | <code>string</code> | The restart policy for the container. Must be one of 'no', 'on-failure', 'always', 'unless-stopped'. Defaults to `no`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.rm">Rm</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, then the container will be automatically removed when it exits. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.runtime">Runtime</a></code> | <code>string</code> | Runtime to use for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.securityOpts">SecurityOpts</a></code> | <code>string[]</code> | List of string values to customize labels for MLS systems, such as SELinux. See https://docs.docker.com/engine/reference/run/#security-configuration. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.shmSize">ShmSize</a></code> | <code>double</code> | Size of `/dev/shm` in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.start">Start</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, then the Docker container will be started after creation. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.stdinOpen">StdinOpen</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, keep STDIN open even if not attached (`docker run -i`). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.stopSignal">StopSignal</a></code> | <code>string</code> | Signal to stop a container (default `SIGTERM`). |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.stopTimeout">StopTimeout</a></code> | <code>double</code> | Timeout (in seconds) to stop a container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.storageOpts">StorageOpts</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Key/value pairs for the storage driver options, e.g. `size`: `120G`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.sysctls">Sysctls</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | A map of kernel parameters (sysctls) to set in the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.timeouts">Timeouts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.tmpfs">Tmpfs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | A map of container directories which should be replaced by `tmpfs mounts`, and their corresponding mount options. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.tty">Tty</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, allocate a pseudo-tty (`docker run -t`). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.ulimit">Ulimit</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]</code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.upload">Upload</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]</code> | upload block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.user">User</a></code> | <code>string</code> | User used for run the first process. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.usernsMode">UsernsMode</a></code> | <code>string</code> | Sets the usernamespace mode for the container when usernamespace remapping option is enabled. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.volumes">Volumes</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]</code> | volumes block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.wait">Wait</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, then the Docker container is waited for being healthy state after creation. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.waitTimeout">WaitTimeout</a></code> | <code>double</code> | The timeout in seconds to wait the container to be healthy after creation. Defaults to `60`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.workingDir">WorkingDir</a></code> | <code>string</code> | The working directory for commands to run in. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-docker.container.ContainerConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.container.ContainerConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-docker.container.ContainerConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-docker.container.ContainerConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-docker.container.ContainerConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-docker.container.ContainerConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-docker.container.ContainerConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `Image`<sup>Required</sup> <a name="Image" id="@cdktn/provider-docker.container.ContainerConfig.property.image"></a>

```csharp
public string Image { get; set; }
```

- *Type:* string

The ID of the image to back this container.

The easiest way to get this value is to use the `image_id` attribute of the `docker_image` resource as is shown in the example.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#image Container#image}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.container.ContainerConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#name Container#name}

---

##### `Attach`<sup>Optional</sup> <a name="Attach" id="@cdktn/provider-docker.container.ContainerConfig.property.attach"></a>

```csharp
public bool|IResolvable Attach { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true` attach to the container after its creation and waits the end of its execution. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#attach Container#attach}

---

##### `Capabilities`<sup>Optional</sup> <a name="Capabilities" id="@cdktn/provider-docker.container.ContainerConfig.property.capabilities"></a>

```csharp
public ContainerCapabilities Capabilities { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

capabilities block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#capabilities Container#capabilities}

---

##### `CgroupnsMode`<sup>Optional</sup> <a name="CgroupnsMode" id="@cdktn/provider-docker.container.ContainerConfig.property.cgroupnsMode"></a>

```csharp
public string CgroupnsMode { get; set; }
```

- *Type:* string

Cgroup namespace mode to use for the container. Possible values are: `private`, `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cgroupns_mode Container#cgroupns_mode}

---

##### `CgroupParent`<sup>Optional</sup> <a name="CgroupParent" id="@cdktn/provider-docker.container.ContainerConfig.property.cgroupParent"></a>

```csharp
public string CgroupParent { get; set; }
```

- *Type:* string

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cgroup_parent Container#cgroup_parent}

---

##### `Command`<sup>Optional</sup> <a name="Command" id="@cdktn/provider-docker.container.ContainerConfig.property.command"></a>

```csharp
public string[] Command { get; set; }
```

- *Type:* string[]

The command to use to start the container.

For example, to run `/usr/bin/myprogram -f baz.conf` set the command to be `["/usr/bin/myprogram","-f","baz.conf"]`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#command Container#command}

---

##### `ContainerReadRefreshTimeoutMilliseconds`<sup>Optional</sup> <a name="ContainerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.ContainerConfig.property.containerReadRefreshTimeoutMilliseconds"></a>

```csharp
public double ContainerReadRefreshTimeoutMilliseconds { get; set; }
```

- *Type:* double

The total number of milliseconds to wait for the container to reach status 'running'.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#container_read_refresh_timeout_milliseconds Container#container_read_refresh_timeout_milliseconds}

---

##### `CpuPeriod`<sup>Optional</sup> <a name="CpuPeriod" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuPeriod"></a>

```csharp
public double CpuPeriod { get; set; }
```

- *Type:* double

Specify the CPU CFS scheduler period (in microseconds), which is used alongside `cpu-quota`. Is ignored if `cpus` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cpu_period Container#cpu_period}

---

##### `CpuQuota`<sup>Optional</sup> <a name="CpuQuota" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuQuota"></a>

```csharp
public double CpuQuota { get; set; }
```

- *Type:* double

Impose a CPU CFS quota on the container (in microseconds).

The number of microseconds per `cpu-period` that the container is limited to before throttled. Is ignored if `cpus` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cpu_quota Container#cpu_quota}

---

##### `Cpus`<sup>Optional</sup> <a name="Cpus" id="@cdktn/provider-docker.container.ContainerConfig.property.cpus"></a>

```csharp
public string Cpus { get; set; }
```

- *Type:* string

Specify how much of the available CPU resources a container can use.

e.g a value of 1.5 means the container is guaranteed at most one and a half of the CPUs. Has precedence over `cpu_period` and `cpu_quota`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cpus Container#cpus}

---

##### `CpuSet`<sup>Optional</sup> <a name="CpuSet" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuSet"></a>

```csharp
public string CpuSet { get; set; }
```

- *Type:* string

A comma-separated list or hyphen-separated range of CPUs a container can use, e.g. `0-1`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cpu_set Container#cpu_set}

---

##### `CpuShares`<sup>Optional</sup> <a name="CpuShares" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuShares"></a>

```csharp
public double CpuShares { get; set; }
```

- *Type:* double

CPU shares (relative weight) for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#cpu_shares Container#cpu_shares}

---

##### `DestroyGraceSeconds`<sup>Optional</sup> <a name="DestroyGraceSeconds" id="@cdktn/provider-docker.container.ContainerConfig.property.destroyGraceSeconds"></a>

```csharp
public double DestroyGraceSeconds { get; set; }
```

- *Type:* double

If defined will attempt to stop the container before destroying.

Container will be destroyed after `n` seconds or on successful stop.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#destroy_grace_seconds Container#destroy_grace_seconds}

---

##### `DeviceReadBps`<sup>Optional</sup> <a name="DeviceReadBps" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceReadBps"></a>

```csharp
public IResolvable|ContainerDeviceReadBps[] DeviceReadBps { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]

device_read_bps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#device_read_bps Container#device_read_bps}

---

##### `DeviceReadIops`<sup>Optional</sup> <a name="DeviceReadIops" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceReadIops"></a>

```csharp
public IResolvable|ContainerDeviceReadIops[] DeviceReadIops { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]

device_read_iops block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#device_read_iops Container#device_read_iops}

---

##### `DeviceRequests`<sup>Optional</sup> <a name="DeviceRequests" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceRequests"></a>

```csharp
public IResolvable|ContainerDeviceRequests[] DeviceRequests { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]

device_requests block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#device_requests Container#device_requests}

---

##### `Devices`<sup>Optional</sup> <a name="Devices" id="@cdktn/provider-docker.container.ContainerConfig.property.devices"></a>

```csharp
public IResolvable|ContainerDevices[] Devices { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]

devices block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#devices Container#devices}

---

##### `DeviceWriteBps`<sup>Optional</sup> <a name="DeviceWriteBps" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteBps"></a>

```csharp
public IResolvable|ContainerDeviceWriteBps[] DeviceWriteBps { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]

device_write_bps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#device_write_bps Container#device_write_bps}

---

##### `DeviceWriteIops`<sup>Optional</sup> <a name="DeviceWriteIops" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteIops"></a>

```csharp
public IResolvable|ContainerDeviceWriteIops[] DeviceWriteIops { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]

device_write_iops block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#device_write_iops Container#device_write_iops}

---

##### `Dns`<sup>Optional</sup> <a name="Dns" id="@cdktn/provider-docker.container.ContainerConfig.property.dns"></a>

```csharp
public string[] Dns { get; set; }
```

- *Type:* string[]

DNS servers to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#dns Container#dns}

---

##### `DnsOpts`<sup>Optional</sup> <a name="DnsOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.dnsOpts"></a>

```csharp
public string[] DnsOpts { get; set; }
```

- *Type:* string[]

DNS options used by the DNS provider(s), see `resolv.conf` documentation for valid list of options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#dns_opts Container#dns_opts}

---

##### `DnsSearch`<sup>Optional</sup> <a name="DnsSearch" id="@cdktn/provider-docker.container.ContainerConfig.property.dnsSearch"></a>

```csharp
public string[] DnsSearch { get; set; }
```

- *Type:* string[]

DNS search domains that are used when bare unqualified hostnames are used inside of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#dns_search Container#dns_search}

---

##### `Domainname`<sup>Optional</sup> <a name="Domainname" id="@cdktn/provider-docker.container.ContainerConfig.property.domainname"></a>

```csharp
public string Domainname { get; set; }
```

- *Type:* string

Domain name of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#domainname Container#domainname}

---

##### `Entrypoint`<sup>Optional</sup> <a name="Entrypoint" id="@cdktn/provider-docker.container.ContainerConfig.property.entrypoint"></a>

```csharp
public string[] Entrypoint { get; set; }
```

- *Type:* string[]

The command to use as the Entrypoint for the container.

The Entrypoint allows you to configure a container to run as an executable. For example, to run `/usr/bin/myprogram` when starting a container, set the entrypoint to be `"/usr/bin/myprogram"]`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#entrypoint Container#entrypoint}

---

##### `Env`<sup>Optional</sup> <a name="Env" id="@cdktn/provider-docker.container.ContainerConfig.property.env"></a>

```csharp
public string[] Env { get; set; }
```

- *Type:* string[]

Environment variables to set in the form of `KEY=VALUE`, e.g. `DEBUG=0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#env Container#env}

---

##### `Gpus`<sup>Optional</sup> <a name="Gpus" id="@cdktn/provider-docker.container.ContainerConfig.property.gpus"></a>

```csharp
public string Gpus { get; set; }
```

- *Type:* string

GPU devices to add to the container. Supported values are `all` or `device=<id[,id...]>`, for example `device=0,2` or `device=GPU-3a23c669-1f69-c64e-cf85-44e9b07e7a2a`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#gpus Container#gpus}

---

##### `GroupAdd`<sup>Optional</sup> <a name="GroupAdd" id="@cdktn/provider-docker.container.ContainerConfig.property.groupAdd"></a>

```csharp
public string[] GroupAdd { get; set; }
```

- *Type:* string[]

Additional groups for the container user.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#group_add Container#group_add}

---

##### `Healthcheck`<sup>Optional</sup> <a name="Healthcheck" id="@cdktn/provider-docker.container.ContainerConfig.property.healthcheck"></a>

```csharp
public ContainerHealthcheck Healthcheck { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

healthcheck block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#healthcheck Container#healthcheck}

---

##### `Host`<sup>Optional</sup> <a name="Host" id="@cdktn/provider-docker.container.ContainerConfig.property.host"></a>

```csharp
public IResolvable|ContainerHost[] Host { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]

host block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#host Container#host}

---

##### `Hostname`<sup>Optional</sup> <a name="Hostname" id="@cdktn/provider-docker.container.ContainerConfig.property.hostname"></a>

```csharp
public string Hostname { get; set; }
```

- *Type:* string

Hostname of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#hostname Container#hostname}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="@cdktn/provider-docker.container.ContainerConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#id Container#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Init`<sup>Optional</sup> <a name="Init" id="@cdktn/provider-docker.container.ContainerConfig.property.init"></a>

```csharp
public bool|IResolvable Init { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Configured whether an init process should be injected for this container.

If unset this will default to the `dockerd` defaults.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#init Container#init}

---

##### `IpcMode`<sup>Optional</sup> <a name="IpcMode" id="@cdktn/provider-docker.container.ContainerConfig.property.ipcMode"></a>

```csharp
public string IpcMode { get; set; }
```

- *Type:* string

IPC sharing mode for the container. Possible values are: `none`, `private`, `shareable`, `container:<name|id>` or `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ipc_mode Container#ipc_mode}

---

##### `Labels`<sup>Optional</sup> <a name="Labels" id="@cdktn/provider-docker.container.ContainerConfig.property.labels"></a>

```csharp
public IResolvable|ContainerLabels[] Labels { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#labels Container#labels}

---

##### `LogDriver`<sup>Optional</sup> <a name="LogDriver" id="@cdktn/provider-docker.container.ContainerConfig.property.logDriver"></a>

```csharp
public string LogDriver { get; set; }
```

- *Type:* string

The logging driver to use for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#log_driver Container#log_driver}

---

##### `LogOpts`<sup>Optional</sup> <a name="LogOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.logOpts"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> LogOpts { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Key/value pairs to use as options for the logging driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#log_opts Container#log_opts}

---

##### `Logs`<sup>Optional</sup> <a name="Logs" id="@cdktn/provider-docker.container.ContainerConfig.property.logs"></a>

```csharp
public bool|IResolvable Logs { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Save the container logs (`attach` must be enabled). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#logs Container#logs}

---

##### `MaxRetryCount`<sup>Optional</sup> <a name="MaxRetryCount" id="@cdktn/provider-docker.container.ContainerConfig.property.maxRetryCount"></a>

```csharp
public double MaxRetryCount { get; set; }
```

- *Type:* double

The maximum amount of times to an attempt a restart when `restart` is set to 'on-failure'.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#max_retry_count Container#max_retry_count}

---

##### `Memory`<sup>Optional</sup> <a name="Memory" id="@cdktn/provider-docker.container.ContainerConfig.property.memory"></a>

```csharp
public double Memory { get; set; }
```

- *Type:* double

The memory limit for the container in MBs.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#memory Container#memory}

---

##### `MemoryReservation`<sup>Optional</sup> <a name="MemoryReservation" id="@cdktn/provider-docker.container.ContainerConfig.property.memoryReservation"></a>

```csharp
public double MemoryReservation { get; set; }
```

- *Type:* double

The memory-resveration for the container in MBs.

Defaults to 0. Allows you to specify a soft limit smaller than `memory` which is activated when Docker detects contention or low memory on the host machine. If you use `memory-reservation`, it must be set lower than `memory` for it to take precedence. Because it is a soft limit, it doesn't guarantee that the container doesn't exceed the limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#memory_reservation Container#memory_reservation}

---

##### `MemorySwap`<sup>Optional</sup> <a name="MemorySwap" id="@cdktn/provider-docker.container.ContainerConfig.property.memorySwap"></a>

```csharp
public double MemorySwap { get; set; }
```

- *Type:* double

The total memory limit (memory + swap) for the container in MBs.

This setting may compute to `-1` after `terraform apply` if the target host doesn't support memory swap, when that is the case docker will use a soft limitation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#memory_swap Container#memory_swap}

---

##### `Mounts`<sup>Optional</sup> <a name="Mounts" id="@cdktn/provider-docker.container.ContainerConfig.property.mounts"></a>

```csharp
public IResolvable|ContainerMounts[] Mounts { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]

mounts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#mounts Container#mounts}

---

##### `MustRun`<sup>Optional</sup> <a name="MustRun" id="@cdktn/provider-docker.container.ContainerConfig.property.mustRun"></a>

```csharp
public bool|IResolvable MustRun { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, then the Docker container will be kept running.

If `false`, Terraform leaves the container alone. This attribute is also used to trigger a restart of a stopped container. If your container is stopped, Terraform will set `must_run` to `false` and this will trigger a change. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#must_run Container#must_run}

---

##### `NetworkMode`<sup>Optional</sup> <a name="NetworkMode" id="@cdktn/provider-docker.container.ContainerConfig.property.networkMode"></a>

```csharp
public string NetworkMode { get; set; }
```

- *Type:* string

Network mode of the container.

Defaults to `bridge`. If your host OS is any other OS, you need to set this value explicitly, e.g. `nat` when your container will be running on an Windows host. See https://docs.docker.com/engine/network/ for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#network_mode Container#network_mode}

---

##### `NetworksAdvanced`<sup>Optional</sup> <a name="NetworksAdvanced" id="@cdktn/provider-docker.container.ContainerConfig.property.networksAdvanced"></a>

```csharp
public IResolvable|ContainerNetworksAdvanced[] NetworksAdvanced { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]

networks_advanced block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#networks_advanced Container#networks_advanced}

---

##### `PidMode`<sup>Optional</sup> <a name="PidMode" id="@cdktn/provider-docker.container.ContainerConfig.property.pidMode"></a>

```csharp
public string PidMode { get; set; }
```

- *Type:* string

The PID (Process) Namespace mode for the container. Either `container:<name|id>` or `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#pid_mode Container#pid_mode}

---

##### `Platform`<sup>Optional</sup> <a name="Platform" id="@cdktn/provider-docker.container.ContainerConfig.property.platform"></a>

```csharp
public string Platform { get; set; }
```

- *Type:* string

Platform in the format `os[/arch[/variant]]` used for image lookup and container runtime, for example `linux/amd64`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#platform Container#platform}

---

##### `Ports`<sup>Optional</sup> <a name="Ports" id="@cdktn/provider-docker.container.ContainerConfig.property.ports"></a>

```csharp
public IResolvable|ContainerPorts[] Ports { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]

ports block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ports Container#ports}

---

##### `Privileged`<sup>Optional</sup> <a name="Privileged" id="@cdktn/provider-docker.container.ContainerConfig.property.privileged"></a>

```csharp
public bool|IResolvable Privileged { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, the container runs in privileged mode.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#privileged Container#privileged}

---

##### `PublishAllPorts`<sup>Optional</sup> <a name="PublishAllPorts" id="@cdktn/provider-docker.container.ContainerConfig.property.publishAllPorts"></a>

```csharp
public bool|IResolvable PublishAllPorts { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Publish all ports of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#publish_all_ports Container#publish_all_ports}

---

##### `ReadOnly`<sup>Optional</sup> <a name="ReadOnly" id="@cdktn/provider-docker.container.ContainerConfig.property.readOnly"></a>

```csharp
public bool|IResolvable ReadOnly { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, the container will be started as readonly. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#read_only Container#read_only}

---

##### `RemoveVolumes`<sup>Optional</sup> <a name="RemoveVolumes" id="@cdktn/provider-docker.container.ContainerConfig.property.removeVolumes"></a>

```csharp
public bool|IResolvable RemoveVolumes { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, it will remove anonymous volumes associated with the container. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#remove_volumes Container#remove_volumes}

---

##### `Restart`<sup>Optional</sup> <a name="Restart" id="@cdktn/provider-docker.container.ContainerConfig.property.restart"></a>

```csharp
public string Restart { get; set; }
```

- *Type:* string

The restart policy for the container. Must be one of 'no', 'on-failure', 'always', 'unless-stopped'. Defaults to `no`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#restart Container#restart}

---

##### `Rm`<sup>Optional</sup> <a name="Rm" id="@cdktn/provider-docker.container.ContainerConfig.property.rm"></a>

```csharp
public bool|IResolvable Rm { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, then the container will be automatically removed when it exits. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#rm Container#rm}

---

##### `Runtime`<sup>Optional</sup> <a name="Runtime" id="@cdktn/provider-docker.container.ContainerConfig.property.runtime"></a>

```csharp
public string Runtime { get; set; }
```

- *Type:* string

Runtime to use for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#runtime Container#runtime}

---

##### `SecurityOpts`<sup>Optional</sup> <a name="SecurityOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.securityOpts"></a>

```csharp
public string[] SecurityOpts { get; set; }
```

- *Type:* string[]

List of string values to customize labels for MLS systems, such as SELinux. See https://docs.docker.com/engine/reference/run/#security-configuration.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#security_opts Container#security_opts}

---

##### `ShmSize`<sup>Optional</sup> <a name="ShmSize" id="@cdktn/provider-docker.container.ContainerConfig.property.shmSize"></a>

```csharp
public double ShmSize { get; set; }
```

- *Type:* double

Size of `/dev/shm` in MBs.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#shm_size Container#shm_size}

---

##### `Start`<sup>Optional</sup> <a name="Start" id="@cdktn/provider-docker.container.ContainerConfig.property.start"></a>

```csharp
public bool|IResolvable Start { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, then the Docker container will be started after creation.

If `false`, then the container is only created. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#start Container#start}

---

##### `StdinOpen`<sup>Optional</sup> <a name="StdinOpen" id="@cdktn/provider-docker.container.ContainerConfig.property.stdinOpen"></a>

```csharp
public bool|IResolvable StdinOpen { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, keep STDIN open even if not attached (`docker run -i`). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#stdin_open Container#stdin_open}

---

##### `StopSignal`<sup>Optional</sup> <a name="StopSignal" id="@cdktn/provider-docker.container.ContainerConfig.property.stopSignal"></a>

```csharp
public string StopSignal { get; set; }
```

- *Type:* string

Signal to stop a container (default `SIGTERM`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#stop_signal Container#stop_signal}

---

##### `StopTimeout`<sup>Optional</sup> <a name="StopTimeout" id="@cdktn/provider-docker.container.ContainerConfig.property.stopTimeout"></a>

```csharp
public double StopTimeout { get; set; }
```

- *Type:* double

Timeout (in seconds) to stop a container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#stop_timeout Container#stop_timeout}

---

##### `StorageOpts`<sup>Optional</sup> <a name="StorageOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.storageOpts"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> StorageOpts { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Key/value pairs for the storage driver options, e.g. `size`: `120G`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#storage_opts Container#storage_opts}

---

##### `Sysctls`<sup>Optional</sup> <a name="Sysctls" id="@cdktn/provider-docker.container.ContainerConfig.property.sysctls"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Sysctls { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

A map of kernel parameters (sysctls) to set in the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#sysctls Container#sysctls}

---

##### `Timeouts`<sup>Optional</sup> <a name="Timeouts" id="@cdktn/provider-docker.container.ContainerConfig.property.timeouts"></a>

```csharp
public ContainerTimeouts Timeouts { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#timeouts Container#timeouts}

---

##### `Tmpfs`<sup>Optional</sup> <a name="Tmpfs" id="@cdktn/provider-docker.container.ContainerConfig.property.tmpfs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Tmpfs { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

A map of container directories which should be replaced by `tmpfs mounts`, and their corresponding mount options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#tmpfs Container#tmpfs}

---

##### `Tty`<sup>Optional</sup> <a name="Tty" id="@cdktn/provider-docker.container.ContainerConfig.property.tty"></a>

```csharp
public bool|IResolvable Tty { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, allocate a pseudo-tty (`docker run -t`). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#tty Container#tty}

---

##### `Ulimit`<sup>Optional</sup> <a name="Ulimit" id="@cdktn/provider-docker.container.ContainerConfig.property.ulimit"></a>

```csharp
public IResolvable|ContainerUlimit[] Ulimit { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ulimit Container#ulimit}

---

##### `Upload`<sup>Optional</sup> <a name="Upload" id="@cdktn/provider-docker.container.ContainerConfig.property.upload"></a>

```csharp
public IResolvable|ContainerUpload[] Upload { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]

upload block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#upload Container#upload}

---

##### `User`<sup>Optional</sup> <a name="User" id="@cdktn/provider-docker.container.ContainerConfig.property.user"></a>

```csharp
public string User { get; set; }
```

- *Type:* string

User used for run the first process.

Format is `user` or `user:group` which user and group can be passed literally or by name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#user Container#user}

---

##### `UsernsMode`<sup>Optional</sup> <a name="UsernsMode" id="@cdktn/provider-docker.container.ContainerConfig.property.usernsMode"></a>

```csharp
public string UsernsMode { get; set; }
```

- *Type:* string

Sets the usernamespace mode for the container when usernamespace remapping option is enabled.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#userns_mode Container#userns_mode}

---

##### `Volumes`<sup>Optional</sup> <a name="Volumes" id="@cdktn/provider-docker.container.ContainerConfig.property.volumes"></a>

```csharp
public IResolvable|ContainerVolumes[] Volumes { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]

volumes block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#volumes Container#volumes}

---

##### `Wait`<sup>Optional</sup> <a name="Wait" id="@cdktn/provider-docker.container.ContainerConfig.property.wait"></a>

```csharp
public bool|IResolvable Wait { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, then the Docker container is waited for being healthy state after creation.

This requires your container to have a healthcheck, otherwise this provider will error. If `false`, then the container health state is not checked. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#wait Container#wait}

---

##### `WaitTimeout`<sup>Optional</sup> <a name="WaitTimeout" id="@cdktn/provider-docker.container.ContainerConfig.property.waitTimeout"></a>

```csharp
public double WaitTimeout { get; set; }
```

- *Type:* double

The timeout in seconds to wait the container to be healthy after creation. Defaults to `60`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#wait_timeout Container#wait_timeout}

---

##### `WorkingDir`<sup>Optional</sup> <a name="WorkingDir" id="@cdktn/provider-docker.container.ContainerConfig.property.workingDir"></a>

```csharp
public string WorkingDir { get; set; }
```

- *Type:* string

The working directory for commands to run in.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#working_dir Container#working_dir}

---

### ContainerDeviceReadBps <a name="ContainerDeviceReadBps" id="@cdktn/provider-docker.container.ContainerDeviceReadBps"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceReadBps.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceReadBps {
    string Path,
    double Rate
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps.property.path">Path</a></code> | <code>string</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps.property.rate">Rate</a></code> | <code>double</code> | The read rate limit in bytes per second. |

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceReadBps.property.path"></a>

```csharp
public string Path { get; set; }
```

- *Type:* string

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#path Container#path}

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceReadBps.property.rate"></a>

```csharp
public double Rate { get; set; }
```

- *Type:* double

The read rate limit in bytes per second.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#rate Container#rate}

---

### ContainerDeviceReadIops <a name="ContainerDeviceReadIops" id="@cdktn/provider-docker.container.ContainerDeviceReadIops"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceReadIops.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceReadIops {
    string Path,
    double Rate
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops.property.path">Path</a></code> | <code>string</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops.property.rate">Rate</a></code> | <code>double</code> | The read IOPS limit. |

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceReadIops.property.path"></a>

```csharp
public string Path { get; set; }
```

- *Type:* string

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#path Container#path}

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceReadIops.property.rate"></a>

```csharp
public double Rate { get; set; }
```

- *Type:* double

The read IOPS limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#rate Container#rate}

---

### ContainerDeviceRequests <a name="ContainerDeviceRequests" id="@cdktn/provider-docker.container.ContainerDeviceRequests"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceRequests.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceRequests {
    string[] Capabilities = null,
    double Count = null,
    string[] DeviceIds = null,
    string Driver = null,
    System.Collections.Generic.IDictionary<string, string> Options = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.capabilities">Capabilities</a></code> | <code>string[]</code> | List of device capabilities. Only used with `nvidia` driver (e.g., `gpu`, `compute`, `utility`). |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.count">Count</a></code> | <code>double</code> | Number of devices to request. Use -1 for all devices. Only used with `nvidia` driver. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.deviceIds">DeviceIds</a></code> | <code>string[]</code> | List of device IDs or CDI device identifiers (e.g., `nvidia.com/gpu=all`). |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.driver">Driver</a></code> | <code>string</code> | The device driver to use. Common values: `cdi` for CDI devices, `nvidia` for NVIDIA GPU requests. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.options">Options</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Driver-specific options. |

---

##### `Capabilities`<sup>Optional</sup> <a name="Capabilities" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.capabilities"></a>

```csharp
public string[] Capabilities { get; set; }
```

- *Type:* string[]

List of device capabilities. Only used with `nvidia` driver (e.g., `gpu`, `compute`, `utility`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#capabilities Container#capabilities}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.count"></a>

```csharp
public double Count { get; set; }
```

- *Type:* double

Number of devices to request. Use -1 for all devices. Only used with `nvidia` driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#count Container#count}

---

##### `DeviceIds`<sup>Optional</sup> <a name="DeviceIds" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.deviceIds"></a>

```csharp
public string[] DeviceIds { get; set; }
```

- *Type:* string[]

List of device IDs or CDI device identifiers (e.g., `nvidia.com/gpu=all`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#device_ids Container#device_ids}

---

##### `Driver`<sup>Optional</sup> <a name="Driver" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.driver"></a>

```csharp
public string Driver { get; set; }
```

- *Type:* string

The device driver to use. Common values: `cdi` for CDI devices, `nvidia` for NVIDIA GPU requests.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#driver Container#driver}

---

##### `Options`<sup>Optional</sup> <a name="Options" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.options"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Options { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Driver-specific options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#options Container#options}

---

### ContainerDevices <a name="ContainerDevices" id="@cdktn/provider-docker.container.ContainerDevices"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDevices.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDevices {
    string HostPath,
    string ContainerPath = null,
    string Permissions = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevices.property.hostPath">HostPath</a></code> | <code>string</code> | The path on the host where the device is located. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevices.property.containerPath">ContainerPath</a></code> | <code>string</code> | The path in the container where the device will be bound. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevices.property.permissions">Permissions</a></code> | <code>string</code> | The cgroup permissions given to the container to access the device. Defaults to `rwm`. |

---

##### `HostPath`<sup>Required</sup> <a name="HostPath" id="@cdktn/provider-docker.container.ContainerDevices.property.hostPath"></a>

```csharp
public string HostPath { get; set; }
```

- *Type:* string

The path on the host where the device is located.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#host_path Container#host_path}

---

##### `ContainerPath`<sup>Optional</sup> <a name="ContainerPath" id="@cdktn/provider-docker.container.ContainerDevices.property.containerPath"></a>

```csharp
public string ContainerPath { get; set; }
```

- *Type:* string

The path in the container where the device will be bound.

If not set, it defaults to the value of `host_path`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#container_path Container#container_path}

---

##### `Permissions`<sup>Optional</sup> <a name="Permissions" id="@cdktn/provider-docker.container.ContainerDevices.property.permissions"></a>

```csharp
public string Permissions { get; set; }
```

- *Type:* string

The cgroup permissions given to the container to access the device. Defaults to `rwm`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#permissions Container#permissions}

---

### ContainerDeviceWriteBps <a name="ContainerDeviceWriteBps" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceWriteBps {
    string Path,
    double Rate
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.path">Path</a></code> | <code>string</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.rate">Rate</a></code> | <code>double</code> | The write rate limit in bytes per second. |

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.path"></a>

```csharp
public string Path { get; set; }
```

- *Type:* string

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#path Container#path}

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.rate"></a>

```csharp
public double Rate { get; set; }
```

- *Type:* double

The write rate limit in bytes per second.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#rate Container#rate}

---

### ContainerDeviceWriteIops <a name="ContainerDeviceWriteIops" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceWriteIops {
    string Path,
    double Rate
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.path">Path</a></code> | <code>string</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.rate">Rate</a></code> | <code>double</code> | The write IOPS limit. |

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.path"></a>

```csharp
public string Path { get; set; }
```

- *Type:* string

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#path Container#path}

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.rate"></a>

```csharp
public double Rate { get; set; }
```

- *Type:* double

The write IOPS limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#rate Container#rate}

---

### ContainerHealthcheck <a name="ContainerHealthcheck" id="@cdktn/provider-docker.container.ContainerHealthcheck"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerHealthcheck.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerHealthcheck {
    string Interval = null,
    double Retries = null,
    string StartInterval = null,
    string StartPeriod = null,
    string[] Test = null,
    string Timeout = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.interval">Interval</a></code> | <code>string</code> | Time between running the check (ms\|s\|m\|h). Defaults to `0s`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.retries">Retries</a></code> | <code>double</code> | Consecutive failures needed to report unhealthy. Defaults to `0`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.startInterval">StartInterval</a></code> | <code>string</code> | Interval before the healthcheck starts (ms\|s\|m\|h). Defaults to `0s`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.startPeriod">StartPeriod</a></code> | <code>string</code> | Start period for the container to initialize before counting retries towards unstable (ms\|s\|m\|h). Defaults to `0s`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.test">Test</a></code> | <code>string[]</code> | Command to run to check health. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.timeout">Timeout</a></code> | <code>string</code> | Maximum time to allow one check to run (ms\|s\|m\|h). Defaults to `0s`. |

---

##### `Interval`<sup>Optional</sup> <a name="Interval" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.interval"></a>

```csharp
public string Interval { get; set; }
```

- *Type:* string

Time between running the check (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#interval Container#interval}

---

##### `Retries`<sup>Optional</sup> <a name="Retries" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.retries"></a>

```csharp
public double Retries { get; set; }
```

- *Type:* double

Consecutive failures needed to report unhealthy. Defaults to `0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#retries Container#retries}

---

##### `StartInterval`<sup>Optional</sup> <a name="StartInterval" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.startInterval"></a>

```csharp
public string StartInterval { get; set; }
```

- *Type:* string

Interval before the healthcheck starts (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#start_interval Container#start_interval}

---

##### `StartPeriod`<sup>Optional</sup> <a name="StartPeriod" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.startPeriod"></a>

```csharp
public string StartPeriod { get; set; }
```

- *Type:* string

Start period for the container to initialize before counting retries towards unstable (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#start_period Container#start_period}

---

##### `Test`<sup>Optional</sup> <a name="Test" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.test"></a>

```csharp
public string[] Test { get; set; }
```

- *Type:* string[]

Command to run to check health.

For example, to run `curl -f localhost/health` set the command to be `["CMD", "curl", "-f", "localhost/health"]`. It works in the same way, and has the same default values, as the HEALTHCHECK Dockerfile instruction set by the service's Docker image. Your Compose file can override the values set in the Dockerfile.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#test Container#test}

---

##### `Timeout`<sup>Optional</sup> <a name="Timeout" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.timeout"></a>

```csharp
public string Timeout { get; set; }
```

- *Type:* string

Maximum time to allow one check to run (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#timeout Container#timeout}

---

### ContainerHost <a name="ContainerHost" id="@cdktn/provider-docker.container.ContainerHost"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerHost.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerHost {
    string Host,
    string Ip
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHost.property.host">Host</a></code> | <code>string</code> | Hostname to add. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHost.property.ip">Ip</a></code> | <code>string</code> | IP address this hostname should resolve to. |

---

##### `Host`<sup>Required</sup> <a name="Host" id="@cdktn/provider-docker.container.ContainerHost.property.host"></a>

```csharp
public string Host { get; set; }
```

- *Type:* string

Hostname to add.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#host Container#host}

---

##### `Ip`<sup>Required</sup> <a name="Ip" id="@cdktn/provider-docker.container.ContainerHost.property.ip"></a>

```csharp
public string Ip { get; set; }
```

- *Type:* string

IP address this hostname should resolve to.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ip Container#ip}

---

### ContainerLabels <a name="ContainerLabels" id="@cdktn/provider-docker.container.ContainerLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerLabels.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerLabels {
    string Label,
    string Value
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabels.property.label">Label</a></code> | <code>string</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabels.property.value">Value</a></code> | <code>string</code> | Value of the label. |

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.container.ContainerLabels.property.label"></a>

```csharp
public string Label { get; set; }
```

- *Type:* string

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#label Container#label}

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerLabels.property.value"></a>

```csharp
public string Value { get; set; }
```

- *Type:* string

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#value Container#value}

---

### ContainerMounts <a name="ContainerMounts" id="@cdktn/provider-docker.container.ContainerMounts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMounts.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMounts {
    string Target,
    string Type,
    ContainerMountsBindOptions BindOptions = null,
    bool|IResolvable ReadOnly = null,
    string Source = null,
    ContainerMountsTmpfsOptions TmpfsOptions = null,
    ContainerMountsVolumeOptions VolumeOptions = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.target">Target</a></code> | <code>string</code> | Container path. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.type">Type</a></code> | <code>string</code> | The mount type. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.bindOptions">BindOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a></code> | bind_options block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.readOnly">ReadOnly</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Whether the mount should be read-only. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.source">Source</a></code> | <code>string</code> | Mount source (e.g. a volume name, a host path). |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.tmpfsOptions">TmpfsOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a></code> | tmpfs_options block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.volumeOptions">VolumeOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a></code> | volume_options block. |

---

##### `Target`<sup>Required</sup> <a name="Target" id="@cdktn/provider-docker.container.ContainerMounts.property.target"></a>

```csharp
public string Target { get; set; }
```

- *Type:* string

Container path.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#target Container#target}

---

##### `Type`<sup>Required</sup> <a name="Type" id="@cdktn/provider-docker.container.ContainerMounts.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

The mount type.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#type Container#type}

---

##### `BindOptions`<sup>Optional</sup> <a name="BindOptions" id="@cdktn/provider-docker.container.ContainerMounts.property.bindOptions"></a>

```csharp
public ContainerMountsBindOptions BindOptions { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

bind_options block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#bind_options Container#bind_options}

---

##### `ReadOnly`<sup>Optional</sup> <a name="ReadOnly" id="@cdktn/provider-docker.container.ContainerMounts.property.readOnly"></a>

```csharp
public bool|IResolvable ReadOnly { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Whether the mount should be read-only.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#read_only Container#read_only}

---

##### `Source`<sup>Optional</sup> <a name="Source" id="@cdktn/provider-docker.container.ContainerMounts.property.source"></a>

```csharp
public string Source { get; set; }
```

- *Type:* string

Mount source (e.g. a volume name, a host path).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#source Container#source}

---

##### `TmpfsOptions`<sup>Optional</sup> <a name="TmpfsOptions" id="@cdktn/provider-docker.container.ContainerMounts.property.tmpfsOptions"></a>

```csharp
public ContainerMountsTmpfsOptions TmpfsOptions { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

tmpfs_options block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#tmpfs_options Container#tmpfs_options}

---

##### `VolumeOptions`<sup>Optional</sup> <a name="VolumeOptions" id="@cdktn/provider-docker.container.ContainerMounts.property.volumeOptions"></a>

```csharp
public ContainerMountsVolumeOptions VolumeOptions { get; set; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

volume_options block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#volume_options Container#volume_options}

---

### ContainerMountsBindOptions <a name="ContainerMountsBindOptions" id="@cdktn/provider-docker.container.ContainerMountsBindOptions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsBindOptions.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsBindOptions {
    string Propagation = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions.property.propagation">Propagation</a></code> | <code>string</code> | A propagation mode with the value. |

---

##### `Propagation`<sup>Optional</sup> <a name="Propagation" id="@cdktn/provider-docker.container.ContainerMountsBindOptions.property.propagation"></a>

```csharp
public string Propagation { get; set; }
```

- *Type:* string

A propagation mode with the value.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#propagation Container#propagation}

---

### ContainerMountsTmpfsOptions <a name="ContainerMountsTmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsTmpfsOptions {
    double Mode = null,
    double SizeBytes = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.mode">Mode</a></code> | <code>double</code> | The permission mode for the tmpfs mount in an integer. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.sizeBytes">SizeBytes</a></code> | <code>double</code> | The size for the tmpfs mount in bytes. |

---

##### `Mode`<sup>Optional</sup> <a name="Mode" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.mode"></a>

```csharp
public double Mode { get; set; }
```

- *Type:* double

The permission mode for the tmpfs mount in an integer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#mode Container#mode}

---

##### `SizeBytes`<sup>Optional</sup> <a name="SizeBytes" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.sizeBytes"></a>

```csharp
public double SizeBytes { get; set; }
```

- *Type:* double

The size for the tmpfs mount in bytes.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#size_bytes Container#size_bytes}

---

### ContainerMountsVolumeOptions <a name="ContainerMountsVolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsVolumeOptions {
    string DriverName = null,
    System.Collections.Generic.IDictionary<string, string> DriverOptions = null,
    IResolvable|ContainerMountsVolumeOptionsLabels[] Labels = null,
    bool|IResolvable NoCopy = null,
    string Subpath = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverName">DriverName</a></code> | <code>string</code> | Name of the driver to use to create the volume. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverOptions">DriverOptions</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | key/value map of driver specific options. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.labels">Labels</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]</code> | labels block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.noCopy">NoCopy</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | Populate volume with data from the target. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.subpath">Subpath</a></code> | <code>string</code> | Path within the volume to mount. Requires docker server version 1.45 or higher. |

---

##### `DriverName`<sup>Optional</sup> <a name="DriverName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverName"></a>

```csharp
public string DriverName { get; set; }
```

- *Type:* string

Name of the driver to use to create the volume.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#driver_name Container#driver_name}

---

##### `DriverOptions`<sup>Optional</sup> <a name="DriverOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverOptions"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> DriverOptions { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

key/value map of driver specific options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#driver_options Container#driver_options}

---

##### `Labels`<sup>Optional</sup> <a name="Labels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.labels"></a>

```csharp
public IResolvable|ContainerMountsVolumeOptionsLabels[] Labels { get; set; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#labels Container#labels}

---

##### `NoCopy`<sup>Optional</sup> <a name="NoCopy" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.noCopy"></a>

```csharp
public bool|IResolvable NoCopy { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

Populate volume with data from the target.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#no_copy Container#no_copy}

---

##### `Subpath`<sup>Optional</sup> <a name="Subpath" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.subpath"></a>

```csharp
public string Subpath { get; set; }
```

- *Type:* string

Path within the volume to mount. Requires docker server version 1.45 or higher.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#subpath Container#subpath}

---

### ContainerMountsVolumeOptionsLabels <a name="ContainerMountsVolumeOptionsLabels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsVolumeOptionsLabels {
    string Label,
    string Value
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.label">Label</a></code> | <code>string</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.value">Value</a></code> | <code>string</code> | Value of the label. |

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.label"></a>

```csharp
public string Label { get; set; }
```

- *Type:* string

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#label Container#label}

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.value"></a>

```csharp
public string Value { get; set; }
```

- *Type:* string

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#value Container#value}

---

### ContainerNetworkData <a name="ContainerNetworkData" id="@cdktn/provider-docker.container.ContainerNetworkData"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerNetworkData.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerNetworkData {

};
```


### ContainerNetworksAdvanced <a name="ContainerNetworksAdvanced" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerNetworksAdvanced {
    string Name,
    string[] Aliases = null,
    string[] DriverOpts = null,
    double GwPriority = null,
    string Ipv4Address = null,
    string Ipv6Address = null,
    string[] LinkLocalIps = null,
    string MacAddress = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.name">Name</a></code> | <code>string</code> | The name or id of the network to use. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.aliases">Aliases</a></code> | <code>string[]</code> | The network aliases of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.driverOpts">DriverOpts</a></code> | <code>string[]</code> | An array of driver options for the network endpoint, e.g. `opts1=value`. This is the equivalent to repeating `--driver-opt` for `docker run`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.gwPriority">GwPriority</a></code> | <code>double</code> | Gateway priority for this endpoint. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv4Address">Ipv4Address</a></code> | <code>string</code> | The IPV4 address of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv6Address">Ipv6Address</a></code> | <code>string</code> | The IPV6 address of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.linkLocalIps">LinkLocalIps</a></code> | <code>string[]</code> | The link-local IPs of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.macAddress">MacAddress</a></code> | <code>string</code> | The MAC address of the container in the specific network. |

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name or id of the network to use.

You can use `name` or `id` attribute from a `docker_network` resource.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#name Container#name}

---

##### `Aliases`<sup>Optional</sup> <a name="Aliases" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.aliases"></a>

```csharp
public string[] Aliases { get; set; }
```

- *Type:* string[]

The network aliases of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#aliases Container#aliases}

---

##### `DriverOpts`<sup>Optional</sup> <a name="DriverOpts" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.driverOpts"></a>

```csharp
public string[] DriverOpts { get; set; }
```

- *Type:* string[]

An array of driver options for the network endpoint, e.g. `opts1=value`. This is the equivalent to repeating `--driver-opt` for `docker run`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#driver_opts Container#driver_opts}

---

##### `GwPriority`<sup>Optional</sup> <a name="GwPriority" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.gwPriority"></a>

```csharp
public double GwPriority { get; set; }
```

- *Type:* double

Gateway priority for this endpoint.

The endpoint with the highest priority will provide the default gateway for the container. This is the equivalent to `--gw-priority` for `docker run`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#gw_priority Container#gw_priority}

---

##### `Ipv4Address`<sup>Optional</sup> <a name="Ipv4Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv4Address"></a>

```csharp
public string Ipv4Address { get; set; }
```

- *Type:* string

The IPV4 address of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ipv4_address Container#ipv4_address}

---

##### `Ipv6Address`<sup>Optional</sup> <a name="Ipv6Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv6Address"></a>

```csharp
public string Ipv6Address { get; set; }
```

- *Type:* string

The IPV6 address of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ipv6_address Container#ipv6_address}

---

##### `LinkLocalIps`<sup>Optional</sup> <a name="LinkLocalIps" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.linkLocalIps"></a>

```csharp
public string[] LinkLocalIps { get; set; }
```

- *Type:* string[]

The link-local IPs of the container in the specific network.

This is the equivalent to repeating `--link-local-ip` for `docker run`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#link_local_ips Container#link_local_ips}

---

##### `MacAddress`<sup>Optional</sup> <a name="MacAddress" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.macAddress"></a>

```csharp
public string MacAddress { get; set; }
```

- *Type:* string

The MAC address of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#mac_address Container#mac_address}

---

### ContainerPorts <a name="ContainerPorts" id="@cdktn/provider-docker.container.ContainerPorts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerPorts.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerPorts {
    double Internal,
    double External = null,
    string Ip = null,
    string Protocol = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.internal">Internal</a></code> | <code>double</code> | Port within the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.external">External</a></code> | <code>double</code> | Port exposed out of the container. If not given a free random port `>= 32768` will be used. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.ip">Ip</a></code> | <code>string</code> | IP address/mask that can access this port. Defaults to `0.0.0.0`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.protocol">Protocol</a></code> | <code>string</code> | Protocol that can be used over this port. Defaults to `tcp`. |

---

##### `Internal`<sup>Required</sup> <a name="Internal" id="@cdktn/provider-docker.container.ContainerPorts.property.internal"></a>

```csharp
public double Internal { get; set; }
```

- *Type:* double

Port within the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#internal Container#internal}

---

##### `External`<sup>Optional</sup> <a name="External" id="@cdktn/provider-docker.container.ContainerPorts.property.external"></a>

```csharp
public double External { get; set; }
```

- *Type:* double

Port exposed out of the container. If not given a free random port `>= 32768` will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#external Container#external}

---

##### `Ip`<sup>Optional</sup> <a name="Ip" id="@cdktn/provider-docker.container.ContainerPorts.property.ip"></a>

```csharp
public string Ip { get; set; }
```

- *Type:* string

IP address/mask that can access this port. Defaults to `0.0.0.0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#ip Container#ip}

---

##### `Protocol`<sup>Optional</sup> <a name="Protocol" id="@cdktn/provider-docker.container.ContainerPorts.property.protocol"></a>

```csharp
public string Protocol { get; set; }
```

- *Type:* string

Protocol that can be used over this port. Defaults to `tcp`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#protocol Container#protocol}

---

### ContainerTimeouts <a name="ContainerTimeouts" id="@cdktn/provider-docker.container.ContainerTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerTimeouts.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerTimeouts {
    string Create = null,
    string Delete = null,
    string Update = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts.property.create">Create</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#create Container#create}. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts.property.delete">Delete</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#delete Container#delete}. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts.property.update">Update</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#update Container#update}. |

---

##### `Create`<sup>Optional</sup> <a name="Create" id="@cdktn/provider-docker.container.ContainerTimeouts.property.create"></a>

```csharp
public string Create { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#create Container#create}.

---

##### `Delete`<sup>Optional</sup> <a name="Delete" id="@cdktn/provider-docker.container.ContainerTimeouts.property.delete"></a>

```csharp
public string Delete { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#delete Container#delete}.

---

##### `Update`<sup>Optional</sup> <a name="Update" id="@cdktn/provider-docker.container.ContainerTimeouts.property.update"></a>

```csharp
public string Update { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#update Container#update}.

---

### ContainerUlimit <a name="ContainerUlimit" id="@cdktn/provider-docker.container.ContainerUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerUlimit.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerUlimit {
    double Hard,
    string Name,
    double Soft
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimit.property.hard">Hard</a></code> | <code>double</code> | The hard limit. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimit.property.name">Name</a></code> | <code>string</code> | The name of the ulimit. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimit.property.soft">Soft</a></code> | <code>double</code> | The soft limit. |

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.container.ContainerUlimit.property.hard"></a>

```csharp
public double Hard { get; set; }
```

- *Type:* double

The hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#hard Container#hard}

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.container.ContainerUlimit.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

The name of the ulimit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#name Container#name}

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.container.ContainerUlimit.property.soft"></a>

```csharp
public double Soft { get; set; }
```

- *Type:* double

The soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#soft Container#soft}

---

### ContainerUpload <a name="ContainerUpload" id="@cdktn/provider-docker.container.ContainerUpload"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerUpload.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerUpload {
    string File,
    string Content = null,
    string ContentBase64 = null,
    bool|IResolvable Executable = null,
    string Permissions = null,
    string Source = null,
    string SourceHash = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.file">File</a></code> | <code>string</code> | Path to the file in the container where is upload goes to. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.content">Content</a></code> | <code>string</code> | Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.contentBase64">ContentBase64</a></code> | <code>string</code> | Base64-encoded data that will be decoded and uploaded as raw bytes for the object content. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.executable">Executable</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, the file will be uploaded with user executable permission. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.permissions">Permissions</a></code> | <code>string</code> | The permission mode for the file in the container. Has precedence over `executable`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.source">Source</a></code> | <code>string</code> | A filename that references a file which will be uploaded as the object content. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.sourceHash">SourceHash</a></code> | <code>string</code> | If using `source`, this will force an update if the file content has updated but the filename has not. |

---

##### `File`<sup>Required</sup> <a name="File" id="@cdktn/provider-docker.container.ContainerUpload.property.file"></a>

```csharp
public string File { get; set; }
```

- *Type:* string

Path to the file in the container where is upload goes to.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#file Container#file}

---

##### `Content`<sup>Optional</sup> <a name="Content" id="@cdktn/provider-docker.container.ContainerUpload.property.content"></a>

```csharp
public string Content { get; set; }
```

- *Type:* string

Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text.

Conflicts with `content_base64` & `source`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#content Container#content}

---

##### `ContentBase64`<sup>Optional</sup> <a name="ContentBase64" id="@cdktn/provider-docker.container.ContainerUpload.property.contentBase64"></a>

```csharp
public string ContentBase64 { get; set; }
```

- *Type:* string

Base64-encoded data that will be decoded and uploaded as raw bytes for the object content.

This allows safely uploading non-UTF8 binary data, but is recommended only for larger binary content such as the result of the `base64encode` interpolation function. See [here](https://github.com/terraform-providers/terraform-provider-docker/issues/48#issuecomment-374174588) for the reason. Conflicts with `content` & `source`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#content_base64 Container#content_base64}

---

##### `Executable`<sup>Optional</sup> <a name="Executable" id="@cdktn/provider-docker.container.ContainerUpload.property.executable"></a>

```csharp
public bool|IResolvable Executable { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, the file will be uploaded with user executable permission. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#executable Container#executable}

---

##### `Permissions`<sup>Optional</sup> <a name="Permissions" id="@cdktn/provider-docker.container.ContainerUpload.property.permissions"></a>

```csharp
public string Permissions { get; set; }
```

- *Type:* string

The permission mode for the file in the container. Has precedence over `executable`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#permissions Container#permissions}

---

##### `Source`<sup>Optional</sup> <a name="Source" id="@cdktn/provider-docker.container.ContainerUpload.property.source"></a>

```csharp
public string Source { get; set; }
```

- *Type:* string

A filename that references a file which will be uploaded as the object content.

This allows for large file uploads that do not get stored in state. Conflicts with `content` & `content_base64`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#source Container#source}

---

##### `SourceHash`<sup>Optional</sup> <a name="SourceHash" id="@cdktn/provider-docker.container.ContainerUpload.property.sourceHash"></a>

```csharp
public string SourceHash { get; set; }
```

- *Type:* string

If using `source`, this will force an update if the file content has updated but the filename has not.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#source_hash Container#source_hash}

---

### ContainerVolumes <a name="ContainerVolumes" id="@cdktn/provider-docker.container.ContainerVolumes"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerVolumes.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerVolumes {
    string ContainerPath = null,
    string FromContainer = null,
    string HostPath = null,
    bool|IResolvable ReadOnly = null,
    string SelinuxRelabel = null,
    string VolumeName = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.containerPath">ContainerPath</a></code> | <code>string</code> | The path in the container where the volume will be mounted. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.fromContainer">FromContainer</a></code> | <code>string</code> | The container where the volume is coming from. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.hostPath">HostPath</a></code> | <code>string</code> | The path on the host where the volume is coming from. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.readOnly">ReadOnly</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | If `true`, this volume will be readonly. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.selinuxRelabel">SelinuxRelabel</a></code> | <code>string</code> | SELinux relabel mode for bind mounts. Supported values are `z` and `Z`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.volumeName">VolumeName</a></code> | <code>string</code> | The name of the docker volume which should be mounted. Ignored when `host_path` is set. |

---

##### `ContainerPath`<sup>Optional</sup> <a name="ContainerPath" id="@cdktn/provider-docker.container.ContainerVolumes.property.containerPath"></a>

```csharp
public string ContainerPath { get; set; }
```

- *Type:* string

The path in the container where the volume will be mounted.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#container_path Container#container_path}

---

##### `FromContainer`<sup>Optional</sup> <a name="FromContainer" id="@cdktn/provider-docker.container.ContainerVolumes.property.fromContainer"></a>

```csharp
public string FromContainer { get; set; }
```

- *Type:* string

The container where the volume is coming from.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#from_container Container#from_container}

---

##### `HostPath`<sup>Optional</sup> <a name="HostPath" id="@cdktn/provider-docker.container.ContainerVolumes.property.hostPath"></a>

```csharp
public string HostPath { get; set; }
```

- *Type:* string

The path on the host where the volume is coming from.

If `host_path` is set, it takes precedence over `volume_name`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#host_path Container#host_path}

---

##### `ReadOnly`<sup>Optional</sup> <a name="ReadOnly" id="@cdktn/provider-docker.container.ContainerVolumes.property.readOnly"></a>

```csharp
public bool|IResolvable ReadOnly { get; set; }
```

- *Type:* bool|Io.Cdktn.IResolvable

If `true`, this volume will be readonly. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#read_only Container#read_only}

---

##### `SelinuxRelabel`<sup>Optional</sup> <a name="SelinuxRelabel" id="@cdktn/provider-docker.container.ContainerVolumes.property.selinuxRelabel"></a>

```csharp
public string SelinuxRelabel { get; set; }
```

- *Type:* string

SELinux relabel mode for bind mounts. Supported values are `z` and `Z`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#selinux_relabel Container#selinux_relabel}

---

##### `VolumeName`<sup>Optional</sup> <a name="VolumeName" id="@cdktn/provider-docker.container.ContainerVolumes.property.volumeName"></a>

```csharp
public string VolumeName { get; set; }
```

- *Type:* string

The name of the docker volume which should be mounted. Ignored when `host_path` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.5.0/docs/resources/container#volume_name Container#volume_name}

---

## Classes <a name="Classes" id="Classes"></a>

### ContainerCapabilitiesOutputReference <a name="ContainerCapabilitiesOutputReference" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerCapabilitiesOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetAdd">ResetAdd</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetDrop">ResetDrop</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAdd` <a name="ResetAdd" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetAdd"></a>

```csharp
private void ResetAdd()
```

##### `ResetDrop` <a name="ResetDrop" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetDrop"></a>

```csharp
private void ResetDrop()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.addInput">AddInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.dropInput">DropInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.add">Add</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.drop">Drop</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AddInput`<sup>Optional</sup> <a name="AddInput" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.addInput"></a>

```csharp
public string[] AddInput { get; }
```

- *Type:* string[]

---

##### `DropInput`<sup>Optional</sup> <a name="DropInput" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.dropInput"></a>

```csharp
public string[] DropInput { get; }
```

- *Type:* string[]

---

##### `Add`<sup>Required</sup> <a name="Add" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.add"></a>

```csharp
public string[] Add { get; }
```

- *Type:* string[]

---

##### `Drop`<sup>Required</sup> <a name="Drop" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.drop"></a>

```csharp
public string[] Drop { get; }
```

- *Type:* string[]

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.internalValue"></a>

```csharp
public ContainerCapabilities InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

---


### ContainerDeviceReadBpsList <a name="ContainerDeviceReadBpsList" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceReadBpsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.get"></a>

```csharp
private ContainerDeviceReadBpsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceReadBps[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>[]

---


### ContainerDeviceReadBpsOutputReference <a name="ContainerDeviceReadBpsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceReadBpsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.pathInput">PathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rateInput">RateInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.path">Path</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rate">Rate</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `PathInput`<sup>Optional</sup> <a name="PathInput" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.pathInput"></a>

```csharp
public string PathInput { get; }
```

- *Type:* string

---

##### `RateInput`<sup>Optional</sup> <a name="RateInput" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rateInput"></a>

```csharp
public double RateInput { get; }
```

- *Type:* double

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.path"></a>

```csharp
public string Path { get; }
```

- *Type:* string

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rate"></a>

```csharp
public double Rate { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceReadBps InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>

---


### ContainerDeviceReadIopsList <a name="ContainerDeviceReadIopsList" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceReadIopsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.get"></a>

```csharp
private ContainerDeviceReadIopsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceReadIops[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>[]

---


### ContainerDeviceReadIopsOutputReference <a name="ContainerDeviceReadIopsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceReadIopsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.pathInput">PathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rateInput">RateInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.path">Path</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rate">Rate</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `PathInput`<sup>Optional</sup> <a name="PathInput" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.pathInput"></a>

```csharp
public string PathInput { get; }
```

- *Type:* string

---

##### `RateInput`<sup>Optional</sup> <a name="RateInput" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rateInput"></a>

```csharp
public double RateInput { get; }
```

- *Type:* double

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.path"></a>

```csharp
public string Path { get; }
```

- *Type:* string

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rate"></a>

```csharp
public double Rate { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceReadIops InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>

---


### ContainerDeviceRequestsList <a name="ContainerDeviceRequestsList" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceRequestsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.get"></a>

```csharp
private ContainerDeviceRequestsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceRequests[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>[]

---


### ContainerDeviceRequestsOutputReference <a name="ContainerDeviceRequestsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceRequestsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCapabilities">ResetCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCount">ResetCount</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDeviceIds">ResetDeviceIds</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDriver">ResetDriver</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetOptions">ResetOptions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetCapabilities` <a name="ResetCapabilities" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCapabilities"></a>

```csharp
private void ResetCapabilities()
```

##### `ResetCount` <a name="ResetCount" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCount"></a>

```csharp
private void ResetCount()
```

##### `ResetDeviceIds` <a name="ResetDeviceIds" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDeviceIds"></a>

```csharp
private void ResetDeviceIds()
```

##### `ResetDriver` <a name="ResetDriver" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDriver"></a>

```csharp
private void ResetDriver()
```

##### `ResetOptions` <a name="ResetOptions" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetOptions"></a>

```csharp
private void ResetOptions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilitiesInput">CapabilitiesInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.countInput">CountInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIdsInput">DeviceIdsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driverInput">DriverInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.optionsInput">OptionsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilities">Capabilities</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.count">Count</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIds">DeviceIds</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driver">Driver</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.options">Options</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `CapabilitiesInput`<sup>Optional</sup> <a name="CapabilitiesInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilitiesInput"></a>

```csharp
public string[] CapabilitiesInput { get; }
```

- *Type:* string[]

---

##### `CountInput`<sup>Optional</sup> <a name="CountInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.countInput"></a>

```csharp
public double CountInput { get; }
```

- *Type:* double

---

##### `DeviceIdsInput`<sup>Optional</sup> <a name="DeviceIdsInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIdsInput"></a>

```csharp
public string[] DeviceIdsInput { get; }
```

- *Type:* string[]

---

##### `DriverInput`<sup>Optional</sup> <a name="DriverInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driverInput"></a>

```csharp
public string DriverInput { get; }
```

- *Type:* string

---

##### `OptionsInput`<sup>Optional</sup> <a name="OptionsInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.optionsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> OptionsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Capabilities`<sup>Required</sup> <a name="Capabilities" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilities"></a>

```csharp
public string[] Capabilities { get; }
```

- *Type:* string[]

---

##### `Count`<sup>Required</sup> <a name="Count" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.count"></a>

```csharp
public double Count { get; }
```

- *Type:* double

---

##### `DeviceIds`<sup>Required</sup> <a name="DeviceIds" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIds"></a>

```csharp
public string[] DeviceIds { get; }
```

- *Type:* string[]

---

##### `Driver`<sup>Required</sup> <a name="Driver" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driver"></a>

```csharp
public string Driver { get; }
```

- *Type:* string

---

##### `Options`<sup>Required</sup> <a name="Options" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.options"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Options { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceRequests InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>

---


### ContainerDevicesList <a name="ContainerDevicesList" id="@cdktn/provider-docker.container.ContainerDevicesList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDevicesList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerDevicesList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDevicesList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDevicesList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDevicesList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDevicesList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDevicesList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerDevicesList.get"></a>

```csharp
private ContainerDevicesOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerDevicesList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDevicesList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDevicesList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDevicesList.property.internalValue"></a>

```csharp
public IResolvable|ContainerDevices[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>[]

---


### ContainerDevicesOutputReference <a name="ContainerDevicesOutputReference" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDevicesOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetContainerPath">ResetContainerPath</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetPermissions">ResetPermissions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetContainerPath` <a name="ResetContainerPath" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetContainerPath"></a>

```csharp
private void ResetContainerPath()
```

##### `ResetPermissions` <a name="ResetPermissions" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetPermissions"></a>

```csharp
private void ResetPermissions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPathInput">ContainerPathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPathInput">HostPathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissionsInput">PermissionsInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPath">ContainerPath</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPath">HostPath</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissions">Permissions</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ContainerPathInput`<sup>Optional</sup> <a name="ContainerPathInput" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPathInput"></a>

```csharp
public string ContainerPathInput { get; }
```

- *Type:* string

---

##### `HostPathInput`<sup>Optional</sup> <a name="HostPathInput" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPathInput"></a>

```csharp
public string HostPathInput { get; }
```

- *Type:* string

---

##### `PermissionsInput`<sup>Optional</sup> <a name="PermissionsInput" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissionsInput"></a>

```csharp
public string PermissionsInput { get; }
```

- *Type:* string

---

##### `ContainerPath`<sup>Required</sup> <a name="ContainerPath" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPath"></a>

```csharp
public string ContainerPath { get; }
```

- *Type:* string

---

##### `HostPath`<sup>Required</sup> <a name="HostPath" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPath"></a>

```csharp
public string HostPath { get; }
```

- *Type:* string

---

##### `Permissions`<sup>Required</sup> <a name="Permissions" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissions"></a>

```csharp
public string Permissions { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerDevices InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>

---


### ContainerDeviceWriteBpsList <a name="ContainerDeviceWriteBpsList" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceWriteBpsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.get"></a>

```csharp
private ContainerDeviceWriteBpsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceWriteBps[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>[]

---


### ContainerDeviceWriteBpsOutputReference <a name="ContainerDeviceWriteBpsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceWriteBpsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.pathInput">PathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rateInput">RateInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.path">Path</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rate">Rate</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `PathInput`<sup>Optional</sup> <a name="PathInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.pathInput"></a>

```csharp
public string PathInput { get; }
```

- *Type:* string

---

##### `RateInput`<sup>Optional</sup> <a name="RateInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rateInput"></a>

```csharp
public double RateInput { get; }
```

- *Type:* double

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.path"></a>

```csharp
public string Path { get; }
```

- *Type:* string

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rate"></a>

```csharp
public double Rate { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceWriteBps InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>

---


### ContainerDeviceWriteIopsList <a name="ContainerDeviceWriteIopsList" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceWriteIopsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.get"></a>

```csharp
private ContainerDeviceWriteIopsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceWriteIops[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>[]

---


### ContainerDeviceWriteIopsOutputReference <a name="ContainerDeviceWriteIopsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerDeviceWriteIopsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.pathInput">PathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rateInput">RateInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.path">Path</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rate">Rate</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `PathInput`<sup>Optional</sup> <a name="PathInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.pathInput"></a>

```csharp
public string PathInput { get; }
```

- *Type:* string

---

##### `RateInput`<sup>Optional</sup> <a name="RateInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rateInput"></a>

```csharp
public double RateInput { get; }
```

- *Type:* double

---

##### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.path"></a>

```csharp
public string Path { get; }
```

- *Type:* string

---

##### `Rate`<sup>Required</sup> <a name="Rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rate"></a>

```csharp
public double Rate { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerDeviceWriteIops InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>

---


### ContainerHealthcheckOutputReference <a name="ContainerHealthcheckOutputReference" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerHealthcheckOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetInterval">ResetInterval</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetRetries">ResetRetries</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartInterval">ResetStartInterval</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartPeriod">ResetStartPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTest">ResetTest</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTimeout">ResetTimeout</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetInterval` <a name="ResetInterval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetInterval"></a>

```csharp
private void ResetInterval()
```

##### `ResetRetries` <a name="ResetRetries" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetRetries"></a>

```csharp
private void ResetRetries()
```

##### `ResetStartInterval` <a name="ResetStartInterval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartInterval"></a>

```csharp
private void ResetStartInterval()
```

##### `ResetStartPeriod` <a name="ResetStartPeriod" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartPeriod"></a>

```csharp
private void ResetStartPeriod()
```

##### `ResetTest` <a name="ResetTest" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTest"></a>

```csharp
private void ResetTest()
```

##### `ResetTimeout` <a name="ResetTimeout" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTimeout"></a>

```csharp
private void ResetTimeout()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.intervalInput">IntervalInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retriesInput">RetriesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startIntervalInput">StartIntervalInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriodInput">StartPeriodInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.testInput">TestInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeoutInput">TimeoutInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.interval">Interval</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retries">Retries</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startInterval">StartInterval</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriod">StartPeriod</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.test">Test</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeout">Timeout</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `IntervalInput`<sup>Optional</sup> <a name="IntervalInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.intervalInput"></a>

```csharp
public string IntervalInput { get; }
```

- *Type:* string

---

##### `RetriesInput`<sup>Optional</sup> <a name="RetriesInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retriesInput"></a>

```csharp
public double RetriesInput { get; }
```

- *Type:* double

---

##### `StartIntervalInput`<sup>Optional</sup> <a name="StartIntervalInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startIntervalInput"></a>

```csharp
public string StartIntervalInput { get; }
```

- *Type:* string

---

##### `StartPeriodInput`<sup>Optional</sup> <a name="StartPeriodInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriodInput"></a>

```csharp
public string StartPeriodInput { get; }
```

- *Type:* string

---

##### `TestInput`<sup>Optional</sup> <a name="TestInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.testInput"></a>

```csharp
public string[] TestInput { get; }
```

- *Type:* string[]

---

##### `TimeoutInput`<sup>Optional</sup> <a name="TimeoutInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeoutInput"></a>

```csharp
public string TimeoutInput { get; }
```

- *Type:* string

---

##### `Interval`<sup>Required</sup> <a name="Interval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.interval"></a>

```csharp
public string Interval { get; }
```

- *Type:* string

---

##### `Retries`<sup>Required</sup> <a name="Retries" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retries"></a>

```csharp
public double Retries { get; }
```

- *Type:* double

---

##### `StartInterval`<sup>Required</sup> <a name="StartInterval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startInterval"></a>

```csharp
public string StartInterval { get; }
```

- *Type:* string

---

##### `StartPeriod`<sup>Required</sup> <a name="StartPeriod" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriod"></a>

```csharp
public string StartPeriod { get; }
```

- *Type:* string

---

##### `Test`<sup>Required</sup> <a name="Test" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.test"></a>

```csharp
public string[] Test { get; }
```

- *Type:* string[]

---

##### `Timeout`<sup>Required</sup> <a name="Timeout" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeout"></a>

```csharp
public string Timeout { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.internalValue"></a>

```csharp
public ContainerHealthcheck InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

---


### ContainerHostList <a name="ContainerHostList" id="@cdktn/provider-docker.container.ContainerHostList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerHostList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerHostList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerHostList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerHostList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerHostList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerHostList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerHostList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerHostList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerHostList.get"></a>

```csharp
private ContainerHostOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerHostList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerHostList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerHostList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerHostList.property.internalValue"></a>

```csharp
public IResolvable|ContainerHost[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>[]

---


### ContainerHostOutputReference <a name="ContainerHostOutputReference" id="@cdktn/provider-docker.container.ContainerHostOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerHostOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerHostOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerHostOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerHostOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerHostOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerHostOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.hostInput">HostInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.ipInput">IpInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.host">Host</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.ip">Ip</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `HostInput`<sup>Optional</sup> <a name="HostInput" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.hostInput"></a>

```csharp
public string HostInput { get; }
```

- *Type:* string

---

##### `IpInput`<sup>Optional</sup> <a name="IpInput" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.ipInput"></a>

```csharp
public string IpInput { get; }
```

- *Type:* string

---

##### `Host`<sup>Required</sup> <a name="Host" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.host"></a>

```csharp
public string Host { get; }
```

- *Type:* string

---

##### `Ip`<sup>Required</sup> <a name="Ip" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.ip"></a>

```csharp
public string Ip { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerHost InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>

---


### ContainerLabelsList <a name="ContainerLabelsList" id="@cdktn/provider-docker.container.ContainerLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerLabelsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerLabelsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerLabelsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerLabelsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerLabelsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerLabelsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerLabelsList.get"></a>

```csharp
private ContainerLabelsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerLabelsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerLabelsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerLabelsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerLabelsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerLabels[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>[]

---


### ContainerLabelsOutputReference <a name="ContainerLabelsOutputReference" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerLabelsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.labelInput">LabelInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.valueInput">ValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.label">Label</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.value">Value</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `LabelInput`<sup>Optional</sup> <a name="LabelInput" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.labelInput"></a>

```csharp
public string LabelInput { get; }
```

- *Type:* string

---

##### `ValueInput`<sup>Optional</sup> <a name="ValueInput" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.valueInput"></a>

```csharp
public string ValueInput { get; }
```

- *Type:* string

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.label"></a>

```csharp
public string Label { get; }
```

- *Type:* string

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.value"></a>

```csharp
public string Value { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerLabels InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>

---


### ContainerMountsBindOptionsOutputReference <a name="ContainerMountsBindOptionsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsBindOptionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resetPropagation">ResetPropagation</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetPropagation` <a name="ResetPropagation" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resetPropagation"></a>

```csharp
private void ResetPropagation()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagationInput">PropagationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagation">Propagation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `PropagationInput`<sup>Optional</sup> <a name="PropagationInput" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagationInput"></a>

```csharp
public string PropagationInput { get; }
```

- *Type:* string

---

##### `Propagation`<sup>Required</sup> <a name="Propagation" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagation"></a>

```csharp
public string Propagation { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.internalValue"></a>

```csharp
public ContainerMountsBindOptions InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

---


### ContainerMountsList <a name="ContainerMountsList" id="@cdktn/provider-docker.container.ContainerMountsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerMountsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerMountsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerMountsList.get"></a>

```csharp
private ContainerMountsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerMountsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerMounts[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>[]

---


### ContainerMountsOutputReference <a name="ContainerMountsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.putBindOptions">PutBindOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.putTmpfsOptions">PutTmpfsOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.putVolumeOptions">PutVolumeOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetBindOptions">ResetBindOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetReadOnly">ResetReadOnly</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetSource">ResetSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetTmpfsOptions">ResetTmpfsOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetVolumeOptions">ResetVolumeOptions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutBindOptions` <a name="PutBindOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putBindOptions"></a>

```csharp
private void PutBindOptions(ContainerMountsBindOptions Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putBindOptions.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

---

##### `PutTmpfsOptions` <a name="PutTmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putTmpfsOptions"></a>

```csharp
private void PutTmpfsOptions(ContainerMountsTmpfsOptions Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putTmpfsOptions.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

---

##### `PutVolumeOptions` <a name="PutVolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putVolumeOptions"></a>

```csharp
private void PutVolumeOptions(ContainerMountsVolumeOptions Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putVolumeOptions.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

---

##### `ResetBindOptions` <a name="ResetBindOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetBindOptions"></a>

```csharp
private void ResetBindOptions()
```

##### `ResetReadOnly` <a name="ResetReadOnly" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetReadOnly"></a>

```csharp
private void ResetReadOnly()
```

##### `ResetSource` <a name="ResetSource" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetSource"></a>

```csharp
private void ResetSource()
```

##### `ResetTmpfsOptions` <a name="ResetTmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetTmpfsOptions"></a>

```csharp
private void ResetTmpfsOptions()
```

##### `ResetVolumeOptions` <a name="ResetVolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetVolumeOptions"></a>

```csharp
private void ResetVolumeOptions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptions">BindOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference">ContainerMountsBindOptionsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptions">TmpfsOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference">ContainerMountsTmpfsOptionsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptions">VolumeOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference">ContainerMountsVolumeOptionsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptionsInput">BindOptionsInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnlyInput">ReadOnlyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.sourceInput">SourceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.targetInput">TargetInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptionsInput">TmpfsOptionsInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptionsInput">VolumeOptionsInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnly">ReadOnly</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.source">Source</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.target">Target</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `BindOptions`<sup>Required</sup> <a name="BindOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptions"></a>

```csharp
public ContainerMountsBindOptionsOutputReference BindOptions { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference">ContainerMountsBindOptionsOutputReference</a>

---

##### `TmpfsOptions`<sup>Required</sup> <a name="TmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptions"></a>

```csharp
public ContainerMountsTmpfsOptionsOutputReference TmpfsOptions { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference">ContainerMountsTmpfsOptionsOutputReference</a>

---

##### `VolumeOptions`<sup>Required</sup> <a name="VolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptions"></a>

```csharp
public ContainerMountsVolumeOptionsOutputReference VolumeOptions { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference">ContainerMountsVolumeOptionsOutputReference</a>

---

##### `BindOptionsInput`<sup>Optional</sup> <a name="BindOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptionsInput"></a>

```csharp
public ContainerMountsBindOptions BindOptionsInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

---

##### `ReadOnlyInput`<sup>Optional</sup> <a name="ReadOnlyInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnlyInput"></a>

```csharp
public bool|IResolvable ReadOnlyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SourceInput`<sup>Optional</sup> <a name="SourceInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.sourceInput"></a>

```csharp
public string SourceInput { get; }
```

- *Type:* string

---

##### `TargetInput`<sup>Optional</sup> <a name="TargetInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.targetInput"></a>

```csharp
public string TargetInput { get; }
```

- *Type:* string

---

##### `TmpfsOptionsInput`<sup>Optional</sup> <a name="TmpfsOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptionsInput"></a>

```csharp
public ContainerMountsTmpfsOptions TmpfsOptionsInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `VolumeOptionsInput`<sup>Optional</sup> <a name="VolumeOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptionsInput"></a>

```csharp
public ContainerMountsVolumeOptions VolumeOptionsInput { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

---

##### `ReadOnly`<sup>Required</sup> <a name="ReadOnly" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnly"></a>

```csharp
public bool|IResolvable ReadOnly { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Source`<sup>Required</sup> <a name="Source" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.source"></a>

```csharp
public string Source { get; }
```

- *Type:* string

---

##### `Target`<sup>Required</sup> <a name="Target" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.target"></a>

```csharp
public string Target { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerMounts InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>

---


### ContainerMountsTmpfsOptionsOutputReference <a name="ContainerMountsTmpfsOptionsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsTmpfsOptionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetMode">ResetMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetSizeBytes">ResetSizeBytes</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetMode` <a name="ResetMode" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetMode"></a>

```csharp
private void ResetMode()
```

##### `ResetSizeBytes` <a name="ResetSizeBytes" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetSizeBytes"></a>

```csharp
private void ResetSizeBytes()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.modeInput">ModeInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytesInput">SizeBytesInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.mode">Mode</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytes">SizeBytes</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ModeInput`<sup>Optional</sup> <a name="ModeInput" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.modeInput"></a>

```csharp
public double ModeInput { get; }
```

- *Type:* double

---

##### `SizeBytesInput`<sup>Optional</sup> <a name="SizeBytesInput" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytesInput"></a>

```csharp
public double SizeBytesInput { get; }
```

- *Type:* double

---

##### `Mode`<sup>Required</sup> <a name="Mode" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.mode"></a>

```csharp
public double Mode { get; }
```

- *Type:* double

---

##### `SizeBytes`<sup>Required</sup> <a name="SizeBytes" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytes"></a>

```csharp
public double SizeBytes { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.internalValue"></a>

```csharp
public ContainerMountsTmpfsOptions InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

---


### ContainerMountsVolumeOptionsLabelsList <a name="ContainerMountsVolumeOptionsLabelsList" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsVolumeOptionsLabelsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.get"></a>

```csharp
private ContainerMountsVolumeOptionsLabelsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerMountsVolumeOptionsLabels[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]

---


### ContainerMountsVolumeOptionsLabelsOutputReference <a name="ContainerMountsVolumeOptionsLabelsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsVolumeOptionsLabelsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.labelInput">LabelInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.valueInput">ValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.label">Label</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.value">Value</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `LabelInput`<sup>Optional</sup> <a name="LabelInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.labelInput"></a>

```csharp
public string LabelInput { get; }
```

- *Type:* string

---

##### `ValueInput`<sup>Optional</sup> <a name="ValueInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.valueInput"></a>

```csharp
public string ValueInput { get; }
```

- *Type:* string

---

##### `Label`<sup>Required</sup> <a name="Label" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.label"></a>

```csharp
public string Label { get; }
```

- *Type:* string

---

##### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.value"></a>

```csharp
public string Value { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerMountsVolumeOptionsLabels InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>

---


### ContainerMountsVolumeOptionsOutputReference <a name="ContainerMountsVolumeOptionsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerMountsVolumeOptionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.putLabels">PutLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverName">ResetDriverName</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverOptions">ResetDriverOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetLabels">ResetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetNoCopy">ResetNoCopy</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetSubpath">ResetSubpath</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutLabels` <a name="PutLabels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.putLabels"></a>

```csharp
private void PutLabels(IResolvable|ContainerMountsVolumeOptionsLabels[] Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.putLabels.parameter.value"></a>

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]

---

##### `ResetDriverName` <a name="ResetDriverName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverName"></a>

```csharp
private void ResetDriverName()
```

##### `ResetDriverOptions` <a name="ResetDriverOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverOptions"></a>

```csharp
private void ResetDriverOptions()
```

##### `ResetLabels` <a name="ResetLabels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetLabels"></a>

```csharp
private void ResetLabels()
```

##### `ResetNoCopy` <a name="ResetNoCopy" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetNoCopy"></a>

```csharp
private void ResetNoCopy()
```

##### `ResetSubpath` <a name="ResetSubpath" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetSubpath"></a>

```csharp
private void ResetSubpath()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labels">Labels</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList">ContainerMountsVolumeOptionsLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverNameInput">DriverNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptionsInput">DriverOptionsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labelsInput">LabelsInput</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopyInput">NoCopyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpathInput">SubpathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverName">DriverName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptions">DriverOptions</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopy">NoCopy</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpath">Subpath</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Labels`<sup>Required</sup> <a name="Labels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labels"></a>

```csharp
public ContainerMountsVolumeOptionsLabelsList Labels { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList">ContainerMountsVolumeOptionsLabelsList</a>

---

##### `DriverNameInput`<sup>Optional</sup> <a name="DriverNameInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverNameInput"></a>

```csharp
public string DriverNameInput { get; }
```

- *Type:* string

---

##### `DriverOptionsInput`<sup>Optional</sup> <a name="DriverOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptionsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> DriverOptionsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `LabelsInput`<sup>Optional</sup> <a name="LabelsInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labelsInput"></a>

```csharp
public IResolvable|ContainerMountsVolumeOptionsLabels[] LabelsInput { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>[]

---

##### `NoCopyInput`<sup>Optional</sup> <a name="NoCopyInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopyInput"></a>

```csharp
public bool|IResolvable NoCopyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SubpathInput`<sup>Optional</sup> <a name="SubpathInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpathInput"></a>

```csharp
public string SubpathInput { get; }
```

- *Type:* string

---

##### `DriverName`<sup>Required</sup> <a name="DriverName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverName"></a>

```csharp
public string DriverName { get; }
```

- *Type:* string

---

##### `DriverOptions`<sup>Required</sup> <a name="DriverOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptions"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> DriverOptions { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `NoCopy`<sup>Required</sup> <a name="NoCopy" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopy"></a>

```csharp
public bool|IResolvable NoCopy { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `Subpath`<sup>Required</sup> <a name="Subpath" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpath"></a>

```csharp
public string Subpath { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.internalValue"></a>

```csharp
public ContainerMountsVolumeOptions InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

---


### ContainerNetworkDataList <a name="ContainerNetworkDataList" id="@cdktn/provider-docker.container.ContainerNetworkDataList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerNetworkDataList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerNetworkDataList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerNetworkDataList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerNetworkDataList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerNetworkDataList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerNetworkDataList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerNetworkDataList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerNetworkDataList.get"></a>

```csharp
private ContainerNetworkDataOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerNetworkDataList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerNetworkDataList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerNetworkDataList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---


### ContainerNetworkDataOutputReference <a name="ContainerNetworkDataOutputReference" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerNetworkDataOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.gateway">Gateway</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6Address">GlobalIpv6Address</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6PrefixLength">GlobalIpv6PrefixLength</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipAddress">IpAddress</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipPrefixLength">IpPrefixLength</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipv6Gateway">Ipv6Gateway</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.macAddress">MacAddress</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.networkName">NetworkName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.internalValue">InternalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerNetworkData">ContainerNetworkData</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Gateway`<sup>Required</sup> <a name="Gateway" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.gateway"></a>

```csharp
public string Gateway { get; }
```

- *Type:* string

---

##### `GlobalIpv6Address`<sup>Required</sup> <a name="GlobalIpv6Address" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6Address"></a>

```csharp
public string GlobalIpv6Address { get; }
```

- *Type:* string

---

##### `GlobalIpv6PrefixLength`<sup>Required</sup> <a name="GlobalIpv6PrefixLength" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6PrefixLength"></a>

```csharp
public double GlobalIpv6PrefixLength { get; }
```

- *Type:* double

---

##### `IpAddress`<sup>Required</sup> <a name="IpAddress" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipAddress"></a>

```csharp
public string IpAddress { get; }
```

- *Type:* string

---

##### `IpPrefixLength`<sup>Required</sup> <a name="IpPrefixLength" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipPrefixLength"></a>

```csharp
public double IpPrefixLength { get; }
```

- *Type:* double

---

##### `Ipv6Gateway`<sup>Required</sup> <a name="Ipv6Gateway" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipv6Gateway"></a>

```csharp
public string Ipv6Gateway { get; }
```

- *Type:* string

---

##### `MacAddress`<sup>Required</sup> <a name="MacAddress" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.macAddress"></a>

```csharp
public string MacAddress { get; }
```

- *Type:* string

---

##### `NetworkName`<sup>Required</sup> <a name="NetworkName" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.networkName"></a>

```csharp
public string NetworkName { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.internalValue"></a>

```csharp
public ContainerNetworkData InternalValue { get; }
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerNetworkData">ContainerNetworkData</a>

---


### ContainerNetworksAdvancedList <a name="ContainerNetworksAdvancedList" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerNetworksAdvancedList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.get"></a>

```csharp
private ContainerNetworksAdvancedOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.internalValue"></a>

```csharp
public IResolvable|ContainerNetworksAdvanced[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>[]

---


### ContainerNetworksAdvancedOutputReference <a name="ContainerNetworksAdvancedOutputReference" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerNetworksAdvancedOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetAliases">ResetAliases</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetDriverOpts">ResetDriverOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetGwPriority">ResetGwPriority</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv4Address">ResetIpv4Address</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv6Address">ResetIpv6Address</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetLinkLocalIps">ResetLinkLocalIps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetMacAddress">ResetMacAddress</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetAliases` <a name="ResetAliases" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetAliases"></a>

```csharp
private void ResetAliases()
```

##### `ResetDriverOpts` <a name="ResetDriverOpts" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetDriverOpts"></a>

```csharp
private void ResetDriverOpts()
```

##### `ResetGwPriority` <a name="ResetGwPriority" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetGwPriority"></a>

```csharp
private void ResetGwPriority()
```

##### `ResetIpv4Address` <a name="ResetIpv4Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv4Address"></a>

```csharp
private void ResetIpv4Address()
```

##### `ResetIpv6Address` <a name="ResetIpv6Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv6Address"></a>

```csharp
private void ResetIpv6Address()
```

##### `ResetLinkLocalIps` <a name="ResetLinkLocalIps" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetLinkLocalIps"></a>

```csharp
private void ResetLinkLocalIps()
```

##### `ResetMacAddress` <a name="ResetMacAddress" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetMacAddress"></a>

```csharp
private void ResetMacAddress()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliasesInput">AliasesInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOptsInput">DriverOptsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriorityInput">GwPriorityInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4AddressInput">Ipv4AddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6AddressInput">Ipv6AddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIpsInput">LinkLocalIpsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddressInput">MacAddressInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliases">Aliases</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOpts">DriverOpts</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriority">GwPriority</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4Address">Ipv4Address</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6Address">Ipv6Address</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIps">LinkLocalIps</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddress">MacAddress</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `AliasesInput`<sup>Optional</sup> <a name="AliasesInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliasesInput"></a>

```csharp
public string[] AliasesInput { get; }
```

- *Type:* string[]

---

##### `DriverOptsInput`<sup>Optional</sup> <a name="DriverOptsInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOptsInput"></a>

```csharp
public string[] DriverOptsInput { get; }
```

- *Type:* string[]

---

##### `GwPriorityInput`<sup>Optional</sup> <a name="GwPriorityInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriorityInput"></a>

```csharp
public double GwPriorityInput { get; }
```

- *Type:* double

---

##### `Ipv4AddressInput`<sup>Optional</sup> <a name="Ipv4AddressInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4AddressInput"></a>

```csharp
public string Ipv4AddressInput { get; }
```

- *Type:* string

---

##### `Ipv6AddressInput`<sup>Optional</sup> <a name="Ipv6AddressInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6AddressInput"></a>

```csharp
public string Ipv6AddressInput { get; }
```

- *Type:* string

---

##### `LinkLocalIpsInput`<sup>Optional</sup> <a name="LinkLocalIpsInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIpsInput"></a>

```csharp
public string[] LinkLocalIpsInput { get; }
```

- *Type:* string[]

---

##### `MacAddressInput`<sup>Optional</sup> <a name="MacAddressInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddressInput"></a>

```csharp
public string MacAddressInput { get; }
```

- *Type:* string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `Aliases`<sup>Required</sup> <a name="Aliases" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliases"></a>

```csharp
public string[] Aliases { get; }
```

- *Type:* string[]

---

##### `DriverOpts`<sup>Required</sup> <a name="DriverOpts" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOpts"></a>

```csharp
public string[] DriverOpts { get; }
```

- *Type:* string[]

---

##### `GwPriority`<sup>Required</sup> <a name="GwPriority" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriority"></a>

```csharp
public double GwPriority { get; }
```

- *Type:* double

---

##### `Ipv4Address`<sup>Required</sup> <a name="Ipv4Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4Address"></a>

```csharp
public string Ipv4Address { get; }
```

- *Type:* string

---

##### `Ipv6Address`<sup>Required</sup> <a name="Ipv6Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6Address"></a>

```csharp
public string Ipv6Address { get; }
```

- *Type:* string

---

##### `LinkLocalIps`<sup>Required</sup> <a name="LinkLocalIps" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIps"></a>

```csharp
public string[] LinkLocalIps { get; }
```

- *Type:* string[]

---

##### `MacAddress`<sup>Required</sup> <a name="MacAddress" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddress"></a>

```csharp
public string MacAddress { get; }
```

- *Type:* string

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerNetworksAdvanced InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>

---


### ContainerPortsList <a name="ContainerPortsList" id="@cdktn/provider-docker.container.ContainerPortsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerPortsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerPortsList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerPortsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerPortsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerPortsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerPortsList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerPortsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerPortsList.get"></a>

```csharp
private ContainerPortsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerPortsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerPortsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerPortsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerPortsList.property.internalValue"></a>

```csharp
public IResolvable|ContainerPorts[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>[]

---


### ContainerPortsOutputReference <a name="ContainerPortsOutputReference" id="@cdktn/provider-docker.container.ContainerPortsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerPortsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resetExternal">ResetExternal</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resetIp">ResetIp</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resetProtocol">ResetProtocol</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetExternal` <a name="ResetExternal" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resetExternal"></a>

```csharp
private void ResetExternal()
```

##### `ResetIp` <a name="ResetIp" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resetIp"></a>

```csharp
private void ResetIp()
```

##### `ResetProtocol` <a name="ResetProtocol" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resetProtocol"></a>

```csharp
private void ResetProtocol()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.externalInput">ExternalInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalInput">InternalInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ipInput">IpInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocolInput">ProtocolInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.external">External</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internal">Internal</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ip">Ip</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocol">Protocol</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ExternalInput`<sup>Optional</sup> <a name="ExternalInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.externalInput"></a>

```csharp
public double ExternalInput { get; }
```

- *Type:* double

---

##### `InternalInput`<sup>Optional</sup> <a name="InternalInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalInput"></a>

```csharp
public double InternalInput { get; }
```

- *Type:* double

---

##### `IpInput`<sup>Optional</sup> <a name="IpInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ipInput"></a>

```csharp
public string IpInput { get; }
```

- *Type:* string

---

##### `ProtocolInput`<sup>Optional</sup> <a name="ProtocolInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocolInput"></a>

```csharp
public string ProtocolInput { get; }
```

- *Type:* string

---

##### `External`<sup>Required</sup> <a name="External" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.external"></a>

```csharp
public double External { get; }
```

- *Type:* double

---

##### `Internal`<sup>Required</sup> <a name="Internal" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internal"></a>

```csharp
public double Internal { get; }
```

- *Type:* double

---

##### `Ip`<sup>Required</sup> <a name="Ip" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ip"></a>

```csharp
public string Ip { get; }
```

- *Type:* string

---

##### `Protocol`<sup>Required</sup> <a name="Protocol" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocol"></a>

```csharp
public string Protocol { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerPorts InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>

---


### ContainerTimeoutsOutputReference <a name="ContainerTimeoutsOutputReference" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerTimeoutsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetCreate">ResetCreate</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetDelete">ResetDelete</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetUpdate">ResetUpdate</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetCreate` <a name="ResetCreate" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetCreate"></a>

```csharp
private void ResetCreate()
```

##### `ResetDelete` <a name="ResetDelete" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetDelete"></a>

```csharp
private void ResetDelete()
```

##### `ResetUpdate` <a name="ResetUpdate" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetUpdate"></a>

```csharp
private void ResetUpdate()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.createInput">CreateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.deleteInput">DeleteInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.updateInput">UpdateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.create">Create</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.delete">Delete</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.update">Update</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `CreateInput`<sup>Optional</sup> <a name="CreateInput" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.createInput"></a>

```csharp
public string CreateInput { get; }
```

- *Type:* string

---

##### `DeleteInput`<sup>Optional</sup> <a name="DeleteInput" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.deleteInput"></a>

```csharp
public string DeleteInput { get; }
```

- *Type:* string

---

##### `UpdateInput`<sup>Optional</sup> <a name="UpdateInput" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.updateInput"></a>

```csharp
public string UpdateInput { get; }
```

- *Type:* string

---

##### `Create`<sup>Required</sup> <a name="Create" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.create"></a>

```csharp
public string Create { get; }
```

- *Type:* string

---

##### `Delete`<sup>Required</sup> <a name="Delete" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.delete"></a>

```csharp
public string Delete { get; }
```

- *Type:* string

---

##### `Update`<sup>Required</sup> <a name="Update" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.update"></a>

```csharp
public string Update { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerTimeouts InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

---


### ContainerUlimitList <a name="ContainerUlimitList" id="@cdktn/provider-docker.container.ContainerUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerUlimitList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerUlimitList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerUlimitList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerUlimitList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerUlimitList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerUlimitList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerUlimitList.get"></a>

```csharp
private ContainerUlimitOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerUlimitList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerUlimitList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerUlimitList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerUlimitList.property.internalValue"></a>

```csharp
public IResolvable|ContainerUlimit[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>[]

---


### ContainerUlimitOutputReference <a name="ContainerUlimitOutputReference" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerUlimitOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hardInput">HardInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.softInput">SoftInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hard">Hard</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.soft">Soft</a></code> | <code>double</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `HardInput`<sup>Optional</sup> <a name="HardInput" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hardInput"></a>

```csharp
public double HardInput { get; }
```

- *Type:* double

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `SoftInput`<sup>Optional</sup> <a name="SoftInput" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.softInput"></a>

```csharp
public double SoftInput { get; }
```

- *Type:* double

---

##### `Hard`<sup>Required</sup> <a name="Hard" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hard"></a>

```csharp
public double Hard { get; }
```

- *Type:* double

---

##### `Name`<sup>Required</sup> <a name="Name" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Soft`<sup>Required</sup> <a name="Soft" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.soft"></a>

```csharp
public double Soft { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerUlimit InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>

---


### ContainerUploadList <a name="ContainerUploadList" id="@cdktn/provider-docker.container.ContainerUploadList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerUploadList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerUploadList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerUploadList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerUploadList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerUploadList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerUploadList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerUploadList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerUploadList.get"></a>

```csharp
private ContainerUploadOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerUploadList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerUploadList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerUploadList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerUploadList.property.internalValue"></a>

```csharp
public IResolvable|ContainerUpload[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>[]

---


### ContainerUploadOutputReference <a name="ContainerUploadOutputReference" id="@cdktn/provider-docker.container.ContainerUploadOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerUploadOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContent">ResetContent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContentBase64">ResetContentBase64</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetExecutable">ResetExecutable</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetPermissions">ResetPermissions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSource">ResetSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSourceHash">ResetSourceHash</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetContent` <a name="ResetContent" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContent"></a>

```csharp
private void ResetContent()
```

##### `ResetContentBase64` <a name="ResetContentBase64" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContentBase64"></a>

```csharp
private void ResetContentBase64()
```

##### `ResetExecutable` <a name="ResetExecutable" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetExecutable"></a>

```csharp
private void ResetExecutable()
```

##### `ResetPermissions` <a name="ResetPermissions" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetPermissions"></a>

```csharp
private void ResetPermissions()
```

##### `ResetSource` <a name="ResetSource" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSource"></a>

```csharp
private void ResetSource()
```

##### `ResetSourceHash` <a name="ResetSourceHash" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSourceHash"></a>

```csharp
private void ResetSourceHash()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64Input">ContentBase64Input</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentInput">ContentInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executableInput">ExecutableInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fileInput">FileInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissionsInput">PermissionsInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHashInput">SourceHashInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceInput">SourceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.content">Content</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64">ContentBase64</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executable">Executable</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.file">File</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissions">Permissions</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.source">Source</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHash">SourceHash</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ContentBase64Input`<sup>Optional</sup> <a name="ContentBase64Input" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64Input"></a>

```csharp
public string ContentBase64Input { get; }
```

- *Type:* string

---

##### `ContentInput`<sup>Optional</sup> <a name="ContentInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentInput"></a>

```csharp
public string ContentInput { get; }
```

- *Type:* string

---

##### `ExecutableInput`<sup>Optional</sup> <a name="ExecutableInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executableInput"></a>

```csharp
public bool|IResolvable ExecutableInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `FileInput`<sup>Optional</sup> <a name="FileInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fileInput"></a>

```csharp
public string FileInput { get; }
```

- *Type:* string

---

##### `PermissionsInput`<sup>Optional</sup> <a name="PermissionsInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissionsInput"></a>

```csharp
public string PermissionsInput { get; }
```

- *Type:* string

---

##### `SourceHashInput`<sup>Optional</sup> <a name="SourceHashInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHashInput"></a>

```csharp
public string SourceHashInput { get; }
```

- *Type:* string

---

##### `SourceInput`<sup>Optional</sup> <a name="SourceInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceInput"></a>

```csharp
public string SourceInput { get; }
```

- *Type:* string

---

##### `Content`<sup>Required</sup> <a name="Content" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.content"></a>

```csharp
public string Content { get; }
```

- *Type:* string

---

##### `ContentBase64`<sup>Required</sup> <a name="ContentBase64" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64"></a>

```csharp
public string ContentBase64 { get; }
```

- *Type:* string

---

##### `Executable`<sup>Required</sup> <a name="Executable" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executable"></a>

```csharp
public bool|IResolvable Executable { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `File`<sup>Required</sup> <a name="File" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.file"></a>

```csharp
public string File { get; }
```

- *Type:* string

---

##### `Permissions`<sup>Required</sup> <a name="Permissions" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissions"></a>

```csharp
public string Permissions { get; }
```

- *Type:* string

---

##### `Source`<sup>Required</sup> <a name="Source" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.source"></a>

```csharp
public string Source { get; }
```

- *Type:* string

---

##### `SourceHash`<sup>Required</sup> <a name="SourceHash" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHash"></a>

```csharp
public string SourceHash { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerUpload InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>

---


### ContainerVolumesList <a name="ContainerVolumesList" id="@cdktn/provider-docker.container.ContainerVolumesList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerVolumesList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.allWithMapKey">AllWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.get">Get</a></code> | *No description.* |

---

##### `AllWithMapKey` <a name="AllWithMapKey" id="@cdktn/provider-docker.container.ContainerVolumesList.allWithMapKey"></a>

```csharp
private DynamicListTerraformIterator AllWithMapKey(string MapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `MapKeyAttributeName`<sup>Required</sup> <a name="MapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerVolumesList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* string

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerVolumesList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerVolumesList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerVolumesList.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerVolumesList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="@cdktn/provider-docker.container.ContainerVolumesList.get"></a>

```csharp
private ContainerVolumesOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="@cdktn/provider-docker.container.ContainerVolumesList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerVolumesList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerVolumesList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerVolumesList.property.internalValue"></a>

```csharp
public IResolvable|ContainerVolumes[] InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>[]

---


### ContainerVolumesOutputReference <a name="ContainerVolumesOutputReference" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Docker;

new ContainerVolumesOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>Io.Cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* Io.Cdktn.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetContainerPath">ResetContainerPath</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetFromContainer">ResetFromContainer</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetHostPath">ResetHostPath</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetReadOnly">ResetReadOnly</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetSelinuxRelabel">ResetSelinuxRelabel</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetVolumeName">ResetVolumeName</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resolve.parameter._context"></a>

- *Type:* Io.Cdktn.IResolveContext

---

##### `ToString` <a name="ToString" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetContainerPath` <a name="ResetContainerPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetContainerPath"></a>

```csharp
private void ResetContainerPath()
```

##### `ResetFromContainer` <a name="ResetFromContainer" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetFromContainer"></a>

```csharp
private void ResetFromContainer()
```

##### `ResetHostPath` <a name="ResetHostPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetHostPath"></a>

```csharp
private void ResetHostPath()
```

##### `ResetReadOnly` <a name="ResetReadOnly" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetReadOnly"></a>

```csharp
private void ResetReadOnly()
```

##### `ResetSelinuxRelabel` <a name="ResetSelinuxRelabel" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetSelinuxRelabel"></a>

```csharp
private void ResetSelinuxRelabel()
```

##### `ResetVolumeName` <a name="ResetVolumeName" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetVolumeName"></a>

```csharp
private void ResetVolumeName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPathInput">ContainerPathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainerInput">FromContainerInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPathInput">HostPathInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnlyInput">ReadOnlyInput</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabelInput">SelinuxRelabelInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeNameInput">VolumeNameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPath">ContainerPath</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainer">FromContainer</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPath">HostPath</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnly">ReadOnly</a></code> | <code>bool\|Io.Cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabel">SelinuxRelabel</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeName">VolumeName</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.internalValue">InternalValue</a></code> | <code>Io.Cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a></code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ContainerPathInput`<sup>Optional</sup> <a name="ContainerPathInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPathInput"></a>

```csharp
public string ContainerPathInput { get; }
```

- *Type:* string

---

##### `FromContainerInput`<sup>Optional</sup> <a name="FromContainerInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainerInput"></a>

```csharp
public string FromContainerInput { get; }
```

- *Type:* string

---

##### `HostPathInput`<sup>Optional</sup> <a name="HostPathInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPathInput"></a>

```csharp
public string HostPathInput { get; }
```

- *Type:* string

---

##### `ReadOnlyInput`<sup>Optional</sup> <a name="ReadOnlyInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnlyInput"></a>

```csharp
public bool|IResolvable ReadOnlyInput { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SelinuxRelabelInput`<sup>Optional</sup> <a name="SelinuxRelabelInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabelInput"></a>

```csharp
public string SelinuxRelabelInput { get; }
```

- *Type:* string

---

##### `VolumeNameInput`<sup>Optional</sup> <a name="VolumeNameInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeNameInput"></a>

```csharp
public string VolumeNameInput { get; }
```

- *Type:* string

---

##### `ContainerPath`<sup>Required</sup> <a name="ContainerPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPath"></a>

```csharp
public string ContainerPath { get; }
```

- *Type:* string

---

##### `FromContainer`<sup>Required</sup> <a name="FromContainer" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainer"></a>

```csharp
public string FromContainer { get; }
```

- *Type:* string

---

##### `HostPath`<sup>Required</sup> <a name="HostPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPath"></a>

```csharp
public string HostPath { get; }
```

- *Type:* string

---

##### `ReadOnly`<sup>Required</sup> <a name="ReadOnly" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnly"></a>

```csharp
public bool|IResolvable ReadOnly { get; }
```

- *Type:* bool|Io.Cdktn.IResolvable

---

##### `SelinuxRelabel`<sup>Required</sup> <a name="SelinuxRelabel" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabel"></a>

```csharp
public string SelinuxRelabel { get; }
```

- *Type:* string

---

##### `VolumeName`<sup>Required</sup> <a name="VolumeName" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeName"></a>

```csharp
public string VolumeName { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.internalValue"></a>

```csharp
public IResolvable|ContainerVolumes InternalValue { get; }
```

- *Type:* Io.Cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>

---



