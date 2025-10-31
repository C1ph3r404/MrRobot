# MrRobot — TryHackMe

## Short summary
Found WordPress creds in a `LICENSE` file, logged in and uploaded a PHP reverse shell to get a `daemon` shell, cracked a raw MD5 hash to get `mrrobot`, and escalated to root using `nmap --interactive` based on the GTFOBins technique.

## Files
- `WriteUp.md` — detailed walkthrough + commands  
- `screenshots/` — evidence: nmap, ffuf, license creds, upload, john, root

## Disclaimer

For TryHackMe labs and learning only. Don’t use these techniques on systems you don’t own or have permission to test.
