# Privilege Escalation Notes Template

## Context

- **Host / Target:**  
- **Operating System:**  
- **Current User / Context:**  
- **Goal:**  
- **Date:**  

## Initial Position

Document what level of access you started with.

## Enumeration Checklist

### System Information
- hostname
- OS version
- architecture
- patch level
- domain / workgroup

### User Context
- current user
- groups
- token privileges
- sudo rights / admin rights

### Services and Processes
- interesting services
- weak service permissions
- unquoted service paths
- writable executables
- unusual running processes

### Scheduled Tasks / Cron
- scheduled tasks
- cron jobs
- writable task/script paths

### Filesystem
- writable directories
- sensitive files
- config files
- scripts running as elevated users

### Credentials
- stored credentials
- config file secrets
- history files
- key material
- password reuse opportunities

### Software / Applications
- vulnerable software
- misconfigured software
- outdated binaries
- third-party services

### Network / Trust Relationships
- local shares
- remote shares
- domain trust clues
- local admin reuse possibilities

## Candidate Escalation Paths

### Path 1
- **Vector:**  
- **Why it looked promising:**  
- **Validation notes:**  
- **Outcome:**  

### Path 2
- **Vector:**  
- **Why it looked promising:**  
- **Validation notes:**  
- **Outcome:**  

## Successful Escalation

### Technique Used
Describe the successful privilege escalation vector.

### Steps
1.  
2.  
3.  

### Proof
Describe proof of elevated access.

## Commands / Artifacts

```text
Add key commands, outputs, paths, or artifacts here.
