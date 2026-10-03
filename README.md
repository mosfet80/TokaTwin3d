# TokaTwin3d Workbench

This workbench was ..


## Troubleshooting

When encountering errors please make sure that the workbench is up-to-date (Addon Manager->Tokatwin3d workbench Workbench->Update).
To make sure you are actually running what you intend to run and that the same workbench version is installed on the python and the FreeCAD side, run

```python
import freecad.toka_twin3d_workbench
freecad.toka_twin3d_workbench.versionInfo()
```

in the FreeCAD python shell and

```python
import toka_twin3d_workbench
toka_twin3d_workbench.versionInfo()
```

in your regular python shell of choice.

Make sure that the workbench versions seen by FreeCAD and by python match and that all the displayed versions and paths match your expectations.
