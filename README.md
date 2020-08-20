# PicoDomain

The PicoDomain is a compact high-fidelity collection of Zeek logs from a realistic intrusion using relevant Tools, Techniques, and Procedures.  It is designed to provide representative traffic of a small Windows domain and be small enough to be used during rapid prototyping. 

# Files

## Red Log

This file contains a record of the adversarial actions that took place within the environment. It includes the machines involved, targeted user (either the user account used to conduct an action or the user compromised from an action), and the action that occurred. The timestamps were recorded manually and may have variations between them but are accurate within 1 minute of the actual event

## Zeek Logs

The Zeek logs (formerly known as Bro logs) are from the July 19th 2019 to July 21st 2019. They contain a robust selection of log types used by the Zeek installation on Security Onion 16.04 and would be representative of what would be collected by Zeek sensors in most modern sensing environments. Zeek was configured to log in UTC and save logs as JSON as is the current industry standard. The logs available are the following types: conn, dce_rpc, dhcp, dns, files, http, kerberos, known_hosts, known_servieces, ntlm, pe, smb_files, smb_mapping, software, ssl, weird, and x509.

## PicoDomain.pdf

This paper describes the development of the dataset, the environment in which it was developed, and its intended uses. 
