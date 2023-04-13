# t440p-hackintosh
- based on valnoxy EFI https://github.com/valnoxy/t440p-oc
## WIP
:construction: 

![](/images/t440-monterey.png)

## Hackintosh
macOS: Monterey

** Working:**
- Everything works fine

## To mount EFI on Windows
- Open PowerShell or Command with admin rights. (Win + X then A)

diskpart

list disk

select disk #

detail disk (verify you have the correct one by checking disk name)

list part

select part 1 (you are usually selecting partition 1. 100-200 mb.)

assign letter=z (any letter works)

Open Explorer++ with admin rights.

Select EFI in the left pane and you can edit contents from the right pane.
- by (https://www.reddit.com/r/hackintosh/comments/b3v3p6/dont_freak_out_if_you_suddenly_cant_boot_access/)[]