Model:
Rectifier

FMI Type:
CoSimulation

Generation Tool:
MWorks.Sysporer 2016

Available Platforms:
win64

Known Errors:
None

FMUChecker:
FMUChecker Version 2.0

run command for ComplianceChecker:
set FMUName=Rectifier
fmuCheck.win64.exe -k cs -o %FMUName%_cc.csv -e %FMUName%_cc.log -h 2e-7 -s 0.1 "%FMUName%.fmu"

Contact email:
chenl@tongyuan.cc
