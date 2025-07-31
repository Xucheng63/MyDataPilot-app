MyDataPilot: AI-Powered Data Science Assistant

If you are using an Apple Silicon Mac (with M1/M2/M3 chips): MyDataPilot-1.0.0-arm64.dmg
If you are using an Intel Mac: MyDataPilot-1.0.0.dmg

(Important)
MacOS will add a "quarantine attribute" to the files, causing the system to consider the application as unsafe.
Solution:
cd ~/Downloads
sudo xattr -r -d com.apple.quarantine MyDataPilot-1.0.0-arm64.dmg 
sudo xattr -r -d com.apple.quarantine MyDataPilot.app
