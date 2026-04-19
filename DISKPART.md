# DISKPART

``First open CMD.``

## Launch diskpart

```powershell
diskpart
```

## List all drives

```powershell
list disk
```

## Select the drive

```powershell
select disk X
```
e.g.: select disk 1

## Wipe it

```powershell
clean
```
``This will erase all data!``

## Create new partition

```powershell
create partition primary
```

## Select new partition

```powershell
select partition 1
```

## Format it

```powershell
format fs=fat32 quick label=MYUSB
```

## Assign drive letter

```powershell
assign
```

## Exit

```powershell
exit
```