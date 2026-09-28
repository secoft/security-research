# NetSupport RAT Phishing Campaign

Sigma detection rules based on observed behavior from a phishing campaign delivering NetSupport RAT.

## Detection coverage

- WScript/CScript creating LNK files in Startup folders
- NetSupport client execution from unusual locations
- WScript/CScript spawning cmd.exe
- cmd.exe spawning client32.exe
- IOC-based C2 retro-hunting

These rules are intended as starting points for threat hunting and may require tuning depending on the environment and available telemetry.
