orchidsconfdir = $(sysconfdir)/orchids
orchidsruledir = $(orchidsconfdir)/rules

orchidsrule_DATA = \
  pid_tracker.rule \
  apachessl.rule \
  portscan.rule \
  dhcp_lease_check.rule \
  password_sniff.rule \
  anti_ssh_scan.rule \
  lin24_ptrace.rule\
  listen_atm_vcc.rule\
  lock_lease_dos.rule\
  leak_memory.rule\
  prelude_anti_ssh_scan.rule\
  prelude_apachessl.rule\
  prelude_dhcp_lease_check.rule\
  prelude_leak_memory.rule\
  prelude_listen_atm_vcc.rule\
  prelude_lock_lease_dos.rule\
  prelude_password_sniff.rule\
  prelude_portscan.rule\
  prelude_ssh_bruteforce.rule\
  ssh_failed_burst.rule\
  ssh_failed_long_window.rule

EXTRA_DIST = $(orchidsrule_DATA) test/*.rule
