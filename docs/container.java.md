# `container` Submodule <a name="`container` Submodule" id="@cdktn/provider-docker.container"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Container <a name="Container" id="@cdktn/provider-docker.container.Container"></a>

Represents a {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container docker_container}.

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.Container.Initializer"></a>

```java
import io.cdktn.providers.docker.container.Container;

Container.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .image(java.lang.String)
    .name(java.lang.String)
//  .attach(java.lang.Boolean|IResolvable)
//  .capabilities(ContainerCapabilities)
//  .cgroupnsMode(java.lang.String)
//  .cgroupParent(java.lang.String)
//  .command(java.util.List<java.lang.String>)
//  .containerReadRefreshTimeoutMilliseconds(java.lang.Number)
//  .cpuPeriod(java.lang.Number)
//  .cpuQuota(java.lang.Number)
//  .cpus(java.lang.String)
//  .cpuSet(java.lang.String)
//  .cpuShares(java.lang.Number)
//  .destroyGraceSeconds(java.lang.Number)
//  .deviceCgroupRules(java.util.List<java.lang.String>)
//  .deviceReadBps(IResolvable|java.util.List<ContainerDeviceReadBps>)
//  .deviceReadIops(IResolvable|java.util.List<ContainerDeviceReadIops>)
//  .deviceRequests(IResolvable|java.util.List<ContainerDeviceRequests>)
//  .devices(IResolvable|java.util.List<ContainerDevices>)
//  .deviceWriteBps(IResolvable|java.util.List<ContainerDeviceWriteBps>)
//  .deviceWriteIops(IResolvable|java.util.List<ContainerDeviceWriteIops>)
//  .dns(java.util.List<java.lang.String>)
//  .dnsOpts(java.util.List<java.lang.String>)
//  .dnsSearch(java.util.List<java.lang.String>)
//  .domainname(java.lang.String)
//  .entrypoint(java.util.List<java.lang.String>)
//  .env(java.util.List<java.lang.String>)
//  .gpus(java.lang.String)
//  .groupAdd(java.util.List<java.lang.String>)
//  .healthcheck(ContainerHealthcheck)
//  .host(IResolvable|java.util.List<ContainerHost>)
//  .hostname(java.lang.String)
//  .id(java.lang.String)
//  .init(java.lang.Boolean|IResolvable)
//  .ipcMode(java.lang.String)
//  .labels(IResolvable|java.util.List<ContainerLabels>)
//  .logDriver(java.lang.String)
//  .logOpts(java.util.Map<java.lang.String, java.lang.String>)
//  .logs(java.lang.Boolean|IResolvable)
//  .maxRetryCount(java.lang.Number)
//  .memory(java.lang.Number)
//  .memoryReservation(java.lang.Number)
//  .memorySwap(java.lang.Number)
//  .mounts(IResolvable|java.util.List<ContainerMounts>)
//  .mustRun(java.lang.Boolean|IResolvable)
//  .networkMode(java.lang.String)
//  .networksAdvanced(IResolvable|java.util.List<ContainerNetworksAdvanced>)
//  .pidMode(java.lang.String)
//  .platform(java.lang.String)
//  .ports(IResolvable|java.util.List<ContainerPorts>)
//  .privileged(java.lang.Boolean|IResolvable)
//  .publishAllPorts(java.lang.Boolean|IResolvable)
//  .readOnly(java.lang.Boolean|IResolvable)
//  .removeVolumes(java.lang.Boolean|IResolvable)
//  .restart(java.lang.String)
//  .rm(java.lang.Boolean|IResolvable)
//  .runtime(java.lang.String)
//  .securityOpts(java.util.List<java.lang.String>)
//  .shmSize(java.lang.Number)
//  .start(java.lang.Boolean|IResolvable)
//  .stdinOpen(java.lang.Boolean|IResolvable)
//  .stopSignal(java.lang.String)
//  .stopTimeout(java.lang.Number)
//  .storageOpts(java.util.Map<java.lang.String, java.lang.String>)
//  .sysctls(java.util.Map<java.lang.String, java.lang.String>)
//  .timeouts(ContainerTimeouts)
//  .tmpfs(java.util.Map<java.lang.String, java.lang.String>)
//  .tty(java.lang.Boolean|IResolvable)
//  .ulimit(IResolvable|java.util.List<ContainerUlimit>)
//  .upload(IResolvable|java.util.List<ContainerUpload>)
//  .user(java.lang.String)
//  .usernsMode(java.lang.String)
//  .volumes(IResolvable|java.util.List<ContainerVolumes>)
//  .wait(java.lang.Boolean|IResolvable)
//  .waitTimeout(java.lang.Number)
//  .workingDir(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.image">image</a></code> | <code>java.lang.String</code> | The ID of the image to back this container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | The name of the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.attach">attach</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true` attach to the container after its creation and waits the end of its execution. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.capabilities">capabilities</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | capabilities block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cgroupnsMode">cgroupnsMode</a></code> | <code>java.lang.String</code> | Cgroup namespace mode to use for the container. Possible values are: `private`, `host`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cgroupParent">cgroupParent</a></code> | <code>java.lang.String</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.command">command</a></code> | <code>java.util.List<java.lang.String></code> | The command to use to start the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.containerReadRefreshTimeoutMilliseconds">containerReadRefreshTimeoutMilliseconds</a></code> | <code>java.lang.Number</code> | The total number of milliseconds to wait for the container to reach status 'running'. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cpuPeriod">cpuPeriod</a></code> | <code>java.lang.Number</code> | Specify the CPU CFS scheduler period (in microseconds), which is used alongside `cpu-quota`. Is ignored if `cpus` is set. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cpuQuota">cpuQuota</a></code> | <code>java.lang.Number</code> | Impose a CPU CFS quota on the container (in microseconds). |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cpus">cpus</a></code> | <code>java.lang.String</code> | Specify how much of the available CPU resources a container can use. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cpuSet">cpuSet</a></code> | <code>java.lang.String</code> | A comma-separated list or hyphen-separated range of CPUs a container can use, e.g. `0-1`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.cpuShares">cpuShares</a></code> | <code>java.lang.Number</code> | CPU shares (relative weight) for the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.destroyGraceSeconds">destroyGraceSeconds</a></code> | <code>java.lang.Number</code> | If defined will attempt to stop the container before destroying. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.deviceCgroupRules">deviceCgroupRules</a></code> | <code>java.util.List<java.lang.String></code> | Cgroup rules to allow access to classes of devices without binding specific device nodes. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.deviceReadBps">deviceReadBps</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>></code> | device_read_bps block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.deviceReadIops">deviceReadIops</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>></code> | device_read_iops block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.deviceRequests">deviceRequests</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>></code> | device_requests block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.devices">devices</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>></code> | devices block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.deviceWriteBps">deviceWriteBps</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>></code> | device_write_bps block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.deviceWriteIops">deviceWriteIops</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>></code> | device_write_iops block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.dns">dns</a></code> | <code>java.util.List<java.lang.String></code> | DNS servers to use. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.dnsOpts">dnsOpts</a></code> | <code>java.util.List<java.lang.String></code> | DNS options used by the DNS provider(s), see `resolv.conf` documentation for valid list of options. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.dnsSearch">dnsSearch</a></code> | <code>java.util.List<java.lang.String></code> | DNS search domains that are used when bare unqualified hostnames are used inside of the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.domainname">domainname</a></code> | <code>java.lang.String</code> | Domain name of the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.entrypoint">entrypoint</a></code> | <code>java.util.List<java.lang.String></code> | The command to use as the Entrypoint for the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.env">env</a></code> | <code>java.util.List<java.lang.String></code> | Environment variables to set in the form of `KEY=VALUE`, e.g. `DEBUG=0`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.gpus">gpus</a></code> | <code>java.lang.String</code> | GPU devices to add to the container. Supported values are `all` or `device=<id[,id...]>`, for example `device=0,2` or `device=GPU-3a23c669-1f69-c64e-cf85-44e9b07e7a2a`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.groupAdd">groupAdd</a></code> | <code>java.util.List<java.lang.String></code> | Additional groups for the container user. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.healthcheck">healthcheck</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | healthcheck block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.host">host</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>></code> | host block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.hostname">hostname</a></code> | <code>java.lang.String</code> | Hostname of the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#id Container#id}. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.init">init</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Configured whether an init process should be injected for this container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.ipcMode">ipcMode</a></code> | <code>java.lang.String</code> | IPC sharing mode for the container. Possible values are: `none`, `private`, `shareable`, `container:<name\|id>` or `host`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.labels">labels</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>></code> | labels block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.logDriver">logDriver</a></code> | <code>java.lang.String</code> | The logging driver to use for the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.logOpts">logOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Key/value pairs to use as options for the logging driver. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.logs">logs</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Save the container logs (`attach` must be enabled). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.maxRetryCount">maxRetryCount</a></code> | <code>java.lang.Number</code> | The maximum amount of times to an attempt a restart when `restart` is set to 'on-failure'. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.memory">memory</a></code> | <code>java.lang.Number</code> | The memory limit for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.memoryReservation">memoryReservation</a></code> | <code>java.lang.Number</code> | The memory-resveration for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.memorySwap">memorySwap</a></code> | <code>java.lang.Number</code> | The total memory limit (memory + swap) for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.mounts">mounts</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>></code> | mounts block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.mustRun">mustRun</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the Docker container will be kept running. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.networkMode">networkMode</a></code> | <code>java.lang.String</code> | Network mode of the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.networksAdvanced">networksAdvanced</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>></code> | networks_advanced block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.pidMode">pidMode</a></code> | <code>java.lang.String</code> | The PID (Process) Namespace mode for the container. Either `container:<name\|id>` or `host`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.platform">platform</a></code> | <code>java.lang.String</code> | Platform in the format `os[/arch[/variant]]` used for image lookup and container runtime, for example `linux/amd64`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.ports">ports</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>></code> | ports block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.privileged">privileged</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the container runs in privileged mode. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.publishAllPorts">publishAllPorts</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Publish all ports of the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the container will be started as readonly. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.removeVolumes">removeVolumes</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, it will remove anonymous volumes associated with the container. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.restart">restart</a></code> | <code>java.lang.String</code> | The restart policy for the container. Must be one of 'no', 'on-failure', 'always', 'unless-stopped'. Defaults to `no`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.rm">rm</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the container will be automatically removed when it exits. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.runtime">runtime</a></code> | <code>java.lang.String</code> | Runtime to use for the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.securityOpts">securityOpts</a></code> | <code>java.util.List<java.lang.String></code> | List of string values to customize labels for MLS systems, such as SELinux. See https://docs.docker.com/engine/reference/run/#security-configuration. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.shmSize">shmSize</a></code> | <code>java.lang.Number</code> | Size of `/dev/shm` in MBs. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.start">start</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the Docker container will be started after creation. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.stdinOpen">stdinOpen</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, keep STDIN open even if not attached (`docker run -i`). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.stopSignal">stopSignal</a></code> | <code>java.lang.String</code> | Signal to stop a container (default `SIGTERM`). |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.stopTimeout">stopTimeout</a></code> | <code>java.lang.Number</code> | Timeout (in seconds) to stop a container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.storageOpts">storageOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Key/value pairs for the storage driver options, e.g. `size`: `120G`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.sysctls">sysctls</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of kernel parameters (sysctls) to set in the container. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.tmpfs">tmpfs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of container directories which should be replaced by `tmpfs mounts`, and their corresponding mount options. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.tty">tty</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, allocate a pseudo-tty (`docker run -t`). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.ulimit">ulimit</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>></code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.upload">upload</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>></code> | upload block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.user">user</a></code> | <code>java.lang.String</code> | User used for run the first process. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.usernsMode">usernsMode</a></code> | <code>java.lang.String</code> | Sets the usernamespace mode for the container when usernamespace remapping option is enabled. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.volumes">volumes</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>></code> | volumes block. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.wait">wait</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the Docker container is waited for being healthy state after creation. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.waitTimeout">waitTimeout</a></code> | <code>java.lang.Number</code> | The timeout in seconds to wait the container to be healthy after creation. Defaults to `60`. |
| <code><a href="#@cdktn/provider-docker.container.Container.Initializer.parameter.workingDir">workingDir</a></code> | <code>java.lang.String</code> | The working directory for commands to run in. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.container.Container.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.container.Container.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.container.Container.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.container.Container.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.container.Container.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.container.Container.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.container.Container.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.container.Container.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.container.Container.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `image`<sup>Required</sup> <a name="image" id="@cdktn/provider-docker.container.Container.Initializer.parameter.image"></a>

- *Type:* java.lang.String

The ID of the image to back this container.

The easiest way to get this value is to use the `image_id` attribute of the `docker_image` resource as is shown in the example.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#image Container#image}

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.Container.Initializer.parameter.name"></a>

- *Type:* java.lang.String

The name of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#name Container#name}

---

##### `attach`<sup>Optional</sup> <a name="attach" id="@cdktn/provider-docker.container.Container.Initializer.parameter.attach"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true` attach to the container after its creation and waits the end of its execution. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#attach Container#attach}

---

##### `capabilities`<sup>Optional</sup> <a name="capabilities" id="@cdktn/provider-docker.container.Container.Initializer.parameter.capabilities"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

capabilities block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#capabilities Container#capabilities}

---

##### `cgroupnsMode`<sup>Optional</sup> <a name="cgroupnsMode" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cgroupnsMode"></a>

- *Type:* java.lang.String

Cgroup namespace mode to use for the container. Possible values are: `private`, `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cgroupns_mode Container#cgroupns_mode}

---

##### `cgroupParent`<sup>Optional</sup> <a name="cgroupParent" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cgroupParent"></a>

- *Type:* java.lang.String

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cgroup_parent Container#cgroup_parent}

---

##### `command`<sup>Optional</sup> <a name="command" id="@cdktn/provider-docker.container.Container.Initializer.parameter.command"></a>

- *Type:* java.util.List<java.lang.String>

The command to use to start the container.

For example, to run `/usr/bin/myprogram -f baz.conf` set the command to be `["/usr/bin/myprogram","-f","baz.conf"]`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#command Container#command}

---

##### `containerReadRefreshTimeoutMilliseconds`<sup>Optional</sup> <a name="containerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.Container.Initializer.parameter.containerReadRefreshTimeoutMilliseconds"></a>

- *Type:* java.lang.Number

The total number of milliseconds to wait for the container to reach status 'running'.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#container_read_refresh_timeout_milliseconds Container#container_read_refresh_timeout_milliseconds}

---

##### `cpuPeriod`<sup>Optional</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cpuPeriod"></a>

- *Type:* java.lang.Number

Specify the CPU CFS scheduler period (in microseconds), which is used alongside `cpu-quota`. Is ignored if `cpus` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_period Container#cpu_period}

---

##### `cpuQuota`<sup>Optional</sup> <a name="cpuQuota" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cpuQuota"></a>

- *Type:* java.lang.Number

Impose a CPU CFS quota on the container (in microseconds).

The number of microseconds per `cpu-period` that the container is limited to before throttled. Is ignored if `cpus` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_quota Container#cpu_quota}

---

##### `cpus`<sup>Optional</sup> <a name="cpus" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cpus"></a>

- *Type:* java.lang.String

Specify how much of the available CPU resources a container can use.

e.g a value of 1.5 means the container is guaranteed at most one and a half of the CPUs. Has precedence over `cpu_period` and `cpu_quota`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpus Container#cpus}

---

##### `cpuSet`<sup>Optional</sup> <a name="cpuSet" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cpuSet"></a>

- *Type:* java.lang.String

A comma-separated list or hyphen-separated range of CPUs a container can use, e.g. `0-1`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_set Container#cpu_set}

---

##### `cpuShares`<sup>Optional</sup> <a name="cpuShares" id="@cdktn/provider-docker.container.Container.Initializer.parameter.cpuShares"></a>

- *Type:* java.lang.Number

CPU shares (relative weight) for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_shares Container#cpu_shares}

---

##### `destroyGraceSeconds`<sup>Optional</sup> <a name="destroyGraceSeconds" id="@cdktn/provider-docker.container.Container.Initializer.parameter.destroyGraceSeconds"></a>

- *Type:* java.lang.Number

If defined will attempt to stop the container before destroying.

Container will be destroyed after `n` seconds or on successful stop.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#destroy_grace_seconds Container#destroy_grace_seconds}

---

##### `deviceCgroupRules`<sup>Optional</sup> <a name="deviceCgroupRules" id="@cdktn/provider-docker.container.Container.Initializer.parameter.deviceCgroupRules"></a>

- *Type:* java.util.List<java.lang.String>

Cgroup rules to allow access to classes of devices without binding specific device nodes.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_cgroup_rules Container#device_cgroup_rules}

---

##### `deviceReadBps`<sup>Optional</sup> <a name="deviceReadBps" id="@cdktn/provider-docker.container.Container.Initializer.parameter.deviceReadBps"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>>

device_read_bps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_read_bps Container#device_read_bps}

---

##### `deviceReadIops`<sup>Optional</sup> <a name="deviceReadIops" id="@cdktn/provider-docker.container.Container.Initializer.parameter.deviceReadIops"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>>

device_read_iops block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_read_iops Container#device_read_iops}

---

##### `deviceRequests`<sup>Optional</sup> <a name="deviceRequests" id="@cdktn/provider-docker.container.Container.Initializer.parameter.deviceRequests"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>>

device_requests block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_requests Container#device_requests}

---

##### `devices`<sup>Optional</sup> <a name="devices" id="@cdktn/provider-docker.container.Container.Initializer.parameter.devices"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>>

devices block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#devices Container#devices}

---

##### `deviceWriteBps`<sup>Optional</sup> <a name="deviceWriteBps" id="@cdktn/provider-docker.container.Container.Initializer.parameter.deviceWriteBps"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>>

device_write_bps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_write_bps Container#device_write_bps}

---

##### `deviceWriteIops`<sup>Optional</sup> <a name="deviceWriteIops" id="@cdktn/provider-docker.container.Container.Initializer.parameter.deviceWriteIops"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>>

device_write_iops block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_write_iops Container#device_write_iops}

---

##### `dns`<sup>Optional</sup> <a name="dns" id="@cdktn/provider-docker.container.Container.Initializer.parameter.dns"></a>

- *Type:* java.util.List<java.lang.String>

DNS servers to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#dns Container#dns}

---

##### `dnsOpts`<sup>Optional</sup> <a name="dnsOpts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.dnsOpts"></a>

- *Type:* java.util.List<java.lang.String>

DNS options used by the DNS provider(s), see `resolv.conf` documentation for valid list of options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#dns_opts Container#dns_opts}

---

##### `dnsSearch`<sup>Optional</sup> <a name="dnsSearch" id="@cdktn/provider-docker.container.Container.Initializer.parameter.dnsSearch"></a>

- *Type:* java.util.List<java.lang.String>

DNS search domains that are used when bare unqualified hostnames are used inside of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#dns_search Container#dns_search}

---

##### `domainname`<sup>Optional</sup> <a name="domainname" id="@cdktn/provider-docker.container.Container.Initializer.parameter.domainname"></a>

- *Type:* java.lang.String

Domain name of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#domainname Container#domainname}

---

##### `entrypoint`<sup>Optional</sup> <a name="entrypoint" id="@cdktn/provider-docker.container.Container.Initializer.parameter.entrypoint"></a>

- *Type:* java.util.List<java.lang.String>

The command to use as the Entrypoint for the container.

The Entrypoint allows you to configure a container to run as an executable. For example, to run `/usr/bin/myprogram` when starting a container, set the entrypoint to be `"/usr/bin/myprogram"]`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#entrypoint Container#entrypoint}

---

##### `env`<sup>Optional</sup> <a name="env" id="@cdktn/provider-docker.container.Container.Initializer.parameter.env"></a>

- *Type:* java.util.List<java.lang.String>

Environment variables to set in the form of `KEY=VALUE`, e.g. `DEBUG=0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#env Container#env}

---

##### `gpus`<sup>Optional</sup> <a name="gpus" id="@cdktn/provider-docker.container.Container.Initializer.parameter.gpus"></a>

- *Type:* java.lang.String

GPU devices to add to the container. Supported values are `all` or `device=<id[,id...]>`, for example `device=0,2` or `device=GPU-3a23c669-1f69-c64e-cf85-44e9b07e7a2a`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#gpus Container#gpus}

---

##### `groupAdd`<sup>Optional</sup> <a name="groupAdd" id="@cdktn/provider-docker.container.Container.Initializer.parameter.groupAdd"></a>

- *Type:* java.util.List<java.lang.String>

Additional groups for the container user.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#group_add Container#group_add}

---

##### `healthcheck`<sup>Optional</sup> <a name="healthcheck" id="@cdktn/provider-docker.container.Container.Initializer.parameter.healthcheck"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

healthcheck block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#healthcheck Container#healthcheck}

---

##### `host`<sup>Optional</sup> <a name="host" id="@cdktn/provider-docker.container.Container.Initializer.parameter.host"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>>

host block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#host Container#host}

---

##### `hostname`<sup>Optional</sup> <a name="hostname" id="@cdktn/provider-docker.container.Container.Initializer.parameter.hostname"></a>

- *Type:* java.lang.String

Hostname of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#hostname Container#hostname}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.container.Container.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#id Container#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `init`<sup>Optional</sup> <a name="init" id="@cdktn/provider-docker.container.Container.Initializer.parameter.init"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Configured whether an init process should be injected for this container.

If unset this will default to the `dockerd` defaults.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#init Container#init}

---

##### `ipcMode`<sup>Optional</sup> <a name="ipcMode" id="@cdktn/provider-docker.container.Container.Initializer.parameter.ipcMode"></a>

- *Type:* java.lang.String

IPC sharing mode for the container. Possible values are: `none`, `private`, `shareable`, `container:<name|id>` or `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ipc_mode Container#ipc_mode}

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.container.Container.Initializer.parameter.labels"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>>

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#labels Container#labels}

---

##### `logDriver`<sup>Optional</sup> <a name="logDriver" id="@cdktn/provider-docker.container.Container.Initializer.parameter.logDriver"></a>

- *Type:* java.lang.String

The logging driver to use for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#log_driver Container#log_driver}

---

##### `logOpts`<sup>Optional</sup> <a name="logOpts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.logOpts"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Key/value pairs to use as options for the logging driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#log_opts Container#log_opts}

---

##### `logs`<sup>Optional</sup> <a name="logs" id="@cdktn/provider-docker.container.Container.Initializer.parameter.logs"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Save the container logs (`attach` must be enabled). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#logs Container#logs}

---

##### `maxRetryCount`<sup>Optional</sup> <a name="maxRetryCount" id="@cdktn/provider-docker.container.Container.Initializer.parameter.maxRetryCount"></a>

- *Type:* java.lang.Number

The maximum amount of times to an attempt a restart when `restart` is set to 'on-failure'.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#max_retry_count Container#max_retry_count}

---

##### `memory`<sup>Optional</sup> <a name="memory" id="@cdktn/provider-docker.container.Container.Initializer.parameter.memory"></a>

- *Type:* java.lang.Number

The memory limit for the container in MBs.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#memory Container#memory}

---

##### `memoryReservation`<sup>Optional</sup> <a name="memoryReservation" id="@cdktn/provider-docker.container.Container.Initializer.parameter.memoryReservation"></a>

- *Type:* java.lang.Number

The memory-resveration for the container in MBs.

Defaults to 0. Allows you to specify a soft limit smaller than `memory` which is activated when Docker detects contention or low memory on the host machine. If you use `memory-reservation`, it must be set lower than `memory` for it to take precedence. Because it is a soft limit, it doesn't guarantee that the container doesn't exceed the limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#memory_reservation Container#memory_reservation}

---

##### `memorySwap`<sup>Optional</sup> <a name="memorySwap" id="@cdktn/provider-docker.container.Container.Initializer.parameter.memorySwap"></a>

- *Type:* java.lang.Number

The total memory limit (memory + swap) for the container in MBs.

This setting may compute to `-1` after `terraform apply` if the target host doesn't support memory swap, when that is the case docker will use a soft limitation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#memory_swap Container#memory_swap}

---

##### `mounts`<sup>Optional</sup> <a name="mounts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.mounts"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>>

mounts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#mounts Container#mounts}

---

##### `mustRun`<sup>Optional</sup> <a name="mustRun" id="@cdktn/provider-docker.container.Container.Initializer.parameter.mustRun"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the Docker container will be kept running.

If `false`, Terraform leaves the container alone. This attribute is also used to trigger a restart of a stopped container. If your container is stopped, Terraform will set `must_run` to `false` and this will trigger a change. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#must_run Container#must_run}

---

##### `networkMode`<sup>Optional</sup> <a name="networkMode" id="@cdktn/provider-docker.container.Container.Initializer.parameter.networkMode"></a>

- *Type:* java.lang.String

Network mode of the container.

Defaults to `bridge`. If your host OS is any other OS, you need to set this value explicitly, e.g. `nat` when your container will be running on an Windows host. See https://docs.docker.com/engine/network/ for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#network_mode Container#network_mode}

---

##### `networksAdvanced`<sup>Optional</sup> <a name="networksAdvanced" id="@cdktn/provider-docker.container.Container.Initializer.parameter.networksAdvanced"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>>

networks_advanced block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#networks_advanced Container#networks_advanced}

---

##### `pidMode`<sup>Optional</sup> <a name="pidMode" id="@cdktn/provider-docker.container.Container.Initializer.parameter.pidMode"></a>

- *Type:* java.lang.String

The PID (Process) Namespace mode for the container. Either `container:<name|id>` or `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#pid_mode Container#pid_mode}

---

##### `platform`<sup>Optional</sup> <a name="platform" id="@cdktn/provider-docker.container.Container.Initializer.parameter.platform"></a>

- *Type:* java.lang.String

Platform in the format `os[/arch[/variant]]` used for image lookup and container runtime, for example `linux/amd64`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#platform Container#platform}

---

##### `ports`<sup>Optional</sup> <a name="ports" id="@cdktn/provider-docker.container.Container.Initializer.parameter.ports"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>>

ports block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ports Container#ports}

---

##### `privileged`<sup>Optional</sup> <a name="privileged" id="@cdktn/provider-docker.container.Container.Initializer.parameter.privileged"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the container runs in privileged mode.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#privileged Container#privileged}

---

##### `publishAllPorts`<sup>Optional</sup> <a name="publishAllPorts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.publishAllPorts"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Publish all ports of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#publish_all_ports Container#publish_all_ports}

---

##### `readOnly`<sup>Optional</sup> <a name="readOnly" id="@cdktn/provider-docker.container.Container.Initializer.parameter.readOnly"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the container will be started as readonly. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#read_only Container#read_only}

---

##### `removeVolumes`<sup>Optional</sup> <a name="removeVolumes" id="@cdktn/provider-docker.container.Container.Initializer.parameter.removeVolumes"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, it will remove anonymous volumes associated with the container. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#remove_volumes Container#remove_volumes}

---

##### `restart`<sup>Optional</sup> <a name="restart" id="@cdktn/provider-docker.container.Container.Initializer.parameter.restart"></a>

- *Type:* java.lang.String

The restart policy for the container. Must be one of 'no', 'on-failure', 'always', 'unless-stopped'. Defaults to `no`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#restart Container#restart}

---

##### `rm`<sup>Optional</sup> <a name="rm" id="@cdktn/provider-docker.container.Container.Initializer.parameter.rm"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the container will be automatically removed when it exits. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#rm Container#rm}

---

##### `runtime`<sup>Optional</sup> <a name="runtime" id="@cdktn/provider-docker.container.Container.Initializer.parameter.runtime"></a>

- *Type:* java.lang.String

Runtime to use for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#runtime Container#runtime}

---

##### `securityOpts`<sup>Optional</sup> <a name="securityOpts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.securityOpts"></a>

- *Type:* java.util.List<java.lang.String>

