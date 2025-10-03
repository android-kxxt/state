- `kernel/xiaomi/sm8450`: Merge branch &#x27;lineage-20&#x27; of https://github.com/LineageOS/android_kernel_qcom_sm8450 into HEAD  <details>
    <summary>Merge Details</summary>

      * 'lineage-20' of https://github.com/LineageOS/android_kernel_qcom_sm8450:
        BACKPORT: net: avoid race between device unregistration and ethnl ops
        UPSTREAM: perf/core: Fix potential NULL deref
        UPSTREAM: net/packet: fix a race in packet_set_ring() and packet_notifier()
        BACKPORT: FROMGIT: f2fs: add sysfs entry for effective lookup mode
        BACKPORT: FROMGIT: f2fs: add lookup_mode mount option
        ANDROID: 16K: Allocate pad vma on the stack
        ANDROID: 16K: Don't copy data vma for maps/smaps output
        ANDROID: GKI: Update oplus symbol list
        ANDROID: vendor_hooks: add hooks in cpu_cgroup subsystem
        ANDROID: vendor_hooks: Add hooks in reweight_entity
        ANDROID: GKI: Export css_task_iter_start()
        UPSTREAM: regulator: core: Fix deadlock in create_regulator()
        UPSTREAM: coresight-etm4x: add isb() before reading the TRCSTATR
        UPSTREAM: usb: gadget: f_uac2: Fix incorrect setting of bNumEndpoints
        UPSTREAM: f2fs: fix to avoid use GC_AT when setting gc_mode as GC_URGENT_LOW or GC_URGENT_MID
        UPSTREAM: usb: typec: fix unreleased fwnode_handle in typec_port_register_altmodes()
        UPSTREAM: xhci: Mitigate failed set dequeue pointer commands
        ANDROID: refresh ABI following type change
        UPSTREAM: net/sched: Always pass notifications when child class becomes empty
        ANDROID: bpf: do not fail to load if log is full
        BACKPORT: Add support for PIO p flag
        Revert "vm_sockets: Add flags field in the vsock address data structure"
        Revert "vm_sockets: Add VMADDR_FLAG_TO_HOST vsock flag"
        Revert "af_vsock: Set VMADDR_FLAG_TO_HOST flag on the receive path"
        Revert "af_vsock: Assign the vsock transport considering the vsock address flags"
        Revert "vsock: Fix transport_* TOCTOU"
        Linux 5.10.240
        rseq: Fix segfault on registration when rseq_cs is non-zero
        x86/process: Move the buffer clearing before MONITOR
        KVM: SVM: Advertise TSA CPUID bits to guests
        KVM: x86: add support for CPUID leaf 0x80000021
        x86/bugs: Add a Transient Scheduler Attacks mitigation
        x86/bugs: Rename MDS machinery to something more generic
        x86/mm: Disable hugetlb page table sharing on 32-bit
        vhost-scsi: protect vq->log_used with vq->mutex
        Input: atkbd - do not skip atkbd_deactivate() when skipping ATKBD_CMD_GETID
        HID: quirks: Add quirk for 2 Chicony Electronics HP 5MP Cameras
        HID: Add IGNORE quirk for SMARTLINKTECHNOLOGY
        vt: add missing notification when switching back to text mode
        net: usb: qmi_wwan: add SIMCom 8230C composition
        um: vector: Reduce stack usage in vector_eth_configure()
        atm: idt77252: Add missing `dma_map_error()`
        bnxt_en: Set DMA unmap len correctly for XDP_REDIRECT
        bnxt_en: Fix DCB ETS validation
        net: ll_temac: Fix missing tx_pending check in ethtools_set_ringparam()
        can: m_can: m_can_handle_lost_msg(): downgrade msg lost in rx message to debug level
        net: phy: microchip: limit 100M workaround to link-down events on LAN88xx
        net: appletalk: Fix device refcount leak in atrtr_create()
        md/raid1: Fix stack memory use after return in raid1_reshape
        wifi: zd1211rw: Fix potential NULL pointer dereference in zd_mac_tx_to_dev()
        dma-buf: fix timeout handling in dma_resv_wait_timeout v2
        Input: xpad - support Acer NGR 200 Controller
        Input: xpad - add VID for Turtle Beach controllers
        Input: xpad - add support for Amazon Game Controller
        netlink: make sure we allow at least one dump skb
        netlink: Fix rmem check in netlink_broadcast_deliver().
        pwm: mediatek: Ensure to disable clocks in error path
        rtc: lib_test: add MODULE_LICENSE
        ethernet: atl1: Add missing DMA mapping error checks and count errors
        Revert "ACPI: battery: negate current when discharging"
        usb: gadget: u_serial: Fix race condition in TTY wakeup
        drm/sched: Increment job count before swapping tail spsc queue
        pinctrl: qcom: msm: mark certain pins as invalid for interrupts
        x86/mce: Make sure CMCI banks are cleared during shutdown on Intel
        x86/mce: Don't remove sysfs if thresholding sysfs init fails
        x86/mce/amd: Fix threshold limit reset
        x86/its: FineIBT-paranoid vs ITS
        x86/its: Fix build errors when CONFIG_MODULES=n
        x86/its: Use dynamic thunks for indirect branches
        x86/modules: Set VM_FLUSH_RESET_PERMS in module_alloc()
        x86/its: Add "vmexit" option to skip mitigation on some CPUs
        x86/its: Enable Indirect Target Selection mitigation
        x86/its: Fix undefined reference to cpu_wants_rethunk_at()
        x86/its: Add support for ITS-safe return thunk
        x86/alternatives: Remove faulty optimization
        x86/alternative: Optimize returns patching
        x86/its: Add support for ITS-safe indirect thunk
        x86/alternatives: Teach text_poke_bp() to patch Jcc.d32 instructions
        x86/alternatives: Introduce int3_emulate_jcc()
        x86/its: Enumerate Indirect Target Selection (ITS) bug
        x86/bhi: Define SPEC_CTRL_BHI_DIS_S
        Documentation: x86/bugs/its: Add ITS documentation
        rxrpc: Fix oops due to non-existence of prealloc backlog struct
        fs/proc: do_task_stat: use __for_each_thread()
        net/sched: Abort __tc_modify_qdisc if parent class does not exist
        atm: clip: Fix NULL pointer dereference in vcc_sendmsg()
        atm: clip: Fix infinite recursive call of clip_push().
        atm: clip: Fix memory leak of struct clip_vcc.
        atm: clip: Fix potential null-ptr-deref in to_atmarpd().
        net: phy: smsc: Fix link failure in forced mode with Auto-MDIX
        net: phy: smsc: Fix Auto-MDIX configuration when disabled by strap
        vsock: Fix IOCTL_VM_SOCKETS_GET_LOCAL_CID to check also `transport_local`
        vsock: Fix transport_* TOCTOU
        af_vsock: Assign the vsock transport considering the vsock address flags
        af_vsock: Set VMADDR_FLAG_TO_HOST flag on the receive path
        vm_sockets: Add VMADDR_FLAG_TO_HOST vsock flag
        vm_sockets: Add flags field in the vsock address data structure
        vsock: Fix transport_{g2h,h2g} TOCTOU
        tipc: Fix use-after-free in tipc_conn_close().
        netlink: Fix wraparounds of sk->sk_rmem_alloc.
        fix proc_sys_compare() handling of in-lookup dentries
        perf: Revert to requiring CAP_SYS_ADMIN for uprobes
        ASoC: fsl_asrc: use internal measured ratio for non-ideal ratio mode
        drm/exynos: exynos7_drm_decon: add vblank check in IRQ handling
        staging: rtl8723bs: Avoid memset() in aes_cipher() and aes_decipher()
        media: uvcvideo: Rollback non processed entities on error
        media: uvcvideo: Send control events for partial succeeds
        media: uvcvideo: Return the number of processed controls
        ACPI: PAD: fix crash in exit_round_robin()
        usb: typec: displayport: Fix potential deadlock
        Logitech C-270 even more broken
        xhci: dbc: Flush queued requests before stopping dbc
        xhci: dbctty: disable ECHO flag by default
        dpaa2-eth: fix xdp_rxq_info leak
        net: dpaa2-eth: rearrange variable in dpaa2_eth_get_ethtool_stats
        dpaa2-eth: Update SINGLE_STEP register access
        dpaa2-eth: Update dpni_get_single_step_cfg command
        dpaa2-eth: rename dpaa2_eth_xdp_release_buf into dpaa2_eth_recycle_buf
        btrfs: use btrfs_record_snapshot_destroy() during rmdir
        btrfs: propagate last_unlink_trans earlier when doing a rmdir
        NFSv4/flexfiles: Fix handling of NFS level errors in I/O
        flexfiles/pNFS: update stats on NFS4ERR_DELAY for v4.1 DSes
        RDMA/mlx5: Fix vport loopback for MPV device
        drm/v3d: Disable interrupts before resetting the GPU
        mtk-sd: reset host->mrq on prepare_data() error
        mtk-sd: Prevent memory corruption from DMA map failure
        mmc: mediatek: use data instead of mrq parameter from msdc_{un}prepare_data()
        regulator: gpio: Fix the out-of-bounds access to drvdata::gpiods
        rcu: Return early if callback is not specified
        ACPICA: Refuse to evaluate a method if arguments are missing
        wifi: ath6kl: remove WARN on bad firmware input
        wifi: mac80211: drop invalid source address OCB frames
        scsi: target: Fix NULL pointer dereference in core_scsi3_decode_spec_i_port()
        powerpc: Fix struct termio related ioctl macros
        ata: pata_cs5536: fix build on 32-bit UML
        ALSA: sb: Force to disable DMAs once when DMA mode is changed
        net/sched: Always pass notifications when child class becomes empty
        nui: Fix dma_mapping_error() check
        rose: fix dangling neighbour pointers in rose_rt_device_down()
        net: rose: Fix fall-through warnings for Clang
        enic: fix incorrect MTU comparison in enic_change_mtu()
        amd-xgbe: align CL37 AN sequence as per databook
        lib: test_objagg: Set error message in check_expect_hints_stats()
        drm/i915/gt: Fix timeline left held on VMA alloc error
        drm/i915/selftests: Change mock_request() to return error pointers
        spi: spi-fsl-dspi: Clear completion counter before initiating transfer
        drm/exynos: fimd: Guard display clock control with runtime PM calls
        btrfs: fix missing error handling when searching for inode refs during log replay
        RDMA/mlx5: Fix CC counters query for MPV
        scsi: ufs: core: Fix spelling of a sysfs attribute name
        scsi: qla4xxx: Fix missing DMA mapping error in qla4xxx_alloc_pdu()
        scsi: qla2xxx: Fix DMA mapping test in qla24xx_get_port_database()
        NFSv4/pNFS: Fix a race to wake on NFS_LAYOUT_DRAIN
        nfs: Clean up /proc/net/rpc/nfs when nfs_fs_proc_net_init() fails.
        RDMA/mlx5: Initialize obj_event->obj_sub_list before xa_insert
        platform/mellanox: mlxbf-tmfifo: fix vring_desc.len assignment
        mtk-sd: Fix a pagefault in dma_unmap_sg() for not prepared data
        usb: typec: altmodes/displayport: do not index invalid pin_assignments
        Revert "mmc: sdhci: Disable SD card clock before changing parameters"
        mmc: sdhci: Add a helper function for dump register in dynamic debug mode
        vsock/vmci: Clear the vmci transport packet properly when initializing it
        rtc: cmos: use spin_lock_irqsave in cmos_interrupt
        arm64: Restrict pagetable teardown to avoid false warning
        Revert "ipv6: save dontfrag in cork"
        s390: Add '-std=gnu11' to decompressor and purgatory CFLAGS
        PCI: hv: Do not set PCI_COMMAND_MEMORY to reduce VM boot time
        drm/bridge: cdns-dsi: Wait for Clk and Data Lanes to be ready
        drm/bridge: cdns-dsi: Check return value when getting default PHY config
        drm/bridge: cdns-dsi: Fix connecting to next bridge
        drm/bridge: cdns-dsi: Fix the clock variable for mode_valid()
        drm/amdkfd: Fix race in GWS queue scheduling
        drm/udl: Unregister device before cleaning up on disconnect
        drm/tegra: Fix a possible null pointer dereference
        drm/tegra: Assign plane type before registration
        HID: wacom: fix kobject reference count leak
        HID: wacom: fix memory leak on sysfs attribute creation failure
        HID: wacom: fix memory leak on kobject creation failure
        btrfs: update superblock's device bytes_used when dropping chunk
        dm-raid: fix variable in journal device check
        Bluetooth: L2CAP: Fix L2CAP MTU negotiation
        dt-bindings: serial: 8250: Make clocks and clock-frequency exclusive
        atm: Release atm_dev_mutex after removing procfs in atm_dev_deregister().
        net: enetc: Correct endianness handling in _enetc_rd_reg64
        um: ubd: Add missing error check in start_io_thread()
        vsock/uapi: fix linux/vm_sockets.h userspace compilation errors
        wifi: mac80211: fix beacon interval calculation overflow
        libbpf: Fix null pointer dereference in btf_dump__free on allocation failure
        attach_recursive_mnt(): do not lock the covering tree when sliding something under it
        ALSA: usb-audio: Fix out-of-bounds read in snd_usb_get_audioformat_uac3()
        atm: clip: prevent NULL deref in clip_push()
        i2c: robotfuzz-osif: disable zero-length read messages
        i2c: tiny-usb: disable zero-length read messages
        net_sched: sch_sfq: reject invalid perturb period
        PCI: cadence-ep: Correct PBA offset in .set_msix() callback
        uio_hv_generic: Align ring size to system page
        uio_hv_generic: Query the ringbuffer size for device
        Drivers: hv: vmbus: Add utility function for querying ring size
        Drivers: hv: Rename 'alloced' to 'allocated'
        Drivers: hv: vmbus: Fix duplicate CPU assignments within a device
        uio: uio_hv_generic: use devm_kzalloc() for private data alloc
        RDMA/iwcm: Fix use-after-free of work objects after cm_id destruction
        RDMA/core: Use refcount_t instead of atomic_t on refcount of iwcm_id_private
        f2fs: don't over-report free space or inodes in statvfs
        can: tcan4x5x: fix power regulator retrieval during probe
        media: omap3isp: use sgtable-based scatterlist wrappers
        jfs: validate AG parameters in dbMount() to prevent crashes
        fs/jfs: consolidate sanity checking in dbMount
        usb: typec: tcpm/tcpci_maxim: Fix bounds check in process_rx()
        usb: typec: tcpci_maxim: add terminating newlines to logging
        usb: typec: tcpci_maxim: remove redundant assignment
        usb: typec: tcpci_maxim: Fix uninitialized return variable
        VMCI: fix race between vmci_host_setup_notify and vmci_ctx_unset_notify
        VMCI: check context->notify_page after call to get_user_pages_fast() to avoid GPF
        ovl: Check for NULL d_inode() in ovl_dentry_upper()
        ceph: fix possible integer overflow in ceph_zero_objects()
        ALSA: hda: Add new pci id for AMD GPU display HD audio controller
        ALSA: hda: Ignore unsol events for cards being shut down
        usb: typec: displayport: Receive DP Status Update NAK request exit dp altmode
        usb: cdc-wdm: avoid setting WDM_READ for ZLP-s
        usb: Add checks for snprintf() calls in usb_alloc_dev()
        usb: common: usb-conn-gpio: use a unique name for usb connector device
        usb: potential integer overflow in usbg_make_tpg()
        um: Add cmpxchg8b_emu and checksum functions to asm-prototypes.h
        iio: pressure: zpa2326: Use aligned_s64 for the timestamp
        bcache: fix NULL pointer in cache_set_flush()
        md/md-bitmap: fix dm-raid max_write_behind setting
        dmaengine: xilinx_dma: Set dma_device directions
        hwmon: (pmbus/max34440) Fix support for max34451
        leds: multicolor: Fix intensity setting while SW blinking
        mfd: max14577: Fix wakeup source leaks on device unbind
        mailbox: Not protect module_put with spin_lock_irqsave
        NFSv4.2: fix listxattr to return selinux security label
        cifs: Fix cifs_query_path_info() for Windows NT servers
        UPSTREAM: rtc: lib_test: add MODULE_LICENSE
        Revert "mm: hugetlb: independent PMD page table shared count"
        UPSTREAM: f2fs: compress: fix error path of inc_valid_block_count()
        BACKPORT: f2fs: compress: fix to avoid inconsistence bewteen i_blocks and dnode
        Revert "net: Rename ->stream_memory_read to ->sock_is_readable"
        Revert "net: Fix TOCTOU issue in sk_is_readable()"
        UPSTREAM: posix-cpu-timers: fix race between handle_posix_cpu_timers() and posix_cpu_timer_del()
        Linux 5.10.239
        scsi: qedf: Use designated initializer for struct qed_fcoe_cb_ops
        bpf: fix precision backtracking instruction iteration
        arm64/ptrace: Fix stack-out-of-bounds read in regs_get_kernel_stack_nth()
        perf: Fix sample vs do_exit()
        s390/pci: Fix __pcilg_mio_inuser() inline assembly
        rtc: test: Fix invalid format specifier.
        hwmon: (occ) Fix P10 VRM temp sensors
        mm/huge_memory: fix dereferencing invalid pmd migration entry
        net_sched: sch_sfq: move the limit validation
        net_sched: sch_sfq: use a temporary work area for validating configuration
        net_sched: sch_sfq: don't allow 1 packet limit
        net_sched: sch_sfq: handle bigger packets
        net_sched: sch_sfq: annotate data-races around q->perturb_period
        rtc: Make rtc_time64_to_tm() support dates before 1970
        rtc: Improve performance of rtc_time64_to_tm(). Add tests.
        bpf: Fix L4 csum update on IPv6 in CHECKSUM_COMPLETE
        net: Fix checksum update for ILA adj-transport
        net/ipv4: fix type mismatch in inet_ehash_locks_alloc() causing build failure
        arm64: proton-pack: Add new CPUs 'k' values for branch mitigation
        arm64: insn: Add support for encoding DSB
        arm64: bpf: Only mitigate cBPF programs loaded by unprivileged users
        arm64: insn: add encoders for atomic operations
        arm64: bpf: Add BHB mitigation to the epilogue for cBPF programs
        arm64: move AARCH64_BREAK_FAULT into insn-def.h
        arm64: spectre: increase parameters that can be used to turn off bhb mitigation individually
        arm64: insn: Add barrier encodings
        arm64: proton-pack: Expose whether the branchy loop k value
        arm64: errata: Add missing sentinels to Spectre-BHB MIDR arrays
        arm64: errata: Add newer ARM cores to the spectre_bhb_loop_affected() lists
        arm64: errata: Add KRYO 2XX/3XX/4XX silver cores to Spectre BHB safe list
        arm64: errata: Assume that unknown CPUs _are_ vulnerable to Spectre BHB
        arm64: proton-pack: Expose whether the platform is mitigated by firmware
        serial: sh-sci: Increment the runtime usage counter for the earlycon device
        ARM: dts: am335x-bone-common: Increase MDIO reset deassert delay to 50ms
        ARM: dts: am335x-bone-common: Increase MDIO reset deassert time
        ARM: dts: am335x-bone-common: Add GPIO PHY reset on revision C3 board
        net: atm: fix /proc/net/atm/lec handling
        net: atm: add lec_mutex
        calipso: Fix null-ptr-deref in calipso_req_{set,del}attr().
        tipc: fix null-ptr-deref when acquiring remote ip of ethernet bearer
        tcp: fix tcp_packet_delayed() for tcp_is_non_sack_preventing_reopen() behavior
        atm: atmtcp: Free invalid length skb in atmtcp_c_send().
        mpls: Use rcu_dereference_rtnl() in mpls_route_input_rcu().
        wifi: carl9170: do not ping device which has failed to load firmware
        net: ice: Perform accurate aRFS flow match
        aoe: clean device rq_list in aoedev_downdev()
        mm/hugetlb: fix huge_pmd_unshare() vs GUP-fast race
        mm: hugetlb: independent PMD page table shared count
        mm/hugetlb: unshare page tables during VMA split, not before
        hugetlb: unshare some PMDs when splitting VMAs
        ALSA: hda/realtek: enable headset mic on Latitude 5420 Rugged
        pldmfw: Select CRC32 when PLDMFW is selected
        ALSA: hda/intel: Add Thinkpad E15 to PM deny list
        hwmon: (occ) fix unaligned accesses
        hwmon: (occ) Rework attribute registration for stack usage
        hwmon: (occ) Add soft minimum power cap attribute
        hwmon: (occ) Add new temperature sensor type
        drm/nouveau/bl: increase buffer size to avoid truncate warning
        erofs: remove unused trace event erofs_destroy_inode
        ALSA: usb-audio: Rename ALSA kcontrol PCM and PCM1 for the KTMicro sound card
        Input: sparcspkr - avoid unannotated fall-through
        HID: usbhid: Eliminate recurrent out-of-bounds bug in usbhid_parse()
        atm: Revert atm_account_tx() if copy_from_iter_full() fails.
        selinux: fix selinux_xfrm_alloc_user() to set correct ctx_len
        udmabuf: use sgtable-based scatterlist wrappers
        scsi: s390: zfcp: Ensure synchronous unit_add
        scsi: storvsc: Increase the timeouts to storvsc_timeout
        jffs2: check jffs2_prealloc_raw_node_refs() result in few other places
        jffs2: check that raw node were preallocated before writing summary
        drivers/rapidio/rio_cm.c: prevent possible heap overwrite
        Revert "x86/bugs: Make spectre user default depend on MITIGATION_SPECTRE_V2" on v6.6 and older
        powerpc/eeh: Fix missing PE bridge reconfiguration during VFIO EEH recovery
        platform/x86: dell_rbu: Stop overwriting data buffer
        platform/x86: dell_rbu: Fix list usage
        platform: Add Surface platform directory
        Revert "bus: ti-sysc: Probe for l4_wkup and l4_cfg interconnect devices first"
        tee: Prevent size calculation wraparound on 32-bit kernels
        ARM: OMAP2+: Fix l4ls clk domain handling in STANDBY
        bus: fsl-mc: increase MC_CMD_COMPLETION_TIMEOUT_MS value
        watchdog: da9052_wdt: respect TWDMIN
        i40e: fix MMIO write access to an invalid page in i40e_clear_hw
        sock: Correct error checking condition for (assign|release)_proto_idx()
        scsi: lpfc: Use memcpy() for BIOS version
        software node: Correct a OOB check in software_node_get_reference_args()
        vxlan: Do not treat dst cache initialization errors as fatal
        iommu/amd: Ensure GA log notifier callbacks finish running before module unload
        scsi: lpfc: Fix lpfc_check_sli_ndlp() handling for GEN_REQUEST64 commands
        clk: rockchip: rk3036: mark ddrphy as critical
        wifi: mac80211: do not offer a mesh path if forwarding is disabled
        net: mlx4: add SOF_TIMESTAMPING_TX_SOFTWARE flag when getting ts info
        pinctrl: armada-37xx: propagate error from armada_37xx_gpio_get()
        pinctrl: armada-37xx: propagate error from armada_37xx_pmx_gpio_set_direction()
        pinctrl: armada-37xx: propagate error from armada_37xx_gpio_get_direction()
        pinctrl: armada-37xx: propagate error from armada_37xx_pmx_set_by_name()
        net: atlantic: generate software timestamp just before the doorbell
        ipv4/route: Use this_cpu_inc() for stats on PREEMPT_RT
        tcp: fix initial tp->rcvq_space.space value for passive TS enabled flows
        tcp: always seek for minimal rtt in tcp_rcv_rtt_update()
        net: dlink: add synchronization for stats update
        i2c: npcm: Add clock toggle recovery
        sctp: Do not wake readers in __sctp_write_space()
        wifi: mt76: mt76x2: Add support for LiteOn WN4516R,WN4519R
        emulex/benet: correct command version selection in be_cmd_get_stats()
        i2c: designware: Invoke runtime suspend on quick slave re-registration
        tipc: use kfree_sensitive() for aead cleanup
        net: macb: Check return value of dma_set_mask_and_coherent()
        cpufreq: Force sync policy boost with global boost on sysfs update
        thermal/drivers/qcom/tsens: Update conditions to strictly evaluate for IP v2+
        nios2: force update_mmu_cache on spurious tlb-permission--related pagefaults
        media: platform: exynos4-is: Add hardware sync wait to fimc_is_hw_change_mode()
        media: tc358743: ignore video while HPD is low
        drm/amdkfd: Set SDMA_RLCx_IB_CNTL/SWITCH_INSIDE_IB
        drm/msm/dpu: don't select single flush for active CTL blocks
        jfs: Fix null-ptr-deref in jfs_ioc_trim
        drm/amdgpu/gfx9: fix CSIB handling
        drm/amdgpu/gfx8: fix CSIB handling
        drm/amdgpu/gfx7: fix CSIB handling
        ext4: prevent stale extent cache entries caused by concurrent get es_cache
        media: uapi: v4l: Change V4L2_TYPE_IS_CAPTURE condition
        sunrpc: fix race in cache cleanup causing stale nextcheck time
        drm/amdgpu/gfx10: fix CSIB handling
        media: rkvdec: Initialize the m2m context before the controls
        drm/msm/a6xx: Increase HFI response timeout
        jfs: fix array-index-out-of-bounds read in add_missing_indices
        drm/amd/display: Add NULL pointer checks in dm_force_atomic_commit()
        ext4: ext4: unify EXT4_EX_NOCACHE|NOFAIL flags in ext4_ext_remove_space()
        media: uapi: v4l: Fix V4L2_TYPE_IS_OUTPUT condition
        drm/msm/hdmi: add runtime PM calls to DDC transfer function
        exfat: fix double free in delayed_free
        drm/bridge: analogix_dp: Add irq flag IRQF_NO_AUTOEN instead of calling disable_irq()
        sunrpc: update nextcheck time when adding new cache entries
        drm/amdgpu/gfx6: fix CSIB handling
        ACPI: battery: negate current when discharging
        PM: runtime: fix denying of auto suspend in pm_suspend_timer_fn()
        ASoC: tegra210_ahub: Add check to of_device_get_match_data()
        ACPICA: utilities: Fix overflow check in vsnprintf()
        power: supply: bq27xxx: Retrieve again when busy
        ACPICA: fix acpi parse and parseext cache leaks
        ASoC: tas2770: Power cycle amp on ISENSE/VSENSE change
        ACPICA: Avoid sequence overread in call to strncmp()
        clocksource: Fix the CPUs' choice in the watchdog per CPU verification
        ACPICA: fix acpi operand cache leak in dswstate.c
        iio: adc: ad7606_spi: fix reg write value mask
        iio: imu: inv_icm42600: Fix temperature calculation
        PCI: Fix lock symmetry in pci_slot_unlock()
        PCI: Add ACS quirk for Loongson PCIe
        uio_hv_generic: Use correct size for interrupt and monitor pages
        regulator: max14577: Add error check for max14577_read_reg()
        mips: Add -std= flag specified in KBUILD_CFLAGS to vdso CFLAGS
        staging: iio: ad5933: Correct settling cycles encoding per datasheet
        net: ch9200: fix uninitialised access during mii_nway_restart
        ftrace: Fix UAF when lookup kallsym after ftrace disabled
        dm-mirror: fix a tiny race condition
        mtd: nand: sunxi: Add randomizer configuration before randomizer enable
        mtd: rawnand: sunxi: Add randomizer configuration in sunxi_nfc_hw_ecc_write_chunk
        mm: fix ratelimit_pages update error in dirty_ratio_handler()
        ipc: fix to protect IPCS lookups using RCU
        clk: meson-g12a: add missing fclk_div2 to spicc
        parisc: fix building with gcc-15
        vgacon: Add check for vc_origin address range in vgacon_scroll()
        fbdev: Fix fb_set_var to prevent null-ptr-deref in fb_videomode_to_var
        EDAC/altera: Use correct write width with the INTTEST register
        NFC: nci: uart: Set tty->disc_data only in success path
        f2fs: fix to do sanity check on sit_bitmap_size
        f2fs: prevent kernel warning due to negative i_nlink from corrupted image
        Input: ims-pcu - check record size in ims_pcu_flash_firmware()
        ext4: ensure i_size is smaller than maxbytes
        ext4: factor out ext4_get_maxbytes()
        ext4: fix calculation of credits for extent tree modification
        ext4: inline: fix len overflow in ext4_prepare_inline_data
        bus: fsl-mc: do not add a device-link for the UAPI used DPMCP device
        ata: pata_via: Force PIO for ATAPI devices on VT6415/VT6330
        bus: mhi: host: Fix conflict between power_up and SYSERR
        ARM: omap: pmic-cpcap: do not mess around without CPCAP or OMAP4
        ARM: 9447/1: arm/memremap: fix arch_memremap_can_ram_remap()
        media: vivid: Change the siize of the composing
        media: vidtv: Terminating the subsequent process of initialization failure
        media: videobuf2: use sgtable-based scatterlist wrappers
        media: venus: Fix probe error handling
        media: v4l2-dev: fix error handling in __video_register_device()
        media: gspca: Add error handling for stv06xx_read_sensor()
        media: cxusb: no longer judge rbuf when the write fails
        media: ov8856: suppress probe deferral errors
        wifi: rtlwifi: disable ASPM for RTL8723BE with subsystem ID 11ad:1723
        jbd2: fix data-race and null-ptr-deref in jbd2_journal_dirty_metadata()
        nfsd: Initialize ssc before laundromat_work to prevent NULL dereference
        nfsd: nfsd4_spo_must_allow() must check this is a v4 compound request
        wifi: p54: prevent buffer-overflow in p54_rx_eeprom_readback()
        net/mlx5: Add error handling in mlx5_query_nic_vport_node_guid()
        net/mlx5_core: Add error handling inmlx5_query_nic_vport_qkey_viol_cntr()
        ASoC: meson: meson-card-utils: use of_property_present() for DT parsing
        ASoC: qcom: sdm845: Add error handling in sdm845_slim_snd_hw_params()
        gfs2: move msleep to sleepable context
        crypto: marvell/cesa - Do not chain submitted requests
        configfs: Do not override creating attribute file failure in populate_attrs()
        tcp: tcp_data_ready() must look at SOCK_DONE
        kbuild: hdrcheck: fix cross build with clang
        kbuild: userprogs: fix bitsize and target detection on clang
        net: usb: aqc111: debug info before sanitation
        calipso: unlock rcu before returning -EAFNOSUPPORT
        x86/iopl: Cure TIF_IO_BITMAP inconsistencies
        xen/arm: call uaccess_ttbr0_enable for dm_op hypercall
        usb: Flush altsetting 0 endpoints before reinitializating them after reset.
        drm/amd/display: Do not add '-mhard-float' to dcn2{1,0}_resource.o for clang
        kbuild: Add KBUILD_CPPFLAGS to as-option invocation
        kbuild: add $(CLANG_FLAGS) to KBUILD_CPPFLAGS
        kbuild: Add CLANG_FLAGS to as-instr
        mips: Include KBUILD_CPPFLAGS in CHECKFLAGS invocation
        drm/amd/display: Do not add '-mhard-float' to dml_ccflags for clang
        kbuild: Update assembler calls to use proper flags and language target
        MIPS: Prefer cc-option for additions to cflags
        MIPS: Move '-Wa,-msoft-float' check from as-option to cc-option
        x86/boot/compressed: prefer cc-option for CFLAGS additions
        posix-cpu-timers: fix race between handle_posix_cpu_timers() and posix_cpu_timer_del()
        fs/filesystems: Fix potential unsigned integer underflow in fs_name()
        net_sched: ets: fix a race in ets_qdisc_change()
        sch_ets: make est_qlen_notify() idempotent
        net_sched: tbf: fix a race in tbf_change()
        net_sched: red: fix a race in __red_change()
        net_sched: prio: fix a race in prio_tune()
        net/mlx5: Fix return value when searching for existing flow group
        net/mlx5: Ensure fw pages are always allocated on same NUMA
        net/mdiobus: Fix potential out-of-bounds read/write access
        net: mdio: C22 is now optional, EOPNOTSUPP if not provided
        macsec: MACsec SCI assignment for ES = 0
        net: Fix TOCTOU issue in sk_is_readable()
        net: Rename ->stream_memory_read to ->sock_is_readable
        bpf: Clean up sockmap related Kconfigs
        tcp: factorize logic into tcp_epollin_ready()
        i40e: retry VFLR handling if there is ongoing VF reset
        i40e: return false from i40e_reset_vf if reset is in progress
        ath10k: snoc: fix unbalanced IRQ enable in crash recovery
        powerpc/vas: Return -EINVAL if the offset is non-zero in mmap()
        ath10k: prevent deinitializing NAPI twice
        powerpc/vas: Move VAS API to book3s common platform
        ath10k: add atomic protection for device recovery
        net_sched: sch_sfq: fix a potential crash on gso_skb handling
        serial: sh-sci: Clean sci_ports[0] after at earlycon exit
        scsi: iscsi: Fix incorrect error path labels for flashnode operations
        serial: sh-sci: Move runtime PM enable to sci_probe_single()
        serial: sh-sci: Check if TX data was written to device in .tx_empty()
        arm64: dts: ti: k3-am65-main: Add missing taps to sdhci0
        arm64: dts: ti: k3-am65-main: Fix sdhci node properties
        arm64: dts: ti: k3-am65-main: Drop deprecated ti,otap-del-sel property
        Input: synaptics-rmi - fix crash with unsupported versions of F34
        Input: synaptics-rmi4 - convert to use sysfs_emit() APIs
        pmdomain: core: Fix error checking in genpd_dev_pm_attach_by_id()
        do_change_type(): refuse to operate on unmounted/not ours mounts
        PM: sleep: Fix power.is_suspended cleanup for direct-complete devices
        vmxnet3: correctly report gso type for UDP tunnels
        ice: create new Tx scheduler nodes for new queues only
        Bluetooth: L2CAP: Fix not responding with L2CAP_CR_LE_ENCRYPTION
        spi: bcm63xx-hsspi: fix shared reset
        spi: bcm63xx-spi: fix shared reset
        net/mlx4_en: Prevent potential integer overflow calculating Hz
        driver: net: ethernet: mtk_star_emac: fix suspend/resume issue
        net: tipc: fix refcount warning in tipc_aead_encrypt
        gve: Fix RX_BUFFERS_POSTED stat to report per-queue fill_cnt
        net: stmmac: platform: guarantee uniqueness of bus_id
        vt: remove VT_RESIZE and VT_RESIZEX from vt_compat_ioctl()
        MIPS: Loongson64: Add missing '#interrupt-cells' for loongson64c_ls7a
        iio: adc: ad7124: Fix 3dB filter frequency reading
        serial: Fix potential null-ptr-deref in mlb_usio_probe()
        usb: renesas_usbhs: Reorder clock handling and power management in probe
        rtc: Fix offset calculation for .start_secs < 0
        PCI/DPC: Initialize aer_err_info before using it
        dmaengine: ti: Add NULL check in udma_probe()
        PCI: cadence: Fix runtime atomic count underflow
        rtc: sh: assign correct interrupts with DT
        nfs: ignore SB_RDONLY when remounting nfs
        nfs: clear SB_RDONLY before getting superblock
        perf record: Fix incorrect --user-regs comments
        perf tests switch-tracking: Fix timestamp comparison
        mfd: stmpe-spi: Correct the name used in MODULE_DEVICE_TABLE
        mfd: exynos-lpass: Avoid calling exynos_lpass_disable() twice in exynos_lpass_remove()
        rpmsg: qcom_smd: Fix uninitialized return variable in __qcom_smd_send()
        perf scripts python: exported-sql-viewer.py: Fix pattern matching with Python 3
        backlight: pm8941: Add NULL check in wled_configure()
        perf ui browser hists: Set actions->thread before calling do_zoom_thread()
        perf build: Warn when libdebuginfod devel files are not available
        fbdev: core: fbcvt: avoid division by 0 in fb_cvt_hperiod()
        soc: aspeed: Add NULL check in aspeed_lpc_enable_snoop()
        soc: aspeed: lpc: Fix impossible judgment condition
        arm64: dts: rockchip: disable unrouted USB controllers and PHY on RK3399 Puma with Haikou
        ARM: dts: qcom: apq8064 merge hw splinlock into corresponding syscon device
        bus: fsl-mc: fix double-free on mc_dev
        nilfs2: do not propagate ENOENT error from nilfs_btree_propagate()
        calipso: Don't call calipso functions for AF_INET sk.
        nilfs2: add pointer check for nilfs_direct_propagate()
        net: lan743x: rename lan743x_reset_phy to lan743x_hw_reset_phy
        Squashfs: check return result of sb_min_blocksize
        net: usb: aqc111: fix error handling of usbnet read calls
        arm64: dts: imx8mm-beacon: Fix RTC capacitive load
        netfilter: nft_tunnel: fix geneve_opt dump
        ARM: dts: at91: at91sam9263: fix NAND chip selects
        vfio/type1: Fix error unwind in migration dirty bitmap allocation
        ARM: dts: at91: usb_a9263: fix GPIO for Dataflash chip select
        f2fs: fix to correct check conditions in f2fs_cross_rename
        f2fs: use d_inode(dentry) cleanup dentry->d_inode
        net: phy: mscc: Stop clearing the the UDPv4 checksum for L2 frames
        net: openvswitch: Fix the dead loop of MPLS parse
        netfilter: nf_tables: nft_fib_ipv6: fix VRF ipv4/ipv6 result discrepancy
        wifi: ath9k_htc: Abort software beacon handling if disabled
        s390/bpf: Store backchain even for leaf progs
        clk: qcom: gcc-msm8939: Fix mclk0 & mclk1 for 24 MHz
        bpf: Fix WARN() in get_bpf_raw_tp_regs
        pinctrl: at91: Fix possible out-of-boundary access
        libbpf: Use proper errno value in nlattr
        ktls, sockmap: Fix missing uncharge operation
        clk: bcm: rpi: Add NULL check in raspberrypi_clk_register()
        RDMA/mlx5: Fix error flow upon firmware failure for RQ destruction
        netfilter: bridge: Move specific fragmented packet to slow_path instead of dropping it
        f2fs: clean up w/ fscrypt_is_bounce_page()
        RDMA/hns: Include hnae3.h in hns_roce_hw_v2.h
        wifi: rtw88: do not ignore hardware read error during DPK
        net: ncsi: Fix GCPS 64-bit member variables
        f2fs: fix to do sanity check on sbi->total_valid_block_count
        wifi: ath11k: fix node corruption in ar->arvifs list
        firmware: SDEI: Allow sdei initialization without ACPI_APEI_GHES
        drm/tegra: rgb: Fix the unbound reference count
        drm/vkms: Adjust vkms_state->active_planes allocation type
        drm: rcar-du: Fix memory leak in rcar_du_vsps_init()
        selftests/seccomp: fix syscall_restart test for arm compat
        firmware: psci: Fix refcount leak in psci_dt_init
        m68k: mac: Fix macintosh_config for Mac II
        media: rkvdec: Fix frame size enumeration
        drm/vmwgfx: Add seqno waiter for sync_files
        spi: sh-msiof: Fix maximum DMA transfer size
        ACPI: OSI: Stop advertising support for "3.0 _SCP Extensions"
        x86/mtrr: Check if fixed-range MTRRs exist in mtrr_save_fixed_ranges()
        PM: wakeup: Delete space in the end of string shown by pm_show_wakelocks()
        power: reset: at91-reset: Optimize at91_reset()
        EDAC/skx_common: Fix general protection fault
        crypto: sun8i-ce - move fallback ahash_request to the end of the struct
        crypto: xts - Only add ecb if it is not already there
        crypto: lrw - Only add ecb if it is not already there
        crypto: marvell/cesa - Avoid empty transfer descriptor
        crypto: marvell/cesa - Handle zero-length skcipher requests
        x86/cpu: Sanitize CPUID(0x80000000) output
        crypto: sun8i-ss - do not use sg_dma_len before calling DMA functions
        perf/core: Fix broken throttling when max_samples_per_tick=1
        gfs2: gfs2_create_inode error handling fix
        netfilter: nft_socket: fix sk refcount leaks
        thunderbolt: Do not double dequeue a configuration request
        usb: usbtmc: Fix timeout value in get_stb
        usb: storage: Ignore UAS driver for SanDisk 3.2 Gen2 storage device
        usb: quirks: Add NO_LPM quirk for SanDisk Extreme 55AE
        acpi-cpufreq: Fix nominal_freq units to KHz in get_max_boost_ratio()
        pinctrl: armada-37xx: set GPIO output value before setting direction
        pinctrl: armada-37xx: use correct OUTPUT_VAL register for GPIOs > 31
        tracing: Fix compilation warning on arm32
        ANDROID: fix kernelci build breaks for dcn_calcs
        FROMGIT: f2fs: sysfs: export linear_lookup in features directory
        FROMGIT: f2fs: sysfs: add encoding_flags entry
        FROMGIT: f2fs: support to disable linear lookup fallback
        Revert "ANDROID: usb: Optimization the transfer rate of accessory mode in USB3.2 mode"
        BACKPORT: binder: Create safe versions of binder log files
        UPSTREAM: binder: Refactor binder_node print synchronization
        Revert "ipv6: save dontfrag in cork"
        UPSTREAM: tracing: Fix compilation warning on arm32
        Revert "coredump: hand a pidfd to the usermode coredump helper"
        Revert "tcp: bring back NUMA dispersion in inet_ehash_locks_alloc()"
        Linux 5.10.238
        perf/arm-cmn: Initialise cmn->cpu earlier
        xen/swiotlb: relax alignment requirements
        platform/x86: thinkpad_acpi: Ignore battery threshold change event notification
        platform/x86: fujitsu-laptop: Support Lifebook S2110 hotkeys
        tpm: tis: Double the timeout B to 4s
        spi: spi-sun4i: fix early activation
        um: let 'make clean' properly clean underlying SUBARCH as well
        platform/x86: thinkpad_acpi: Support also NEC Lavie X1475JAS
        nfs: don't share pNFS DS connections between net namespaces
        HID: quirks: Add ADATA XPG alpha wireless mouse support
        coredump: hand a pidfd to the usermode coredump helper
        fork: use pidfd_prepare()
        pid: add pidfd_prepare()
        coredump: fix error handling for replace_fd()
        net_sched: hfsc: Address reentrant enqueue adding class to eltree twice
        smb: client: Reset all search buffer pointers when releasing buffer
        smb: client: Fix use-after-free in cifs_fill_dirent
        drm/i915/gvt: fix unterminated-string-initialization warning
        kbuild: Disable -Wdefault-const-init-unsafe
        spi: spi-fsl-dspi: Reset SR flags before sending a new message
        spi: spi-fsl-dspi: Halt the module after a new message transfer
        spi: spi-fsl-dspi: restrict register range for regmap access
        mm/page_alloc.c: avoid infinite retries caused by cpuset race
        memcg: always call cond_resched() after fn()
        drm/edid: fixed the bug that hdr metadata was not reset
        llc: fix data loss when reading from a socket in llc_ui_recvmsg()
        ALSA: pcm: Fix race of buffer access at PCM OSS layer
        can: bcm: add missing rcu read protection for procfs content
        can: bcm: add locking for bcm_op runtime updates
        padata: do not leak refcount in reorder_work
        crypto: algif_hash - fix double free in hash_accept
        net/tipc: fix slab-use-after-free Read in tipc_aead_encrypt_done
        sch_hfsc: Fix qlen accounting bug when using peek in hfsc_enqueue()
        net: dwmac-sun8i: Use parsed internal PHY address instead of 1
        bridge: netfilter: Fix forwarding of fragmented packets
        xfrm: Sanitize marks before insert
        __legitimize_mnt(): check for MNT_SYNC_UMOUNT should be under mount_lock
        xenbus: Allow PVH dom0 a non-local xenstore
        btrfs: correct the order of prelim_ref arguments in btrfs__prelim_ref
        nvmet-tcp: don't restore null sk_state_change
        ALSA: hda/realtek: Add quirk for HP Spectre x360 15-df1xxx
        ASoC: Intel: bytcr_rt5640: Add DMI quirk for Acer Aspire SW3-013
        pinctrl: meson: define the pull up/down resistor value as 60 kOhm
        drm: Add valid clones check
        drm/atomic: clarify the rules around drm_atomic_state->allow_modeset
        regulator: ad5398: Add device tree support
        spi: zynqmp-gqspi: Always acknowledge interrupts
        wifi: rtw88: Don't use static local variable in rtw8822b_set_tx_power_index_by_rate
        perf/amd/ibs: Fix perf_ibs_op.cnt_mask for CurCnt
        bpftool: Fix readlink usage in get_fd_type
        drm/ast: Find VBIOS mode from regular display size
        HID: usbkbd: Fix the bit shift number for LED_KANA
        scsi: st: Restore some drive settings after reset
        scsi: lpfc: Handle duplicate D_IDs in ndlp search-by D_ID routine
        rcu: fix header guard for rcu_all_qs()
        rcu: handle quiescent states for PREEMPT_RCU=n, PREEMPT_COUNT=y
        vxlan: Annotate FDB data races
        hwmon: (xgene-hwmon) use appropriate type for the latency value
        wifi: rtw88: Fix download_firmware_validate() for RTL8814AU
        ip: fib_rules: Fetch net from fib_rule in fib[46]_rule_configure().
        net/mlx5e: reduce rep rxq depth to 256 for ECPF
        net/mlx5e: set the tx_queue_len for pfifo_fast
        net/mlx5: Extend Ethtool loopback selftest to support non-linear SKB
        drm/amd/display: Initial psr_version with correct setting
        phy: core: don't require set_mode() callback for phy_get_mode() to work
        net/mlx4_core: Avoid impossible mlx4_db_alloc() order value
        media: v4l: Memset argument to 0 before calling get_mbus_config pad op
        smack: recognize ipv4 CIPSO w/o categories
        pinctrl: devicetree: do not goto err when probing hogs in pinctrl_dt_to_map
        ASoC: soc-dai: check return value at snd_soc_dai_set_tdm_slot()
        ASoC: tas2764: Power up/down amp on mute ops
        ASoC: ops: Enforce platform maximum on initial value
        net/mlx5: Apply rate-limiting to high temperature warning
        net/mlx5: Modify LSB bitmask in temperature event to include only the first bit
        ACPI: HED: Always initialize before evged
        PCI: Fix old_size lower bound in calculate_iosize() too
        eth: mlx4: don't try to complete XDP frames in netpoll
        can: c_can: Use of_property_present() to test existence of DT property
        EDAC/ie31200: work around false positive build warning
        net: pktgen: fix access outside of user given buffer in pktgen_thread_write()
        wifi: rtw88: Fix rtw_desc_to_mcsrate() to handle MCS16-31
        wifi: rtw88: Fix rtw_init_ht_cap() for RTL8814AU
        wifi: rtw88: Fix rtw_init_vht_cap() for RTL8814AU
        scsi: mpt3sas: Send a diag reset if target reset fails
        clocksource: mips-gic-timer: Enable counter when CPUs start
        MIPS: pm-cps: Use per-CPU variables as per-CPU, not per-core
        MIPS: Use arch specific syscall name match function
        libbpf: Fix out-of-bound read
        cpuidle: menu: Avoid discarding useful information
        x86/nmi: Add an emergency handler in nmi_desc & use it in nmi_shootdown_cpus()
        soc: ti: k3-socinfo: Do not use syscon helper to build regmap
        bonding: report duplicate MAC address in all situations
        net: xgene-v2: remove incorrect ACPI_PTR annotation
        drm/amdkfd: KFD release_work possible circular locking
        net/mlx5: Avoid report two health errors on same syndrome
        PCI: brcmstb: Add a softdep to MIP MSI-X driver
        PCI: brcmstb: Expand inbound window size up to 64GB
        fpga: altera-cvp: Increase credit timeout
        drm/mediatek: mtk_dpi: Add checks for reg_h_fre_con existence
        hwmon: (gpio-fan) Add missing mutex locks
        x86/bugs: Make spectre user default depend on MITIGATION_SPECTRE_V2
        clk: imx8mp: inform CCF of maximum frequency of clocks
        ipv4: fib: Move fib_valid_key_len() to rtm_to_fib_config().
        net: pktgen: fix mpls maximum labels list parsing
        net: ethernet: ti: cpsw_new: populate netdev of_node
        pinctrl: bcm281xx: Use "unsigned int" instead of bare "unsigned"
        media: cx231xx: set device_caps for 417
        drm/amdgpu: Do not program AGP BAR regs under SRIOV in gfxhub_v1_0.c
        orangefs: Do not truncate file size
        dm cache: prevent BUG_ON by blocking retries on failed device resumes
        media: c8sectpfe: Call of_node_put(i2c_bus) only once in c8sectpfe_probe()
        ARM: tegra: Switch DSI-B clock parent to PLLD on Tegra114
        ieee802154: ca8210: Use proper setters and getters for bitwise types
        rtc: ds1307: stop disabling alarms on probe
        tcp: bring back NUMA dispersion in inet_ehash_locks_alloc()
        powerpc/prom_init: Fixup missing #size-cells on PowerBook6,7
        arm64: tegra: p2597: Fix gpio for vdd-1v8-dis regulator
        ipv6: save dontfrag in cork
        mmc: sdhci: Disable SD card clock before changing parameters
        arm64/mm: Check PUD_TYPE_TABLE in pud_bad()
        netfilter: conntrack: Bound nf_conntrack sysctl writes
        posix-timers: Add cond_resched() to posix_timer_add() search loop
        xen: Add support for XenServer 6.1 platform device
        dm: restrict dm device size to 2^63-512 bytes
        kbuild: fix argument parsing in scripts/config
        rtc: rv3032: fix EERD location
        tcp: reorganize tcp_in_ack_event() and tcp_count_delivered()
        scsi: st: ERASE does not change tape location
        scsi: st: Tighten the page format heuristics with MODE SELECT
        ext4: reorder capability check last
        um: Update min_low_pfn to match changes in uml_reserved
        um: Store full CSGSFS and SS register from mcontext
        btrfs: send: return -ENAMETOOLONG when attempting a path that is too long
        btrfs: avoid linker error in btrfs_find_create_tree_block()
        i2c: pxa: fix call balance of i2c->clk handling routines
        i2c: qup: Vote for interconnect bandwidth to DRAM
        mmc: host: Wait for Vdd to settle on card power off
        libnvdimm/labels: Fix divide error in nd_label_data_init()
        pNFS/flexfiles: Report ENETDOWN as a connection error
        tools/build: Don't pass test log files to linker
        dql: Fix dql->limit value when reset.
        thermal/drivers/qoriq: Power down TMU on system suspend
        SUNRPC: rpcbind should never reset the port to the value '0'
        SUNRPC: rpc_clnt_set_transport() must not change the autobind setting
        NFSv4: Treat ENETUNREACH errors as fatal for state recovery
        fbdev: core: tileblit: Implement missing margin clearing for tileblit
        fbcon: Use correct erase colour for clearing in fbcon
        fbdev: fsl-diu-fb: add missing device_remove_file()
        mailbox: use error ret code of of_parse_phandle_with_args()
        NFSv4: Check for delegation validity in nfs_start_delegation_return_locked()
        kconfig: merge_config: use an empty file as initfile
        cgroup: Fix compilation issue due to cgroup_mutex not being exported
        dma-mapping: avoid potential unused data compilation warning
        scsi: target: iscsi: Fix timeout on deleted connection
        ice: arfs: fix use-after-free when freeing @rx_cpu_rmap
        netfilter: nf_tables: do not defer rule destruction via call_rcu
        netfilter: nf_tables: wait for rcu grace period on net_device removal
        netfilter: nf_tables: pass nft_chain to destroy function, not nft_ctx
        btrfs: don't BUG_ON() when 0 reference count at btrfs_lookup_extent_info()
        selftests/mm: compaction_test: support platform with huge mount of memory
        usb: typec: fix pm usage counter imbalance in ucsi_ccg_sync_control()
        usb: typec: fix potential array underflow in ucsi_ccg_sync_control()
        usb: typec: altmodes/displayport: create sysfs nodes as driver's default device attribute group
        drm/vmwgfx: Fix a deadlock in dma buf fence polling
        ASoC: q6afe-clocks: fix reprobing of the driver
        clocksource/i8253: Use raw_spinlock_irqsave() in clockevent_i8253_disable()
        dmaengine: ti: k3-udma: Use cap_mask directly from dma_device structure instead of a local copy
        dmaengine: ti: k3-udma: Add missing locking
        wifi: mt76: disable napi on driver removal
        phy: renesas: rcar-gen3-usb2: Set timing registers only once
        phy: Fix error handling in tegra_xusb_port_init
        tracing: samples: Initialize trace_array_printk() with the correct function
        ALSA: es1968: Add error handling for snd_pcm_hw_constraint_pow2()
        ACPI: PPTT: Fix processor subtable walk
        dmaengine: Revert "dmaengine: dmatest: Fix dmatest waiting less when interrupted"
        NFSv4/pnfs: Reset the layout state after a layoutreturn
        qlcnic: fix memory leak in qlcnic_sriov_channel_cfg_cmd()
        ALSA: sh: SND_AICA should depend on SH_DMA_API
        net: dsa: sja1105: discard incoming frames in BR_STATE_LISTENING
        net: cadence: macb: Fix a possible deadlock in macb_halt_tx.
        net_sched: Flush gso_skb list too during ->change()
        spi: loopback-test: Do not split 1024-byte hexdumps
        nfs: handle failure of nfs_get_lock_context in unlock path
        RDMA/rxe: Fix slab-use-after-free Read in rxe_queue_cleanup bug
        iio: chemical: sps30: use aligned_s64 for timestamp
        iio: adc: ad7768-1: Fix insufficient alignment of timestamp.
        platform/x86: asus-wmi: Fix wlan_ctrl_by_user detection
        do_umount(): add missing barrier before refcount checks in sync case
        nvme: unblock ctrl state transition for firmware update
        drm/panel: simple: Update timings for AUO G101EVN010
        MIPS: Fix MAX_REG_OFFSET
        iio: adc: dln2: Use aligned_s64 for timestamp
        types: Complement the aligned types with signed 64-bit one
        usb: usbtmc: Fix erroneous generic_read ioctl return
        usb: usbtmc: Fix erroneous wait_srq ioctl return
        usb: usbtmc: Fix erroneous get_stb ioctl error returns
        USB: usbtmc: use interruptible sleep in usbtmc_read
        usb: typec: ucsi: displayport: Fix NULL pointer access
        usb: typec: tcpm: delay SNK_TRY_WAIT_DEBOUNCE to SRC_TRYWAIT transition
        usb: host: tegra: Prevent host controller crash when OTG port is used
        usb: gadget: tegra-xudc: ACK ST_RC after clearing CTRL_RUN
        ocfs2: stop quota recovery before disabling quotas
        ocfs2: implement handshaking with ocfs2 recovery thread
        ocfs2: switch osb->disable_recovery to enum
        module: ensure that kobject_put() is safe for module type kobjects
        xenbus: Use kref to track req lifetime
        usb: uhci-platform: Make the clock really optional
        iio: imu: st_lsm6dsx: fix possible lockup in st_lsm6dsx_read_tagged_fifo
        iio: imu: st_lsm6dsx: fix possible lockup in st_lsm6dsx_read_fifo
        iio: adis16201: Correct inclinometer channel resolution
        iio: adc: ad7606: fix serial register access
        staging: axis-fifo: Correct handling of tx_fifo_depth for size validation
        staging: axis-fifo: Remove hardware resets for user errors
        staging: iio: adc: ad7816: Correct conditional logic for store mode
        Input: synaptics - enable InterTouch on TUXEDO InfinityBook Pro 14 v5
        Input: synaptics - enable SMBus for HP Elitebook 850 G1
        Input: synaptics - enable InterTouch on Dell Precision M3800
        Input: synaptics - enable InterTouch on Dynabook Portege X30L-G
        Input: synaptics - enable InterTouch on Dynabook Portege X30-D
        net: dsa: b53: fix learning on VLAN unaware bridges
        net: dsa: b53: fix VLAN ID for untagged vlan on bridge leave
        net: dsa: b53: allow leaky reserved multicast
        netfilter: ipset: fix region locking in hash types
        can: gw: fix RCU/BH usage in cgw_create_job()
        rcu/kvfree: Add kvfree_rcu_mightsleep() and kfree_rcu_mightsleep()
        can: gw: use call_rcu() instead of costly synchronize_rcu()
        openvswitch: Fix unsafe attribute parsing in output_userspace()
        can: mcp251xfd: mcp251xfd_remove(): fix order of unregistration calls
        scsi: target: Fix WRITE_SAME No Data Buffer crash
        dm: fix copying after src array boundaries
        usb: chipidea: ci_hdrc_imx: implement usb_phy_init() error handling
        usb: chipidea: ci_hdrc_imx: use dev_err_probe()
        irqchip/gic-v2m: Prevent use after free of gicv2m_get_fwnode()
        irqchip/gic-v2m: Mark a few functions __init
        irqchip/gic-v2m: Add const to of_device_id
        Revert "drm/meson: vclk: fix calculation of 59.94 fractional rates"
        of: module: add buffer overflow check in of_modalias()
        PCI: imx6: Skip controller_id generation logic for i.MX7D
        net: fec: ERR007885 Workaround for conventional TX
        net: lan743x: Fix memleak issue when GSO enabled
        nvme-tcp: fix premature queue removal and I/O failover
        bnxt_en: Fix ethtool -d byte order for 32-bit values
        net: ipv6: fix UDPv6 GSO segmentation with NAT
        net: dlink: Correct endianness handling of led_mode
        net_sched: qfq: Fix double list add in class with netem as child qdisc
        net_sched: ets: Fix double list add in class with netem as child qdisc
        net_sched: hfsc: Fix a UAF vulnerability in class with netem as child qdisc
        net_sched: drr: Fix double list add in class with netem as child qdisc
        net/mlx5: E-switch, Fix error handling for enabling roce
        net/mlx5: Remove return statement exist at the end of void function
        net/mlx5: E-Switch, Initialize MAC Address for Default GID
        net/sched: act_mirred: don't override retval if we already lost the skb
        tracing: Fix oob write in trace_seq_to_buffer()
        iommu/vt-d: Apply quirk_iommu_igfx for 8086:0044 (QM57/QS57)
        iommu/amd: Fix potential buffer overflow in parse_ivrs_acpihid
        dm: always update the array size in realloc_argv on success
        dm-integrity: fix a warning on invalid table line
        wifi: brcm80211: fmac: Add error handling for brcmf_usb_dl_writeimage()
        mmc: renesas_sdhi: Fix error handling in renesas_sdhi_probe
        amd-xgbe: Fix to ensure dependent features are toggled with RX checksum offload
        parisc: Fix double SIGFPE crash
        i2c: imx-lpi2c: Fix clock count when probe defers
        EDAC/altera: Set DDR and SDMMC interrupt mask before registration
        EDAC/altera: Test the correct error reg offset
        drm/nouveau: Fix WARN_ON in nouveau_fence_context_kill()
        ALSA: usb-audio: Add second USB ID for Jabra Evolve 65 headset


    </details>

  2025-09-19T14:04:55Z by [Arian](mailto:arian.kulmer@web.de) [7c16c16e527d](https://github.com/LineageOS/android_kernel_xiaomi_sm8450/commit/7c16c16e527d)  [Review](https://review.lineageos.org/q/Ic6ac406d5b838709854668d36c8281be607a0964)
- `device/xiaomi/sm8450-common`: Revert &quot;sm8450-common: audio: Add stereo out to supported VOIP RX channels&quot;<br>
  2025-09-22T08:57:03Z by [Arian](mailto:arian.kulmer@web.de) [b1fde9da13a4](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/b1fde9da13a4)  [Review](https://review.lineageos.org/q/I579d43579f1922e5729f6256efd2964f008bc977)
- `device/xiaomi/sm8450-common`: sm8450-common: configs: taro: remove direct flag for VOIP RX<br>
  2025-09-22T08:57:04Z by [Vaibhav Raut](mailto:quic_vraut@quicinc.com) [ea8611a38e58](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/ea8611a38e58)  [Review](https://review.lineageos.org/q/I7be90063cef07ce14dc98ced6dc55056cf7fa054)
- `device/xiaomi/sm8450-common`: Revert &quot;sm8450-common: Move BT profiles props to vendor&quot;<br>
  2025-09-22T11:04:36Z by [Arian](mailto:arian.kulmer@web.de) [ff8ae6684e3f](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/ff8ae6684e3f)  [Review](https://review.lineageos.org/q/I1ab35e31f765c7ff7a4ec30ea5e80cdfc6a780da)
- `device/xiaomi/sm8450-common`: sm8450-common: BLE: Max GATT connections as a central are increased to 10<br>
  2025-09-22T11:04:36Z by [Nitin Shivpure](mailto:quic_nshivpur@quicinc.com) [2955fd415d02](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/2955fd415d02)  [Review](https://review.lineageos.org/q/Id29b8fb76bfa16cd332ccb60493ae544dbc8fd62)
- `device/xiaomi/sm8450-common`: sm8450-common: BT-Intf: Enable LEAudio bydefault for all Android-V upgrades.<br>
  2025-09-22T11:04:36Z by [Satheesh Kumar Pallemoni](mailto:quic_spallemo@quicinc.com) [e81a75ff0765](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/e81a75ff0765)  [Review](https://review.lineageos.org/q/Iaba5ca4be3c1e8ce2d7939b8b0aa330290b91de4)
- `device/xiaomi/sm8450-common`: sm8450-common: BT-Intf: Enable LEAudio swb bydefault for all Android-V upgrades.<br>
  2025-09-22T11:04:36Z by [Satheesh Kumar Pallemoni](mailto:quic_spallemo@quicinc.com) [3f98fe5ab19e](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/3f98fe5ab19e)  [Review](https://review.lineageos.org/q/Ic70d79e1385b71b8049eb4af6bc3b4abfe84caa4)
- `device/xiaomi/sm8450-common`: sm8450-common: BT-interfaces: Don&#x27;t enable ASHA for all chipsets.<br>
  2025-09-22T11:04:36Z by [Satheesh Kumar Pallemoni](mailto:quic_spallemo@quicinc.com) [0b2f232907d0](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/0b2f232907d0)  [Review](https://review.lineageos.org/q/I29bd43ac1cb41d3993c0ae7d29530b053a54f222)
- `device/xiaomi/sm8450-common`: sm8450-common: BT: Enable Battery Service profile (BAS)<br>
  2025-09-22T11:04:36Z by [Sai Aravind Chakravarthy Gosamsetti](mailto:quic_sgosamse@quicinc.com) [551f5c26dc85](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/551f5c26dc85)  [Review](https://review.lineageos.org/q/Ib31827ad8889aedd5af28aa0042ff8366b879375)
- `device/xiaomi/sm8450-common`: sm8450-common: BT: Enable PBAP SIM feature<br>
  2025-09-22T11:04:36Z by [Nitin Shivpure](mailto:quic_nshivpur@quicinc.com) [a486baa76526](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/a486baa76526)  [Review](https://review.lineageos.org/q/I7e0a90be6b3e0e4d2d7821f5fe777c11d7b85073)
- `device/xiaomi/sm8450-common`: sm8450-common: BT: Move SAP server property to system ext<br>
  2025-09-22T11:04:36Z by [Katta Karthik Reddy](mailto:quic_kattkart@quicinc.com) [bb03bd71593f](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/bb03bd71593f)  [Review](https://review.lineageos.org/q/I6f090afa6513b74d43aefb4d156bdff1bad532d1)
- `device/xiaomi/sm8450-common`: sm8450-common: Bluetooth: Changing vendor ID as QTI for Device ID Profile<br>
  2025-09-22T11:04:36Z by [Pragati](mailto:quic_pragati@quicinc.com) [070a1507c473](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/070a1507c473)  [Review](https://review.lineageos.org/q/I8e6b415b46f1724a8b8abe0f894b211613ec7e6d)
- `device/xiaomi/sm8450-common`: sm8450-common: Bluetooth: Disable HID Device Profile<br>
  2025-09-22T11:04:36Z by [Sai Aravind Chakravarthy Gosamsetti](mailto:quic_sgosamse@quicinc.com) [af9e05395119](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/af9e05395119)  [Review](https://review.lineageos.org/q/I6816924990928b4cf5972c0b07fad22846e22956)
- `device/xiaomi/sm8450-common`: sm8450-common: Enable AptX voice property<br>
  2025-09-22T11:04:36Z by [Satish Kumar Kodishala](mailto:quic_skodisha@quicinc.com) [589d6fd39dfa](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/589d6fd39dfa)  [Review](https://review.lineageos.org/q/Ic9f35d2a1ba5756f4a9b4a6fd24a5d2da047a11b)
- `device/xiaomi/sm8450-common`: sm8450-common: Enable LE audio offload support property<br>
  2025-09-22T11:04:36Z by [Satish Kumar Kodishala](mailto:quic_skodisha@quicinc.com) [aad700a2c6ac](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/aad700a2c6ac)  [Review](https://review.lineageos.org/q/I0c5ccb1c28abc5e5e4e499cff711d2c6da1dfd06)
- `device/xiaomi/sm8450-common`: sm8450-common: Enable bluetooth asha central profile from vendor.prop<br>
  2025-09-22T11:04:36Z by [Arian](mailto:arian.kulmer@web.de) [1f397c3d4002](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/1f397c3d4002)  [Review](https://review.lineageos.org/q/I2a84d12d58b7c4a6c94cb88877d80d59556a7d43)
- `device/xiaomi/sm8450-common`: sm8450-common: Enable bluetooth avrcp controller profile<br>
  2025-09-22T11:04:36Z by [Arian](mailto:arian.kulmer@web.de) [56fa2736b78e](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/56fa2736b78e)  [Review](https://review.lineageos.org/q/I46cb81127967d55458e0a61e81b6cce4fdf37e40)
- `device/xiaomi/sm8450-common`: sm8450-common: Enable bluetooth sap server profile<br>
  2025-09-22T11:04:36Z by [Arian](mailto:arian.kulmer@web.de) [2126d513f4d0](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/2126d513f4d0)  [Review](https://review.lineageos.org/q/I911b55034ba1fd4d73cd90db2d7eaf219c43e757)
- `device/xiaomi/sm8450-common`: sm8450-common: HFP: AG: Enable AptX voice power management prop<br>
  2025-09-22T11:04:36Z by [Satish Kumar Kodishala](mailto:quic_skodisha@quicinc.com) [29f826c70dd5](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/29f826c70dd5)  [Review](https://review.lineageos.org/q/I3d2f605cad0ffa8132c06f05b72b37492279f39e)
- `device/xiaomi/sm8450-common`: sm8450-common: Le-Audio: Enable C-I-S-&gt;SCO sync for Android-V targets.<br>
  2025-09-22T11:04:36Z by [Satheesh Kumar Pallemoni](mailto:quic_spallemo@quicinc.com) [c35d8403efdf](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/c35d8403efdf)  [Review](https://review.lineageos.org/q/I34917917ebec9faa0187042d84bfd3ce7276fb8c)
- `device/xiaomi/sm8450-common`: sm8450-common: Set Class of device from property<br>
  2025-09-22T11:04:36Z by [Venkata Jagadeesh Garaga](mailto:quic_vgaraga@quicinc.com) [98a54a147024](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/98a54a147024)  [Review](https://review.lineageos.org/q/I03be6eb5dcebf80e4d32e78e2792e789627bb104)
- `lineage/wiki`: wiki: Add OnePlus Nord CE4 (benz)<br>
  2025-09-25T09:01:35Z by [inferno0230](mailto:mail@inferno0230.in) [afba45b7da71](https://github.com/LineageOS/lineage_wiki/commit/afba45b7da71)  [Review](https://review.lineageos.org/q/Ic27251456c83ecd1e1aec3df67337e0957cf7a89)
- `state`: Save state of mondrian-2025-09-26-02-26-15-release<br>
  2025-09-26T02:47:16Z by [kxxt](mailto:rsworktech@outlook.com) [23edab3ea76c](https://github.com/android-kxxt/state/commit/23edab3ea76c) 
- `lineage/wiki`: wiki: Add OnePlus 12R (aston)<br>
  2025-09-26T06:40:04Z by [inferno0230](mailto:mail@inferno0230.in) [0c5e7876ea68](https://github.com/LineageOS/lineage_wiki/commit/0c5e7876ea68)  [Review](https://review.lineageos.org/q/I9f8a05ffab8e5d8dbd79b5596ac2084941944b39)
- `lineage/wiki`: wiki: Swap aston.png to one that matches other OnePlus devices<br>
  2025-09-26T07:07:04Z by [LuK1337](mailto:priv.luk@gmail.com) [cd0ce91fdcf4](https://github.com/LineageOS/lineage_wiki/commit/cd0ce91fdcf4)  [Review](https://review.lineageos.org/q/Ida12fa027d22371271cf17e781e1a9157cf51a3f)
- `lineage/mirror`: Updated to 26-Sep-2025 11:59 UTC<br>
  2025-09-26T11:59:28Z by [Michael Bestas](mailto:mkbestas@gmail.com) [196583b5d40b](https://github.com/LineageOS/mirror/commit/196583b5d40b) 
- `state`: manually update last build<br>
  2025-09-26T12:43:16Z by [kxxt](mailto:rsworktech@outlook.com) [99eb60ae64b6](https://github.com/android-kxxt/state/commit/99eb60ae64b6) 
- `ota`: Update OTA metadata for mondrian (UNOFFICIAL, Release)<br>
  2025-09-26T12:52:21Z by [kxxt](mailto:rsworktech@outlook.com) [7f47d97e4a35](https://github.com/android-kxxt/ota/commit/7f47d97e4a35) 
- `state`: Save state of lmi-2025-09-26-09-03-32-test<br>
  2025-09-26T12:52:52Z by [kxxt](mailto:rsworktech@outlook.com) [cffc0c3ef50d](https://github.com/android-kxxt/state/commit/cffc0c3ef50d) 
- `state`: Generate changelog for lmi-2025-09-26-09-03-32-test<br>
  2025-09-26T12:53:17Z by [kxxt](mailto:rsworktech@outlook.com) [d3ce001766c1](https://github.com/android-kxxt/state/commit/d3ce001766c1) 
- `ota`: Update OTA metadata for lmi (UNOFFICIAL, Test)<br>
  2025-09-26T13:02:40Z by [kxxt](mailto:rsworktech@outlook.com) [fc73044ffb91](https://github.com/android-kxxt/ota/commit/fc73044ffb91) 
- `state`: Generate changelog for mondrian-2025-09-26-02-26-15-release<br>
  2025-09-26T13:10:21Z by [kxxt](mailto:rsworktech@outlook.com) [33e0c9e9f92d](https://github.com/android-kxxt/state/commit/33e0c9e9f92d) 
- `lineage/scripts`: build-webview: Update default webview to 140.0.7339.207<br>
  2025-09-26T15:50:33Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [51478520409a](https://github.com/LineageOS/scripts/commit/51478520409a)  [Review](https://review.lineageos.org/q/Iddbd70ec4ebb82b204106e86e1783d0c1a52d238)
- `external/chromium-webview/patches`: Update Chromium Webview to 140.0.7339.207<br>
  2025-09-26T15:55:19Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [22fb1dd3d992](https://github.com/LineageOS/android_external_chromium-webview_patches/commit/22fb1dd3d992)  [Review](https://review.lineageos.org/q/I0e21561834cd02ef5535090ad3746532437539e3)
- `packages/apps/FMRadio`: FmService: Set RECEIVER_NOT_EXPORTED<br>
  2025-09-26T18:30:01Z by [Cyber Knight](mailto:cyberknight755@gmail.com) [7e89b012877f](https://github.com/LineageOS/android_packages_apps_FMRadio/commit/7e89b012877f)  [Review](https://review.lineageos.org/q/I00627c63d1da2a9a91585e3ff5ae55d260076fce)
- `packages/apps/Jelly`: Jelly: Implement Web Share API<br>
  2025-09-26T20:58:10Z by [SaeedDev94](mailto:saeedp47@gmail.com) [67d7b58d0063](https://github.com/LineageOS/android_packages_apps_Jelly/commit/67d7b58d0063)  [Review](https://review.lineageos.org/q/I46f47cef931bec94ce42e142056fe028761ba16a)
- `packages/apps/Jelly`: Jelly: Load scripts once<br>
  2025-09-26T21:00:41Z by [Luca Stefani](mailto:luca.stefani.ge1@gmail.com) [2d8559bd5468](https://github.com/LineageOS/android_packages_apps_Jelly/commit/2d8559bd5468)  [Review](https://review.lineageos.org/q/Ia90e0a99aaf6e159e7e19bfac54feeb98f7e2056)
- `lineage/mirror`: Updated lineage-minimal to 26-Sep-2025 22:02 UTC<br>
  2025-09-26T22:02:04Z by [Tim Schumacher](mailto:timschumi@gmx.de) [6140202f2046](https://github.com/LineageOS/mirror/commit/6140202f2046)  [Review](https://review.lineageos.org/q/Ia6fbf2b105bb3933ac0be4c5d5baa2b2b1745062)
- `device/xiaomi/sm8450-common`: sm8450-common: overlay: Bring back QTI UIM GBA package<br>
  2025-09-27T10:58:56Z by [Fiqri Ardyansyah](mailto:fiqri191002@gmail.com) [5f7fddd1c77b](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/5f7fddd1c77b)  [Review](https://review.lineageos.org/q/I13d06b1b01dff58d0ca3ad4772ac8292e6c37f8c)
- `device/xiaomi/sm8450-common`: sm8450-common: Import missing permission for QCC app<br>
  2025-09-27T11:07:16Z by [Fiqri Ardyansyah](mailto:fiqri191002@gmail.com) [3c24511567a1](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/3c24511567a1)  [Review](https://review.lineageos.org/q/I76e2ac0fe03e61e100628104533d5e8013e3861f)
- `vendor/xiaomi/sm8450-common`: sm8450-common: Import missing permission for QCC app<br>
  2025-09-27T11:08:06Z by [Fiqri Ardyansyah](mailto:fiqri191002@gmail.com) [807c31b3fac3](https://github.com/TheMuppets/proprietary_vendor_xiaomi_sm8450-common/commit/807c31b3fac3) 
- `device/xiaomi/sm8450-common`: sm8450-common: taro: Set SoC manufacturer and model properties<br>
  2025-09-27T11:14:24Z by [Roopesh Nataraja](mailto:roopeshr@codeaurora.org) [fa0c08d6d3f2](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/fa0c08d6d3f2)  [Review](https://review.lineageos.org/q/I69a3f051e0ae812a5a88170f10d586f2009b5109)
- `device/xiaomi/sm8450-common`: sm8450-common: taro: Move soc model property to qcv utils<br>
  2025-09-27T11:15:02Z by [Benergy Meenan Ravuri](mailto:bravuri@codeaurora.org) [dd444e2d93ac](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/dd444e2d93ac)  [Review](https://review.lineageos.org/q/I51f698e662fee1db731e1781965e8736b60f6364)
- `device/xiaomi/sm8450-common`: sm8450-common: taro: update API level to 32<br>
  2025-09-27T11:16:22Z by [Benergy Meenan Ravuri](mailto:quic_bravuri@quicinc.com) [b9f583834f2b](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/b9f583834f2b)  [Review](https://review.lineageos.org/q/I56416ba1f5d72673638c61a4e2ffbf677bc0a19f)
- `device/xiaomi/mondrian`: mondrian: audio: Enable get_module_version for hotword sound model config<br>
  2025-09-27T11:29:18Z by [Arian](mailto:arian.kulmer@web.de) [3d5764bcb943](https://github.com/LineageOS/android_device_xiaomi_mondrian/commit/3d5764bcb943)  [Review](https://review.lineageos.org/q/I11858bca5d44884188f33a7462b6d236aef0b482)
- `hardware/lineage/interfaces`: sensors: Add a sensors 2.0 -&gt; 1.0 subhal wrapper<br>
  2025-09-27T13:25:38Z by [bengris32](mailto:bengris32@protonmail.ch) [01b0b5b7e99c](https://github.com/LineageOS/android_hardware_lineage_interfaces/commit/01b0b5b7e99c)  [Review](https://review.lineageos.org/q/I2f76c69be280f09c8463442f47d9afd14a7ad67c)
- `cicd`: ci: include changelog and tree status link in release notes<br>
  2025-09-27T14:01:14Z by [kxxt](mailto:rsworktech@outlook.com) [af025f6cd809](https://github.com/android-kxxt/cicd/commit/af025f6cd809) 
- `cicd`: ci: continue even if changelog generation fail<br>
  2025-09-27T14:02:46Z by [kxxt](mailto:rsworktech@outlook.com) [85392206c3ff](https://github.com/android-kxxt/cicd/commit/85392206c3ff) 
- `external/chromium-webview/prebuilt/arm`: Update Chromium Webview arm to 140.0.7339.207<br>
  2025-09-27T14:22:39Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [35d15d3fa71f](https://github.com/LineageOS/android_external_chromium-webview_prebuilt_arm/commit/35d15d3fa71f)  [Review](https://review.lineageos.org/q/I0e062447988f4258877a7732729abd386b1992bc)
- `external/chromium-webview/prebuilt/arm64`: Update Chromium Webview arm64 to 140.0.7339.207<br>
  2025-09-27T14:22:45Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [676064763fbc](https://github.com/LineageOS/android_external_chromium-webview_prebuilt_arm64/commit/676064763fbc)  [Review](https://review.lineageos.org/q/I8bc47d1ea2200a4a92f48ca2ebf94a500cc49854)
- `external/chromium-webview/prebuilt/x86`: Update Chromium Webview x86 to 140.0.7339.207<br>
  2025-09-27T14:22:49Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [c18e2192efb4](https://github.com/LineageOS/android_external_chromium-webview_prebuilt_x86/commit/c18e2192efb4)  [Review](https://review.lineageos.org/q/I808dab1d7696f1ed35799c1f0f4e472a952afcc6)
- `external/chromium-webview/prebuilt/x86_64`: Update Chromium Webview x86_64 to 140.0.7339.207<br>
  2025-09-27T14:22:53Z by [Kevin F. Haggerty](mailto:haggertk@lineageos.org) [856f1ce05579](https://github.com/LineageOS/android_external_chromium-webview_prebuilt_x86_64/commit/856f1ce05579)  [Review](https://review.lineageos.org/q/Ie881b29bcf38b04e4f9b0d6ce23755797b742ffb)
- `device/xiaomi/sm8450-common`: sm8450-common: Set 120Hz frame rate multiple threshold<br>
  2025-09-27T15:27:05Z by [Ken Huang](mailto:kenbshuang@google.com) [e63915623f19](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/e63915623f19)  [Review](https://review.lineageos.org/q/Ie638f9dcf11e25bdd903d6cde2d0eeb794668e52)
- `device/xiaomi/sm8450-common`: sm8450-common: sensors: Add even more padding to oem_msg<br>
  2025-09-27T17:03:37Z by [Arian](mailto:arian.kulmer@web.de) [ba5d180baef0](https://github.com/LineageOS/android_device_xiaomi_sm8450-common/commit/ba5d180baef0)  [Review](https://review.lineageos.org/q/Id09b74a1bf2125a136861012be81fadc7a15ba3f)
- `lineage/hudson`: 洱海<br>
  2025-09-28T09:20:01Z by [LuK1337](mailto:priv.luk@gmail.com) [c9c398aeb02e](https://github.com/LineageOS/hudson/commit/c9c398aeb02e)  [Review](https://review.lineageos.org/q/I8ae09671d6ee38b4dcb91287c04335d623d88c52)
- `lineage/wiki`: wiki: Add erhai<br>
  2025-09-28T09:20:40Z by [LuK1337](mailto:priv.luk@gmail.com) [9264484e04e6](https://github.com/LineageOS/lineage_wiki/commit/9264484e04e6)  [Review](https://review.lineageos.org/q/If20bea233429721b7a6e4aece538d7f87eb0d67e)
- `lineage/scripts`: best-caf-kernel: chmod +x<br>
  2025-09-28T19:29:32Z by [LuK1337](mailto:priv.luk@gmail.com) [7b8ba9e060e4](https://github.com/LineageOS/scripts/commit/7b8ba9e060e4)  [Review](https://review.lineageos.org/q/If94008167aa1b756fd5a19935ff72f08e43cde57)
- `lineage/mirror`: Updated to 28-Sep-2025 22:01 UTC<br>
  2025-09-28T22:01:24Z by [Tim Schumacher](mailto:timschumi@gmx.de) [2860df006944](https://github.com/LineageOS/mirror/commit/2860df006944)  [Review](https://review.lineageos.org/q/I30c7032b5fa280cad8b40e2b1e9d1872f73e7c3e)
- `lineage/hudson`: Regenerate device dependency mappings<br>
  2025-09-28T23:30:47Z by [LineageOS Infra](mailto:infra@lineageos.org) [25b46d65b53e](https://github.com/LineageOS/hudson/commit/25b46d65b53e)  [Review](https://review.lineageos.org/q/I79e435b374731646f37b0e860952bf7cfe41e9bf)
- `lineage/hudson`: Regenerate device dependency mappings<br>
  2025-09-29T23:30:47Z by [LineageOS Infra](mailto:infra@lineageos.org) [8ba473930d96](https://github.com/LineageOS/hudson/commit/8ba473930d96)  [Review](https://review.lineageos.org/q/Ib4ff87a854372815d9f2e67763642f74b9f983e0)
- `packages/apps/Glimpse`: Glimpse: Add file size to media info<br>
  2025-09-30T18:44:31Z by [Luca Stefani](mailto:luca.stefani.ge1@gmail.com) [6fcd70c0cbba](https://github.com/LineageOS/android_packages_apps_Glimpse/commit/6fcd70c0cbba)  [Review](https://review.lineageos.org/q/I1db5084b883f668ad50b3d3bd038cb36e95ccce3)
- `device/qcom/sepolicy_vndr/legacy-um`: sepolicy_vndr: lito: Label more wakeup nodes<br>
  2025-10-01T23:15:14Z by [Michael Bestas](mailto:mkbestas@lineageos.org) [d7ffab38109b](https://github.com/LineageOS/android_device_qcom_sepolicy_vndr/commit/d7ffab38109b)  [Review](https://review.lineageos.org/q/I9cdf901385b383f2243429a911a68a1a7de61049)
- `lineage-sdk`: Automatic translation import<br>
  2025-10-01T23:32:42Z by [LineageOS Infra](mailto:infra@lineageos.org) [a0ab6a82f473](https://github.com/LineageOS/android_lineage-sdk/commit/a0ab6a82f473)  [Review](https://review.lineageos.org/q/I0418ca2b3d5ec8f9924c96979c408cb23166b8a4)
- `packages/apps/Glimpse`: Automatic translation import<br>
  2025-10-01T23:32:43Z by [LineageOS Infra](mailto:infra@lineageos.org) [bf55f6adfe03](https://github.com/LineageOS/android_packages_apps_Glimpse/commit/bf55f6adfe03)  [Review](https://review.lineageos.org/q/I1a0d314b92b417c364ddf6a692a5e59caa2fe3d6)
- `packages/apps/LineageParts`: Automatic translation import<br>
  2025-10-01T23:32:44Z by [LineageOS Infra](mailto:infra@lineageos.org) [362124708beb](https://github.com/LineageOS/android_packages_apps_LineageParts/commit/362124708beb)  [Review](https://review.lineageos.org/q/I1133070c92df17c50265cf70c154c3c634646a90)
- `packages/apps/Settings`: Automatic translation import<br>
  2025-10-01T23:32:45Z by [LineageOS Infra](mailto:infra@lineageos.org) [02302c34d4a5](https://github.com/LineageOS/android_packages_apps_Settings/commit/02302c34d4a5)  [Review](https://review.lineageos.org/q/I1e7b20d897c113bd93af727c4e055c1cab17ef14)
- `packages/apps/Trebuchet`: Automatic translation import<br>
  2025-10-01T23:32:46Z by [LineageOS Infra](mailto:infra@lineageos.org) [3c1310fa0193](https://github.com/LineageOS/android_packages_apps_Trebuchet/commit/3c1310fa0193)  [Review](https://review.lineageos.org/q/I938f21f62daa5744efa7d5ef969c24053a88ecfb)
- `packages/apps/Twelve`: Automatic translation import<br>
  2025-10-01T23:32:46Z by [LineageOS Infra](mailto:infra@lineageos.org) [5463caa533f7](https://github.com/LineageOS/android_packages_apps_Twelve/commit/5463caa533f7)  [Review](https://review.lineageos.org/q/I47a358b9db21031f8f5e141826f0b2fe55d9e43a)
- `packages/apps/Updater`: Automatic translation import<br>
  2025-10-01T23:32:47Z by [LineageOS Infra](mailto:infra@lineageos.org) [312b283349a0](https://github.com/LineageOS/android_packages_apps_Updater/commit/312b283349a0)  [Review](https://review.lineageos.org/q/I13efc3054e54ac69e43f3853d894e695030d8323)
- `packages/resources/devicesettings`: Automatic translation import<br>
  2025-10-01T23:32:48Z by [LineageOS Infra](mailto:infra@lineageos.org) [885204a06c9f](https://github.com/LineageOS/android_packages_resources_devicesettings/commit/885204a06c9f)  [Review](https://review.lineageos.org/q/I1e1410b16c78e5c926d0c5cc748d6e1686d577ed)
- `lineage/wiki`: wiki: devices: aston/benz: Add init_boot to flash partitions before recovery<br>
  2025-10-02T10:29:06Z by [inferno0230](mailto:mail@inferno0230.in) [fb0292486ce1](https://github.com/LineageOS/lineage_wiki/commit/fb0292486ce1)  [Review](https://review.lineageos.org/q/I763c85d81c3a369b1f7309a029cc4f5ce77fa77f)
- `lineage/wiki`: devices: salami: Add init_boot to flash partitions before recovery<br>
  2025-10-02T21:40:54Z by [Bruno Martins](mailto:bgcngm@gmail.com) [ee4ffa2f8b5e](https://github.com/LineageOS/lineage_wiki/commit/ee4ffa2f8b5e)  [Review](https://review.lineageos.org/q/I79afb762f0f65ac87f56cbc324ea384e0ea71e5b)
- `ota`: Update OTA metadata for lmi (UNOFFICIAL, Test)<br>
  2025-10-03T06:57:55Z by [kxxt](mailto:rsworktech@outlook.com) [6db92d19ff05](https://github.com/android-kxxt/ota/commit/6db92d19ff05) 
