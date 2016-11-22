# Great Interview Questions

### Networks 
| Question      | Answer      |
|---------------|-------------|
|               |             |

### Systems
| Question      | Answer      |
|---------------|-------------|
|               |             |

### Security
| # |Question     | Answer      |
|---|-------------|-------------|
| 1 | What is a public key finger print? What can you use if for and when? Do only public keys have fingerprints? | It is a sequence of bytes, a shortened version of the full public key for which it is the fingerprint of. The fingerprint is generated by applying a cryptographic hash function (any cryptographic function can be used for that (SHA1 or MD5), the lenght of the fingerprint desired being the primary factor for choosing (md5 produces a 128 bit fingerprint, sha1 - 160 bit) ) to the initial public key. The primary uses include (i) simplified key management; (ii) identification of the public key; (iii) |
| 2 | | |

```
vagrant@node1:~/.ssh$ ssh-keygen -lf public_git.key 
4096 ed:58:09:fc:95:63:9b:99:30:77:55:de:68:0e:11:93  darbas.mindaugas@gmail.com (RSA)
```

```
mindaugas@Mindaugas-Lenovo-Y50-70:~/.ssh/private_keys$ ssh-add node3.priv 
Enter passphrase for node3.priv: 
Identity added: node3.priv (node3.priv)
mindaugas@Mindaugas-Lenovo-Y50-70:~/.ssh/private_keys$ ssh-add -l
4096 70:33:6c:5d:30:38:42:f6:dc:54:1a:f2:03:05:84:cd node3.priv (RSA)
```

### C/C++ 
| Question      | Answer      |
|---------------|-------------|
|               |             |

### Git
``` How sync branches from remote to local when remote branches were deleted?
```
``` Blah
```

### Java
| Question      | Answer      |
|---------------|-------------|
|               |             |

### Android Development
| Question      | Answer      |
|---------------|-------------|
|               |             |

### QA/Testing
| Question      | Answer      |
|---------------|-------------|
|               |             |
