
# Welcome to the G24 Fogorow HUB!
> In here we try to unlock the bootloader for g24.
> Since Motorolas a pain.
**This Documentation will have all latest info in process of unlocking the G24 (fogorow).




# G24 Writeable Partitions
preloader	NO	
pgpt	NO	
misc	NO		
para	NO	
expdb	NO	
frp	NO		
vbmeta_a	NO
vbmeta_system_a	YES
vbmeta_vendor_a	YES
vbmeta_b	YES 
vbmeta_system_b	YES
vbmeta_vendor_b	YES
md_udc	NO	
metadata	YES
nvcfg	NO
nvdata	NO
persist	NO	
protect1	NO
protect2	NO	
seccfg	NO	
md1img_a	NO	
spmfw_a	NO	
scp_a		NO
sspm_a	NO
gz_a		NO
lk_a		NO
boot_a	NO	
vendor_boot_a	YES 
init_boot_a	YES
dtbo_a	NO		
tee_a	NO
sec1	YES
proinfo	NO	
efuse	NO
boot_para	NO
nvram	NO
logo	NO
md1img_b	NO
spmfw_b	YES
scp_b	YES
sspm_b	YES
gz_b	NO
lk_b	NO
boot_b	NO	
vendor_boot_b	YES
init_boot_b	YES
dtbo_b	NO
tee_b	YES
oem_mfd	NO	
elabel	YES		
super NO		
blackbox	NO		
userdata	NO		
mrdump	YES	
otp	YES	
flashinfo	NO	
sgpt	NO	

# What have we tried?

> Writing to seccfg with mtkclient.
> **Operation successful? : ❌**
