MyDataPilot: AI-Powered Data Science Assistant

If you are using an Apple Silicon Mac (with M1/M2/M3 chips): MyDataPilot-1.0.0-arm64.dmg
If you are using an Intel Mac: MyDataPilot-1.0.0.dmg

(Important)
MacOS will add a "quarantine attribute" to the files, causing the system to consider the application as unsafe.
Solution:
# Enter the directory where the downloaded files are located 
cd ~/Downloads

# Remove quarantine attribute
sudo xattr -r -d com.apple.quarantine MyDataPilot-1.0.0-arm64.dmg 
# Even if the application has already been decompressed, the application itself still needs to be processed. sudo xattr -r -d com.apple.quarantine MyDataPilot.app
