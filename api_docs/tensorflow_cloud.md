description: Core module in tensorflow_cloud.

<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tensorflow_cloud" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="COMMON_MACHINE_CONFIGS"/>
<meta itemprop="property" content="__version__"/>
</div>

# Module: tensorflow_cloud

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api nocontent" align="left">
<td>
  <a target="_blank" href="https://github.com/tensorflow/examples/blob/master/__init__.py">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td>
</table>



Core module in tensorflow_cloud.



## Classes

[`class AcceleratorType`](./tensorflow_cloud/AcceleratorType.md): Types of accelerators.

[`class CloudOracle`](./tensorflow_cloud/CloudOracle.md): KerasTuner Oracle interface for CAIP Optimizer Service backend.

[`class CloudTuner`](./tensorflow_cloud/CloudTuner.md): KerasTuner interface implementation backed by CAIP Optimizer Service.

[`class DockerConfig`](./tensorflow_cloud/DockerConfig.md): Represents Docker-related configuration for the `run` API.

[`class MachineConfig`](./tensorflow_cloud/MachineConfig.md): Represents the configuration or type of machine to be used.

## Functions

[`remote(...)`](./tensorflow_cloud/remote.md): True when code is run in a remote cloud environment by TF Cloud.

[`run(...)`](./tensorflow_cloud/run.md): Runs your Tensorflow code in Google Cloud Platform.

[`run_cloudtuner(...)`](./tensorflow_cloud/run_cloudtuner.md): A wrapper for tfc.run that allows for running concurrent CloudTuner jobs.



<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Other Members</h2></th></tr>

<tr>
<td>
COMMON_MACHINE_CONFIGS<a id="COMMON_MACHINE_CONFIGS"></a>
</td>
<td>
```
{
 'CPU': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c54469dc0>,
 'K80_1X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c5455c460>,
 'K80_4X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c5455c520>,
 'K80_8X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9520>,
 'P100_1X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9580>,
 'P100_4X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd95e0>,
 'P4_1X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9640>,
 'P4_4X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd96a0>,
 'T4_1X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd97c0>,
 'T4_4X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9820>,
 'TPU': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9880>,
 'V100_1X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9700>,
 'V100_4X': <tensorflow_cloud.core.machine_config.MachineConfig object at 0x7f7c53fd9760>
}
```
</td>
</tr><tr>
<td>
__version__<a id="__version__"></a>
</td>
<td>
`'0.1.13'`
</td>
</tr>
</table>

