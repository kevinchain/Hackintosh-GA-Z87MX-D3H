- Installation Date: Mar 7, 2020
- Open Core: v.0.5.6 (471ea9a) released on Mar 2, 2020

# Hardware

## 2014 Haswell

- MB [GA-Z87MX-D3H](Extra/Specification-GA-Z87MX-D3H.md) @ BIOS [F6 (of F7)](https://www.gigabyte.com/Motherboard/GA-Z87MX-D3H-rev-1x/support#support-dl-bios)
- CPU [Intel Core i7-4770](https://ark.intel.com/content/www/us/en/ark/products/75122/intel-core-i7-4770-processor-8m-cache-up-to-3-90-ghz.html) @ 3.4 GHz
- iGPU Intel HD Graphics 4600
- GPU Radeon RX 580 4 GB
- RAM 16 GB 1866 MHz DDR3
- Realtek ALC892 audio codec


### Network

- Ethernet `00:00:00:00:00:00` I217-V from Intel 
- Wi-Fi `00:00:00:00:00:00`  **BCM43602** 802.11ac


---

## SMBIOS Info

```
         Model: iMac14,2
      Board ID: Mac-0000000000000000
    FW Version: 141.0.0.0.0
 Hardware UUID: 00000000-0000-0000-0000-000000000000
 Serial Number: 000000000000
       Country:  000 - Unknown
          Year:    N - 2014
          Week:    V - 50 (10.12.2014-16.12.2014)
          Line:  000 - 815 (copy 1)
         Model: 0000 - iMac14,2
   SystemModel: iMac (27-inch, Late 2013)
         Valid: Possibly
     System ID: 00000000-0000-0000-0000-000000000000
           ROM: 000000000000
           MLB: 00000000000000000
```

---

## BIOS Settings

**Disable:**

- Fast Boot
- VT-d (can be enabled if you set DisableIoMapper to YES)
- CSM
- Intel SGX
- Intel Platform Trust

**Enable:**

- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS type: Windows 8.1/10 UEFI Mode
- DVMT Pre-Allocated(iGPU Memory): 64MB


### Not present in BIOS

**Disable**

- Thunderbolt
- CFG Lock

**Enable**

- VT-x
- Hyper Threading
- Execute Disable Bit