List of string values to customize labels for MLS systems, such as SELinux. See https://docs.docker.com/engine/reference/run/#security-configuration.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#security_opts Container#security_opts}

---

##### `shmSize`<sup>Optional</sup> <a name="shmSize" id="@cdktn/provider-docker.container.Container.Initializer.parameter.shmSize"></a>

- *Type:* java.lang.Number

Size of `/dev/shm` in MBs.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#shm_size Container#shm_size}

---

##### `start`<sup>Optional</sup> <a name="start" id="@cdktn/provider-docker.container.Container.Initializer.parameter.start"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the Docker container will be started after creation.

If `false`, then the container is only created. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#start Container#start}

---

##### `stdinOpen`<sup>Optional</sup> <a name="stdinOpen" id="@cdktn/provider-docker.container.Container.Initializer.parameter.stdinOpen"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, keep STDIN open even if not attached (`docker run -i`). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#stdin_open Container#stdin_open}

---

##### `stopSignal`<sup>Optional</sup> <a name="stopSignal" id="@cdktn/provider-docker.container.Container.Initializer.parameter.stopSignal"></a>

- *Type:* java.lang.String

Signal to stop a container (default `SIGTERM`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#stop_signal Container#stop_signal}

---

##### `stopTimeout`<sup>Optional</sup> <a name="stopTimeout" id="@cdktn/provider-docker.container.Container.Initializer.parameter.stopTimeout"></a>

- *Type:* java.lang.Number

Timeout (in seconds) to stop a container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#stop_timeout Container#stop_timeout}

---

##### `storageOpts`<sup>Optional</sup> <a name="storageOpts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.storageOpts"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Key/value pairs for the storage driver options, e.g. `size`: `120G`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#storage_opts Container#storage_opts}

---

##### `sysctls`<sup>Optional</sup> <a name="sysctls" id="@cdktn/provider-docker.container.Container.Initializer.parameter.sysctls"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of kernel parameters (sysctls) to set in the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#sysctls Container#sysctls}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.container.Container.Initializer.parameter.timeouts"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#timeouts Container#timeouts}

---

##### `tmpfs`<sup>Optional</sup> <a name="tmpfs" id="@cdktn/provider-docker.container.Container.Initializer.parameter.tmpfs"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of container directories which should be replaced by `tmpfs mounts`, and their corresponding mount options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#tmpfs Container#tmpfs}

---

##### `tty`<sup>Optional</sup> <a name="tty" id="@cdktn/provider-docker.container.Container.Initializer.parameter.tty"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, allocate a pseudo-tty (`docker run -t`). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#tty Container#tty}

---

##### `ulimit`<sup>Optional</sup> <a name="ulimit" id="@cdktn/provider-docker.container.Container.Initializer.parameter.ulimit"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>>

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ulimit Container#ulimit}

---

##### `upload`<sup>Optional</sup> <a name="upload" id="@cdktn/provider-docker.container.Container.Initializer.parameter.upload"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>>

upload block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#upload Container#upload}

---

##### `user`<sup>Optional</sup> <a name="user" id="@cdktn/provider-docker.container.Container.Initializer.parameter.user"></a>

- *Type:* java.lang.String

User used for run the first process.

Format is `user` or `user:group` which user and group can be passed literally or by name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#user Container#user}

---

##### `usernsMode`<sup>Optional</sup> <a name="usernsMode" id="@cdktn/provider-docker.container.Container.Initializer.parameter.usernsMode"></a>

- *Type:* java.lang.String

Sets the usernamespace mode for the container when usernamespace remapping option is enabled.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#userns_mode Container#userns_mode}

---

##### `volumes`<sup>Optional</sup> <a name="volumes" id="@cdktn/provider-docker.container.Container.Initializer.parameter.volumes"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>>

volumes block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#volumes Container#volumes}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.container.Container.Initializer.parameter.wait"></a>

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the Docker container is waited for being healthy state after creation.

This requires your container to have a healthcheck, otherwise this provider will error. If `false`, then the container health state is not checked. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#wait Container#wait}

---

##### `waitTimeout`<sup>Optional</sup> <a name="waitTimeout" id="@cdktn/provider-docker.container.Container.Initializer.parameter.waitTimeout"></a>

- *Type:* java.lang.Number

The timeout in seconds to wait the container to be healthy after creation. Defaults to `60`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#wait_timeout Container#wait_timeout}

---

##### `workingDir`<sup>Optional</sup> <a name="workingDir" id="@cdktn/provider-docker.container.Container.Initializer.parameter.workingDir"></a>

- *Type:* java.lang.String

The working directory for commands to run in.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#working_dir Container#working_dir}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-docker.container.Container.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-docker.container.Container.toHclTerraform">toHclTerraform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-docker.container.Container.addMoveTarget">addMoveTarget</a></code> | Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move. |
| <code><a href="#@cdktn/provider-docker.container.Container.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.hasResourceMove">hasResourceMove</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.importFrom">importFrom</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.moveFromId">moveFromId</a></code> | Move the resource corresponding to "id" to this resource. |
| <code><a href="#@cdktn/provider-docker.container.Container.moveTo">moveTo</a></code> | Moves this resource to the target resource given by moveTarget. |
| <code><a href="#@cdktn/provider-docker.container.Container.moveToId">moveToId</a></code> | Moves this resource to the resource corresponding to "id". |
| <code><a href="#@cdktn/provider-docker.container.Container.putCapabilities">putCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceReadBps">putDeviceReadBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceReadIops">putDeviceReadIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceRequests">putDeviceRequests</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDevices">putDevices</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceWriteBps">putDeviceWriteBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putDeviceWriteIops">putDeviceWriteIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putHealthcheck">putHealthcheck</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putHost">putHost</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putLabels">putLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putMounts">putMounts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putNetworksAdvanced">putNetworksAdvanced</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putPorts">putPorts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putTimeouts">putTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putUlimit">putUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putUpload">putUpload</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.putVolumes">putVolumes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetAttach">resetAttach</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCapabilities">resetCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCgroupnsMode">resetCgroupnsMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCgroupParent">resetCgroupParent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCommand">resetCommand</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetContainerReadRefreshTimeoutMilliseconds">resetContainerReadRefreshTimeoutMilliseconds</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuPeriod">resetCpuPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuQuota">resetCpuQuota</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpus">resetCpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuSet">resetCpuSet</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetCpuShares">resetCpuShares</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDestroyGraceSeconds">resetDestroyGraceSeconds</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceCgroupRules">resetDeviceCgroupRules</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceReadBps">resetDeviceReadBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceReadIops">resetDeviceReadIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceRequests">resetDeviceRequests</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDevices">resetDevices</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceWriteBps">resetDeviceWriteBps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDeviceWriteIops">resetDeviceWriteIops</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDns">resetDns</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDnsOpts">resetDnsOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDnsSearch">resetDnsSearch</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetDomainname">resetDomainname</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetEntrypoint">resetEntrypoint</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetEnv">resetEnv</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetGpus">resetGpus</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetGroupAdd">resetGroupAdd</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetHealthcheck">resetHealthcheck</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetHost">resetHost</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetHostname">resetHostname</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetId">resetId</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetInit">resetInit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetIpcMode">resetIpcMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLabels">resetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLogDriver">resetLogDriver</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLogOpts">resetLogOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetLogs">resetLogs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMaxRetryCount">resetMaxRetryCount</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMemory">resetMemory</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMemoryReservation">resetMemoryReservation</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMemorySwap">resetMemorySwap</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMounts">resetMounts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetMustRun">resetMustRun</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetNetworkMode">resetNetworkMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetNetworksAdvanced">resetNetworksAdvanced</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPidMode">resetPidMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPlatform">resetPlatform</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPorts">resetPorts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPrivileged">resetPrivileged</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetPublishAllPorts">resetPublishAllPorts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetReadOnly">resetReadOnly</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRemoveVolumes">resetRemoveVolumes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRestart">resetRestart</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRm">resetRm</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetRuntime">resetRuntime</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetSecurityOpts">resetSecurityOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetShmSize">resetShmSize</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStart">resetStart</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStdinOpen">resetStdinOpen</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStopSignal">resetStopSignal</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStopTimeout">resetStopTimeout</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetStorageOpts">resetStorageOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetSysctls">resetSysctls</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetTimeouts">resetTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetTmpfs">resetTmpfs</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetTty">resetTty</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUlimit">resetUlimit</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUpload">resetUpload</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUser">resetUser</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetUsernsMode">resetUsernsMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetVolumes">resetVolumes</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetWait">resetWait</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetWaitTimeout">resetWaitTimeout</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.resetWorkingDir">resetWorkingDir</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.Container.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-docker.container.Container.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-docker.container.Container.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-docker.container.Container.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.Container.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-docker.container.Container.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-docker.container.Container.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-docker.container.Container.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-docker.container.Container.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-docker.container.Container.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-docker.container.Container.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `addMoveTarget` <a name="addMoveTarget" id="@cdktn/provider-docker.container.Container.addMoveTarget"></a>

```java
public void addMoveTarget(java.lang.String moveTarget)
```

Adds a user defined moveTarget string to this resource to be later used in .moveTo(moveTarget) to resolve the location of the move.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.container.Container.addMoveTarget.parameter.moveTarget"></a>

- *Type:* java.lang.String

The string move target that will correspond to this resource.

---

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.Container.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.Container.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.Container.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.Container.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.Container.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.Container.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.Container.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.Container.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.Container.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `hasResourceMove` <a name="hasResourceMove" id="@cdktn/provider-docker.container.Container.hasResourceMove"></a>

```java
public TerraformResourceMoveByTarget|TerraformResourceMoveById hasResourceMove()
```

##### `importFrom` <a name="importFrom" id="@cdktn/provider-docker.container.Container.importFrom"></a>

```java
public void importFrom(java.lang.String id)
public void importFrom(java.lang.String id, TerraformProvider provider)
```

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.container.Container.importFrom.parameter.id"></a>

- *Type:* java.lang.String

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.container.Container.importFrom.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.Container.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.Container.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `moveFromId` <a name="moveFromId" id="@cdktn/provider-docker.container.Container.moveFromId"></a>

```java
public void moveFromId(java.lang.String id)
```

Move the resource corresponding to "id" to this resource.

Note that the resource being moved from must be marked as moved using its instance function.

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.container.Container.moveFromId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource being moved from, e.g. "aws_s3_bucket.example".

---

##### `moveTo` <a name="moveTo" id="@cdktn/provider-docker.container.Container.moveTo"></a>

```java
public void moveTo(java.lang.String moveTarget)
public void moveTo(java.lang.String moveTarget, java.lang.String|java.lang.Number index)
```

Moves this resource to the target resource given by moveTarget.

###### `moveTarget`<sup>Required</sup> <a name="moveTarget" id="@cdktn/provider-docker.container.Container.moveTo.parameter.moveTarget"></a>

- *Type:* java.lang.String

The previously set user defined string set by .addMoveTarget() corresponding to the resource to move to.

---

###### `index`<sup>Optional</sup> <a name="index" id="@cdktn/provider-docker.container.Container.moveTo.parameter.index"></a>

- *Type:* java.lang.String|java.lang.Number

Optional The index corresponding to the key the resource is to appear in the foreach of a resource to move to.

---

##### `moveToId` <a name="moveToId" id="@cdktn/provider-docker.container.Container.moveToId"></a>

```java
public void moveToId(java.lang.String id)
```

Moves this resource to the resource corresponding to "id".

###### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.container.Container.moveToId.parameter.id"></a>

- *Type:* java.lang.String

Full id of resource to move to, e.g. "aws_s3_bucket.example".

---

##### `putCapabilities` <a name="putCapabilities" id="@cdktn/provider-docker.container.Container.putCapabilities"></a>

```java
public void putCapabilities(ContainerCapabilities value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putCapabilities.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

---

##### `putDeviceReadBps` <a name="putDeviceReadBps" id="@cdktn/provider-docker.container.Container.putDeviceReadBps"></a>

```java
public void putDeviceReadBps(IResolvable|java.util.List<ContainerDeviceReadBps> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putDeviceReadBps.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>>

---

##### `putDeviceReadIops` <a name="putDeviceReadIops" id="@cdktn/provider-docker.container.Container.putDeviceReadIops"></a>

```java
public void putDeviceReadIops(IResolvable|java.util.List<ContainerDeviceReadIops> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putDeviceReadIops.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>>

---

##### `putDeviceRequests` <a name="putDeviceRequests" id="@cdktn/provider-docker.container.Container.putDeviceRequests"></a>

```java
public void putDeviceRequests(IResolvable|java.util.List<ContainerDeviceRequests> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putDeviceRequests.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>>

---

##### `putDevices` <a name="putDevices" id="@cdktn/provider-docker.container.Container.putDevices"></a>

```java
public void putDevices(IResolvable|java.util.List<ContainerDevices> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putDevices.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>>

---

##### `putDeviceWriteBps` <a name="putDeviceWriteBps" id="@cdktn/provider-docker.container.Container.putDeviceWriteBps"></a>

```java
public void putDeviceWriteBps(IResolvable|java.util.List<ContainerDeviceWriteBps> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putDeviceWriteBps.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>>

---

##### `putDeviceWriteIops` <a name="putDeviceWriteIops" id="@cdktn/provider-docker.container.Container.putDeviceWriteIops"></a>

```java
public void putDeviceWriteIops(IResolvable|java.util.List<ContainerDeviceWriteIops> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putDeviceWriteIops.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>>

---

##### `putHealthcheck` <a name="putHealthcheck" id="@cdktn/provider-docker.container.Container.putHealthcheck"></a>

```java
public void putHealthcheck(ContainerHealthcheck value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putHealthcheck.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

---

##### `putHost` <a name="putHost" id="@cdktn/provider-docker.container.Container.putHost"></a>

```java
public void putHost(IResolvable|java.util.List<ContainerHost> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putHost.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>>

---

##### `putLabels` <a name="putLabels" id="@cdktn/provider-docker.container.Container.putLabels"></a>

```java
public void putLabels(IResolvable|java.util.List<ContainerLabels> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putLabels.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>>

---

##### `putMounts` <a name="putMounts" id="@cdktn/provider-docker.container.Container.putMounts"></a>

```java
public void putMounts(IResolvable|java.util.List<ContainerMounts> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putMounts.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>>

---

##### `putNetworksAdvanced` <a name="putNetworksAdvanced" id="@cdktn/provider-docker.container.Container.putNetworksAdvanced"></a>

```java
public void putNetworksAdvanced(IResolvable|java.util.List<ContainerNetworksAdvanced> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putNetworksAdvanced.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>>

---

##### `putPorts` <a name="putPorts" id="@cdktn/provider-docker.container.Container.putPorts"></a>

```java
public void putPorts(IResolvable|java.util.List<ContainerPorts> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putPorts.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>>

---

##### `putTimeouts` <a name="putTimeouts" id="@cdktn/provider-docker.container.Container.putTimeouts"></a>

```java
public void putTimeouts(ContainerTimeouts value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putTimeouts.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

---

##### `putUlimit` <a name="putUlimit" id="@cdktn/provider-docker.container.Container.putUlimit"></a>

```java
public void putUlimit(IResolvable|java.util.List<ContainerUlimit> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putUlimit.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>>

---

##### `putUpload` <a name="putUpload" id="@cdktn/provider-docker.container.Container.putUpload"></a>

```java
public void putUpload(IResolvable|java.util.List<ContainerUpload> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putUpload.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>>

---

##### `putVolumes` <a name="putVolumes" id="@cdktn/provider-docker.container.Container.putVolumes"></a>

```java
public void putVolumes(IResolvable|java.util.List<ContainerVolumes> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.Container.putVolumes.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>>

---

##### `resetAttach` <a name="resetAttach" id="@cdktn/provider-docker.container.Container.resetAttach"></a>

```java
public void resetAttach()
```

##### `resetCapabilities` <a name="resetCapabilities" id="@cdktn/provider-docker.container.Container.resetCapabilities"></a>

```java
public void resetCapabilities()
```

##### `resetCgroupnsMode` <a name="resetCgroupnsMode" id="@cdktn/provider-docker.container.Container.resetCgroupnsMode"></a>

```java
public void resetCgroupnsMode()
```

##### `resetCgroupParent` <a name="resetCgroupParent" id="@cdktn/provider-docker.container.Container.resetCgroupParent"></a>

```java
public void resetCgroupParent()
```

##### `resetCommand` <a name="resetCommand" id="@cdktn/provider-docker.container.Container.resetCommand"></a>

```java
public void resetCommand()
```

##### `resetContainerReadRefreshTimeoutMilliseconds` <a name="resetContainerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.Container.resetContainerReadRefreshTimeoutMilliseconds"></a>

```java
public void resetContainerReadRefreshTimeoutMilliseconds()
```

##### `resetCpuPeriod` <a name="resetCpuPeriod" id="@cdktn/provider-docker.container.Container.resetCpuPeriod"></a>

```java
public void resetCpuPeriod()
```

##### `resetCpuQuota` <a name="resetCpuQuota" id="@cdktn/provider-docker.container.Container.resetCpuQuota"></a>

```java
public void resetCpuQuota()
```

##### `resetCpus` <a name="resetCpus" id="@cdktn/provider-docker.container.Container.resetCpus"></a>

```java
public void resetCpus()
```

##### `resetCpuSet` <a name="resetCpuSet" id="@cdktn/provider-docker.container.Container.resetCpuSet"></a>

```java
public void resetCpuSet()
```

##### `resetCpuShares` <a name="resetCpuShares" id="@cdktn/provider-docker.container.Container.resetCpuShares"></a>

```java
public void resetCpuShares()
```

##### `resetDestroyGraceSeconds` <a name="resetDestroyGraceSeconds" id="@cdktn/provider-docker.container.Container.resetDestroyGraceSeconds"></a>

```java
public void resetDestroyGraceSeconds()
```

##### `resetDeviceCgroupRules` <a name="resetDeviceCgroupRules" id="@cdktn/provider-docker.container.Container.resetDeviceCgroupRules"></a>

```java
public void resetDeviceCgroupRules()
```

##### `resetDeviceReadBps` <a name="resetDeviceReadBps" id="@cdktn/provider-docker.container.Container.resetDeviceReadBps"></a>

```java
public void resetDeviceReadBps()
```

##### `resetDeviceReadIops` <a name="resetDeviceReadIops" id="@cdktn/provider-docker.container.Container.resetDeviceReadIops"></a>

```java
public void resetDeviceReadIops()
```

##### `resetDeviceRequests` <a name="resetDeviceRequests" id="@cdktn/provider-docker.container.Container.resetDeviceRequests"></a>

```java
public void resetDeviceRequests()
```

##### `resetDevices` <a name="resetDevices" id="@cdktn/provider-docker.container.Container.resetDevices"></a>

```java
public void resetDevices()
```

##### `resetDeviceWriteBps` <a name="resetDeviceWriteBps" id="@cdktn/provider-docker.container.Container.resetDeviceWriteBps"></a>

```java
public void resetDeviceWriteBps()
```

##### `resetDeviceWriteIops` <a name="resetDeviceWriteIops" id="@cdktn/provider-docker.container.Container.resetDeviceWriteIops"></a>

```java
public void resetDeviceWriteIops()
```

##### `resetDns` <a name="resetDns" id="@cdktn/provider-docker.container.Container.resetDns"></a>

```java
public void resetDns()
```

##### `resetDnsOpts` <a name="resetDnsOpts" id="@cdktn/provider-docker.container.Container.resetDnsOpts"></a>

```java
public void resetDnsOpts()
```

##### `resetDnsSearch` <a name="resetDnsSearch" id="@cdktn/provider-docker.container.Container.resetDnsSearch"></a>

```java
public void resetDnsSearch()
```

##### `resetDomainname` <a name="resetDomainname" id="@cdktn/provider-docker.container.Container.resetDomainname"></a>

```java
public void resetDomainname()
```

##### `resetEntrypoint` <a name="resetEntrypoint" id="@cdktn/provider-docker.container.Container.resetEntrypoint"></a>

```java
public void resetEntrypoint()
```

##### `resetEnv` <a name="resetEnv" id="@cdktn/provider-docker.container.Container.resetEnv"></a>

```java
public void resetEnv()
```

##### `resetGpus` <a name="resetGpus" id="@cdktn/provider-docker.container.Container.resetGpus"></a>

```java
public void resetGpus()
```

##### `resetGroupAdd` <a name="resetGroupAdd" id="@cdktn/provider-docker.container.Container.resetGroupAdd"></a>

```java
public void resetGroupAdd()
```

##### `resetHealthcheck` <a name="resetHealthcheck" id="@cdktn/provider-docker.container.Container.resetHealthcheck"></a>

```java
public void resetHealthcheck()
```

##### `resetHost` <a name="resetHost" id="@cdktn/provider-docker.container.Container.resetHost"></a>

```java
public void resetHost()
```

##### `resetHostname` <a name="resetHostname" id="@cdktn/provider-docker.container.Container.resetHostname"></a>

```java
public void resetHostname()
```

##### `resetId` <a name="resetId" id="@cdktn/provider-docker.container.Container.resetId"></a>

```java
public void resetId()
```

##### `resetInit` <a name="resetInit" id="@cdktn/provider-docker.container.Container.resetInit"></a>

```java
public void resetInit()
```

##### `resetIpcMode` <a name="resetIpcMode" id="@cdktn/provider-docker.container.Container.resetIpcMode"></a>

```java
public void resetIpcMode()
```

##### `resetLabels` <a name="resetLabels" id="@cdktn/provider-docker.container.Container.resetLabels"></a>

```java
public void resetLabels()
```

##### `resetLogDriver` <a name="resetLogDriver" id="@cdktn/provider-docker.container.Container.resetLogDriver"></a>

```java
public void resetLogDriver()
```

##### `resetLogOpts` <a name="resetLogOpts" id="@cdktn/provider-docker.container.Container.resetLogOpts"></a>

```java
public void resetLogOpts()
```

##### `resetLogs` <a name="resetLogs" id="@cdktn/provider-docker.container.Container.resetLogs"></a>

```java
public void resetLogs()
```

##### `resetMaxRetryCount` <a name="resetMaxRetryCount" id="@cdktn/provider-docker.container.Container.resetMaxRetryCount"></a>

```java
public void resetMaxRetryCount()
```

##### `resetMemory` <a name="resetMemory" id="@cdktn/provider-docker.container.Container.resetMemory"></a>

```java
public void resetMemory()
```

##### `resetMemoryReservation` <a name="resetMemoryReservation" id="@cdktn/provider-docker.container.Container.resetMemoryReservation"></a>

```java
public void resetMemoryReservation()
```

##### `resetMemorySwap` <a name="resetMemorySwap" id="@cdktn/provider-docker.container.Container.resetMemorySwap"></a>

```java
public void resetMemorySwap()
```

##### `resetMounts` <a name="resetMounts" id="@cdktn/provider-docker.container.Container.resetMounts"></a>

```java
public void resetMounts()
```

##### `resetMustRun` <a name="resetMustRun" id="@cdktn/provider-docker.container.Container.resetMustRun"></a>

```java
public void resetMustRun()
```

##### `resetNetworkMode` <a name="resetNetworkMode" id="@cdktn/provider-docker.container.Container.resetNetworkMode"></a>

```java
public void resetNetworkMode()
```

##### `resetNetworksAdvanced` <a name="resetNetworksAdvanced" id="@cdktn/provider-docker.container.Container.resetNetworksAdvanced"></a>

```java
public void resetNetworksAdvanced()
```

##### `resetPidMode` <a name="resetPidMode" id="@cdktn/provider-docker.container.Container.resetPidMode"></a>

```java
public void resetPidMode()
```

##### `resetPlatform` <a name="resetPlatform" id="@cdktn/provider-docker.container.Container.resetPlatform"></a>

```java
public void resetPlatform()
```

##### `resetPorts` <a name="resetPorts" id="@cdktn/provider-docker.container.Container.resetPorts"></a>

```java
public void resetPorts()
```

##### `resetPrivileged` <a name="resetPrivileged" id="@cdktn/provider-docker.container.Container.resetPrivileged"></a>

```java
public void resetPrivileged()
```

##### `resetPublishAllPorts` <a name="resetPublishAllPorts" id="@cdktn/provider-docker.container.Container.resetPublishAllPorts"></a>

```java
public void resetPublishAllPorts()
```

##### `resetReadOnly` <a name="resetReadOnly" id="@cdktn/provider-docker.container.Container.resetReadOnly"></a>

```java
public void resetReadOnly()
```

##### `resetRemoveVolumes` <a name="resetRemoveVolumes" id="@cdktn/provider-docker.container.Container.resetRemoveVolumes"></a>

```java
public void resetRemoveVolumes()
```

##### `resetRestart` <a name="resetRestart" id="@cdktn/provider-docker.container.Container.resetRestart"></a>

```java
public void resetRestart()
```

##### `resetRm` <a name="resetRm" id="@cdktn/provider-docker.container.Container.resetRm"></a>

```java
public void resetRm()
```

##### `resetRuntime` <a name="resetRuntime" id="@cdktn/provider-docker.container.Container.resetRuntime"></a>

```java
public void resetRuntime()
```

##### `resetSecurityOpts` <a name="resetSecurityOpts" id="@cdktn/provider-docker.container.Container.resetSecurityOpts"></a>

```java
public void resetSecurityOpts()
```

##### `resetShmSize` <a name="resetShmSize" id="@cdktn/provider-docker.container.Container.resetShmSize"></a>

```java
public void resetShmSize()
```

##### `resetStart` <a name="resetStart" id="@cdktn/provider-docker.container.Container.resetStart"></a>

```java
public void resetStart()
```

##### `resetStdinOpen` <a name="resetStdinOpen" id="@cdktn/provider-docker.container.Container.resetStdinOpen"></a>

```java
public void resetStdinOpen()
```

##### `resetStopSignal` <a name="resetStopSignal" id="@cdktn/provider-docker.container.Container.resetStopSignal"></a>

```java
public void resetStopSignal()
```

##### `resetStopTimeout` <a name="resetStopTimeout" id="@cdktn/provider-docker.container.Container.resetStopTimeout"></a>

```java
public void resetStopTimeout()
```

##### `resetStorageOpts` <a name="resetStorageOpts" id="@cdktn/provider-docker.container.Container.resetStorageOpts"></a>

```java
public void resetStorageOpts()
```

##### `resetSysctls` <a name="resetSysctls" id="@cdktn/provider-docker.container.Container.resetSysctls"></a>

```java
public void resetSysctls()
```

##### `resetTimeouts` <a name="resetTimeouts" id="@cdktn/provider-docker.container.Container.resetTimeouts"></a>

```java
public void resetTimeouts()
```

##### `resetTmpfs` <a name="resetTmpfs" id="@cdktn/provider-docker.container.Container.resetTmpfs"></a>

```java
public void resetTmpfs()
```

##### `resetTty` <a name="resetTty" id="@cdktn/provider-docker.container.Container.resetTty"></a>

```java
public void resetTty()
```

##### `resetUlimit` <a name="resetUlimit" id="@cdktn/provider-docker.container.Container.resetUlimit"></a>

```java
public void resetUlimit()
```

##### `resetUpload` <a name="resetUpload" id="@cdktn/provider-docker.container.Container.resetUpload"></a>

```java
public void resetUpload()
```

##### `resetUser` <a name="resetUser" id="@cdktn/provider-docker.container.Container.resetUser"></a>

```java
public void resetUser()
```

##### `resetUsernsMode` <a name="resetUsernsMode" id="@cdktn/provider-docker.container.Container.resetUsernsMode"></a>

```java
public void resetUsernsMode()
```

##### `resetVolumes` <a name="resetVolumes" id="@cdktn/provider-docker.container.Container.resetVolumes"></a>

```java
public void resetVolumes()
```

##### `resetWait` <a name="resetWait" id="@cdktn/provider-docker.container.Container.resetWait"></a>

```java
public void resetWait()
```

##### `resetWaitTimeout` <a name="resetWaitTimeout" id="@cdktn/provider-docker.container.Container.resetWaitTimeout"></a>

```java
public void resetWaitTimeout()
```

##### `resetWorkingDir` <a name="resetWorkingDir" id="@cdktn/provider-docker.container.Container.resetWorkingDir"></a>

```java
public void resetWorkingDir()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-docker.container.Container.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.isTerraformResource">isTerraformResource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a Container resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-docker.container.Container.isConstruct"></a>

```java
import io.cdktn.providers.docker.container.Container;

Container.isConstruct(java.lang.Object x)
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.container.Container.isConstruct.parameter.x"></a>

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-docker.container.Container.isTerraformElement"></a>

```java
import io.cdktn.providers.docker.container.Container;

Container.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.container.Container.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="@cdktn/provider-docker.container.Container.isTerraformResource"></a>

```java
import io.cdktn.providers.docker.container.Container;

Container.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-docker.container.Container.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-docker.container.Container.generateConfigForImport"></a>

```java
import io.cdktn.providers.docker.container.Container;

Container.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),Container.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a Container resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the Container to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing Container that should be imported.

Refer to the {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.container.Container.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the Container to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.bridge">bridge</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.capabilities">capabilities</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference">ContainerCapabilitiesOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.containerLogs">containerLogs</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadBps">deviceReadBps</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList">ContainerDeviceReadBpsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadIops">deviceReadIops</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList">ContainerDeviceReadIopsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceRequests">deviceRequests</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList">ContainerDeviceRequestsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.devices">devices</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList">ContainerDevicesList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteBps">deviceWriteBps</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList">ContainerDeviceWriteBpsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteIops">deviceWriteIops</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList">ContainerDeviceWriteIopsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.exitCode">exitCode</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.healthcheck">healthcheck</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference">ContainerHealthcheckOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.host">host</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHostList">ContainerHostList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.labels">labels</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList">ContainerLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mounts">mounts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsList">ContainerMountsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networkData">networkData</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList">ContainerNetworkDataList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networksAdvanced">networksAdvanced</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList">ContainerNetworksAdvancedList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ports">ports</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerPortsList">ContainerPortsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference">ContainerTimeoutsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ulimit">ulimit</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList">ContainerUlimitList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.upload">upload</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerUploadList">ContainerUploadList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.volumes">volumes</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList">ContainerVolumesList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.attachInput">attachInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.capabilitiesInput">capabilitiesInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupnsModeInput">cgroupnsModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupParentInput">cgroupParentInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.commandInput">commandInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMillisecondsInput">containerReadRefreshTimeoutMillisecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuPeriodInput">cpuPeriodInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuQuotaInput">cpuQuotaInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuSetInput">cpuSetInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuSharesInput">cpuSharesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpusInput">cpusInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.destroyGraceSecondsInput">destroyGraceSecondsInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceCgroupRulesInput">deviceCgroupRulesInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadBpsInput">deviceReadBpsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceReadIopsInput">deviceReadIopsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceRequestsInput">deviceRequestsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.devicesInput">devicesInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteBpsInput">deviceWriteBpsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceWriteIopsInput">deviceWriteIopsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsInput">dnsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsOptsInput">dnsOptsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsSearchInput">dnsSearchInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.domainnameInput">domainnameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.entrypointInput">entrypointInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.envInput">envInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.gpusInput">gpusInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.groupAddInput">groupAddInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.healthcheckInput">healthcheckInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.hostInput">hostInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.hostnameInput">hostnameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.imageInput">imageInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.initInput">initInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ipcModeInput">ipcModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.labelsInput">labelsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logDriverInput">logDriverInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logOptsInput">logOptsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logsInput">logsInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.maxRetryCountInput">maxRetryCountInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memoryInput">memoryInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memoryReservationInput">memoryReservationInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memorySwapInput">memorySwapInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mountsInput">mountsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mustRunInput">mustRunInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networkModeInput">networkModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networksAdvancedInput">networksAdvancedInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.pidModeInput">pidModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.platformInput">platformInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.portsInput">portsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.privilegedInput">privilegedInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.publishAllPortsInput">publishAllPortsInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.readOnlyInput">readOnlyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.removeVolumesInput">removeVolumesInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.restartInput">restartInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.rmInput">rmInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.runtimeInput">runtimeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.securityOptsInput">securityOptsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.shmSizeInput">shmSizeInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.startInput">startInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stdinOpenInput">stdinOpenInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopSignalInput">stopSignalInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopTimeoutInput">stopTimeoutInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.storageOptsInput">storageOptsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.sysctlsInput">sysctlsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.timeoutsInput">timeoutsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tmpfsInput">tmpfsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ttyInput">ttyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ulimitInput">ulimitInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.uploadInput">uploadInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.userInput">userInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.usernsModeInput">usernsModeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.volumesInput">volumesInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.waitInput">waitInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.waitTimeoutInput">waitTimeoutInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.workingDirInput">workingDirInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.attach">attach</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupnsMode">cgroupnsMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cgroupParent">cgroupParent</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.command">command</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMilliseconds">containerReadRefreshTimeoutMilliseconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuPeriod">cpuPeriod</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuQuota">cpuQuota</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpus">cpus</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuSet">cpuSet</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.cpuShares">cpuShares</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.destroyGraceSeconds">destroyGraceSeconds</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.deviceCgroupRules">deviceCgroupRules</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dns">dns</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsOpts">dnsOpts</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.dnsSearch">dnsSearch</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.domainname">domainname</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.entrypoint">entrypoint</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.env">env</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.gpus">gpus</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.groupAdd">groupAdd</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.hostname">hostname</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.image">image</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.init">init</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.ipcMode">ipcMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logDriver">logDriver</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logOpts">logOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.logs">logs</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.maxRetryCount">maxRetryCount</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memory">memory</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memoryReservation">memoryReservation</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.memorySwap">memorySwap</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.mustRun">mustRun</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.networkMode">networkMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.pidMode">pidMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.platform">platform</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.privileged">privileged</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.publishAllPorts">publishAllPorts</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.removeVolumes">removeVolumes</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.restart">restart</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.rm">rm</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.runtime">runtime</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.securityOpts">securityOpts</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.shmSize">shmSize</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.start">start</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stdinOpen">stdinOpen</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopSignal">stopSignal</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.stopTimeout">stopTimeout</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.storageOpts">storageOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.sysctls">sysctls</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tmpfs">tmpfs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tty">tty</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.user">user</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.usernsMode">usernsMode</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.wait">wait</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.waitTimeout">waitTimeout</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.Container.property.workingDir">workingDir</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-docker.container.Container.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-docker.container.Container.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.Container.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-docker.container.Container.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-docker.container.Container.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-docker.container.Container.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-docker.container.Container.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.container.Container.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.container.Container.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.container.Container.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.container.Container.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.container.Container.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.container.Container.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.container.Container.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `bridge`<sup>Required</sup> <a name="bridge" id="@cdktn/provider-docker.container.Container.property.bridge"></a>

```java
public java.lang.String getBridge();
```

- *Type:* java.lang.String

---

##### `capabilities`<sup>Required</sup> <a name="capabilities" id="@cdktn/provider-docker.container.Container.property.capabilities"></a>

```java
public ContainerCapabilitiesOutputReference getCapabilities();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference">ContainerCapabilitiesOutputReference</a>

---

##### `containerLogs`<sup>Required</sup> <a name="containerLogs" id="@cdktn/provider-docker.container.Container.property.containerLogs"></a>

```java
public java.lang.String getContainerLogs();
```

- *Type:* java.lang.String

---

##### `deviceReadBps`<sup>Required</sup> <a name="deviceReadBps" id="@cdktn/provider-docker.container.Container.property.deviceReadBps"></a>

```java
public ContainerDeviceReadBpsList getDeviceReadBps();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList">ContainerDeviceReadBpsList</a>

---

##### `deviceReadIops`<sup>Required</sup> <a name="deviceReadIops" id="@cdktn/provider-docker.container.Container.property.deviceReadIops"></a>

```java
public ContainerDeviceReadIopsList getDeviceReadIops();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList">ContainerDeviceReadIopsList</a>

---

##### `deviceRequests`<sup>Required</sup> <a name="deviceRequests" id="@cdktn/provider-docker.container.Container.property.deviceRequests"></a>

```java
public ContainerDeviceRequestsList getDeviceRequests();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList">ContainerDeviceRequestsList</a>

---

##### `devices`<sup>Required</sup> <a name="devices" id="@cdktn/provider-docker.container.Container.property.devices"></a>

```java
public ContainerDevicesList getDevices();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDevicesList">ContainerDevicesList</a>

---

##### `deviceWriteBps`<sup>Required</sup> <a name="deviceWriteBps" id="@cdktn/provider-docker.container.Container.property.deviceWriteBps"></a>

```java
public ContainerDeviceWriteBpsList getDeviceWriteBps();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList">ContainerDeviceWriteBpsList</a>

---

##### `deviceWriteIops`<sup>Required</sup> <a name="deviceWriteIops" id="@cdktn/provider-docker.container.Container.property.deviceWriteIops"></a>

```java
public ContainerDeviceWriteIopsList getDeviceWriteIops();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList">ContainerDeviceWriteIopsList</a>

---

##### `exitCode`<sup>Required</sup> <a name="exitCode" id="@cdktn/provider-docker.container.Container.property.exitCode"></a>

```java
public java.lang.Number getExitCode();
```

- *Type:* java.lang.Number

---

##### `healthcheck`<sup>Required</sup> <a name="healthcheck" id="@cdktn/provider-docker.container.Container.property.healthcheck"></a>

```java
public ContainerHealthcheckOutputReference getHealthcheck();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference">ContainerHealthcheckOutputReference</a>

---

##### `host`<sup>Required</sup> <a name="host" id="@cdktn/provider-docker.container.Container.property.host"></a>

```java
public ContainerHostList getHost();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHostList">ContainerHostList</a>

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.container.Container.property.labels"></a>

```java
public ContainerLabelsList getLabels();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerLabelsList">ContainerLabelsList</a>

---

##### `mounts`<sup>Required</sup> <a name="mounts" id="@cdktn/provider-docker.container.Container.property.mounts"></a>

```java
public ContainerMountsList getMounts();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsList">ContainerMountsList</a>

---

##### `networkData`<sup>Required</sup> <a name="networkData" id="@cdktn/provider-docker.container.Container.property.networkData"></a>

```java
public ContainerNetworkDataList getNetworkData();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerNetworkDataList">ContainerNetworkDataList</a>

---

##### `networksAdvanced`<sup>Required</sup> <a name="networksAdvanced" id="@cdktn/provider-docker.container.Container.property.networksAdvanced"></a>

```java
public ContainerNetworksAdvancedList getNetworksAdvanced();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList">ContainerNetworksAdvancedList</a>

---

##### `ports`<sup>Required</sup> <a name="ports" id="@cdktn/provider-docker.container.Container.property.ports"></a>

```java
public ContainerPortsList getPorts();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerPortsList">ContainerPortsList</a>

---

##### `timeouts`<sup>Required</sup> <a name="timeouts" id="@cdktn/provider-docker.container.Container.property.timeouts"></a>

```java
public ContainerTimeoutsOutputReference getTimeouts();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference">ContainerTimeoutsOutputReference</a>

---

##### `ulimit`<sup>Required</sup> <a name="ulimit" id="@cdktn/provider-docker.container.Container.property.ulimit"></a>

```java
public ContainerUlimitList getUlimit();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerUlimitList">ContainerUlimitList</a>

---

##### `upload`<sup>Required</sup> <a name="upload" id="@cdktn/provider-docker.container.Container.property.upload"></a>

```java
public ContainerUploadList getUpload();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerUploadList">ContainerUploadList</a>

---

##### `volumes`<sup>Required</sup> <a name="volumes" id="@cdktn/provider-docker.container.Container.property.volumes"></a>

```java
public ContainerVolumesList getVolumes();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerVolumesList">ContainerVolumesList</a>

---

##### `attachInput`<sup>Optional</sup> <a name="attachInput" id="@cdktn/provider-docker.container.Container.property.attachInput"></a>

```java
public java.lang.Boolean|IResolvable getAttachInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `capabilitiesInput`<sup>Optional</sup> <a name="capabilitiesInput" id="@cdktn/provider-docker.container.Container.property.capabilitiesInput"></a>

```java
public ContainerCapabilities getCapabilitiesInput();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

---

##### `cgroupnsModeInput`<sup>Optional</sup> <a name="cgroupnsModeInput" id="@cdktn/provider-docker.container.Container.property.cgroupnsModeInput"></a>

```java
public java.lang.String getCgroupnsModeInput();
```

- *Type:* java.lang.String

---

##### `cgroupParentInput`<sup>Optional</sup> <a name="cgroupParentInput" id="@cdktn/provider-docker.container.Container.property.cgroupParentInput"></a>

```java
public java.lang.String getCgroupParentInput();
```

- *Type:* java.lang.String

---

##### `commandInput`<sup>Optional</sup> <a name="commandInput" id="@cdktn/provider-docker.container.Container.property.commandInput"></a>

```java
public java.util.List<java.lang.String> getCommandInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `containerReadRefreshTimeoutMillisecondsInput`<sup>Optional</sup> <a name="containerReadRefreshTimeoutMillisecondsInput" id="@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMillisecondsInput"></a>

```java
public java.lang.Number getContainerReadRefreshTimeoutMillisecondsInput();
```

- *Type:* java.lang.Number

---

##### `cpuPeriodInput`<sup>Optional</sup> <a name="cpuPeriodInput" id="@cdktn/provider-docker.container.Container.property.cpuPeriodInput"></a>

```java
public java.lang.Number getCpuPeriodInput();
```

- *Type:* java.lang.Number

---

##### `cpuQuotaInput`<sup>Optional</sup> <a name="cpuQuotaInput" id="@cdktn/provider-docker.container.Container.property.cpuQuotaInput"></a>

```java
public java.lang.Number getCpuQuotaInput();
```

- *Type:* java.lang.Number

---

##### `cpuSetInput`<sup>Optional</sup> <a name="cpuSetInput" id="@cdktn/provider-docker.container.Container.property.cpuSetInput"></a>

```java
public java.lang.String getCpuSetInput();
```

- *Type:* java.lang.String

---

##### `cpuSharesInput`<sup>Optional</sup> <a name="cpuSharesInput" id="@cdktn/provider-docker.container.Container.property.cpuSharesInput"></a>

```java
public java.lang.Number getCpuSharesInput();
```

- *Type:* java.lang.Number

---

##### `cpusInput`<sup>Optional</sup> <a name="cpusInput" id="@cdktn/provider-docker.container.Container.property.cpusInput"></a>

```java
public java.lang.String getCpusInput();
```

- *Type:* java.lang.String

---

##### `destroyGraceSecondsInput`<sup>Optional</sup> <a name="destroyGraceSecondsInput" id="@cdktn/provider-docker.container.Container.property.destroyGraceSecondsInput"></a>

```java
public java.lang.Number getDestroyGraceSecondsInput();
```

- *Type:* java.lang.Number

---

##### `deviceCgroupRulesInput`<sup>Optional</sup> <a name="deviceCgroupRulesInput" id="@cdktn/provider-docker.container.Container.property.deviceCgroupRulesInput"></a>

```java
public java.util.List<java.lang.String> getDeviceCgroupRulesInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `deviceReadBpsInput`<sup>Optional</sup> <a name="deviceReadBpsInput" id="@cdktn/provider-docker.container.Container.property.deviceReadBpsInput"></a>

```java
public IResolvable|java.util.List<ContainerDeviceReadBps> getDeviceReadBpsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>>

---

##### `deviceReadIopsInput`<sup>Optional</sup> <a name="deviceReadIopsInput" id="@cdktn/provider-docker.container.Container.property.deviceReadIopsInput"></a>

```java
public IResolvable|java.util.List<ContainerDeviceReadIops> getDeviceReadIopsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>>

---

##### `deviceRequestsInput`<sup>Optional</sup> <a name="deviceRequestsInput" id="@cdktn/provider-docker.container.Container.property.deviceRequestsInput"></a>

```java
public IResolvable|java.util.List<ContainerDeviceRequests> getDeviceRequestsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>>

---

##### `devicesInput`<sup>Optional</sup> <a name="devicesInput" id="@cdktn/provider-docker.container.Container.property.devicesInput"></a>

```java
public IResolvable|java.util.List<ContainerDevices> getDevicesInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>>

---

##### `deviceWriteBpsInput`<sup>Optional</sup> <a name="deviceWriteBpsInput" id="@cdktn/provider-docker.container.Container.property.deviceWriteBpsInput"></a>

```java
public IResolvable|java.util.List<ContainerDeviceWriteBps> getDeviceWriteBpsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>>

---

##### `deviceWriteIopsInput`<sup>Optional</sup> <a name="deviceWriteIopsInput" id="@cdktn/provider-docker.container.Container.property.deviceWriteIopsInput"></a>

```java
public IResolvable|java.util.List<ContainerDeviceWriteIops> getDeviceWriteIopsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>>

---

##### `dnsInput`<sup>Optional</sup> <a name="dnsInput" id="@cdktn/provider-docker.container.Container.property.dnsInput"></a>

```java
public java.util.List<java.lang.String> getDnsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `dnsOptsInput`<sup>Optional</sup> <a name="dnsOptsInput" id="@cdktn/provider-docker.container.Container.property.dnsOptsInput"></a>

```java
public java.util.List<java.lang.String> getDnsOptsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `dnsSearchInput`<sup>Optional</sup> <a name="dnsSearchInput" id="@cdktn/provider-docker.container.Container.property.dnsSearchInput"></a>

```java
public java.util.List<java.lang.String> getDnsSearchInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `domainnameInput`<sup>Optional</sup> <a name="domainnameInput" id="@cdktn/provider-docker.container.Container.property.domainnameInput"></a>

```java
public java.lang.String getDomainnameInput();
```

- *Type:* java.lang.String

---

##### `entrypointInput`<sup>Optional</sup> <a name="entrypointInput" id="@cdktn/provider-docker.container.Container.property.entrypointInput"></a>

```java
public java.util.List<java.lang.String> getEntrypointInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `envInput`<sup>Optional</sup> <a name="envInput" id="@cdktn/provider-docker.container.Container.property.envInput"></a>

```java
public java.util.List<java.lang.String> getEnvInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `gpusInput`<sup>Optional</sup> <a name="gpusInput" id="@cdktn/provider-docker.container.Container.property.gpusInput"></a>

```java
public java.lang.String getGpusInput();
```

- *Type:* java.lang.String

---

##### `groupAddInput`<sup>Optional</sup> <a name="groupAddInput" id="@cdktn/provider-docker.container.Container.property.groupAddInput"></a>

```java
public java.util.List<java.lang.String> getGroupAddInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `healthcheckInput`<sup>Optional</sup> <a name="healthcheckInput" id="@cdktn/provider-docker.container.Container.property.healthcheckInput"></a>

```java
public ContainerHealthcheck getHealthcheckInput();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

---

##### `hostInput`<sup>Optional</sup> <a name="hostInput" id="@cdktn/provider-docker.container.Container.property.hostInput"></a>

```java
public IResolvable|java.util.List<ContainerHost> getHostInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>>

---

##### `hostnameInput`<sup>Optional</sup> <a name="hostnameInput" id="@cdktn/provider-docker.container.Container.property.hostnameInput"></a>

```java
public java.lang.String getHostnameInput();
```

- *Type:* java.lang.String

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="@cdktn/provider-docker.container.Container.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `imageInput`<sup>Optional</sup> <a name="imageInput" id="@cdktn/provider-docker.container.Container.property.imageInput"></a>

```java
public java.lang.String getImageInput();
```

- *Type:* java.lang.String

---

##### `initInput`<sup>Optional</sup> <a name="initInput" id="@cdktn/provider-docker.container.Container.property.initInput"></a>

```java
public java.lang.Boolean|IResolvable getInitInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `ipcModeInput`<sup>Optional</sup> <a name="ipcModeInput" id="@cdktn/provider-docker.container.Container.property.ipcModeInput"></a>

```java
public java.lang.String getIpcModeInput();
```

- *Type:* java.lang.String

---

##### `labelsInput`<sup>Optional</sup> <a name="labelsInput" id="@cdktn/provider-docker.container.Container.property.labelsInput"></a>

```java
public IResolvable|java.util.List<ContainerLabels> getLabelsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>>

---

##### `logDriverInput`<sup>Optional</sup> <a name="logDriverInput" id="@cdktn/provider-docker.container.Container.property.logDriverInput"></a>

```java
public java.lang.String getLogDriverInput();
```

- *Type:* java.lang.String

---

##### `logOptsInput`<sup>Optional</sup> <a name="logOptsInput" id="@cdktn/provider-docker.container.Container.property.logOptsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLogOptsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `logsInput`<sup>Optional</sup> <a name="logsInput" id="@cdktn/provider-docker.container.Container.property.logsInput"></a>

```java
public java.lang.Boolean|IResolvable getLogsInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `maxRetryCountInput`<sup>Optional</sup> <a name="maxRetryCountInput" id="@cdktn/provider-docker.container.Container.property.maxRetryCountInput"></a>

```java
public java.lang.Number getMaxRetryCountInput();
```

- *Type:* java.lang.Number

---

##### `memoryInput`<sup>Optional</sup> <a name="memoryInput" id="@cdktn/provider-docker.container.Container.property.memoryInput"></a>

```java
public java.lang.Number getMemoryInput();
```

- *Type:* java.lang.Number

---

##### `memoryReservationInput`<sup>Optional</sup> <a name="memoryReservationInput" id="@cdktn/provider-docker.container.Container.property.memoryReservationInput"></a>

```java
public java.lang.Number getMemoryReservationInput();
```

- *Type:* java.lang.Number

---

##### `memorySwapInput`<sup>Optional</sup> <a name="memorySwapInput" id="@cdktn/provider-docker.container.Container.property.memorySwapInput"></a>

```java
public java.lang.Number getMemorySwapInput();
```

- *Type:* java.lang.Number

---

##### `mountsInput`<sup>Optional</sup> <a name="mountsInput" id="@cdktn/provider-docker.container.Container.property.mountsInput"></a>

```java
public IResolvable|java.util.List<ContainerMounts> getMountsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>>

---

##### `mustRunInput`<sup>Optional</sup> <a name="mustRunInput" id="@cdktn/provider-docker.container.Container.property.mustRunInput"></a>

```java
public java.lang.Boolean|IResolvable getMustRunInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.container.Container.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `networkModeInput`<sup>Optional</sup> <a name="networkModeInput" id="@cdktn/provider-docker.container.Container.property.networkModeInput"></a>

```java
public java.lang.String getNetworkModeInput();
```

- *Type:* java.lang.String

---

##### `networksAdvancedInput`<sup>Optional</sup> <a name="networksAdvancedInput" id="@cdktn/provider-docker.container.Container.property.networksAdvancedInput"></a>

```java
public IResolvable|java.util.List<ContainerNetworksAdvanced> getNetworksAdvancedInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>>

---

##### `pidModeInput`<sup>Optional</sup> <a name="pidModeInput" id="@cdktn/provider-docker.container.Container.property.pidModeInput"></a>

```java
public java.lang.String getPidModeInput();
```

- *Type:* java.lang.String

---

##### `platformInput`<sup>Optional</sup> <a name="platformInput" id="@cdktn/provider-docker.container.Container.property.platformInput"></a>

```java
public java.lang.String getPlatformInput();
```

- *Type:* java.lang.String

---

##### `portsInput`<sup>Optional</sup> <a name="portsInput" id="@cdktn/provider-docker.container.Container.property.portsInput"></a>

```java
public IResolvable|java.util.List<ContainerPorts> getPortsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>>

---

##### `privilegedInput`<sup>Optional</sup> <a name="privilegedInput" id="@cdktn/provider-docker.container.Container.property.privilegedInput"></a>

```java
public java.lang.Boolean|IResolvable getPrivilegedInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `publishAllPortsInput`<sup>Optional</sup> <a name="publishAllPortsInput" id="@cdktn/provider-docker.container.Container.property.publishAllPortsInput"></a>

```java
public java.lang.Boolean|IResolvable getPublishAllPortsInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `readOnlyInput`<sup>Optional</sup> <a name="readOnlyInput" id="@cdktn/provider-docker.container.Container.property.readOnlyInput"></a>

```java
public java.lang.Boolean|IResolvable getReadOnlyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `removeVolumesInput`<sup>Optional</sup> <a name="removeVolumesInput" id="@cdktn/provider-docker.container.Container.property.removeVolumesInput"></a>

```java
public java.lang.Boolean|IResolvable getRemoveVolumesInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `restartInput`<sup>Optional</sup> <a name="restartInput" id="@cdktn/provider-docker.container.Container.property.restartInput"></a>

```java
public java.lang.String getRestartInput();
```

- *Type:* java.lang.String

---

##### `rmInput`<sup>Optional</sup> <a name="rmInput" id="@cdktn/provider-docker.container.Container.property.rmInput"></a>

```java
public java.lang.Boolean|IResolvable getRmInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `runtimeInput`<sup>Optional</sup> <a name="runtimeInput" id="@cdktn/provider-docker.container.Container.property.runtimeInput"></a>

```java
public java.lang.String getRuntimeInput();
```

- *Type:* java.lang.String

---

##### `securityOptsInput`<sup>Optional</sup> <a name="securityOptsInput" id="@cdktn/provider-docker.container.Container.property.securityOptsInput"></a>

```java
public java.util.List<java.lang.String> getSecurityOptsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `shmSizeInput`<sup>Optional</sup> <a name="shmSizeInput" id="@cdktn/provider-docker.container.Container.property.shmSizeInput"></a>

```java
public java.lang.Number getShmSizeInput();
```

- *Type:* java.lang.Number

---

##### `startInput`<sup>Optional</sup> <a name="startInput" id="@cdktn/provider-docker.container.Container.property.startInput"></a>

```java
public java.lang.Boolean|IResolvable getStartInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `stdinOpenInput`<sup>Optional</sup> <a name="stdinOpenInput" id="@cdktn/provider-docker.container.Container.property.stdinOpenInput"></a>

```java
public java.lang.Boolean|IResolvable getStdinOpenInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `stopSignalInput`<sup>Optional</sup> <a name="stopSignalInput" id="@cdktn/provider-docker.container.Container.property.stopSignalInput"></a>

```java
public java.lang.String getStopSignalInput();
```

- *Type:* java.lang.String

---

##### `stopTimeoutInput`<sup>Optional</sup> <a name="stopTimeoutInput" id="@cdktn/provider-docker.container.Container.property.stopTimeoutInput"></a>

```java
public java.lang.Number getStopTimeoutInput();
```

- *Type:* java.lang.Number

---

##### `storageOptsInput`<sup>Optional</sup> <a name="storageOptsInput" id="@cdktn/provider-docker.container.Container.property.storageOptsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStorageOptsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `sysctlsInput`<sup>Optional</sup> <a name="sysctlsInput" id="@cdktn/provider-docker.container.Container.property.sysctlsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getSysctlsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `timeoutsInput`<sup>Optional</sup> <a name="timeoutsInput" id="@cdktn/provider-docker.container.Container.property.timeoutsInput"></a>

```java
public IResolvable|ContainerTimeouts getTimeoutsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

---

##### `tmpfsInput`<sup>Optional</sup> <a name="tmpfsInput" id="@cdktn/provider-docker.container.Container.property.tmpfsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getTmpfsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `ttyInput`<sup>Optional</sup> <a name="ttyInput" id="@cdktn/provider-docker.container.Container.property.ttyInput"></a>

```java
public java.lang.Boolean|IResolvable getTtyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `ulimitInput`<sup>Optional</sup> <a name="ulimitInput" id="@cdktn/provider-docker.container.Container.property.ulimitInput"></a>

```java
public IResolvable|java.util.List<ContainerUlimit> getUlimitInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>>

---

##### `uploadInput`<sup>Optional</sup> <a name="uploadInput" id="@cdktn/provider-docker.container.Container.property.uploadInput"></a>

```java
public IResolvable|java.util.List<ContainerUpload> getUploadInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>>

---

##### `userInput`<sup>Optional</sup> <a name="userInput" id="@cdktn/provider-docker.container.Container.property.userInput"></a>

```java
public java.lang.String getUserInput();
```

- *Type:* java.lang.String

---

##### `usernsModeInput`<sup>Optional</sup> <a name="usernsModeInput" id="@cdktn/provider-docker.container.Container.property.usernsModeInput"></a>

```java
public java.lang.String getUsernsModeInput();
```

- *Type:* java.lang.String

---

##### `volumesInput`<sup>Optional</sup> <a name="volumesInput" id="@cdktn/provider-docker.container.Container.property.volumesInput"></a>

```java
public IResolvable|java.util.List<ContainerVolumes> getVolumesInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>>

---

##### `waitInput`<sup>Optional</sup> <a name="waitInput" id="@cdktn/provider-docker.container.Container.property.waitInput"></a>

```java
public java.lang.Boolean|IResolvable getWaitInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `waitTimeoutInput`<sup>Optional</sup> <a name="waitTimeoutInput" id="@cdktn/provider-docker.container.Container.property.waitTimeoutInput"></a>

```java
public java.lang.Number getWaitTimeoutInput();
```

- *Type:* java.lang.Number

---

##### `workingDirInput`<sup>Optional</sup> <a name="workingDirInput" id="@cdktn/provider-docker.container.Container.property.workingDirInput"></a>

```java
public java.lang.String getWorkingDirInput();
```

- *Type:* java.lang.String

---

##### `attach`<sup>Required</sup> <a name="attach" id="@cdktn/provider-docker.container.Container.property.attach"></a>

```java
public java.lang.Boolean|IResolvable getAttach();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `cgroupnsMode`<sup>Required</sup> <a name="cgroupnsMode" id="@cdktn/provider-docker.container.Container.property.cgroupnsMode"></a>

```java
public java.lang.String getCgroupnsMode();
```

- *Type:* java.lang.String

---

##### `cgroupParent`<sup>Required</sup> <a name="cgroupParent" id="@cdktn/provider-docker.container.Container.property.cgroupParent"></a>

```java
public java.lang.String getCgroupParent();
```

- *Type:* java.lang.String

---

##### `command`<sup>Required</sup> <a name="command" id="@cdktn/provider-docker.container.Container.property.command"></a>

```java
public java.util.List<java.lang.String> getCommand();
```

- *Type:* java.util.List<java.lang.String>

---

##### `containerReadRefreshTimeoutMilliseconds`<sup>Required</sup> <a name="containerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.Container.property.containerReadRefreshTimeoutMilliseconds"></a>

```java
public java.lang.Number getContainerReadRefreshTimeoutMilliseconds();
```

- *Type:* java.lang.Number

---

##### `cpuPeriod`<sup>Required</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.container.Container.property.cpuPeriod"></a>

```java
public java.lang.Number getCpuPeriod();
```

- *Type:* java.lang.Number

---

##### `cpuQuota`<sup>Required</sup> <a name="cpuQuota" id="@cdktn/provider-docker.container.Container.property.cpuQuota"></a>

```java
public java.lang.Number getCpuQuota();
```

- *Type:* java.lang.Number

---

##### `cpus`<sup>Required</sup> <a name="cpus" id="@cdktn/provider-docker.container.Container.property.cpus"></a>

```java
public java.lang.String getCpus();
```

- *Type:* java.lang.String

---

##### `cpuSet`<sup>Required</sup> <a name="cpuSet" id="@cdktn/provider-docker.container.Container.property.cpuSet"></a>

```java
public java.lang.String getCpuSet();
```

- *Type:* java.lang.String

---

##### `cpuShares`<sup>Required</sup> <a name="cpuShares" id="@cdktn/provider-docker.container.Container.property.cpuShares"></a>

```java
public java.lang.Number getCpuShares();
```

- *Type:* java.lang.Number

---

##### `destroyGraceSeconds`<sup>Required</sup> <a name="destroyGraceSeconds" id="@cdktn/provider-docker.container.Container.property.destroyGraceSeconds"></a>

```java
public java.lang.Number getDestroyGraceSeconds();
```

- *Type:* java.lang.Number

---

##### `deviceCgroupRules`<sup>Required</sup> <a name="deviceCgroupRules" id="@cdktn/provider-docker.container.Container.property.deviceCgroupRules"></a>

```java
public java.util.List<java.lang.String> getDeviceCgroupRules();
```

- *Type:* java.util.List<java.lang.String>

---

##### `dns`<sup>Required</sup> <a name="dns" id="@cdktn/provider-docker.container.Container.property.dns"></a>

```java
public java.util.List<java.lang.String> getDns();
```

- *Type:* java.util.List<java.lang.String>

---

##### `dnsOpts`<sup>Required</sup> <a name="dnsOpts" id="@cdktn/provider-docker.container.Container.property.dnsOpts"></a>

```java
public java.util.List<java.lang.String> getDnsOpts();
```

- *Type:* java.util.List<java.lang.String>

---

##### `dnsSearch`<sup>Required</sup> <a name="dnsSearch" id="@cdktn/provider-docker.container.Container.property.dnsSearch"></a>

```java
public java.util.List<java.lang.String> getDnsSearch();
```

- *Type:* java.util.List<java.lang.String>

---

##### `domainname`<sup>Required</sup> <a name="domainname" id="@cdktn/provider-docker.container.Container.property.domainname"></a>

```java
public java.lang.String getDomainname();
```

- *Type:* java.lang.String

---

##### `entrypoint`<sup>Required</sup> <a name="entrypoint" id="@cdktn/provider-docker.container.Container.property.entrypoint"></a>

```java
public java.util.List<java.lang.String> getEntrypoint();
```

- *Type:* java.util.List<java.lang.String>

---

##### `env`<sup>Required</sup> <a name="env" id="@cdktn/provider-docker.container.Container.property.env"></a>

```java
public java.util.List<java.lang.String> getEnv();
```

- *Type:* java.util.List<java.lang.String>

---

##### `gpus`<sup>Required</sup> <a name="gpus" id="@cdktn/provider-docker.container.Container.property.gpus"></a>

```java
public java.lang.String getGpus();
```

- *Type:* java.lang.String

---

##### `groupAdd`<sup>Required</sup> <a name="groupAdd" id="@cdktn/provider-docker.container.Container.property.groupAdd"></a>

```java
public java.util.List<java.lang.String> getGroupAdd();
```

- *Type:* java.util.List<java.lang.String>

---

##### `hostname`<sup>Required</sup> <a name="hostname" id="@cdktn/provider-docker.container.Container.property.hostname"></a>

```java
public java.lang.String getHostname();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-docker.container.Container.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `image`<sup>Required</sup> <a name="image" id="@cdktn/provider-docker.container.Container.property.image"></a>

```java
public java.lang.String getImage();
```

- *Type:* java.lang.String

---

##### `init`<sup>Required</sup> <a name="init" id="@cdktn/provider-docker.container.Container.property.init"></a>

```java
public java.lang.Boolean|IResolvable getInit();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `ipcMode`<sup>Required</sup> <a name="ipcMode" id="@cdktn/provider-docker.container.Container.property.ipcMode"></a>

```java
public java.lang.String getIpcMode();
```

- *Type:* java.lang.String

---

##### `logDriver`<sup>Required</sup> <a name="logDriver" id="@cdktn/provider-docker.container.Container.property.logDriver"></a>

```java
public java.lang.String getLogDriver();
```

- *Type:* java.lang.String

---

##### `logOpts`<sup>Required</sup> <a name="logOpts" id="@cdktn/provider-docker.container.Container.property.logOpts"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLogOpts();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `logs`<sup>Required</sup> <a name="logs" id="@cdktn/provider-docker.container.Container.property.logs"></a>

```java
public java.lang.Boolean|IResolvable getLogs();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `maxRetryCount`<sup>Required</sup> <a name="maxRetryCount" id="@cdktn/provider-docker.container.Container.property.maxRetryCount"></a>

```java
public java.lang.Number getMaxRetryCount();
```

- *Type:* java.lang.Number

---

##### `memory`<sup>Required</sup> <a name="memory" id="@cdktn/provider-docker.container.Container.property.memory"></a>

```java
public java.lang.Number getMemory();
```

- *Type:* java.lang.Number

---

##### `memoryReservation`<sup>Required</sup> <a name="memoryReservation" id="@cdktn/provider-docker.container.Container.property.memoryReservation"></a>

```java
public java.lang.Number getMemoryReservation();
```

- *Type:* java.lang.Number

---

##### `memorySwap`<sup>Required</sup> <a name="memorySwap" id="@cdktn/provider-docker.container.Container.property.memorySwap"></a>

```java
public java.lang.Number getMemorySwap();
```

- *Type:* java.lang.Number

---

##### `mustRun`<sup>Required</sup> <a name="mustRun" id="@cdktn/provider-docker.container.Container.property.mustRun"></a>

```java
public java.lang.Boolean|IResolvable getMustRun();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.Container.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `networkMode`<sup>Required</sup> <a name="networkMode" id="@cdktn/provider-docker.container.Container.property.networkMode"></a>

```java
public java.lang.String getNetworkMode();
```

- *Type:* java.lang.String

---

##### `pidMode`<sup>Required</sup> <a name="pidMode" id="@cdktn/provider-docker.container.Container.property.pidMode"></a>

```java
public java.lang.String getPidMode();
```

- *Type:* java.lang.String

---

##### `platform`<sup>Required</sup> <a name="platform" id="@cdktn/provider-docker.container.Container.property.platform"></a>

```java
public java.lang.String getPlatform();
```

- *Type:* java.lang.String

---

##### `privileged`<sup>Required</sup> <a name="privileged" id="@cdktn/provider-docker.container.Container.property.privileged"></a>

```java
public java.lang.Boolean|IResolvable getPrivileged();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `publishAllPorts`<sup>Required</sup> <a name="publishAllPorts" id="@cdktn/provider-docker.container.Container.property.publishAllPorts"></a>

```java
public java.lang.Boolean|IResolvable getPublishAllPorts();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `readOnly`<sup>Required</sup> <a name="readOnly" id="@cdktn/provider-docker.container.Container.property.readOnly"></a>

```java
public java.lang.Boolean|IResolvable getReadOnly();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `removeVolumes`<sup>Required</sup> <a name="removeVolumes" id="@cdktn/provider-docker.container.Container.property.removeVolumes"></a>

```java
public java.lang.Boolean|IResolvable getRemoveVolumes();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `restart`<sup>Required</sup> <a name="restart" id="@cdktn/provider-docker.container.Container.property.restart"></a>

```java
public java.lang.String getRestart();
```

- *Type:* java.lang.String

---

##### `rm`<sup>Required</sup> <a name="rm" id="@cdktn/provider-docker.container.Container.property.rm"></a>

```java
public java.lang.Boolean|IResolvable getRm();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `runtime`<sup>Required</sup> <a name="runtime" id="@cdktn/provider-docker.container.Container.property.runtime"></a>

```java
public java.lang.String getRuntime();
```

- *Type:* java.lang.String

---

##### `securityOpts`<sup>Required</sup> <a name="securityOpts" id="@cdktn/provider-docker.container.Container.property.securityOpts"></a>

```java
public java.util.List<java.lang.String> getSecurityOpts();
```

- *Type:* java.util.List<java.lang.String>

---

##### `shmSize`<sup>Required</sup> <a name="shmSize" id="@cdktn/provider-docker.container.Container.property.shmSize"></a>

```java
public java.lang.Number getShmSize();
```

- *Type:* java.lang.Number

---

##### `start`<sup>Required</sup> <a name="start" id="@cdktn/provider-docker.container.Container.property.start"></a>

```java
public java.lang.Boolean|IResolvable getStart();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `stdinOpen`<sup>Required</sup> <a name="stdinOpen" id="@cdktn/provider-docker.container.Container.property.stdinOpen"></a>

```java
public java.lang.Boolean|IResolvable getStdinOpen();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `stopSignal`<sup>Required</sup> <a name="stopSignal" id="@cdktn/provider-docker.container.Container.property.stopSignal"></a>

```java
public java.lang.String getStopSignal();
```

- *Type:* java.lang.String

---

##### `stopTimeout`<sup>Required</sup> <a name="stopTimeout" id="@cdktn/provider-docker.container.Container.property.stopTimeout"></a>

```java
public java.lang.Number getStopTimeout();
```

- *Type:* java.lang.Number

---

##### `storageOpts`<sup>Required</sup> <a name="storageOpts" id="@cdktn/provider-docker.container.Container.property.storageOpts"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStorageOpts();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `sysctls`<sup>Required</sup> <a name="sysctls" id="@cdktn/provider-docker.container.Container.property.sysctls"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getSysctls();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `tmpfs`<sup>Required</sup> <a name="tmpfs" id="@cdktn/provider-docker.container.Container.property.tmpfs"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getTmpfs();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `tty`<sup>Required</sup> <a name="tty" id="@cdktn/provider-docker.container.Container.property.tty"></a>

```java
public java.lang.Boolean|IResolvable getTty();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `user`<sup>Required</sup> <a name="user" id="@cdktn/provider-docker.container.Container.property.user"></a>

```java
public java.lang.String getUser();
```

- *Type:* java.lang.String

---

##### `usernsMode`<sup>Required</sup> <a name="usernsMode" id="@cdktn/provider-docker.container.Container.property.usernsMode"></a>

```java
public java.lang.String getUsernsMode();
```

- *Type:* java.lang.String

---

##### `wait`<sup>Required</sup> <a name="wait" id="@cdktn/provider-docker.container.Container.property.wait"></a>

```java
public java.lang.Boolean|IResolvable getWait();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `waitTimeout`<sup>Required</sup> <a name="waitTimeout" id="@cdktn/provider-docker.container.Container.property.waitTimeout"></a>

```java
public java.lang.Number getWaitTimeout();
```

- *Type:* java.lang.Number

---

##### `workingDir`<sup>Required</sup> <a name="workingDir" id="@cdktn/provider-docker.container.Container.property.workingDir"></a>

```java
public java.lang.String getWorkingDir();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.Container.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-docker.container.Container.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### ContainerCapabilities <a name="ContainerCapabilities" id="@cdktn/provider-docker.container.ContainerCapabilities"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerCapabilities.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerCapabilities;

ContainerCapabilities.builder()
//  .add(java.util.List<java.lang.String>)
//  .drop(java.util.List<java.lang.String>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities.property.add">add</a></code> | <code>java.util.List<java.lang.String></code> | List of linux capabilities to add. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities.property.drop">drop</a></code> | <code>java.util.List<java.lang.String></code> | List of linux capabilities to drop. |

---

##### `add`<sup>Optional</sup> <a name="add" id="@cdktn/provider-docker.container.ContainerCapabilities.property.add"></a>

```java
public java.util.List<java.lang.String> getAdd();
```

- *Type:* java.util.List<java.lang.String>

List of linux capabilities to add.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#add Container#add}

---

##### `drop`<sup>Optional</sup> <a name="drop" id="@cdktn/provider-docker.container.ContainerCapabilities.property.drop"></a>

```java
public java.util.List<java.lang.String> getDrop();
```

- *Type:* java.util.List<java.lang.String>

List of linux capabilities to drop.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#drop Container#drop}

---

### ContainerConfig <a name="ContainerConfig" id="@cdktn/provider-docker.container.ContainerConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerConfig.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerConfig;

ContainerConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .image(java.lang.String)
    .name(java.lang.String)
//  .attach(java.lang.Boolean|IResolvable)
//  .capabilities(ContainerCapabilities)
//  .cgroupnsMode(java.lang.String)
//  .cgroupParent(java.lang.String)
//  .command(java.util.List<java.lang.String>)
//  .containerReadRefreshTimeoutMilliseconds(java.lang.Number)
//  .cpuPeriod(java.lang.Number)
//  .cpuQuota(java.lang.Number)
//  .cpus(java.lang.String)
//  .cpuSet(java.lang.String)
//  .cpuShares(java.lang.Number)
//  .destroyGraceSeconds(java.lang.Number)
//  .deviceCgroupRules(java.util.List<java.lang.String>)
//  .deviceReadBps(IResolvable|java.util.List<ContainerDeviceReadBps>)
//  .deviceReadIops(IResolvable|java.util.List<ContainerDeviceReadIops>)
//  .deviceRequests(IResolvable|java.util.List<ContainerDeviceRequests>)
//  .devices(IResolvable|java.util.List<ContainerDevices>)
//  .deviceWriteBps(IResolvable|java.util.List<ContainerDeviceWriteBps>)
//  .deviceWriteIops(IResolvable|java.util.List<ContainerDeviceWriteIops>)
//  .dns(java.util.List<java.lang.String>)
//  .dnsOpts(java.util.List<java.lang.String>)
//  .dnsSearch(java.util.List<java.lang.String>)
//  .domainname(java.lang.String)
//  .entrypoint(java.util.List<java.lang.String>)
//  .env(java.util.List<java.lang.String>)
//  .gpus(java.lang.String)
//  .groupAdd(java.util.List<java.lang.String>)
//  .healthcheck(ContainerHealthcheck)
//  .host(IResolvable|java.util.List<ContainerHost>)
//  .hostname(java.lang.String)
//  .id(java.lang.String)
//  .init(java.lang.Boolean|IResolvable)
//  .ipcMode(java.lang.String)
//  .labels(IResolvable|java.util.List<ContainerLabels>)
//  .logDriver(java.lang.String)
//  .logOpts(java.util.Map<java.lang.String, java.lang.String>)
//  .logs(java.lang.Boolean|IResolvable)
//  .maxRetryCount(java.lang.Number)
//  .memory(java.lang.Number)
//  .memoryReservation(java.lang.Number)
//  .memorySwap(java.lang.Number)
//  .mounts(IResolvable|java.util.List<ContainerMounts>)
//  .mustRun(java.lang.Boolean|IResolvable)
//  .networkMode(java.lang.String)
//  .networksAdvanced(IResolvable|java.util.List<ContainerNetworksAdvanced>)
//  .pidMode(java.lang.String)
//  .platform(java.lang.String)
//  .ports(IResolvable|java.util.List<ContainerPorts>)
//  .privileged(java.lang.Boolean|IResolvable)
//  .publishAllPorts(java.lang.Boolean|IResolvable)
//  .readOnly(java.lang.Boolean|IResolvable)
//  .removeVolumes(java.lang.Boolean|IResolvable)
//  .restart(java.lang.String)
//  .rm(java.lang.Boolean|IResolvable)
//  .runtime(java.lang.String)
//  .securityOpts(java.util.List<java.lang.String>)
//  .shmSize(java.lang.Number)
//  .start(java.lang.Boolean|IResolvable)
//  .stdinOpen(java.lang.Boolean|IResolvable)
//  .stopSignal(java.lang.String)
//  .stopTimeout(java.lang.Number)
//  .storageOpts(java.util.Map<java.lang.String, java.lang.String>)
//  .sysctls(java.util.Map<java.lang.String, java.lang.String>)
//  .timeouts(ContainerTimeouts)
//  .tmpfs(java.util.Map<java.lang.String, java.lang.String>)
//  .tty(java.lang.Boolean|IResolvable)
//  .ulimit(IResolvable|java.util.List<ContainerUlimit>)
//  .upload(IResolvable|java.util.List<ContainerUpload>)
//  .user(java.lang.String)
//  .usernsMode(java.lang.String)
//  .volumes(IResolvable|java.util.List<ContainerVolumes>)
//  .wait(java.lang.Boolean|IResolvable)
//  .waitTimeout(java.lang.Number)
//  .workingDir(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.image">image</a></code> | <code>java.lang.String</code> | The ID of the image to back this container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.name">name</a></code> | <code>java.lang.String</code> | The name of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.attach">attach</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true` attach to the container after its creation and waits the end of its execution. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.capabilities">capabilities</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | capabilities block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cgroupnsMode">cgroupnsMode</a></code> | <code>java.lang.String</code> | Cgroup namespace mode to use for the container. Possible values are: `private`, `host`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cgroupParent">cgroupParent</a></code> | <code>java.lang.String</code> | Optional parent cgroup for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.command">command</a></code> | <code>java.util.List<java.lang.String></code> | The command to use to start the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.containerReadRefreshTimeoutMilliseconds">containerReadRefreshTimeoutMilliseconds</a></code> | <code>java.lang.Number</code> | The total number of milliseconds to wait for the container to reach status 'running'. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuPeriod">cpuPeriod</a></code> | <code>java.lang.Number</code> | Specify the CPU CFS scheduler period (in microseconds), which is used alongside `cpu-quota`. Is ignored if `cpus` is set. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuQuota">cpuQuota</a></code> | <code>java.lang.Number</code> | Impose a CPU CFS quota on the container (in microseconds). |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpus">cpus</a></code> | <code>java.lang.String</code> | Specify how much of the available CPU resources a container can use. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuSet">cpuSet</a></code> | <code>java.lang.String</code> | A comma-separated list or hyphen-separated range of CPUs a container can use, e.g. `0-1`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.cpuShares">cpuShares</a></code> | <code>java.lang.Number</code> | CPU shares (relative weight) for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.destroyGraceSeconds">destroyGraceSeconds</a></code> | <code>java.lang.Number</code> | If defined will attempt to stop the container before destroying. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceCgroupRules">deviceCgroupRules</a></code> | <code>java.util.List<java.lang.String></code> | Cgroup rules to allow access to classes of devices without binding specific device nodes. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceReadBps">deviceReadBps</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>></code> | device_read_bps block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceReadIops">deviceReadIops</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>></code> | device_read_iops block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceRequests">deviceRequests</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>></code> | device_requests block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.devices">devices</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>></code> | devices block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteBps">deviceWriteBps</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>></code> | device_write_bps block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteIops">deviceWriteIops</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>></code> | device_write_iops block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dns">dns</a></code> | <code>java.util.List<java.lang.String></code> | DNS servers to use. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dnsOpts">dnsOpts</a></code> | <code>java.util.List<java.lang.String></code> | DNS options used by the DNS provider(s), see `resolv.conf` documentation for valid list of options. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.dnsSearch">dnsSearch</a></code> | <code>java.util.List<java.lang.String></code> | DNS search domains that are used when bare unqualified hostnames are used inside of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.domainname">domainname</a></code> | <code>java.lang.String</code> | Domain name of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.entrypoint">entrypoint</a></code> | <code>java.util.List<java.lang.String></code> | The command to use as the Entrypoint for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.env">env</a></code> | <code>java.util.List<java.lang.String></code> | Environment variables to set in the form of `KEY=VALUE`, e.g. `DEBUG=0`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.gpus">gpus</a></code> | <code>java.lang.String</code> | GPU devices to add to the container. Supported values are `all` or `device=<id[,id...]>`, for example `device=0,2` or `device=GPU-3a23c669-1f69-c64e-cf85-44e9b07e7a2a`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.groupAdd">groupAdd</a></code> | <code>java.util.List<java.lang.String></code> | Additional groups for the container user. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.healthcheck">healthcheck</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | healthcheck block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.host">host</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>></code> | host block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.hostname">hostname</a></code> | <code>java.lang.String</code> | Hostname of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#id Container#id}. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.init">init</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Configured whether an init process should be injected for this container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.ipcMode">ipcMode</a></code> | <code>java.lang.String</code> | IPC sharing mode for the container. Possible values are: `none`, `private`, `shareable`, `container:<name\|id>` or `host`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.labels">labels</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>></code> | labels block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.logDriver">logDriver</a></code> | <code>java.lang.String</code> | The logging driver to use for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.logOpts">logOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Key/value pairs to use as options for the logging driver. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.logs">logs</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Save the container logs (`attach` must be enabled). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.maxRetryCount">maxRetryCount</a></code> | <code>java.lang.Number</code> | The maximum amount of times to an attempt a restart when `restart` is set to 'on-failure'. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.memory">memory</a></code> | <code>java.lang.Number</code> | The memory limit for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.memoryReservation">memoryReservation</a></code> | <code>java.lang.Number</code> | The memory-resveration for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.memorySwap">memorySwap</a></code> | <code>java.lang.Number</code> | The total memory limit (memory + swap) for the container in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.mounts">mounts</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>></code> | mounts block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.mustRun">mustRun</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the Docker container will be kept running. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.networkMode">networkMode</a></code> | <code>java.lang.String</code> | Network mode of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.networksAdvanced">networksAdvanced</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>></code> | networks_advanced block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.pidMode">pidMode</a></code> | <code>java.lang.String</code> | The PID (Process) Namespace mode for the container. Either `container:<name\|id>` or `host`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.platform">platform</a></code> | <code>java.lang.String</code> | Platform in the format `os[/arch[/variant]]` used for image lookup and container runtime, for example `linux/amd64`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.ports">ports</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>></code> | ports block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.privileged">privileged</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the container runs in privileged mode. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.publishAllPorts">publishAllPorts</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Publish all ports of the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the container will be started as readonly. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.removeVolumes">removeVolumes</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, it will remove anonymous volumes associated with the container. Defaults to `true`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.restart">restart</a></code> | <code>java.lang.String</code> | The restart policy for the container. Must be one of 'no', 'on-failure', 'always', 'unless-stopped'. Defaults to `no`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.rm">rm</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the container will be automatically removed when it exits. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.runtime">runtime</a></code> | <code>java.lang.String</code> | Runtime to use for the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.securityOpts">securityOpts</a></code> | <code>java.util.List<java.lang.String></code> | List of string values to customize labels for MLS systems, such as SELinux. See https://docs.docker.com/engine/reference/run/#security-configuration. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.shmSize">shmSize</a></code> | <code>java.lang.Number</code> | Size of `/dev/shm` in MBs. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.start">start</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the Docker container will be started after creation. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.stdinOpen">stdinOpen</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, keep STDIN open even if not attached (`docker run -i`). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.stopSignal">stopSignal</a></code> | <code>java.lang.String</code> | Signal to stop a container (default `SIGTERM`). |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.stopTimeout">stopTimeout</a></code> | <code>java.lang.Number</code> | Timeout (in seconds) to stop a container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.storageOpts">storageOpts</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Key/value pairs for the storage driver options, e.g. `size`: `120G`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.sysctls">sysctls</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of kernel parameters (sysctls) to set in the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.timeouts">timeouts</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | timeouts block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.tmpfs">tmpfs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of container directories which should be replaced by `tmpfs mounts`, and their corresponding mount options. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.tty">tty</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, allocate a pseudo-tty (`docker run -t`). Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.ulimit">ulimit</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>></code> | ulimit block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.upload">upload</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>></code> | upload block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.user">user</a></code> | <code>java.lang.String</code> | User used for run the first process. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.usernsMode">usernsMode</a></code> | <code>java.lang.String</code> | Sets the usernamespace mode for the container when usernamespace remapping option is enabled. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.volumes">volumes</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>></code> | volumes block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.wait">wait</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, then the Docker container is waited for being healthy state after creation. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.waitTimeout">waitTimeout</a></code> | <code>java.lang.Number</code> | The timeout in seconds to wait the container to be healthy after creation. Defaults to `60`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerConfig.property.workingDir">workingDir</a></code> | <code>java.lang.String</code> | The working directory for commands to run in. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-docker.container.ContainerConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.container.ContainerConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-docker.container.ContainerConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-docker.container.ContainerConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-docker.container.ContainerConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-docker.container.ContainerConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-docker.container.ContainerConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `image`<sup>Required</sup> <a name="image" id="@cdktn/provider-docker.container.ContainerConfig.property.image"></a>

```java
public java.lang.String getImage();
```

- *Type:* java.lang.String

The ID of the image to back this container.

The easiest way to get this value is to use the `image_id` attribute of the `docker_image` resource as is shown in the example.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#image Container#image}

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.ContainerConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The name of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#name Container#name}

---

##### `attach`<sup>Optional</sup> <a name="attach" id="@cdktn/provider-docker.container.ContainerConfig.property.attach"></a>

```java
public java.lang.Boolean|IResolvable getAttach();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true` attach to the container after its creation and waits the end of its execution. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#attach Container#attach}

---

##### `capabilities`<sup>Optional</sup> <a name="capabilities" id="@cdktn/provider-docker.container.ContainerConfig.property.capabilities"></a>

```java
public ContainerCapabilities getCapabilities();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

capabilities block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#capabilities Container#capabilities}

---

##### `cgroupnsMode`<sup>Optional</sup> <a name="cgroupnsMode" id="@cdktn/provider-docker.container.ContainerConfig.property.cgroupnsMode"></a>

```java
public java.lang.String getCgroupnsMode();
```

- *Type:* java.lang.String

Cgroup namespace mode to use for the container. Possible values are: `private`, `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cgroupns_mode Container#cgroupns_mode}

---

##### `cgroupParent`<sup>Optional</sup> <a name="cgroupParent" id="@cdktn/provider-docker.container.ContainerConfig.property.cgroupParent"></a>

```java
public java.lang.String getCgroupParent();
```

- *Type:* java.lang.String

Optional parent cgroup for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cgroup_parent Container#cgroup_parent}

---

##### `command`<sup>Optional</sup> <a name="command" id="@cdktn/provider-docker.container.ContainerConfig.property.command"></a>

```java
public java.util.List<java.lang.String> getCommand();
```

- *Type:* java.util.List<java.lang.String>

The command to use to start the container.

For example, to run `/usr/bin/myprogram -f baz.conf` set the command to be `["/usr/bin/myprogram","-f","baz.conf"]`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#command Container#command}

---

##### `containerReadRefreshTimeoutMilliseconds`<sup>Optional</sup> <a name="containerReadRefreshTimeoutMilliseconds" id="@cdktn/provider-docker.container.ContainerConfig.property.containerReadRefreshTimeoutMilliseconds"></a>

```java
public java.lang.Number getContainerReadRefreshTimeoutMilliseconds();
```

- *Type:* java.lang.Number

The total number of milliseconds to wait for the container to reach status 'running'.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#container_read_refresh_timeout_milliseconds Container#container_read_refresh_timeout_milliseconds}

---

##### `cpuPeriod`<sup>Optional</sup> <a name="cpuPeriod" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuPeriod"></a>

```java
public java.lang.Number getCpuPeriod();
```

- *Type:* java.lang.Number

Specify the CPU CFS scheduler period (in microseconds), which is used alongside `cpu-quota`. Is ignored if `cpus` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_period Container#cpu_period}

---

##### `cpuQuota`<sup>Optional</sup> <a name="cpuQuota" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuQuota"></a>

```java
public java.lang.Number getCpuQuota();
```

- *Type:* java.lang.Number

Impose a CPU CFS quota on the container (in microseconds).

The number of microseconds per `cpu-period` that the container is limited to before throttled. Is ignored if `cpus` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_quota Container#cpu_quota}

---

##### `cpus`<sup>Optional</sup> <a name="cpus" id="@cdktn/provider-docker.container.ContainerConfig.property.cpus"></a>

```java
public java.lang.String getCpus();
```

- *Type:* java.lang.String

Specify how much of the available CPU resources a container can use.

e.g a value of 1.5 means the container is guaranteed at most one and a half of the CPUs. Has precedence over `cpu_period` and `cpu_quota`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpus Container#cpus}

---

##### `cpuSet`<sup>Optional</sup> <a name="cpuSet" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuSet"></a>

```java
public java.lang.String getCpuSet();
```

- *Type:* java.lang.String

A comma-separated list or hyphen-separated range of CPUs a container can use, e.g. `0-1`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_set Container#cpu_set}

---

##### `cpuShares`<sup>Optional</sup> <a name="cpuShares" id="@cdktn/provider-docker.container.ContainerConfig.property.cpuShares"></a>

```java
public java.lang.Number getCpuShares();
```

- *Type:* java.lang.Number

CPU shares (relative weight) for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#cpu_shares Container#cpu_shares}

---

##### `destroyGraceSeconds`<sup>Optional</sup> <a name="destroyGraceSeconds" id="@cdktn/provider-docker.container.ContainerConfig.property.destroyGraceSeconds"></a>

```java
public java.lang.Number getDestroyGraceSeconds();
```

- *Type:* java.lang.Number

If defined will attempt to stop the container before destroying.

Container will be destroyed after `n` seconds or on successful stop.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#destroy_grace_seconds Container#destroy_grace_seconds}

---

##### `deviceCgroupRules`<sup>Optional</sup> <a name="deviceCgroupRules" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceCgroupRules"></a>

```java
public java.util.List<java.lang.String> getDeviceCgroupRules();
```

- *Type:* java.util.List<java.lang.String>

Cgroup rules to allow access to classes of devices without binding specific device nodes.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_cgroup_rules Container#device_cgroup_rules}

---

##### `deviceReadBps`<sup>Optional</sup> <a name="deviceReadBps" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceReadBps"></a>

```java
public IResolvable|java.util.List<ContainerDeviceReadBps> getDeviceReadBps();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>>

device_read_bps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_read_bps Container#device_read_bps}

---

##### `deviceReadIops`<sup>Optional</sup> <a name="deviceReadIops" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceReadIops"></a>

```java
public IResolvable|java.util.List<ContainerDeviceReadIops> getDeviceReadIops();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>>

device_read_iops block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_read_iops Container#device_read_iops}

---

##### `deviceRequests`<sup>Optional</sup> <a name="deviceRequests" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceRequests"></a>

```java
public IResolvable|java.util.List<ContainerDeviceRequests> getDeviceRequests();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>>

device_requests block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_requests Container#device_requests}

---

##### `devices`<sup>Optional</sup> <a name="devices" id="@cdktn/provider-docker.container.ContainerConfig.property.devices"></a>

```java
public IResolvable|java.util.List<ContainerDevices> getDevices();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>>

devices block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#devices Container#devices}

---

##### `deviceWriteBps`<sup>Optional</sup> <a name="deviceWriteBps" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteBps"></a>

```java
public IResolvable|java.util.List<ContainerDeviceWriteBps> getDeviceWriteBps();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>>

device_write_bps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_write_bps Container#device_write_bps}

---

##### `deviceWriteIops`<sup>Optional</sup> <a name="deviceWriteIops" id="@cdktn/provider-docker.container.ContainerConfig.property.deviceWriteIops"></a>

```java
public IResolvable|java.util.List<ContainerDeviceWriteIops> getDeviceWriteIops();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>>

device_write_iops block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_write_iops Container#device_write_iops}

---

##### `dns`<sup>Optional</sup> <a name="dns" id="@cdktn/provider-docker.container.ContainerConfig.property.dns"></a>

```java
public java.util.List<java.lang.String> getDns();
```

- *Type:* java.util.List<java.lang.String>

DNS servers to use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#dns Container#dns}

---

##### `dnsOpts`<sup>Optional</sup> <a name="dnsOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.dnsOpts"></a>

```java
public java.util.List<java.lang.String> getDnsOpts();
```

- *Type:* java.util.List<java.lang.String>

DNS options used by the DNS provider(s), see `resolv.conf` documentation for valid list of options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#dns_opts Container#dns_opts}

---

##### `dnsSearch`<sup>Optional</sup> <a name="dnsSearch" id="@cdktn/provider-docker.container.ContainerConfig.property.dnsSearch"></a>

```java
public java.util.List<java.lang.String> getDnsSearch();
```

- *Type:* java.util.List<java.lang.String>

DNS search domains that are used when bare unqualified hostnames are used inside of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#dns_search Container#dns_search}

---

##### `domainname`<sup>Optional</sup> <a name="domainname" id="@cdktn/provider-docker.container.ContainerConfig.property.domainname"></a>

```java
public java.lang.String getDomainname();
```

- *Type:* java.lang.String

Domain name of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#domainname Container#domainname}

---

##### `entrypoint`<sup>Optional</sup> <a name="entrypoint" id="@cdktn/provider-docker.container.ContainerConfig.property.entrypoint"></a>

```java
public java.util.List<java.lang.String> getEntrypoint();
```

- *Type:* java.util.List<java.lang.String>

The command to use as the Entrypoint for the container.

The Entrypoint allows you to configure a container to run as an executable. For example, to run `/usr/bin/myprogram` when starting a container, set the entrypoint to be `"/usr/bin/myprogram"]`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#entrypoint Container#entrypoint}

---

##### `env`<sup>Optional</sup> <a name="env" id="@cdktn/provider-docker.container.ContainerConfig.property.env"></a>

```java
public java.util.List<java.lang.String> getEnv();
```

- *Type:* java.util.List<java.lang.String>

Environment variables to set in the form of `KEY=VALUE`, e.g. `DEBUG=0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#env Container#env}

---

##### `gpus`<sup>Optional</sup> <a name="gpus" id="@cdktn/provider-docker.container.ContainerConfig.property.gpus"></a>

```java
public java.lang.String getGpus();
```

- *Type:* java.lang.String

GPU devices to add to the container. Supported values are `all` or `device=<id[,id...]>`, for example `device=0,2` or `device=GPU-3a23c669-1f69-c64e-cf85-44e9b07e7a2a`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#gpus Container#gpus}

---

##### `groupAdd`<sup>Optional</sup> <a name="groupAdd" id="@cdktn/provider-docker.container.ContainerConfig.property.groupAdd"></a>

```java
public java.util.List<java.lang.String> getGroupAdd();
```

- *Type:* java.util.List<java.lang.String>

Additional groups for the container user.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#group_add Container#group_add}

---

##### `healthcheck`<sup>Optional</sup> <a name="healthcheck" id="@cdktn/provider-docker.container.ContainerConfig.property.healthcheck"></a>

```java
public ContainerHealthcheck getHealthcheck();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

healthcheck block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#healthcheck Container#healthcheck}

---

##### `host`<sup>Optional</sup> <a name="host" id="@cdktn/provider-docker.container.ContainerConfig.property.host"></a>

```java
public IResolvable|java.util.List<ContainerHost> getHost();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>>

host block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#host Container#host}

---

##### `hostname`<sup>Optional</sup> <a name="hostname" id="@cdktn/provider-docker.container.ContainerConfig.property.hostname"></a>

```java
public java.lang.String getHostname();
```

- *Type:* java.lang.String

Hostname of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#hostname Container#hostname}

---

##### `id`<sup>Optional</sup> <a name="id" id="@cdktn/provider-docker.container.ContainerConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#id Container#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `init`<sup>Optional</sup> <a name="init" id="@cdktn/provider-docker.container.ContainerConfig.property.init"></a>

```java
public java.lang.Boolean|IResolvable getInit();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Configured whether an init process should be injected for this container.

If unset this will default to the `dockerd` defaults.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#init Container#init}

---

##### `ipcMode`<sup>Optional</sup> <a name="ipcMode" id="@cdktn/provider-docker.container.ContainerConfig.property.ipcMode"></a>

```java
public java.lang.String getIpcMode();
```

- *Type:* java.lang.String

IPC sharing mode for the container. Possible values are: `none`, `private`, `shareable`, `container:<name|id>` or `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ipc_mode Container#ipc_mode}

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.container.ContainerConfig.property.labels"></a>

```java
public IResolvable|java.util.List<ContainerLabels> getLabels();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>>

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#labels Container#labels}

---

##### `logDriver`<sup>Optional</sup> <a name="logDriver" id="@cdktn/provider-docker.container.ContainerConfig.property.logDriver"></a>

```java
public java.lang.String getLogDriver();
```

- *Type:* java.lang.String

The logging driver to use for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#log_driver Container#log_driver}

---

##### `logOpts`<sup>Optional</sup> <a name="logOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.logOpts"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getLogOpts();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Key/value pairs to use as options for the logging driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#log_opts Container#log_opts}

---

##### `logs`<sup>Optional</sup> <a name="logs" id="@cdktn/provider-docker.container.ContainerConfig.property.logs"></a>

```java
public java.lang.Boolean|IResolvable getLogs();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Save the container logs (`attach` must be enabled). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#logs Container#logs}

---

##### `maxRetryCount`<sup>Optional</sup> <a name="maxRetryCount" id="@cdktn/provider-docker.container.ContainerConfig.property.maxRetryCount"></a>

```java
public java.lang.Number getMaxRetryCount();
```

- *Type:* java.lang.Number

The maximum amount of times to an attempt a restart when `restart` is set to 'on-failure'.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#max_retry_count Container#max_retry_count}

---

##### `memory`<sup>Optional</sup> <a name="memory" id="@cdktn/provider-docker.container.ContainerConfig.property.memory"></a>

```java
public java.lang.Number getMemory();
```

- *Type:* java.lang.Number

The memory limit for the container in MBs.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#memory Container#memory}

---

##### `memoryReservation`<sup>Optional</sup> <a name="memoryReservation" id="@cdktn/provider-docker.container.ContainerConfig.property.memoryReservation"></a>

```java
public java.lang.Number getMemoryReservation();
```

- *Type:* java.lang.Number

The memory-resveration for the container in MBs.

Defaults to 0. Allows you to specify a soft limit smaller than `memory` which is activated when Docker detects contention or low memory on the host machine. If you use `memory-reservation`, it must be set lower than `memory` for it to take precedence. Because it is a soft limit, it doesn't guarantee that the container doesn't exceed the limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#memory_reservation Container#memory_reservation}

---

##### `memorySwap`<sup>Optional</sup> <a name="memorySwap" id="@cdktn/provider-docker.container.ContainerConfig.property.memorySwap"></a>

```java
public java.lang.Number getMemorySwap();
```

- *Type:* java.lang.Number

The total memory limit (memory + swap) for the container in MBs.

This setting may compute to `-1` after `terraform apply` if the target host doesn't support memory swap, when that is the case docker will use a soft limitation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#memory_swap Container#memory_swap}

---

##### `mounts`<sup>Optional</sup> <a name="mounts" id="@cdktn/provider-docker.container.ContainerConfig.property.mounts"></a>

```java
public IResolvable|java.util.List<ContainerMounts> getMounts();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>>

mounts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#mounts Container#mounts}

---

##### `mustRun`<sup>Optional</sup> <a name="mustRun" id="@cdktn/provider-docker.container.ContainerConfig.property.mustRun"></a>

```java
public java.lang.Boolean|IResolvable getMustRun();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the Docker container will be kept running.

If `false`, Terraform leaves the container alone. This attribute is also used to trigger a restart of a stopped container. If your container is stopped, Terraform will set `must_run` to `false` and this will trigger a change. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#must_run Container#must_run}

---

##### `networkMode`<sup>Optional</sup> <a name="networkMode" id="@cdktn/provider-docker.container.ContainerConfig.property.networkMode"></a>

```java
public java.lang.String getNetworkMode();
```

- *Type:* java.lang.String

Network mode of the container.

Defaults to `bridge`. If your host OS is any other OS, you need to set this value explicitly, e.g. `nat` when your container will be running on an Windows host. See https://docs.docker.com/engine/network/ for more information.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#network_mode Container#network_mode}

---

##### `networksAdvanced`<sup>Optional</sup> <a name="networksAdvanced" id="@cdktn/provider-docker.container.ContainerConfig.property.networksAdvanced"></a>

```java
public IResolvable|java.util.List<ContainerNetworksAdvanced> getNetworksAdvanced();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>>

networks_advanced block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#networks_advanced Container#networks_advanced}

---

##### `pidMode`<sup>Optional</sup> <a name="pidMode" id="@cdktn/provider-docker.container.ContainerConfig.property.pidMode"></a>

```java
public java.lang.String getPidMode();
```

- *Type:* java.lang.String

The PID (Process) Namespace mode for the container. Either `container:<name|id>` or `host`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#pid_mode Container#pid_mode}

---

##### `platform`<sup>Optional</sup> <a name="platform" id="@cdktn/provider-docker.container.ContainerConfig.property.platform"></a>

```java
public java.lang.String getPlatform();
```

- *Type:* java.lang.String

Platform in the format `os[/arch[/variant]]` used for image lookup and container runtime, for example `linux/amd64`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#platform Container#platform}

---

##### `ports`<sup>Optional</sup> <a name="ports" id="@cdktn/provider-docker.container.ContainerConfig.property.ports"></a>

```java
public IResolvable|java.util.List<ContainerPorts> getPorts();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>>

ports block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ports Container#ports}

---

##### `privileged`<sup>Optional</sup> <a name="privileged" id="@cdktn/provider-docker.container.ContainerConfig.property.privileged"></a>

```java
public java.lang.Boolean|IResolvable getPrivileged();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the container runs in privileged mode.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#privileged Container#privileged}

---

##### `publishAllPorts`<sup>Optional</sup> <a name="publishAllPorts" id="@cdktn/provider-docker.container.ContainerConfig.property.publishAllPorts"></a>

```java
public java.lang.Boolean|IResolvable getPublishAllPorts();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Publish all ports of the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#publish_all_ports Container#publish_all_ports}

---

##### `readOnly`<sup>Optional</sup> <a name="readOnly" id="@cdktn/provider-docker.container.ContainerConfig.property.readOnly"></a>

```java
public java.lang.Boolean|IResolvable getReadOnly();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the container will be started as readonly. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#read_only Container#read_only}

---

##### `removeVolumes`<sup>Optional</sup> <a name="removeVolumes" id="@cdktn/provider-docker.container.ContainerConfig.property.removeVolumes"></a>

```java
public java.lang.Boolean|IResolvable getRemoveVolumes();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, it will remove anonymous volumes associated with the container. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#remove_volumes Container#remove_volumes}

---

##### `restart`<sup>Optional</sup> <a name="restart" id="@cdktn/provider-docker.container.ContainerConfig.property.restart"></a>

```java
public java.lang.String getRestart();
```

- *Type:* java.lang.String

The restart policy for the container. Must be one of 'no', 'on-failure', 'always', 'unless-stopped'. Defaults to `no`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#restart Container#restart}

---

##### `rm`<sup>Optional</sup> <a name="rm" id="@cdktn/provider-docker.container.ContainerConfig.property.rm"></a>

```java
public java.lang.Boolean|IResolvable getRm();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the container will be automatically removed when it exits. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#rm Container#rm}

---

##### `runtime`<sup>Optional</sup> <a name="runtime" id="@cdktn/provider-docker.container.ContainerConfig.property.runtime"></a>

```java
public java.lang.String getRuntime();
```

- *Type:* java.lang.String

Runtime to use for the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#runtime Container#runtime}

---

##### `securityOpts`<sup>Optional</sup> <a name="securityOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.securityOpts"></a>

```java
public java.util.List<java.lang.String> getSecurityOpts();
```

- *Type:* java.util.List<java.lang.String>

List of string values to customize labels for MLS systems, such as SELinux. See https://docs.docker.com/engine/reference/run/#security-configuration.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#security_opts Container#security_opts}

---

##### `shmSize`<sup>Optional</sup> <a name="shmSize" id="@cdktn/provider-docker.container.ContainerConfig.property.shmSize"></a>

```java
public java.lang.Number getShmSize();
```

- *Type:* java.lang.Number

Size of `/dev/shm` in MBs.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#shm_size Container#shm_size}

---

##### `start`<sup>Optional</sup> <a name="start" id="@cdktn/provider-docker.container.ContainerConfig.property.start"></a>

```java
public java.lang.Boolean|IResolvable getStart();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the Docker container will be started after creation.

If `false`, then the container is only created. Defaults to `true`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#start Container#start}

---

##### `stdinOpen`<sup>Optional</sup> <a name="stdinOpen" id="@cdktn/provider-docker.container.ContainerConfig.property.stdinOpen"></a>

```java
public java.lang.Boolean|IResolvable getStdinOpen();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, keep STDIN open even if not attached (`docker run -i`). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#stdin_open Container#stdin_open}

---

##### `stopSignal`<sup>Optional</sup> <a name="stopSignal" id="@cdktn/provider-docker.container.ContainerConfig.property.stopSignal"></a>

```java
public java.lang.String getStopSignal();
```

- *Type:* java.lang.String

Signal to stop a container (default `SIGTERM`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#stop_signal Container#stop_signal}

---

##### `stopTimeout`<sup>Optional</sup> <a name="stopTimeout" id="@cdktn/provider-docker.container.ContainerConfig.property.stopTimeout"></a>

```java
public java.lang.Number getStopTimeout();
```

- *Type:* java.lang.Number

Timeout (in seconds) to stop a container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#stop_timeout Container#stop_timeout}

---

##### `storageOpts`<sup>Optional</sup> <a name="storageOpts" id="@cdktn/provider-docker.container.ContainerConfig.property.storageOpts"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStorageOpts();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Key/value pairs for the storage driver options, e.g. `size`: `120G`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#storage_opts Container#storage_opts}

---

##### `sysctls`<sup>Optional</sup> <a name="sysctls" id="@cdktn/provider-docker.container.ContainerConfig.property.sysctls"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getSysctls();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of kernel parameters (sysctls) to set in the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#sysctls Container#sysctls}

---

##### `timeouts`<sup>Optional</sup> <a name="timeouts" id="@cdktn/provider-docker.container.ContainerConfig.property.timeouts"></a>

```java
public ContainerTimeouts getTimeouts();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

timeouts block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#timeouts Container#timeouts}

---

##### `tmpfs`<sup>Optional</sup> <a name="tmpfs" id="@cdktn/provider-docker.container.ContainerConfig.property.tmpfs"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getTmpfs();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of container directories which should be replaced by `tmpfs mounts`, and their corresponding mount options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#tmpfs Container#tmpfs}

---

##### `tty`<sup>Optional</sup> <a name="tty" id="@cdktn/provider-docker.container.ContainerConfig.property.tty"></a>

```java
public java.lang.Boolean|IResolvable getTty();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, allocate a pseudo-tty (`docker run -t`). Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#tty Container#tty}

---

##### `ulimit`<sup>Optional</sup> <a name="ulimit" id="@cdktn/provider-docker.container.ContainerConfig.property.ulimit"></a>

```java
public IResolvable|java.util.List<ContainerUlimit> getUlimit();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>>

ulimit block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ulimit Container#ulimit}

---

##### `upload`<sup>Optional</sup> <a name="upload" id="@cdktn/provider-docker.container.ContainerConfig.property.upload"></a>

```java
public IResolvable|java.util.List<ContainerUpload> getUpload();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>>

upload block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#upload Container#upload}

---

##### `user`<sup>Optional</sup> <a name="user" id="@cdktn/provider-docker.container.ContainerConfig.property.user"></a>

```java
public java.lang.String getUser();
```

- *Type:* java.lang.String

User used for run the first process.

Format is `user` or `user:group` which user and group can be passed literally or by name.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#user Container#user}

---

##### `usernsMode`<sup>Optional</sup> <a name="usernsMode" id="@cdktn/provider-docker.container.ContainerConfig.property.usernsMode"></a>

```java
public java.lang.String getUsernsMode();
```

- *Type:* java.lang.String

Sets the usernamespace mode for the container when usernamespace remapping option is enabled.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#userns_mode Container#userns_mode}

---

##### `volumes`<sup>Optional</sup> <a name="volumes" id="@cdktn/provider-docker.container.ContainerConfig.property.volumes"></a>

```java
public IResolvable|java.util.List<ContainerVolumes> getVolumes();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>>

volumes block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#volumes Container#volumes}

---

##### `wait`<sup>Optional</sup> <a name="wait" id="@cdktn/provider-docker.container.ContainerConfig.property.wait"></a>

```java
public java.lang.Boolean|IResolvable getWait();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, then the Docker container is waited for being healthy state after creation.

This requires your container to have a healthcheck, otherwise this provider will error. If `false`, then the container health state is not checked. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#wait Container#wait}

---

##### `waitTimeout`<sup>Optional</sup> <a name="waitTimeout" id="@cdktn/provider-docker.container.ContainerConfig.property.waitTimeout"></a>

```java
public java.lang.Number getWaitTimeout();
```

- *Type:* java.lang.Number

The timeout in seconds to wait the container to be healthy after creation. Defaults to `60`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#wait_timeout Container#wait_timeout}

---

##### `workingDir`<sup>Optional</sup> <a name="workingDir" id="@cdktn/provider-docker.container.ContainerConfig.property.workingDir"></a>

```java
public java.lang.String getWorkingDir();
```

- *Type:* java.lang.String

The working directory for commands to run in.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#working_dir Container#working_dir}

---

### ContainerDeviceReadBps <a name="ContainerDeviceReadBps" id="@cdktn/provider-docker.container.ContainerDeviceReadBps"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceReadBps.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceReadBps;

ContainerDeviceReadBps.builder()
    .path(java.lang.String)
    .rate(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps.property.path">path</a></code> | <code>java.lang.String</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps.property.rate">rate</a></code> | <code>java.lang.Number</code> | The read rate limit in bytes per second. |

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceReadBps.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#path Container#path}

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceReadBps.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

The read rate limit in bytes per second.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#rate Container#rate}

---

### ContainerDeviceReadIops <a name="ContainerDeviceReadIops" id="@cdktn/provider-docker.container.ContainerDeviceReadIops"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceReadIops.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceReadIops;

ContainerDeviceReadIops.builder()
    .path(java.lang.String)
    .rate(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops.property.path">path</a></code> | <code>java.lang.String</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops.property.rate">rate</a></code> | <code>java.lang.Number</code> | The read IOPS limit. |

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceReadIops.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#path Container#path}

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceReadIops.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

The read IOPS limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#rate Container#rate}

---

### ContainerDeviceRequests <a name="ContainerDeviceRequests" id="@cdktn/provider-docker.container.ContainerDeviceRequests"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceRequests.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceRequests;

ContainerDeviceRequests.builder()
//  .capabilities(java.util.List<java.lang.String>)
//  .count(java.lang.Number)
//  .deviceIds(java.util.List<java.lang.String>)
//  .driver(java.lang.String)
//  .options(java.util.Map<java.lang.String, java.lang.String>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.capabilities">capabilities</a></code> | <code>java.util.List<java.lang.String></code> | List of device capabilities. Only used with `nvidia` driver (e.g., `gpu`, `compute`, `utility`). |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.count">count</a></code> | <code>java.lang.Number</code> | Number of devices to request. Use -1 for all devices. Only used with `nvidia` driver. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.deviceIds">deviceIds</a></code> | <code>java.util.List<java.lang.String></code> | List of device IDs or CDI device identifiers (e.g., `nvidia.com/gpu=all`). |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.driver">driver</a></code> | <code>java.lang.String</code> | The device driver to use. Common values: `cdi` for CDI devices, `nvidia` for NVIDIA GPU requests. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequests.property.options">options</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Driver-specific options. |

---

##### `capabilities`<sup>Optional</sup> <a name="capabilities" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.capabilities"></a>

```java
public java.util.List<java.lang.String> getCapabilities();
```

- *Type:* java.util.List<java.lang.String>

List of device capabilities. Only used with `nvidia` driver (e.g., `gpu`, `compute`, `utility`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#capabilities Container#capabilities}

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

Number of devices to request. Use -1 for all devices. Only used with `nvidia` driver.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#count Container#count}

---

##### `deviceIds`<sup>Optional</sup> <a name="deviceIds" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.deviceIds"></a>

```java
public java.util.List<java.lang.String> getDeviceIds();
```

- *Type:* java.util.List<java.lang.String>

List of device IDs or CDI device identifiers (e.g., `nvidia.com/gpu=all`).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#device_ids Container#device_ids}

---

##### `driver`<sup>Optional</sup> <a name="driver" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.driver"></a>

```java
public java.lang.String getDriver();
```

- *Type:* java.lang.String

The device driver to use. Common values: `cdi` for CDI devices, `nvidia` for NVIDIA GPU requests.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#driver Container#driver}

---

##### `options`<sup>Optional</sup> <a name="options" id="@cdktn/provider-docker.container.ContainerDeviceRequests.property.options"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getOptions();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Driver-specific options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#options Container#options}

---

### ContainerDevices <a name="ContainerDevices" id="@cdktn/provider-docker.container.ContainerDevices"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDevices.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDevices;

ContainerDevices.builder()
    .hostPath(java.lang.String)
//  .containerPath(java.lang.String)
//  .permissions(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevices.property.hostPath">hostPath</a></code> | <code>java.lang.String</code> | The path on the host where the device is located. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevices.property.containerPath">containerPath</a></code> | <code>java.lang.String</code> | The path in the container where the device will be bound. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevices.property.permissions">permissions</a></code> | <code>java.lang.String</code> | The cgroup permissions given to the container to access the device. Defaults to `rwm`. |

---

##### `hostPath`<sup>Required</sup> <a name="hostPath" id="@cdktn/provider-docker.container.ContainerDevices.property.hostPath"></a>

```java
public java.lang.String getHostPath();
```

- *Type:* java.lang.String

The path on the host where the device is located.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#host_path Container#host_path}

---

##### `containerPath`<sup>Optional</sup> <a name="containerPath" id="@cdktn/provider-docker.container.ContainerDevices.property.containerPath"></a>

```java
public java.lang.String getContainerPath();
```

- *Type:* java.lang.String

The path in the container where the device will be bound.

If not set, it defaults to the value of `host_path`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#container_path Container#container_path}

---

##### `permissions`<sup>Optional</sup> <a name="permissions" id="@cdktn/provider-docker.container.ContainerDevices.property.permissions"></a>

```java
public java.lang.String getPermissions();
```

- *Type:* java.lang.String

The cgroup permissions given to the container to access the device. Defaults to `rwm`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#permissions Container#permissions}

---

### ContainerDeviceWriteBps <a name="ContainerDeviceWriteBps" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceWriteBps;

ContainerDeviceWriteBps.builder()
    .path(java.lang.String)
    .rate(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.path">path</a></code> | <code>java.lang.String</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.rate">rate</a></code> | <code>java.lang.Number</code> | The write rate limit in bytes per second. |

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#path Container#path}

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteBps.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

The write rate limit in bytes per second.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#rate Container#rate}

---

### ContainerDeviceWriteIops <a name="ContainerDeviceWriteIops" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceWriteIops;

ContainerDeviceWriteIops.builder()
    .path(java.lang.String)
    .rate(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.path">path</a></code> | <code>java.lang.String</code> | The device path on the host, e.g. `/dev/sda`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.rate">rate</a></code> | <code>java.lang.Number</code> | The write IOPS limit. |

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

The device path on the host, e.g. `/dev/sda`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#path Container#path}

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteIops.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

The write IOPS limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#rate Container#rate}

---

### ContainerHealthcheck <a name="ContainerHealthcheck" id="@cdktn/provider-docker.container.ContainerHealthcheck"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerHealthcheck.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerHealthcheck;

ContainerHealthcheck.builder()
//  .interval(java.lang.String)
//  .retries(java.lang.Number)
//  .startInterval(java.lang.String)
//  .startPeriod(java.lang.String)
//  .test(java.util.List<java.lang.String>)
//  .timeout(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.interval">interval</a></code> | <code>java.lang.String</code> | Time between running the check (ms\|s\|m\|h). Defaults to `0s`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.retries">retries</a></code> | <code>java.lang.Number</code> | Consecutive failures needed to report unhealthy. Defaults to `0`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.startInterval">startInterval</a></code> | <code>java.lang.String</code> | Interval before the healthcheck starts (ms\|s\|m\|h). Defaults to `0s`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.startPeriod">startPeriod</a></code> | <code>java.lang.String</code> | Start period for the container to initialize before counting retries towards unstable (ms\|s\|m\|h). Defaults to `0s`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.test">test</a></code> | <code>java.util.List<java.lang.String></code> | Command to run to check health. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck.property.timeout">timeout</a></code> | <code>java.lang.String</code> | Maximum time to allow one check to run (ms\|s\|m\|h). Defaults to `0s`. |

---

##### `interval`<sup>Optional</sup> <a name="interval" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.interval"></a>

```java
public java.lang.String getInterval();
```

- *Type:* java.lang.String

Time between running the check (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#interval Container#interval}

---

##### `retries`<sup>Optional</sup> <a name="retries" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.retries"></a>

```java
public java.lang.Number getRetries();
```

- *Type:* java.lang.Number

Consecutive failures needed to report unhealthy. Defaults to `0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#retries Container#retries}

---

##### `startInterval`<sup>Optional</sup> <a name="startInterval" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.startInterval"></a>

```java
public java.lang.String getStartInterval();
```

- *Type:* java.lang.String

Interval before the healthcheck starts (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#start_interval Container#start_interval}

---

##### `startPeriod`<sup>Optional</sup> <a name="startPeriod" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.startPeriod"></a>

```java
public java.lang.String getStartPeriod();
```

- *Type:* java.lang.String

Start period for the container to initialize before counting retries towards unstable (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#start_period Container#start_period}

---

##### `test`<sup>Optional</sup> <a name="test" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.test"></a>

```java
public java.util.List<java.lang.String> getTest();
```

- *Type:* java.util.List<java.lang.String>

Command to run to check health.

For example, to run `curl -f localhost/health` set the command to be `["CMD", "curl", "-f", "localhost/health"]`. It works in the same way, and has the same default values, as the HEALTHCHECK Dockerfile instruction set by the service's Docker image. Your Compose file can override the values set in the Dockerfile.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#test Container#test}

---

##### `timeout`<sup>Optional</sup> <a name="timeout" id="@cdktn/provider-docker.container.ContainerHealthcheck.property.timeout"></a>

```java
public java.lang.String getTimeout();
```

- *Type:* java.lang.String

Maximum time to allow one check to run (ms|s|m|h). Defaults to `0s`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#timeout Container#timeout}

---

### ContainerHost <a name="ContainerHost" id="@cdktn/provider-docker.container.ContainerHost"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerHost.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerHost;

ContainerHost.builder()
    .host(java.lang.String)
    .ip(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHost.property.host">host</a></code> | <code>java.lang.String</code> | Hostname to add. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHost.property.ip">ip</a></code> | <code>java.lang.String</code> | IP address this hostname should resolve to. |

---

##### `host`<sup>Required</sup> <a name="host" id="@cdktn/provider-docker.container.ContainerHost.property.host"></a>

```java
public java.lang.String getHost();
```

- *Type:* java.lang.String

Hostname to add.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#host Container#host}

---

##### `ip`<sup>Required</sup> <a name="ip" id="@cdktn/provider-docker.container.ContainerHost.property.ip"></a>

```java
public java.lang.String getIp();
```

- *Type:* java.lang.String

IP address this hostname should resolve to.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ip Container#ip}

---

### ContainerLabels <a name="ContainerLabels" id="@cdktn/provider-docker.container.ContainerLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerLabels.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerLabels;

ContainerLabels.builder()
    .label(java.lang.String)
    .value(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabels.property.label">label</a></code> | <code>java.lang.String</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabels.property.value">value</a></code> | <code>java.lang.String</code> | Value of the label. |

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.container.ContainerLabels.property.label"></a>

```java
public java.lang.String getLabel();
```

- *Type:* java.lang.String

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#label Container#label}

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerLabels.property.value"></a>

```java
public java.lang.String getValue();
```

- *Type:* java.lang.String

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#value Container#value}

---

### ContainerMounts <a name="ContainerMounts" id="@cdktn/provider-docker.container.ContainerMounts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMounts.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMounts;

ContainerMounts.builder()
    .target(java.lang.String)
    .type(java.lang.String)
//  .bindOptions(ContainerMountsBindOptions)
//  .readOnly(java.lang.Boolean|IResolvable)
//  .source(java.lang.String)
//  .tmpfsOptions(ContainerMountsTmpfsOptions)
//  .volumeOptions(ContainerMountsVolumeOptions)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.target">target</a></code> | <code>java.lang.String</code> | Container path. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.type">type</a></code> | <code>java.lang.String</code> | The mount type. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.bindOptions">bindOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a></code> | bind_options block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Whether the mount should be read-only. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.source">source</a></code> | <code>java.lang.String</code> | Mount source (e.g. a volume name, a host path). |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.tmpfsOptions">tmpfsOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a></code> | tmpfs_options block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMounts.property.volumeOptions">volumeOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a></code> | volume_options block. |

---

##### `target`<sup>Required</sup> <a name="target" id="@cdktn/provider-docker.container.ContainerMounts.property.target"></a>

```java
public java.lang.String getTarget();
```

- *Type:* java.lang.String

Container path.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#target Container#target}

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktn/provider-docker.container.ContainerMounts.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

The mount type.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#type Container#type}

---

##### `bindOptions`<sup>Optional</sup> <a name="bindOptions" id="@cdktn/provider-docker.container.ContainerMounts.property.bindOptions"></a>

```java
public ContainerMountsBindOptions getBindOptions();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

bind_options block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#bind_options Container#bind_options}

---

##### `readOnly`<sup>Optional</sup> <a name="readOnly" id="@cdktn/provider-docker.container.ContainerMounts.property.readOnly"></a>

```java
public java.lang.Boolean|IResolvable getReadOnly();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Whether the mount should be read-only.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#read_only Container#read_only}

---

##### `source`<sup>Optional</sup> <a name="source" id="@cdktn/provider-docker.container.ContainerMounts.property.source"></a>

```java
public java.lang.String getSource();
```

- *Type:* java.lang.String

Mount source (e.g. a volume name, a host path).

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#source Container#source}

---

##### `tmpfsOptions`<sup>Optional</sup> <a name="tmpfsOptions" id="@cdktn/provider-docker.container.ContainerMounts.property.tmpfsOptions"></a>

```java
public ContainerMountsTmpfsOptions getTmpfsOptions();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

tmpfs_options block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#tmpfs_options Container#tmpfs_options}

---

##### `volumeOptions`<sup>Optional</sup> <a name="volumeOptions" id="@cdktn/provider-docker.container.ContainerMounts.property.volumeOptions"></a>

```java
public ContainerMountsVolumeOptions getVolumeOptions();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

volume_options block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#volume_options Container#volume_options}

---

### ContainerMountsBindOptions <a name="ContainerMountsBindOptions" id="@cdktn/provider-docker.container.ContainerMountsBindOptions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsBindOptions.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsBindOptions;

ContainerMountsBindOptions.builder()
//  .propagation(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions.property.propagation">propagation</a></code> | <code>java.lang.String</code> | A propagation mode with the value. |

---

##### `propagation`<sup>Optional</sup> <a name="propagation" id="@cdktn/provider-docker.container.ContainerMountsBindOptions.property.propagation"></a>

```java
public java.lang.String getPropagation();
```

- *Type:* java.lang.String

A propagation mode with the value.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#propagation Container#propagation}

---

### ContainerMountsTmpfsOptions <a name="ContainerMountsTmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsTmpfsOptions;

ContainerMountsTmpfsOptions.builder()
//  .mode(java.lang.Number)
//  .sizeBytes(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.mode">mode</a></code> | <code>java.lang.Number</code> | The permission mode for the tmpfs mount in an integer. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.sizeBytes">sizeBytes</a></code> | <code>java.lang.Number</code> | The size for the tmpfs mount in bytes. |

---

##### `mode`<sup>Optional</sup> <a name="mode" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.mode"></a>

```java
public java.lang.Number getMode();
```

- *Type:* java.lang.Number

The permission mode for the tmpfs mount in an integer.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#mode Container#mode}

---

##### `sizeBytes`<sup>Optional</sup> <a name="sizeBytes" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptions.property.sizeBytes"></a>

```java
public java.lang.Number getSizeBytes();
```

- *Type:* java.lang.Number

The size for the tmpfs mount in bytes.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#size_bytes Container#size_bytes}

---

### ContainerMountsVolumeOptions <a name="ContainerMountsVolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsVolumeOptions;

ContainerMountsVolumeOptions.builder()
//  .driverName(java.lang.String)
//  .driverOptions(java.util.Map<java.lang.String, java.lang.String>)
//  .labels(IResolvable|java.util.List<ContainerMountsVolumeOptionsLabels>)
//  .noCopy(java.lang.Boolean|IResolvable)
//  .subpath(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverName">driverName</a></code> | <code>java.lang.String</code> | Name of the driver to use to create the volume. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverOptions">driverOptions</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | key/value map of driver specific options. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.labels">labels</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>></code> | labels block. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.noCopy">noCopy</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | Populate volume with data from the target. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.subpath">subpath</a></code> | <code>java.lang.String</code> | Path within the volume to mount. Requires docker server version 1.45 or higher. |

---

##### `driverName`<sup>Optional</sup> <a name="driverName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverName"></a>

```java
public java.lang.String getDriverName();
```

- *Type:* java.lang.String

Name of the driver to use to create the volume.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#driver_name Container#driver_name}

---

##### `driverOptions`<sup>Optional</sup> <a name="driverOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.driverOptions"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDriverOptions();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

key/value map of driver specific options.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#driver_options Container#driver_options}

---

##### `labels`<sup>Optional</sup> <a name="labels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.labels"></a>

```java
public IResolvable|java.util.List<ContainerMountsVolumeOptionsLabels> getLabels();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>>

labels block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#labels Container#labels}

---

##### `noCopy`<sup>Optional</sup> <a name="noCopy" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.noCopy"></a>

```java
public java.lang.Boolean|IResolvable getNoCopy();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

Populate volume with data from the target.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#no_copy Container#no_copy}

---

##### `subpath`<sup>Optional</sup> <a name="subpath" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptions.property.subpath"></a>

```java
public java.lang.String getSubpath();
```

- *Type:* java.lang.String

Path within the volume to mount. Requires docker server version 1.45 or higher.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#subpath Container#subpath}

---

### ContainerMountsVolumeOptionsLabels <a name="ContainerMountsVolumeOptionsLabels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsVolumeOptionsLabels;

ContainerMountsVolumeOptionsLabels.builder()
    .label(java.lang.String)
    .value(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.label">label</a></code> | <code>java.lang.String</code> | Name of the label. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.value">value</a></code> | <code>java.lang.String</code> | Value of the label. |

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.label"></a>

```java
public java.lang.String getLabel();
```

- *Type:* java.lang.String

Name of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#label Container#label}

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels.property.value"></a>

```java
public java.lang.String getValue();
```

- *Type:* java.lang.String

Value of the label.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#value Container#value}

---

### ContainerNetworkData <a name="ContainerNetworkData" id="@cdktn/provider-docker.container.ContainerNetworkData"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerNetworkData.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerNetworkData;

ContainerNetworkData.builder()
    .build();
```


### ContainerNetworksAdvanced <a name="ContainerNetworksAdvanced" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerNetworksAdvanced;

ContainerNetworksAdvanced.builder()
    .name(java.lang.String)
//  .aliases(java.util.List<java.lang.String>)
//  .driverOpts(java.util.List<java.lang.String>)
//  .gwPriority(java.lang.Number)
//  .ipv4Address(java.lang.String)
//  .ipv6Address(java.lang.String)
//  .linkLocalIps(java.util.List<java.lang.String>)
//  .macAddress(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.name">name</a></code> | <code>java.lang.String</code> | The name or id of the network to use. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.aliases">aliases</a></code> | <code>java.util.List<java.lang.String></code> | The network aliases of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.driverOpts">driverOpts</a></code> | <code>java.util.List<java.lang.String></code> | An array of driver options for the network endpoint, e.g. `opts1=value`. This is the equivalent to repeating `--driver-opt` for `docker run`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.gwPriority">gwPriority</a></code> | <code>java.lang.Number</code> | Gateway priority for this endpoint. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv4Address">ipv4Address</a></code> | <code>java.lang.String</code> | The IPV4 address of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv6Address">ipv6Address</a></code> | <code>java.lang.String</code> | The IPV6 address of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.linkLocalIps">linkLocalIps</a></code> | <code>java.util.List<java.lang.String></code> | The link-local IPs of the container in the specific network. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.macAddress">macAddress</a></code> | <code>java.lang.String</code> | The MAC address of the container in the specific network. |

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The name or id of the network to use.

You can use `name` or `id` attribute from a `docker_network` resource.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#name Container#name}

---

##### `aliases`<sup>Optional</sup> <a name="aliases" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.aliases"></a>

```java
public java.util.List<java.lang.String> getAliases();
```

- *Type:* java.util.List<java.lang.String>

The network aliases of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#aliases Container#aliases}

---

##### `driverOpts`<sup>Optional</sup> <a name="driverOpts" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.driverOpts"></a>

```java
public java.util.List<java.lang.String> getDriverOpts();
```

- *Type:* java.util.List<java.lang.String>

An array of driver options for the network endpoint, e.g. `opts1=value`. This is the equivalent to repeating `--driver-opt` for `docker run`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#driver_opts Container#driver_opts}

---

##### `gwPriority`<sup>Optional</sup> <a name="gwPriority" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.gwPriority"></a>

```java
public java.lang.Number getGwPriority();
```

- *Type:* java.lang.Number

Gateway priority for this endpoint.

The endpoint with the highest priority will provide the default gateway for the container. This is the equivalent to `--gw-priority` for `docker run`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#gw_priority Container#gw_priority}

---

##### `ipv4Address`<sup>Optional</sup> <a name="ipv4Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv4Address"></a>

```java
public java.lang.String getIpv4Address();
```

- *Type:* java.lang.String

The IPV4 address of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ipv4_address Container#ipv4_address}

---

##### `ipv6Address`<sup>Optional</sup> <a name="ipv6Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.ipv6Address"></a>

```java
public java.lang.String getIpv6Address();
```

- *Type:* java.lang.String

The IPV6 address of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ipv6_address Container#ipv6_address}

---

##### `linkLocalIps`<sup>Optional</sup> <a name="linkLocalIps" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.linkLocalIps"></a>

```java
public java.util.List<java.lang.String> getLinkLocalIps();
```

- *Type:* java.util.List<java.lang.String>

The link-local IPs of the container in the specific network.

This is the equivalent to repeating `--link-local-ip` for `docker run`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#link_local_ips Container#link_local_ips}

---

##### `macAddress`<sup>Optional</sup> <a name="macAddress" id="@cdktn/provider-docker.container.ContainerNetworksAdvanced.property.macAddress"></a>

```java
public java.lang.String getMacAddress();
```

- *Type:* java.lang.String

The MAC address of the container in the specific network.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#mac_address Container#mac_address}

---

### ContainerPorts <a name="ContainerPorts" id="@cdktn/provider-docker.container.ContainerPorts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerPorts.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerPorts;

ContainerPorts.builder()
    .internal(java.lang.Number)
//  .external(java.lang.Number)
//  .ip(java.lang.String)
//  .protocol(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.internal">internal</a></code> | <code>java.lang.Number</code> | Port within the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.external">external</a></code> | <code>java.lang.Number</code> | Port exposed out of the container. If not given a free random port `>= 32768` will be used. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.ip">ip</a></code> | <code>java.lang.String</code> | IP address/mask that can access this port. Defaults to `0.0.0.0`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPorts.property.protocol">protocol</a></code> | <code>java.lang.String</code> | Protocol that can be used over this port. Defaults to `tcp`. |

---

##### `internal`<sup>Required</sup> <a name="internal" id="@cdktn/provider-docker.container.ContainerPorts.property.internal"></a>

```java
public java.lang.Number getInternal();
```

- *Type:* java.lang.Number

Port within the container.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#internal Container#internal}

---

##### `external`<sup>Optional</sup> <a name="external" id="@cdktn/provider-docker.container.ContainerPorts.property.external"></a>

```java
public java.lang.Number getExternal();
```

- *Type:* java.lang.Number

Port exposed out of the container. If not given a free random port `>= 32768` will be used.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#external Container#external}

---

##### `ip`<sup>Optional</sup> <a name="ip" id="@cdktn/provider-docker.container.ContainerPorts.property.ip"></a>

```java
public java.lang.String getIp();
```

- *Type:* java.lang.String

IP address/mask that can access this port. Defaults to `0.0.0.0`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#ip Container#ip}

---

##### `protocol`<sup>Optional</sup> <a name="protocol" id="@cdktn/provider-docker.container.ContainerPorts.property.protocol"></a>

```java
public java.lang.String getProtocol();
```

- *Type:* java.lang.String

Protocol that can be used over this port. Defaults to `tcp`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#protocol Container#protocol}

---

### ContainerTimeouts <a name="ContainerTimeouts" id="@cdktn/provider-docker.container.ContainerTimeouts"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerTimeouts.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerTimeouts;

ContainerTimeouts.builder()
//  .create(java.lang.String)
//  .delete(java.lang.String)
//  .update(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts.property.create">create</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#create Container#create}. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts.property.delete">delete</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#delete Container#delete}. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeouts.property.update">update</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#update Container#update}. |

---

##### `create`<sup>Optional</sup> <a name="create" id="@cdktn/provider-docker.container.ContainerTimeouts.property.create"></a>

```java
public java.lang.String getCreate();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#create Container#create}.

---

##### `delete`<sup>Optional</sup> <a name="delete" id="@cdktn/provider-docker.container.ContainerTimeouts.property.delete"></a>

```java
public java.lang.String getDelete();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#delete Container#delete}.

---

##### `update`<sup>Optional</sup> <a name="update" id="@cdktn/provider-docker.container.ContainerTimeouts.property.update"></a>

```java
public java.lang.String getUpdate();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#update Container#update}.

---

### ContainerUlimit <a name="ContainerUlimit" id="@cdktn/provider-docker.container.ContainerUlimit"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerUlimit.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerUlimit;

ContainerUlimit.builder()
    .hard(java.lang.Number)
    .name(java.lang.String)
    .soft(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimit.property.hard">hard</a></code> | <code>java.lang.Number</code> | The hard limit. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimit.property.name">name</a></code> | <code>java.lang.String</code> | The name of the ulimit. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimit.property.soft">soft</a></code> | <code>java.lang.Number</code> | The soft limit. |

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.container.ContainerUlimit.property.hard"></a>

```java
public java.lang.Number getHard();
```

- *Type:* java.lang.Number

The hard limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#hard Container#hard}

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.ContainerUlimit.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

The name of the ulimit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#name Container#name}

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.container.ContainerUlimit.property.soft"></a>

```java
public java.lang.Number getSoft();
```

- *Type:* java.lang.Number

The soft limit.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#soft Container#soft}

---

### ContainerUpload <a name="ContainerUpload" id="@cdktn/provider-docker.container.ContainerUpload"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerUpload.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerUpload;

ContainerUpload.builder()
    .file(java.lang.String)
//  .content(java.lang.String)
//  .contentBase64(java.lang.String)
//  .executable(java.lang.Boolean|IResolvable)
//  .group(java.lang.String)
//  .owner(java.lang.String)
//  .permissions(java.lang.String)
//  .source(java.lang.String)
//  .sourceHash(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.file">file</a></code> | <code>java.lang.String</code> | Path to the file in the container where is upload goes to. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.content">content</a></code> | <code>java.lang.String</code> | Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.contentBase64">contentBase64</a></code> | <code>java.lang.String</code> | Base64-encoded data that will be decoded and uploaded as raw bytes for the object content. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.executable">executable</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, the file will be uploaded with user executable permission. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.group">group</a></code> | <code>java.lang.String</code> | The group of the file in the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.owner">owner</a></code> | <code>java.lang.String</code> | The owner of the file in the container. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.permissions">permissions</a></code> | <code>java.lang.String</code> | The permission mode for the file in the container. Has precedence over `executable`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.source">source</a></code> | <code>java.lang.String</code> | A filename that references a file which will be uploaded as the object content. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUpload.property.sourceHash">sourceHash</a></code> | <code>java.lang.String</code> | If using `source`, this will force an update if the file content has updated but the filename has not. |

---

##### `file`<sup>Required</sup> <a name="file" id="@cdktn/provider-docker.container.ContainerUpload.property.file"></a>

```java
public java.lang.String getFile();
```

- *Type:* java.lang.String

Path to the file in the container where is upload goes to.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#file Container#file}

---

##### `content`<sup>Optional</sup> <a name="content" id="@cdktn/provider-docker.container.ContainerUpload.property.content"></a>

```java
public java.lang.String getContent();
```

- *Type:* java.lang.String

Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text.

Conflicts with `content_base64` & `source`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#content Container#content}

---

##### `contentBase64`<sup>Optional</sup> <a name="contentBase64" id="@cdktn/provider-docker.container.ContainerUpload.property.contentBase64"></a>

```java
public java.lang.String getContentBase64();
```

- *Type:* java.lang.String

Base64-encoded data that will be decoded and uploaded as raw bytes for the object content.

This allows safely uploading non-UTF8 binary data, but is recommended only for larger binary content such as the result of the `base64encode` interpolation function. See [here](https://github.com/terraform-providers/terraform-provider-docker/issues/48#issuecomment-374174588) for the reason. Conflicts with `content` & `source`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#content_base64 Container#content_base64}

---

##### `executable`<sup>Optional</sup> <a name="executable" id="@cdktn/provider-docker.container.ContainerUpload.property.executable"></a>

```java
public java.lang.Boolean|IResolvable getExecutable();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, the file will be uploaded with user executable permission. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#executable Container#executable}

---

##### `group`<sup>Optional</sup> <a name="group" id="@cdktn/provider-docker.container.ContainerUpload.property.group"></a>

```java
public java.lang.String getGroup();
```

- *Type:* java.lang.String

The group of the file in the container.

Names are resolved using the Terraform host's group database; numeric IDs can be used directly.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#group Container#group}

---

##### `owner`<sup>Optional</sup> <a name="owner" id="@cdktn/provider-docker.container.ContainerUpload.property.owner"></a>

```java
public java.lang.String getOwner();
```

- *Type:* java.lang.String

The owner of the file in the container.

Names are resolved using the Terraform host's user database; numeric IDs can be used directly.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#owner Container#owner}

---

##### `permissions`<sup>Optional</sup> <a name="permissions" id="@cdktn/provider-docker.container.ContainerUpload.property.permissions"></a>

```java
public java.lang.String getPermissions();
```

- *Type:* java.lang.String

The permission mode for the file in the container. Has precedence over `executable`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#permissions Container#permissions}

---

##### `source`<sup>Optional</sup> <a name="source" id="@cdktn/provider-docker.container.ContainerUpload.property.source"></a>

```java
public java.lang.String getSource();
```

- *Type:* java.lang.String

A filename that references a file which will be uploaded as the object content.

This allows for large file uploads that do not get stored in state. Conflicts with `content` & `content_base64`

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#source Container#source}

---

##### `sourceHash`<sup>Optional</sup> <a name="sourceHash" id="@cdktn/provider-docker.container.ContainerUpload.property.sourceHash"></a>

```java
public java.lang.String getSourceHash();
```

- *Type:* java.lang.String

If using `source`, this will force an update if the file content has updated but the filename has not.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#source_hash Container#source_hash}

---

### ContainerVolumes <a name="ContainerVolumes" id="@cdktn/provider-docker.container.ContainerVolumes"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-docker.container.ContainerVolumes.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerVolumes;

ContainerVolumes.builder()
//  .containerPath(java.lang.String)
//  .fromContainer(java.lang.String)
//  .hostPath(java.lang.String)
//  .readOnly(java.lang.Boolean|IResolvable)
//  .selinuxRelabel(java.lang.String)
//  .volumeName(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.containerPath">containerPath</a></code> | <code>java.lang.String</code> | The path in the container where the volume will be mounted. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.fromContainer">fromContainer</a></code> | <code>java.lang.String</code> | The container where the volume is coming from. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.hostPath">hostPath</a></code> | <code>java.lang.String</code> | The path on the host where the volume is coming from. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | If `true`, this volume will be readonly. Defaults to `false`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.selinuxRelabel">selinuxRelabel</a></code> | <code>java.lang.String</code> | SELinux relabel mode for bind mounts. Supported values are `z` and `Z`. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumes.property.volumeName">volumeName</a></code> | <code>java.lang.String</code> | The name of the docker volume which should be mounted. Ignored when `host_path` is set. |

---

##### `containerPath`<sup>Optional</sup> <a name="containerPath" id="@cdktn/provider-docker.container.ContainerVolumes.property.containerPath"></a>

```java
public java.lang.String getContainerPath();
```

- *Type:* java.lang.String

The path in the container where the volume will be mounted.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#container_path Container#container_path}

---

##### `fromContainer`<sup>Optional</sup> <a name="fromContainer" id="@cdktn/provider-docker.container.ContainerVolumes.property.fromContainer"></a>

```java
public java.lang.String getFromContainer();
```

- *Type:* java.lang.String

The container where the volume is coming from.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#from_container Container#from_container}

---

##### `hostPath`<sup>Optional</sup> <a name="hostPath" id="@cdktn/provider-docker.container.ContainerVolumes.property.hostPath"></a>

```java
public java.lang.String getHostPath();
```

- *Type:* java.lang.String

The path on the host where the volume is coming from.

If `host_path` is set, it takes precedence over `volume_name`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#host_path Container#host_path}

---

##### `readOnly`<sup>Optional</sup> <a name="readOnly" id="@cdktn/provider-docker.container.ContainerVolumes.property.readOnly"></a>

```java
public java.lang.Boolean|IResolvable getReadOnly();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

If `true`, this volume will be readonly. Defaults to `false`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#read_only Container#read_only}

---

##### `selinuxRelabel`<sup>Optional</sup> <a name="selinuxRelabel" id="@cdktn/provider-docker.container.ContainerVolumes.property.selinuxRelabel"></a>

```java
public java.lang.String getSelinuxRelabel();
```

- *Type:* java.lang.String

SELinux relabel mode for bind mounts. Supported values are `z` and `Z`.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#selinux_relabel Container#selinux_relabel}

---

##### `volumeName`<sup>Optional</sup> <a name="volumeName" id="@cdktn/provider-docker.container.ContainerVolumes.property.volumeName"></a>

```java
public java.lang.String getVolumeName();
```

- *Type:* java.lang.String

The name of the docker volume which should be mounted. Ignored when `host_path` is set.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/kreuzwerker/docker/4.6.0/docs/resources/container#volume_name Container#volume_name}

---

## Classes <a name="Classes" id="Classes"></a>

### ContainerCapabilitiesOutputReference <a name="ContainerCapabilitiesOutputReference" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerCapabilitiesOutputReference;

new ContainerCapabilitiesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetAdd">resetAdd</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetDrop">resetDrop</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAdd` <a name="resetAdd" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetAdd"></a>

```java
public void resetAdd()
```

##### `resetDrop` <a name="resetDrop" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.resetDrop"></a>

```java
public void resetDrop()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.addInput">addInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.dropInput">dropInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.add">add</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.drop">drop</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `addInput`<sup>Optional</sup> <a name="addInput" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.addInput"></a>

```java
public java.util.List<java.lang.String> getAddInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `dropInput`<sup>Optional</sup> <a name="dropInput" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.dropInput"></a>

```java
public java.util.List<java.lang.String> getDropInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `add`<sup>Required</sup> <a name="add" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.add"></a>

```java
public java.util.List<java.lang.String> getAdd();
```

- *Type:* java.util.List<java.lang.String>

---

##### `drop`<sup>Required</sup> <a name="drop" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.drop"></a>

```java
public java.util.List<java.lang.String> getDrop();
```

- *Type:* java.util.List<java.lang.String>

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerCapabilitiesOutputReference.property.internalValue"></a>

```java
public ContainerCapabilities getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerCapabilities">ContainerCapabilities</a>

---


### ContainerDeviceReadBpsList <a name="ContainerDeviceReadBpsList" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceReadBpsList;

new ContainerDeviceReadBpsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.get"></a>

```java
public ContainerDeviceReadBpsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerDeviceReadBps> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>>

---


### ContainerDeviceReadBpsOutputReference <a name="ContainerDeviceReadBpsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceReadBpsOutputReference;

new ContainerDeviceReadBpsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.pathInput">pathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rateInput">rateInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.path">path</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rate">rate</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `pathInput`<sup>Optional</sup> <a name="pathInput" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.pathInput"></a>

```java
public java.lang.String getPathInput();
```

- *Type:* java.lang.String

---

##### `rateInput`<sup>Optional</sup> <a name="rateInput" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rateInput"></a>

```java
public java.lang.Number getRateInput();
```

- *Type:* java.lang.Number

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadBpsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerDeviceReadBps getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadBps">ContainerDeviceReadBps</a>

---


### ContainerDeviceReadIopsList <a name="ContainerDeviceReadIopsList" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceReadIopsList;

new ContainerDeviceReadIopsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.get"></a>

```java
public ContainerDeviceReadIopsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerDeviceReadIops> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>>

---


### ContainerDeviceReadIopsOutputReference <a name="ContainerDeviceReadIopsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceReadIopsOutputReference;

new ContainerDeviceReadIopsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.pathInput">pathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rateInput">rateInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.path">path</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rate">rate</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `pathInput`<sup>Optional</sup> <a name="pathInput" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.pathInput"></a>

```java
public java.lang.String getPathInput();
```

- *Type:* java.lang.String

---

##### `rateInput`<sup>Optional</sup> <a name="rateInput" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rateInput"></a>

```java
public java.lang.Number getRateInput();
```

- *Type:* java.lang.Number

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceReadIopsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerDeviceReadIops getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceReadIops">ContainerDeviceReadIops</a>

---


### ContainerDeviceRequestsList <a name="ContainerDeviceRequestsList" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceRequestsList;

new ContainerDeviceRequestsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.get"></a>

```java
public ContainerDeviceRequestsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceRequestsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerDeviceRequests> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>>

---


### ContainerDeviceRequestsOutputReference <a name="ContainerDeviceRequestsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceRequestsOutputReference;

new ContainerDeviceRequestsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCapabilities">resetCapabilities</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCount">resetCount</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDeviceIds">resetDeviceIds</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDriver">resetDriver</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetOptions">resetOptions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetCapabilities` <a name="resetCapabilities" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCapabilities"></a>

```java
public void resetCapabilities()
```

##### `resetCount` <a name="resetCount" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetCount"></a>

```java
public void resetCount()
```

##### `resetDeviceIds` <a name="resetDeviceIds" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDeviceIds"></a>

```java
public void resetDeviceIds()
```

##### `resetDriver` <a name="resetDriver" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetDriver"></a>

```java
public void resetDriver()
```

##### `resetOptions` <a name="resetOptions" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.resetOptions"></a>

```java
public void resetOptions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilitiesInput">capabilitiesInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.countInput">countInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIdsInput">deviceIdsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driverInput">driverInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.optionsInput">optionsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilities">capabilities</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.count">count</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIds">deviceIds</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driver">driver</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.options">options</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `capabilitiesInput`<sup>Optional</sup> <a name="capabilitiesInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilitiesInput"></a>

```java
public java.util.List<java.lang.String> getCapabilitiesInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `countInput`<sup>Optional</sup> <a name="countInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.countInput"></a>

```java
public java.lang.Number getCountInput();
```

- *Type:* java.lang.Number

---

##### `deviceIdsInput`<sup>Optional</sup> <a name="deviceIdsInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIdsInput"></a>

```java
public java.util.List<java.lang.String> getDeviceIdsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `driverInput`<sup>Optional</sup> <a name="driverInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driverInput"></a>

```java
public java.lang.String getDriverInput();
```

- *Type:* java.lang.String

---

##### `optionsInput`<sup>Optional</sup> <a name="optionsInput" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.optionsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getOptionsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `capabilities`<sup>Required</sup> <a name="capabilities" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.capabilities"></a>

```java
public java.util.List<java.lang.String> getCapabilities();
```

- *Type:* java.util.List<java.lang.String>

---

##### `count`<sup>Required</sup> <a name="count" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

---

##### `deviceIds`<sup>Required</sup> <a name="deviceIds" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.deviceIds"></a>

```java
public java.util.List<java.lang.String> getDeviceIds();
```

- *Type:* java.util.List<java.lang.String>

---

##### `driver`<sup>Required</sup> <a name="driver" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.driver"></a>

```java
public java.lang.String getDriver();
```

- *Type:* java.lang.String

---

##### `options`<sup>Required</sup> <a name="options" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.options"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getOptions();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceRequestsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerDeviceRequests getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceRequests">ContainerDeviceRequests</a>

---


### ContainerDevicesList <a name="ContainerDevicesList" id="@cdktn/provider-docker.container.ContainerDevicesList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDevicesList;

new ContainerDevicesList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerDevicesList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerDevicesList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDevicesList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDevicesList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDevicesList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDevicesList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDevicesList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerDevicesList.get"></a>

```java
public ContainerDevicesOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerDevicesList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDevicesList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDevicesList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDevicesList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerDevices> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>>

---


### ContainerDevicesOutputReference <a name="ContainerDevicesOutputReference" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDevicesOutputReference;

new ContainerDevicesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetContainerPath">resetContainerPath</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetPermissions">resetPermissions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetContainerPath` <a name="resetContainerPath" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetContainerPath"></a>

```java
public void resetContainerPath()
```

##### `resetPermissions` <a name="resetPermissions" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.resetPermissions"></a>

```java
public void resetPermissions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPathInput">containerPathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPathInput">hostPathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissionsInput">permissionsInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPath">containerPath</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPath">hostPath</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissions">permissions</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `containerPathInput`<sup>Optional</sup> <a name="containerPathInput" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPathInput"></a>

```java
public java.lang.String getContainerPathInput();
```

- *Type:* java.lang.String

---

##### `hostPathInput`<sup>Optional</sup> <a name="hostPathInput" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPathInput"></a>

```java
public java.lang.String getHostPathInput();
```

- *Type:* java.lang.String

---

##### `permissionsInput`<sup>Optional</sup> <a name="permissionsInput" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissionsInput"></a>

```java
public java.lang.String getPermissionsInput();
```

- *Type:* java.lang.String

---

##### `containerPath`<sup>Required</sup> <a name="containerPath" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.containerPath"></a>

```java
public java.lang.String getContainerPath();
```

- *Type:* java.lang.String

---

##### `hostPath`<sup>Required</sup> <a name="hostPath" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.hostPath"></a>

```java
public java.lang.String getHostPath();
```

- *Type:* java.lang.String

---

##### `permissions`<sup>Required</sup> <a name="permissions" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.permissions"></a>

```java
public java.lang.String getPermissions();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDevicesOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerDevices getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDevices">ContainerDevices</a>

---


### ContainerDeviceWriteBpsList <a name="ContainerDeviceWriteBpsList" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceWriteBpsList;

new ContainerDeviceWriteBpsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.get"></a>

```java
public ContainerDeviceWriteBpsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerDeviceWriteBps> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>>

---


### ContainerDeviceWriteBpsOutputReference <a name="ContainerDeviceWriteBpsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceWriteBpsOutputReference;

new ContainerDeviceWriteBpsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.pathInput">pathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rateInput">rateInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.path">path</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rate">rate</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `pathInput`<sup>Optional</sup> <a name="pathInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.pathInput"></a>

```java
public java.lang.String getPathInput();
```

- *Type:* java.lang.String

---

##### `rateInput`<sup>Optional</sup> <a name="rateInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rateInput"></a>

```java
public java.lang.Number getRateInput();
```

- *Type:* java.lang.Number

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteBpsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerDeviceWriteBps getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteBps">ContainerDeviceWriteBps</a>

---


### ContainerDeviceWriteIopsList <a name="ContainerDeviceWriteIopsList" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceWriteIopsList;

new ContainerDeviceWriteIopsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.get"></a>

```java
public ContainerDeviceWriteIopsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerDeviceWriteIops> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>>

---


### ContainerDeviceWriteIopsOutputReference <a name="ContainerDeviceWriteIopsOutputReference" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerDeviceWriteIopsOutputReference;

new ContainerDeviceWriteIopsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.pathInput">pathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rateInput">rateInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.path">path</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rate">rate</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `pathInput`<sup>Optional</sup> <a name="pathInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.pathInput"></a>

```java
public java.lang.String getPathInput();
```

- *Type:* java.lang.String

---

##### `rateInput`<sup>Optional</sup> <a name="rateInput" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rateInput"></a>

```java
public java.lang.Number getRateInput();
```

- *Type:* java.lang.Number

---

##### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.path"></a>

```java
public java.lang.String getPath();
```

- *Type:* java.lang.String

---

##### `rate`<sup>Required</sup> <a name="rate" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.rate"></a>

```java
public java.lang.Number getRate();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerDeviceWriteIopsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerDeviceWriteIops getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerDeviceWriteIops">ContainerDeviceWriteIops</a>

---


### ContainerHealthcheckOutputReference <a name="ContainerHealthcheckOutputReference" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerHealthcheckOutputReference;

new ContainerHealthcheckOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetInterval">resetInterval</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetRetries">resetRetries</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartInterval">resetStartInterval</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartPeriod">resetStartPeriod</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTest">resetTest</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTimeout">resetTimeout</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetInterval` <a name="resetInterval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetInterval"></a>

```java
public void resetInterval()
```

##### `resetRetries` <a name="resetRetries" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetRetries"></a>

```java
public void resetRetries()
```

##### `resetStartInterval` <a name="resetStartInterval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartInterval"></a>

```java
public void resetStartInterval()
```

##### `resetStartPeriod` <a name="resetStartPeriod" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetStartPeriod"></a>

```java
public void resetStartPeriod()
```

##### `resetTest` <a name="resetTest" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTest"></a>

```java
public void resetTest()
```

##### `resetTimeout` <a name="resetTimeout" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.resetTimeout"></a>

```java
public void resetTimeout()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.intervalInput">intervalInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retriesInput">retriesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startIntervalInput">startIntervalInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriodInput">startPeriodInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.testInput">testInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeoutInput">timeoutInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.interval">interval</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retries">retries</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startInterval">startInterval</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriod">startPeriod</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.test">test</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeout">timeout</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `intervalInput`<sup>Optional</sup> <a name="intervalInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.intervalInput"></a>

```java
public java.lang.String getIntervalInput();
```

- *Type:* java.lang.String

---

##### `retriesInput`<sup>Optional</sup> <a name="retriesInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retriesInput"></a>

```java
public java.lang.Number getRetriesInput();
```

- *Type:* java.lang.Number

---

##### `startIntervalInput`<sup>Optional</sup> <a name="startIntervalInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startIntervalInput"></a>

```java
public java.lang.String getStartIntervalInput();
```

- *Type:* java.lang.String

---

##### `startPeriodInput`<sup>Optional</sup> <a name="startPeriodInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriodInput"></a>

```java
public java.lang.String getStartPeriodInput();
```

- *Type:* java.lang.String

---

##### `testInput`<sup>Optional</sup> <a name="testInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.testInput"></a>

```java
public java.util.List<java.lang.String> getTestInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `timeoutInput`<sup>Optional</sup> <a name="timeoutInput" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeoutInput"></a>

```java
public java.lang.String getTimeoutInput();
```

- *Type:* java.lang.String

---

##### `interval`<sup>Required</sup> <a name="interval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.interval"></a>

```java
public java.lang.String getInterval();
```

- *Type:* java.lang.String

---

##### `retries`<sup>Required</sup> <a name="retries" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.retries"></a>

```java
public java.lang.Number getRetries();
```

- *Type:* java.lang.Number

---

##### `startInterval`<sup>Required</sup> <a name="startInterval" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startInterval"></a>

```java
public java.lang.String getStartInterval();
```

- *Type:* java.lang.String

---

##### `startPeriod`<sup>Required</sup> <a name="startPeriod" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.startPeriod"></a>

```java
public java.lang.String getStartPeriod();
```

- *Type:* java.lang.String

---

##### `test`<sup>Required</sup> <a name="test" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.test"></a>

```java
public java.util.List<java.lang.String> getTest();
```

- *Type:* java.util.List<java.lang.String>

---

##### `timeout`<sup>Required</sup> <a name="timeout" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.timeout"></a>

```java
public java.lang.String getTimeout();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerHealthcheckOutputReference.property.internalValue"></a>

```java
public ContainerHealthcheck getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerHealthcheck">ContainerHealthcheck</a>

---


### ContainerHostList <a name="ContainerHostList" id="@cdktn/provider-docker.container.ContainerHostList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerHostList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerHostList;

new ContainerHostList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerHostList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerHostList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerHostList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerHostList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerHostList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerHostList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerHostList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerHostList.get"></a>

```java
public ContainerHostOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerHostList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerHostList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerHostList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerHostList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerHost> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>>

---


### ContainerHostOutputReference <a name="ContainerHostOutputReference" id="@cdktn/provider-docker.container.ContainerHostOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerHostOutputReference;

new ContainerHostOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerHostOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerHostOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerHostOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerHostOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerHostOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerHostOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerHostOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.hostInput">hostInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.ipInput">ipInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.host">host</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.ip">ip</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerHostOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `hostInput`<sup>Optional</sup> <a name="hostInput" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.hostInput"></a>

```java
public java.lang.String getHostInput();
```

- *Type:* java.lang.String

---

##### `ipInput`<sup>Optional</sup> <a name="ipInput" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.ipInput"></a>

```java
public java.lang.String getIpInput();
```

- *Type:* java.lang.String

---

##### `host`<sup>Required</sup> <a name="host" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.host"></a>

```java
public java.lang.String getHost();
```

- *Type:* java.lang.String

---

##### `ip`<sup>Required</sup> <a name="ip" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.ip"></a>

```java
public java.lang.String getIp();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerHostOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerHost getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerHost">ContainerHost</a>

---


### ContainerLabelsList <a name="ContainerLabelsList" id="@cdktn/provider-docker.container.ContainerLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerLabelsList;

new ContainerLabelsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerLabelsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerLabelsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerLabelsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerLabelsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerLabelsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerLabelsList.get"></a>

```java
public ContainerLabelsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerLabelsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerLabelsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerLabelsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerLabelsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerLabels> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>>

---


### ContainerLabelsOutputReference <a name="ContainerLabelsOutputReference" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerLabelsOutputReference;

new ContainerLabelsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.labelInput">labelInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.valueInput">valueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.label">label</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.value">value</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `labelInput`<sup>Optional</sup> <a name="labelInput" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.labelInput"></a>

```java
public java.lang.String getLabelInput();
```

- *Type:* java.lang.String

---

##### `valueInput`<sup>Optional</sup> <a name="valueInput" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.valueInput"></a>

```java
public java.lang.String getValueInput();
```

- *Type:* java.lang.String

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.label"></a>

```java
public java.lang.String getLabel();
```

- *Type:* java.lang.String

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.value"></a>

```java
public java.lang.String getValue();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerLabelsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerLabels getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerLabels">ContainerLabels</a>

---


### ContainerMountsBindOptionsOutputReference <a name="ContainerMountsBindOptionsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsBindOptionsOutputReference;

new ContainerMountsBindOptionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resetPropagation">resetPropagation</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetPropagation` <a name="resetPropagation" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.resetPropagation"></a>

```java
public void resetPropagation()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagationInput">propagationInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagation">propagation</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `propagationInput`<sup>Optional</sup> <a name="propagationInput" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagationInput"></a>

```java
public java.lang.String getPropagationInput();
```

- *Type:* java.lang.String

---

##### `propagation`<sup>Required</sup> <a name="propagation" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.propagation"></a>

```java
public java.lang.String getPropagation();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference.property.internalValue"></a>

```java
public ContainerMountsBindOptions getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

---


### ContainerMountsList <a name="ContainerMountsList" id="@cdktn/provider-docker.container.ContainerMountsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsList;

new ContainerMountsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerMountsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerMountsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerMountsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerMountsList.get"></a>

```java
public ContainerMountsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerMountsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerMounts> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>>

---


### ContainerMountsOutputReference <a name="ContainerMountsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsOutputReference;

new ContainerMountsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.putBindOptions">putBindOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.putTmpfsOptions">putTmpfsOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.putVolumeOptions">putVolumeOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetBindOptions">resetBindOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetReadOnly">resetReadOnly</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetSource">resetSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetTmpfsOptions">resetTmpfsOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.resetVolumeOptions">resetVolumeOptions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putBindOptions` <a name="putBindOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putBindOptions"></a>

```java
public void putBindOptions(ContainerMountsBindOptions value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putBindOptions.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

---

##### `putTmpfsOptions` <a name="putTmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putTmpfsOptions"></a>

```java
public void putTmpfsOptions(ContainerMountsTmpfsOptions value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putTmpfsOptions.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

---

##### `putVolumeOptions` <a name="putVolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putVolumeOptions"></a>

```java
public void putVolumeOptions(ContainerMountsVolumeOptions value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.putVolumeOptions.parameter.value"></a>

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

---

##### `resetBindOptions` <a name="resetBindOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetBindOptions"></a>

```java
public void resetBindOptions()
```

##### `resetReadOnly` <a name="resetReadOnly" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetReadOnly"></a>

```java
public void resetReadOnly()
```

##### `resetSource` <a name="resetSource" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetSource"></a>

```java
public void resetSource()
```

##### `resetTmpfsOptions` <a name="resetTmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetTmpfsOptions"></a>

```java
public void resetTmpfsOptions()
```

##### `resetVolumeOptions` <a name="resetVolumeOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.resetVolumeOptions"></a>

```java
public void resetVolumeOptions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptions">bindOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference">ContainerMountsBindOptionsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptions">tmpfsOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference">ContainerMountsTmpfsOptionsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptions">volumeOptions</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference">ContainerMountsVolumeOptionsOutputReference</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptionsInput">bindOptionsInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnlyInput">readOnlyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.sourceInput">sourceInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.targetInput">targetInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptionsInput">tmpfsOptionsInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptionsInput">volumeOptionsInput</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.source">source</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.target">target</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `bindOptions`<sup>Required</sup> <a name="bindOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptions"></a>

```java
public ContainerMountsBindOptionsOutputReference getBindOptions();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptionsOutputReference">ContainerMountsBindOptionsOutputReference</a>

---

##### `tmpfsOptions`<sup>Required</sup> <a name="tmpfsOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptions"></a>

```java
public ContainerMountsTmpfsOptionsOutputReference getTmpfsOptions();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference">ContainerMountsTmpfsOptionsOutputReference</a>

---

##### `volumeOptions`<sup>Required</sup> <a name="volumeOptions" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptions"></a>

```java
public ContainerMountsVolumeOptionsOutputReference getVolumeOptions();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference">ContainerMountsVolumeOptionsOutputReference</a>

---

##### `bindOptionsInput`<sup>Optional</sup> <a name="bindOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.bindOptionsInput"></a>

```java
public ContainerMountsBindOptions getBindOptionsInput();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsBindOptions">ContainerMountsBindOptions</a>

---

##### `readOnlyInput`<sup>Optional</sup> <a name="readOnlyInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnlyInput"></a>

```java
public java.lang.Boolean|IResolvable getReadOnlyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `sourceInput`<sup>Optional</sup> <a name="sourceInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.sourceInput"></a>

```java
public java.lang.String getSourceInput();
```

- *Type:* java.lang.String

---

##### `targetInput`<sup>Optional</sup> <a name="targetInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.targetInput"></a>

```java
public java.lang.String getTargetInput();
```

- *Type:* java.lang.String

---

##### `tmpfsOptionsInput`<sup>Optional</sup> <a name="tmpfsOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.tmpfsOptionsInput"></a>

```java
public ContainerMountsTmpfsOptions getTmpfsOptionsInput();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `volumeOptionsInput`<sup>Optional</sup> <a name="volumeOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.volumeOptionsInput"></a>

```java
public ContainerMountsVolumeOptions getVolumeOptionsInput();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

---

##### `readOnly`<sup>Required</sup> <a name="readOnly" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.readOnly"></a>

```java
public java.lang.Boolean|IResolvable getReadOnly();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `source`<sup>Required</sup> <a name="source" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.source"></a>

```java
public java.lang.String getSource();
```

- *Type:* java.lang.String

---

##### `target`<sup>Required</sup> <a name="target" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.target"></a>

```java
public java.lang.String getTarget();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerMounts getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMounts">ContainerMounts</a>

---


### ContainerMountsTmpfsOptionsOutputReference <a name="ContainerMountsTmpfsOptionsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsTmpfsOptionsOutputReference;

new ContainerMountsTmpfsOptionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetMode">resetMode</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetSizeBytes">resetSizeBytes</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetMode` <a name="resetMode" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetMode"></a>

```java
public void resetMode()
```

##### `resetSizeBytes` <a name="resetSizeBytes" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.resetSizeBytes"></a>

```java
public void resetSizeBytes()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.modeInput">modeInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytesInput">sizeBytesInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.mode">mode</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytes">sizeBytes</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `modeInput`<sup>Optional</sup> <a name="modeInput" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.modeInput"></a>

```java
public java.lang.Number getModeInput();
```

- *Type:* java.lang.Number

---

##### `sizeBytesInput`<sup>Optional</sup> <a name="sizeBytesInput" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytesInput"></a>

```java
public java.lang.Number getSizeBytesInput();
```

- *Type:* java.lang.Number

---

##### `mode`<sup>Required</sup> <a name="mode" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.mode"></a>

```java
public java.lang.Number getMode();
```

- *Type:* java.lang.Number

---

##### `sizeBytes`<sup>Required</sup> <a name="sizeBytes" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.sizeBytes"></a>

```java
public java.lang.Number getSizeBytes();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsTmpfsOptionsOutputReference.property.internalValue"></a>

```java
public ContainerMountsTmpfsOptions getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsTmpfsOptions">ContainerMountsTmpfsOptions</a>

---


### ContainerMountsVolumeOptionsLabelsList <a name="ContainerMountsVolumeOptionsLabelsList" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsVolumeOptionsLabelsList;

new ContainerMountsVolumeOptionsLabelsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.get"></a>

```java
public ContainerMountsVolumeOptionsLabelsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerMountsVolumeOptionsLabels> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>>

---


### ContainerMountsVolumeOptionsLabelsOutputReference <a name="ContainerMountsVolumeOptionsLabelsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsVolumeOptionsLabelsOutputReference;

new ContainerMountsVolumeOptionsLabelsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.labelInput">labelInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.valueInput">valueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.label">label</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.value">value</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `labelInput`<sup>Optional</sup> <a name="labelInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.labelInput"></a>

```java
public java.lang.String getLabelInput();
```

- *Type:* java.lang.String

---

##### `valueInput`<sup>Optional</sup> <a name="valueInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.valueInput"></a>

```java
public java.lang.String getValueInput();
```

- *Type:* java.lang.String

---

##### `label`<sup>Required</sup> <a name="label" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.label"></a>

```java
public java.lang.String getLabel();
```

- *Type:* java.lang.String

---

##### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.value"></a>

```java
public java.lang.String getValue();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerMountsVolumeOptionsLabels getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>

---


### ContainerMountsVolumeOptionsOutputReference <a name="ContainerMountsVolumeOptionsOutputReference" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerMountsVolumeOptionsOutputReference;

new ContainerMountsVolumeOptionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.putLabels">putLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverName">resetDriverName</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverOptions">resetDriverOptions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetLabels">resetLabels</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetNoCopy">resetNoCopy</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetSubpath">resetSubpath</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putLabels` <a name="putLabels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.putLabels"></a>

```java
public void putLabels(IResolvable|java.util.List<ContainerMountsVolumeOptionsLabels> value)
```

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.putLabels.parameter.value"></a>

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>>

---

##### `resetDriverName` <a name="resetDriverName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverName"></a>

```java
public void resetDriverName()
```

##### `resetDriverOptions` <a name="resetDriverOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetDriverOptions"></a>

```java
public void resetDriverOptions()
```

##### `resetLabels` <a name="resetLabels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetLabels"></a>

```java
public void resetLabels()
```

##### `resetNoCopy` <a name="resetNoCopy" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetNoCopy"></a>

```java
public void resetNoCopy()
```

##### `resetSubpath` <a name="resetSubpath" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.resetSubpath"></a>

```java
public void resetSubpath()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labels">labels</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList">ContainerMountsVolumeOptionsLabelsList</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverNameInput">driverNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptionsInput">driverOptionsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labelsInput">labelsInput</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopyInput">noCopyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpathInput">subpathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverName">driverName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptions">driverOptions</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopy">noCopy</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpath">subpath</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `labels`<sup>Required</sup> <a name="labels" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labels"></a>

```java
public ContainerMountsVolumeOptionsLabelsList getLabels();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabelsList">ContainerMountsVolumeOptionsLabelsList</a>

---

##### `driverNameInput`<sup>Optional</sup> <a name="driverNameInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverNameInput"></a>

```java
public java.lang.String getDriverNameInput();
```

- *Type:* java.lang.String

---

##### `driverOptionsInput`<sup>Optional</sup> <a name="driverOptionsInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptionsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDriverOptionsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `labelsInput`<sup>Optional</sup> <a name="labelsInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.labelsInput"></a>

```java
public IResolvable|java.util.List<ContainerMountsVolumeOptionsLabels> getLabelsInput();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptionsLabels">ContainerMountsVolumeOptionsLabels</a>>

---

##### `noCopyInput`<sup>Optional</sup> <a name="noCopyInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopyInput"></a>

```java
public java.lang.Boolean|IResolvable getNoCopyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `subpathInput`<sup>Optional</sup> <a name="subpathInput" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpathInput"></a>

```java
public java.lang.String getSubpathInput();
```

- *Type:* java.lang.String

---

##### `driverName`<sup>Required</sup> <a name="driverName" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverName"></a>

```java
public java.lang.String getDriverName();
```

- *Type:* java.lang.String

---

##### `driverOptions`<sup>Required</sup> <a name="driverOptions" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.driverOptions"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDriverOptions();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `noCopy`<sup>Required</sup> <a name="noCopy" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.noCopy"></a>

```java
public java.lang.Boolean|IResolvable getNoCopy();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `subpath`<sup>Required</sup> <a name="subpath" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.subpath"></a>

```java
public java.lang.String getSubpath();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerMountsVolumeOptionsOutputReference.property.internalValue"></a>

```java
public ContainerMountsVolumeOptions getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerMountsVolumeOptions">ContainerMountsVolumeOptions</a>

---


### ContainerNetworkDataList <a name="ContainerNetworkDataList" id="@cdktn/provider-docker.container.ContainerNetworkDataList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerNetworkDataList;

new ContainerNetworkDataList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerNetworkDataList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerNetworkDataList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerNetworkDataList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerNetworkDataList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerNetworkDataList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerNetworkDataList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerNetworkDataList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerNetworkDataList.get"></a>

```java
public ContainerNetworkDataOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerNetworkDataList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerNetworkDataList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerNetworkDataList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---


### ContainerNetworkDataOutputReference <a name="ContainerNetworkDataOutputReference" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerNetworkDataOutputReference;

new ContainerNetworkDataOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.gateway">gateway</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6Address">globalIpv6Address</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6PrefixLength">globalIpv6PrefixLength</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipAddress">ipAddress</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipPrefixLength">ipPrefixLength</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipv6Gateway">ipv6Gateway</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.macAddress">macAddress</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.networkName">networkName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.internalValue">internalValue</a></code> | <code><a href="#@cdktn/provider-docker.container.ContainerNetworkData">ContainerNetworkData</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `gateway`<sup>Required</sup> <a name="gateway" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.gateway"></a>

```java
public java.lang.String getGateway();
```

- *Type:* java.lang.String

---

##### `globalIpv6Address`<sup>Required</sup> <a name="globalIpv6Address" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6Address"></a>

```java
public java.lang.String getGlobalIpv6Address();
```

- *Type:* java.lang.String

---

##### `globalIpv6PrefixLength`<sup>Required</sup> <a name="globalIpv6PrefixLength" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.globalIpv6PrefixLength"></a>

```java
public java.lang.Number getGlobalIpv6PrefixLength();
```

- *Type:* java.lang.Number

---

##### `ipAddress`<sup>Required</sup> <a name="ipAddress" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipAddress"></a>

```java
public java.lang.String getIpAddress();
```

- *Type:* java.lang.String

---

##### `ipPrefixLength`<sup>Required</sup> <a name="ipPrefixLength" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipPrefixLength"></a>

```java
public java.lang.Number getIpPrefixLength();
```

- *Type:* java.lang.Number

---

##### `ipv6Gateway`<sup>Required</sup> <a name="ipv6Gateway" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.ipv6Gateway"></a>

```java
public java.lang.String getIpv6Gateway();
```

- *Type:* java.lang.String

---

##### `macAddress`<sup>Required</sup> <a name="macAddress" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.macAddress"></a>

```java
public java.lang.String getMacAddress();
```

- *Type:* java.lang.String

---

##### `networkName`<sup>Required</sup> <a name="networkName" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.networkName"></a>

```java
public java.lang.String getNetworkName();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerNetworkDataOutputReference.property.internalValue"></a>

```java
public ContainerNetworkData getInternalValue();
```

- *Type:* <a href="#@cdktn/provider-docker.container.ContainerNetworkData">ContainerNetworkData</a>

---


### ContainerNetworksAdvancedList <a name="ContainerNetworksAdvancedList" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerNetworksAdvancedList;

new ContainerNetworksAdvancedList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.get"></a>

```java
public ContainerNetworksAdvancedOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerNetworksAdvanced> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>>

---


### ContainerNetworksAdvancedOutputReference <a name="ContainerNetworksAdvancedOutputReference" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerNetworksAdvancedOutputReference;

new ContainerNetworksAdvancedOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetAliases">resetAliases</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetDriverOpts">resetDriverOpts</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetGwPriority">resetGwPriority</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv4Address">resetIpv4Address</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv6Address">resetIpv6Address</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetLinkLocalIps">resetLinkLocalIps</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetMacAddress">resetMacAddress</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetAliases` <a name="resetAliases" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetAliases"></a>

```java
public void resetAliases()
```

##### `resetDriverOpts` <a name="resetDriverOpts" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetDriverOpts"></a>

```java
public void resetDriverOpts()
```

##### `resetGwPriority` <a name="resetGwPriority" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetGwPriority"></a>

```java
public void resetGwPriority()
```

##### `resetIpv4Address` <a name="resetIpv4Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv4Address"></a>

```java
public void resetIpv4Address()
```

##### `resetIpv6Address` <a name="resetIpv6Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetIpv6Address"></a>

```java
public void resetIpv6Address()
```

##### `resetLinkLocalIps` <a name="resetLinkLocalIps" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetLinkLocalIps"></a>

```java
public void resetLinkLocalIps()
```

##### `resetMacAddress` <a name="resetMacAddress" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.resetMacAddress"></a>

```java
public void resetMacAddress()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliasesInput">aliasesInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOptsInput">driverOptsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriorityInput">gwPriorityInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4AddressInput">ipv4AddressInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6AddressInput">ipv6AddressInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIpsInput">linkLocalIpsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddressInput">macAddressInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliases">aliases</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOpts">driverOpts</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriority">gwPriority</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4Address">ipv4Address</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6Address">ipv6Address</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIps">linkLocalIps</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddress">macAddress</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `aliasesInput`<sup>Optional</sup> <a name="aliasesInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliasesInput"></a>

```java
public java.util.List<java.lang.String> getAliasesInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `driverOptsInput`<sup>Optional</sup> <a name="driverOptsInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOptsInput"></a>

```java
public java.util.List<java.lang.String> getDriverOptsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `gwPriorityInput`<sup>Optional</sup> <a name="gwPriorityInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriorityInput"></a>

```java
public java.lang.Number getGwPriorityInput();
```

- *Type:* java.lang.Number

---

##### `ipv4AddressInput`<sup>Optional</sup> <a name="ipv4AddressInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4AddressInput"></a>

```java
public java.lang.String getIpv4AddressInput();
```

- *Type:* java.lang.String

---

##### `ipv6AddressInput`<sup>Optional</sup> <a name="ipv6AddressInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6AddressInput"></a>

```java
public java.lang.String getIpv6AddressInput();
```

- *Type:* java.lang.String

---

##### `linkLocalIpsInput`<sup>Optional</sup> <a name="linkLocalIpsInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIpsInput"></a>

```java
public java.util.List<java.lang.String> getLinkLocalIpsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `macAddressInput`<sup>Optional</sup> <a name="macAddressInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddressInput"></a>

```java
public java.lang.String getMacAddressInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `aliases`<sup>Required</sup> <a name="aliases" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.aliases"></a>

```java
public java.util.List<java.lang.String> getAliases();
```

- *Type:* java.util.List<java.lang.String>

---

##### `driverOpts`<sup>Required</sup> <a name="driverOpts" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.driverOpts"></a>

```java
public java.util.List<java.lang.String> getDriverOpts();
```

- *Type:* java.util.List<java.lang.String>

---

##### `gwPriority`<sup>Required</sup> <a name="gwPriority" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.gwPriority"></a>

```java
public java.lang.Number getGwPriority();
```

- *Type:* java.lang.Number

---

##### `ipv4Address`<sup>Required</sup> <a name="ipv4Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv4Address"></a>

```java
public java.lang.String getIpv4Address();
```

- *Type:* java.lang.String

---

##### `ipv6Address`<sup>Required</sup> <a name="ipv6Address" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.ipv6Address"></a>

```java
public java.lang.String getIpv6Address();
```

- *Type:* java.lang.String

---

##### `linkLocalIps`<sup>Required</sup> <a name="linkLocalIps" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.linkLocalIps"></a>

```java
public java.util.List<java.lang.String> getLinkLocalIps();
```

- *Type:* java.util.List<java.lang.String>

---

##### `macAddress`<sup>Required</sup> <a name="macAddress" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.macAddress"></a>

```java
public java.lang.String getMacAddress();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerNetworksAdvancedOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerNetworksAdvanced getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerNetworksAdvanced">ContainerNetworksAdvanced</a>

---


### ContainerPortsList <a name="ContainerPortsList" id="@cdktn/provider-docker.container.ContainerPortsList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerPortsList;

new ContainerPortsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerPortsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerPortsList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerPortsList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerPortsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerPortsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerPortsList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerPortsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerPortsList.get"></a>

```java
public ContainerPortsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerPortsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerPortsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerPortsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerPortsList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerPorts> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>>

---


### ContainerPortsOutputReference <a name="ContainerPortsOutputReference" id="@cdktn/provider-docker.container.ContainerPortsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerPortsOutputReference;

new ContainerPortsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resetExternal">resetExternal</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resetIp">resetIp</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.resetProtocol">resetProtocol</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExternal` <a name="resetExternal" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resetExternal"></a>

```java
public void resetExternal()
```

##### `resetIp` <a name="resetIp" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resetIp"></a>

```java
public void resetIp()
```

##### `resetProtocol` <a name="resetProtocol" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.resetProtocol"></a>

```java
public void resetProtocol()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.externalInput">externalInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalInput">internalInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ipInput">ipInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocolInput">protocolInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.external">external</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internal">internal</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ip">ip</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocol">protocol</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `externalInput`<sup>Optional</sup> <a name="externalInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.externalInput"></a>

```java
public java.lang.Number getExternalInput();
```

- *Type:* java.lang.Number

---

##### `internalInput`<sup>Optional</sup> <a name="internalInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalInput"></a>

```java
public java.lang.Number getInternalInput();
```

- *Type:* java.lang.Number

---

##### `ipInput`<sup>Optional</sup> <a name="ipInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ipInput"></a>

```java
public java.lang.String getIpInput();
```

- *Type:* java.lang.String

---

##### `protocolInput`<sup>Optional</sup> <a name="protocolInput" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocolInput"></a>

```java
public java.lang.String getProtocolInput();
```

- *Type:* java.lang.String

---

##### `external`<sup>Required</sup> <a name="external" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.external"></a>

```java
public java.lang.Number getExternal();
```

- *Type:* java.lang.Number

---

##### `internal`<sup>Required</sup> <a name="internal" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internal"></a>

```java
public java.lang.Number getInternal();
```

- *Type:* java.lang.Number

---

##### `ip`<sup>Required</sup> <a name="ip" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.ip"></a>

```java
public java.lang.String getIp();
```

- *Type:* java.lang.String

---

##### `protocol`<sup>Required</sup> <a name="protocol" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.protocol"></a>

```java
public java.lang.String getProtocol();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerPortsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerPorts getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerPorts">ContainerPorts</a>

---


### ContainerTimeoutsOutputReference <a name="ContainerTimeoutsOutputReference" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerTimeoutsOutputReference;

new ContainerTimeoutsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetCreate">resetCreate</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetDelete">resetDelete</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetUpdate">resetUpdate</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetCreate` <a name="resetCreate" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetCreate"></a>

```java
public void resetCreate()
```

##### `resetDelete` <a name="resetDelete" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetDelete"></a>

```java
public void resetDelete()
```

##### `resetUpdate` <a name="resetUpdate" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.resetUpdate"></a>

```java
public void resetUpdate()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.createInput">createInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.deleteInput">deleteInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.updateInput">updateInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.create">create</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.delete">delete</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.update">update</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `createInput`<sup>Optional</sup> <a name="createInput" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.createInput"></a>

```java
public java.lang.String getCreateInput();
```

- *Type:* java.lang.String

---

##### `deleteInput`<sup>Optional</sup> <a name="deleteInput" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.deleteInput"></a>

```java
public java.lang.String getDeleteInput();
```

- *Type:* java.lang.String

---

##### `updateInput`<sup>Optional</sup> <a name="updateInput" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.updateInput"></a>

```java
public java.lang.String getUpdateInput();
```

- *Type:* java.lang.String

---

##### `create`<sup>Required</sup> <a name="create" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.create"></a>

```java
public java.lang.String getCreate();
```

- *Type:* java.lang.String

---

##### `delete`<sup>Required</sup> <a name="delete" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.delete"></a>

```java
public java.lang.String getDelete();
```

- *Type:* java.lang.String

---

##### `update`<sup>Required</sup> <a name="update" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.update"></a>

```java
public java.lang.String getUpdate();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerTimeoutsOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerTimeouts getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerTimeouts">ContainerTimeouts</a>

---


### ContainerUlimitList <a name="ContainerUlimitList" id="@cdktn/provider-docker.container.ContainerUlimitList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerUlimitList;

new ContainerUlimitList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerUlimitList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerUlimitList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerUlimitList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerUlimitList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerUlimitList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerUlimitList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerUlimitList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerUlimitList.get"></a>

```java
public ContainerUlimitOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerUlimitList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerUlimitList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerUlimitList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerUlimitList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerUlimit> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>>

---


### ContainerUlimitOutputReference <a name="ContainerUlimitOutputReference" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerUlimitOutputReference;

new ContainerUlimitOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hardInput">hardInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.softInput">softInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hard">hard</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.soft">soft</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `hardInput`<sup>Optional</sup> <a name="hardInput" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hardInput"></a>

```java
public java.lang.Number getHardInput();
```

- *Type:* java.lang.Number

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `softInput`<sup>Optional</sup> <a name="softInput" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.softInput"></a>

```java
public java.lang.Number getSoftInput();
```

- *Type:* java.lang.Number

---

##### `hard`<sup>Required</sup> <a name="hard" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.hard"></a>

```java
public java.lang.Number getHard();
```

- *Type:* java.lang.Number

---

##### `name`<sup>Required</sup> <a name="name" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `soft`<sup>Required</sup> <a name="soft" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.soft"></a>

```java
public java.lang.Number getSoft();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerUlimitOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerUlimit getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUlimit">ContainerUlimit</a>

---


### ContainerUploadList <a name="ContainerUploadList" id="@cdktn/provider-docker.container.ContainerUploadList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerUploadList;

new ContainerUploadList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerUploadList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerUploadList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerUploadList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerUploadList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerUploadList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerUploadList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerUploadList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerUploadList.get"></a>

```java
public ContainerUploadOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerUploadList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerUploadList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerUploadList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerUploadList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerUpload> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>>

---


### ContainerUploadOutputReference <a name="ContainerUploadOutputReference" id="@cdktn/provider-docker.container.ContainerUploadOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerUploadOutputReference;

new ContainerUploadOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContent">resetContent</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContentBase64">resetContentBase64</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetExecutable">resetExecutable</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetGroup">resetGroup</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetOwner">resetOwner</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetPermissions">resetPermissions</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSource">resetSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSourceHash">resetSourceHash</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetContent` <a name="resetContent" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContent"></a>

```java
public void resetContent()
```

##### `resetContentBase64` <a name="resetContentBase64" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetContentBase64"></a>

```java
public void resetContentBase64()
```

##### `resetExecutable` <a name="resetExecutable" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetExecutable"></a>

```java
public void resetExecutable()
```

##### `resetGroup` <a name="resetGroup" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetGroup"></a>

```java
public void resetGroup()
```

##### `resetOwner` <a name="resetOwner" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetOwner"></a>

```java
public void resetOwner()
```

##### `resetPermissions` <a name="resetPermissions" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetPermissions"></a>

```java
public void resetPermissions()
```

##### `resetSource` <a name="resetSource" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSource"></a>

```java
public void resetSource()
```

##### `resetSourceHash` <a name="resetSourceHash" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.resetSourceHash"></a>

```java
public void resetSourceHash()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64Input">contentBase64Input</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentInput">contentInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executableInput">executableInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fileInput">fileInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.groupInput">groupInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.ownerInput">ownerInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissionsInput">permissionsInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHashInput">sourceHashInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceInput">sourceInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.content">content</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64">contentBase64</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executable">executable</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.file">file</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.group">group</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.owner">owner</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissions">permissions</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.source">source</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHash">sourceHash</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerUploadOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `contentBase64Input`<sup>Optional</sup> <a name="contentBase64Input" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64Input"></a>

```java
public java.lang.String getContentBase64Input();
```

- *Type:* java.lang.String

---

##### `contentInput`<sup>Optional</sup> <a name="contentInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentInput"></a>

```java
public java.lang.String getContentInput();
```

- *Type:* java.lang.String

---

##### `executableInput`<sup>Optional</sup> <a name="executableInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executableInput"></a>

```java
public java.lang.Boolean|IResolvable getExecutableInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `fileInput`<sup>Optional</sup> <a name="fileInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.fileInput"></a>

```java
public java.lang.String getFileInput();
```

- *Type:* java.lang.String

---

##### `groupInput`<sup>Optional</sup> <a name="groupInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.groupInput"></a>

```java
public java.lang.String getGroupInput();
```

- *Type:* java.lang.String

---

##### `ownerInput`<sup>Optional</sup> <a name="ownerInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.ownerInput"></a>

```java
public java.lang.String getOwnerInput();
```

- *Type:* java.lang.String

---

##### `permissionsInput`<sup>Optional</sup> <a name="permissionsInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissionsInput"></a>

```java
public java.lang.String getPermissionsInput();
```

- *Type:* java.lang.String

---

##### `sourceHashInput`<sup>Optional</sup> <a name="sourceHashInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHashInput"></a>

```java
public java.lang.String getSourceHashInput();
```

- *Type:* java.lang.String

---

##### `sourceInput`<sup>Optional</sup> <a name="sourceInput" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceInput"></a>

```java
public java.lang.String getSourceInput();
```

- *Type:* java.lang.String

---

##### `content`<sup>Required</sup> <a name="content" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.content"></a>

```java
public java.lang.String getContent();
```

- *Type:* java.lang.String

---

##### `contentBase64`<sup>Required</sup> <a name="contentBase64" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.contentBase64"></a>

```java
public java.lang.String getContentBase64();
```

- *Type:* java.lang.String

---

##### `executable`<sup>Required</sup> <a name="executable" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.executable"></a>

```java
public java.lang.Boolean|IResolvable getExecutable();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `file`<sup>Required</sup> <a name="file" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.file"></a>

```java
public java.lang.String getFile();
```

- *Type:* java.lang.String

---

##### `group`<sup>Required</sup> <a name="group" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.group"></a>

```java
public java.lang.String getGroup();
```

- *Type:* java.lang.String

---

##### `owner`<sup>Required</sup> <a name="owner" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.owner"></a>

```java
public java.lang.String getOwner();
```

- *Type:* java.lang.String

---

##### `permissions`<sup>Required</sup> <a name="permissions" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.permissions"></a>

```java
public java.lang.String getPermissions();
```

- *Type:* java.lang.String

---

##### `source`<sup>Required</sup> <a name="source" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.source"></a>

```java
public java.lang.String getSource();
```

- *Type:* java.lang.String

---

##### `sourceHash`<sup>Required</sup> <a name="sourceHash" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.sourceHash"></a>

```java
public java.lang.String getSourceHash();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerUploadOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerUpload getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerUpload">ContainerUpload</a>

---


### ContainerVolumesList <a name="ContainerVolumesList" id="@cdktn/provider-docker.container.ContainerVolumesList"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerVolumesList;

new ContainerVolumesList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="@cdktn/provider-docker.container.ContainerVolumesList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.allWithMapKey">allWithMapKey</a></code> | Creating an iterator for this complex list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.get">get</a></code> | *No description.* |

---

##### `allWithMapKey` <a name="allWithMapKey" id="@cdktn/provider-docker.container.ContainerVolumesList.allWithMapKey"></a>

```java
public DynamicListTerraformIterator allWithMapKey(java.lang.String mapKeyAttributeName)
```

Creating an iterator for this complex list.

The list will be converted into a map with the mapKeyAttributeName as the key.

###### `mapKeyAttributeName`<sup>Required</sup> <a name="mapKeyAttributeName" id="@cdktn/provider-docker.container.ContainerVolumesList.allWithMapKey.parameter.mapKeyAttributeName"></a>

- *Type:* java.lang.String

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerVolumesList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerVolumesList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerVolumesList.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerVolumesList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="@cdktn/provider-docker.container.ContainerVolumesList.get"></a>

```java
public ContainerVolumesOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="@cdktn/provider-docker.container.ContainerVolumesList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesList.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerVolumesList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerVolumesList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerVolumesList.property.internalValue"></a>

```java
public IResolvable|java.util.List<ContainerVolumes> getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|java.util.List<<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>>

---


### ContainerVolumesOutputReference <a name="ContainerVolumesOutputReference" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference"></a>

#### Initializers <a name="Initializers" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer"></a>

```java
import io.cdktn.providers.docker.container.ContainerVolumesOutputReference;

new ContainerVolumesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>io.cdktn.cdktn.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* io.cdktn.cdktn.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetContainerPath">resetContainerPath</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetFromContainer">resetFromContainer</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetHostPath">resetHostPath</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetReadOnly">resetReadOnly</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetSelinuxRelabel">resetSelinuxRelabel</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetVolumeName">resetVolumeName</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resolve.parameter._context"></a>

- *Type:* io.cdktn.cdktn.IResolveContext

---

##### `toString` <a name="toString" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetContainerPath` <a name="resetContainerPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetContainerPath"></a>

```java
public void resetContainerPath()
```

##### `resetFromContainer` <a name="resetFromContainer" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetFromContainer"></a>

```java
public void resetFromContainer()
```

##### `resetHostPath` <a name="resetHostPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetHostPath"></a>

```java
public void resetHostPath()
```

##### `resetReadOnly` <a name="resetReadOnly" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetReadOnly"></a>

```java
public void resetReadOnly()
```

##### `resetSelinuxRelabel` <a name="resetSelinuxRelabel" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetSelinuxRelabel"></a>

```java
public void resetSelinuxRelabel()
```

##### `resetVolumeName` <a name="resetVolumeName" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.resetVolumeName"></a>

```java
public void resetVolumeName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPathInput">containerPathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainerInput">fromContainerInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPathInput">hostPathInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnlyInput">readOnlyInput</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabelInput">selinuxRelabelInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeNameInput">volumeNameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPath">containerPath</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainer">fromContainer</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPath">hostPath</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnly">readOnly</a></code> | <code>java.lang.Boolean\|io.cdktn.cdktn.IResolvable</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabel">selinuxRelabel</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeName">volumeName</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.internalValue">internalValue</a></code> | <code>io.cdktn.cdktn.IResolvable\|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `containerPathInput`<sup>Optional</sup> <a name="containerPathInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPathInput"></a>

```java
public java.lang.String getContainerPathInput();
```

- *Type:* java.lang.String

---

##### `fromContainerInput`<sup>Optional</sup> <a name="fromContainerInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainerInput"></a>

```java
public java.lang.String getFromContainerInput();
```

- *Type:* java.lang.String

---

##### `hostPathInput`<sup>Optional</sup> <a name="hostPathInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPathInput"></a>

```java
public java.lang.String getHostPathInput();
```

- *Type:* java.lang.String

---

##### `readOnlyInput`<sup>Optional</sup> <a name="readOnlyInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnlyInput"></a>

```java
public java.lang.Boolean|IResolvable getReadOnlyInput();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `selinuxRelabelInput`<sup>Optional</sup> <a name="selinuxRelabelInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabelInput"></a>

```java
public java.lang.String getSelinuxRelabelInput();
```

- *Type:* java.lang.String

---

##### `volumeNameInput`<sup>Optional</sup> <a name="volumeNameInput" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeNameInput"></a>

```java
public java.lang.String getVolumeNameInput();
```

- *Type:* java.lang.String

---

##### `containerPath`<sup>Required</sup> <a name="containerPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.containerPath"></a>

```java
public java.lang.String getContainerPath();
```

- *Type:* java.lang.String

---

##### `fromContainer`<sup>Required</sup> <a name="fromContainer" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.fromContainer"></a>

```java
public java.lang.String getFromContainer();
```

- *Type:* java.lang.String

---

##### `hostPath`<sup>Required</sup> <a name="hostPath" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.hostPath"></a>

```java
public java.lang.String getHostPath();
```

- *Type:* java.lang.String

---

##### `readOnly`<sup>Required</sup> <a name="readOnly" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.readOnly"></a>

```java
public java.lang.Boolean|IResolvable getReadOnly();
```

- *Type:* java.lang.Boolean|io.cdktn.cdktn.IResolvable

---

##### `selinuxRelabel`<sup>Required</sup> <a name="selinuxRelabel" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.selinuxRelabel"></a>

```java
public java.lang.String getSelinuxRelabel();
```

- *Type:* java.lang.String

---

##### `volumeName`<sup>Required</sup> <a name="volumeName" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.volumeName"></a>

```java
public java.lang.String getVolumeName();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="@cdktn/provider-docker.container.ContainerVolumesOutputReference.property.internalValue"></a>

```java
public IResolvable|ContainerVolumes getInternalValue();
```

- *Type:* io.cdktn.cdktn.IResolvable|<a href="#@cdktn/provider-docker.container.ContainerVolumes">ContainerVolumes</a>

---



