# Windows configuration

## Install Windows

Get Windows and use the Creation Tool or Rufus to create a bootable USB.

* [**Windows**](https://www.microsoft.com/software-download/)

(OPTIONAL)

* [**Rufus**](https://github.com/pbatard/rufus)

## Install Updates

## Install Drivers

[**Dell Drivers**](https://www.dell.com/support/home/pl-pl/product-support/product/latitude-15-5580-laptop/drivers)

```txt
Intel-Chipset-Device-Software_HMDR4_WIN_10.1.1.38_A05_06

Realtek-Memory-Card-Reader-Driver_R16KJ_WIN_10.0.17763.21313_A02_02

STMicroelectronics-Free-Fall-Data-Protection-Driver_FXX2G_WIN_4.10.106_A02

Intel-HID-Event-Filter-Driver_33CDY_WIN_2.2.1.377_A11_04

Dell-Touchpad-Driver_2VV2N_WIN_10.3201.101.216_A10

Dell-Touchpad-Settings-Application_CPPN8_WIN64_10.1.11.0_A03

Intel-9560-9260-8265-7265-3165-Bluetooth-UWD-Driver_MCC7Y_WIN64_22.130.0.2_A34_02

Intel-9560-9260-8265-7265-3165-Wi-Fi-Driver_FCCJ9_WIN_22.130.0.5_A30_04

Realtek-High-Definition-Audio-Driver_88XXX_WIN_6.0.8895.1_A23_01
```

## Software

### **Mandatory:**

```powershell
winget install File-New-Project.EarTrumpet -i

winget install 7-Zip -i

winget install Brave.Brave -i

winget install KeePassXCTeam.KeePassXC -i

winget install Microsoft.WindowsTerminal -i

winget install Microsoft.PowerShell -i

winget install Git.Git -i

winget install Docker.DockerDesktop -i

winget install Microsoft.VisualStudioCode -i

winget install Microsoft.AzureCLI -i
```

Printer Drivers

### **Install WSL**

[WSL Configuration](https://github.com/RustyTake-Off/my-configs/tree/main/wsl_2)

### **Other:**

Install [arkade](https://github.com/alexellis/arkade) and other tools through arkade. Use arkade commands through Git Bash.

```bash
arkade get arkade

arkade get gh

arkade get lazygit

arkade get kubectl

arkade get kubectx

arkade get kubecm

arkade get helm

arkade get minikube

arkade get kind

arkade get k9s

arkade get hadolint

arkade get terraform

arkade get packer

arkade get vagrant

arkade get linkerd2

arkade get istioctl

arkade get osm

arkade get flux

arkade get sops

arkade get yq

arkade get jq
```

### **Optional:**

```powershell
winget install CPUID.HWMonitor -i

winget install SumatraPDF.SumatraPDF -i

winget install ShareX.ShareX -i

winget install Greenshot.Greenshot -i

winget install Flameshot.Flameshot -i

winget install IrfanSkiljan.IrfanView -i

winget install DuongDieuPhap.ImageGlass -i

winget install OBSProject.OBSStudio -i

winget install Microsoft.Teams -i

winget install clsid2.mpc-hc -i

winget install TheDocumentFoundation.LibreOffice -i

winget install Microsoft.VCRedist.2005.x64

winget install Microsoft.VCRedist.2008.x64

winget install Microsoft.VCRedist.2010.x64

winget install Microsoft.VCRedist.2012.x64

winget install Microsoft.VCRedist.2013.x64

winget install Microsoft.VCRedist.2015+.x64
```

## (OPTIONAL) Windows Debloat

```powershell
iwr -useb https://christitus.com/win | iex
```
