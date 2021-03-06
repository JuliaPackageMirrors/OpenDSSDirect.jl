
<a id='opendssdirect-documentation-outline'></a>
# OpenDSSDirect Documentation Outline


<a id='package-manual'></a>
## Package Manual

- [OpenDSSDirect](introduction.md#opendssdirect)
    - [Installation](introduction.md#installation)
    - [Features](introduction.md#features)
- [Main API (module DSS)](api.md#main-api-module-dss)
    - [`ActiveClass`](api.md#activeclass)
    - [`Basic`](api.md#basic)
    - [`Bus`](api.md#bus)
    - [`Capacitors`](api.md#capacitors)
    - [`CapControls`](api.md#capcontrols)
    - [`Circuit`](api.md#circuit)
    - [`CktElement`](api.md#cktelement)
    - [`CtrlQueue`](api.md#ctrlqueue)
    - [`Element`](api.md#element)
    - [`Executive`](api.md#executive)
    - [`Fuses`](api.md#fuses)
    - [`Generators`](api.md#generators)
    - [`Isource`](api.md#isource)
    - [`Lines`](api.md#lines)
    - [`Loads`](api.md#loads)
    - [`LoadShape`](api.md#loadshape)
    - [`Meters`](api.md#meters)
    - [`Monitors`](api.md#monitors)
    - [`Parser`](api.md#parser)
    - [`PDElements`](api.md#pdelements)
    - [`Progress`](api.md#progress)
    - [`PVsystems`](api.md#pvsystems)
    - [`Reclosers`](api.md#reclosers)
    - [`RegControls`](api.md#regcontrols)
    - [`Relays`](api.md#relays)
    - [`Sensors`](api.md#sensors)
    - [`Settings`](api.md#settings)
    - [`Solution`](api.md#solution)
    - [`SwtControls`](api.md#swtcontrols)
    - [`Topology`](api.md#topology)
    - [`Transformers`](api.md#transformers)
    - [`Vsources`](api.md#vsources)
    - [`XYCurves`](api.md#xycurves)
- [Flag objects](flags.md#flag-objects)
- [DSS REPL Mode](dssmode.md#dss-repl-mode)
- [Low-level API (module DSSCore)](lowlevel.md#low-level-api-module-dsscore)
    - [Limitations](lowlevel.md#limitations)

<a id='documentation-index'></a>
## Documentation Index

- [`ActiveClass`](api.md#OpenDSSDirect.DSS.ActiveClass)
- [`Basic`](api.md#OpenDSSDirect.DSS.Basic)
- [`Bus`](api.md#OpenDSSDirect.DSS.Bus)
- [`CapControls`](api.md#OpenDSSDirect.DSS.CapControls)
- [`Capacitors`](api.md#OpenDSSDirect.DSS.Capacitors)
- [`Circuit`](api.md#OpenDSSDirect.DSS.Circuit)
- [`CktElement`](api.md#OpenDSSDirect.DSS.CktElement)
- [`CtrlQueue`](api.md#OpenDSSDirect.DSS.CtrlQueue)
- [`Element`](api.md#OpenDSSDirect.DSS.Element)
- [`Executive`](api.md#OpenDSSDirect.DSS.Executive)
- [`Fuses`](api.md#OpenDSSDirect.DSS.Fuses)
- [`Generators`](api.md#OpenDSSDirect.DSS.Generators)
- [`Isource`](api.md#OpenDSSDirect.DSS.Isource)
- [`Lines`](api.md#OpenDSSDirect.DSS.Lines)
- [`LoadShape`](api.md#OpenDSSDirect.DSS.LoadShape)
- [`Loads`](api.md#OpenDSSDirect.DSS.Loads)
- [`Meters`](api.md#OpenDSSDirect.DSS.Meters)
- [`Monitors`](api.md#OpenDSSDirect.DSS.Monitors)
- [`PDElements`](api.md#OpenDSSDirect.DSS.PDElements)
- [`PVsystems`](api.md#OpenDSSDirect.DSS.PVsystems)
- [`Parser`](api.md#OpenDSSDirect.DSS.Parser)
- [`Progress`](api.md#OpenDSSDirect.DSS.Progress)
- [`Reclosers`](api.md#OpenDSSDirect.DSS.Reclosers)
- [`RegControls`](api.md#OpenDSSDirect.DSS.RegControls)
- [`Relays`](api.md#OpenDSSDirect.DSS.Relays)
- [`Sensors`](api.md#OpenDSSDirect.DSS.Sensors)
- [`Settings`](api.md#OpenDSSDirect.DSS.Settings)
- [`Solution`](api.md#OpenDSSDirect.DSS.Solution)
- [`SwtControls`](api.md#OpenDSSDirect.DSS.SwtControls)
- [`Topology`](api.md#OpenDSSDirect.DSS.Topology)
- [`Transformers`](api.md#OpenDSSDirect.DSS.Transformers)
- [`Vsources`](api.md#OpenDSSDirect.DSS.Vsources)
- [`XYCurves`](api.md#OpenDSSDirect.DSS.XYCurves)
- [`ActionCodes`](flags.md#OpenDSSDirect.DSS.ActionCodes)
- [`CapControlModes`](flags.md#OpenDSSDirect.DSS.CapControlModes)
- [`LineUnits`](flags.md#OpenDSSDirect.DSS.LineUnits)
- [`LoadModels`](flags.md#OpenDSSDirect.DSS.LoadModels)
- [`LoadStatus`](flags.md#OpenDSSDirect.DSS.LoadStatus)
- [`MonitorModes`](flags.md#OpenDSSDirect.DSS.MonitorModes)
- [`Options`](flags.md#OpenDSSDirect.DSS.Options)
- [`SolveModes`](flags.md#OpenDSSDirect.DSS.SolveModes)
- [`AddInAuxCurrents`](lowlevel.md#OpenDSSDirect.DSSCore.AddInAuxCurrents)
- [`BuildYMatrixD`](lowlevel.md#OpenDSSDirect.DSSCore.BuildYMatrixD)
- [`GetPCInjCurr`](lowlevel.md#OpenDSSDirect.DSSCore.GetPCInjCurr)
- [`GetSourceInjCurrents`](lowlevel.md#OpenDSSDirect.DSSCore.GetSourceInjCurrents)
- [`SolveSystem`](lowlevel.md#OpenDSSDirect.DSSCore.SolveSystem)
- [`SystemYChanged`](lowlevel.md#OpenDSSDirect.DSSCore.SystemYChanged)
- [`UseAuxCurrents`](lowlevel.md#OpenDSSDirect.DSSCore.UseAuxCurrents)
- [`ZeroInjCurr`](lowlevel.md#OpenDSSDirect.DSSCore.ZeroInjCurr)
- [`getI`](lowlevel.md#OpenDSSDirect.DSSCore.getI)
- [`getV`](lowlevel.md#OpenDSSDirect.DSSCore.getV)
- [`getYsparse`](lowlevel.md#OpenDSSDirect.DSSCore.getYsparse)
