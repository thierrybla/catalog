# Security Scan

## Helm-Chart

##### Scan Results

2021-12-04T19:51:55.158Z	[34mINFO[0m	Detected config files: 1
#### podgrab/templates/common.yaml
    
**kubernetes**

      
| No Vulnerabilities found         |
|:---------------------------------|

      

## Containers

##### Detected Containers

          tccr.io/truecharts/alpine:v3.14.2@sha256:4095394abbae907e94b1f2fd2e2de6c4f201a5b9704573243ca8eb16db8cdb7c
          tccr.io/truecharts/podgrab:v1.0.0@sha256:069fb1ef81d47a37137da2cfd249423c8dc330086c2a2e1271c5895f9f8cae9f

##### Scan Results

**Container: tccr.io/truecharts/alpine:v3.14.2@sha256:4095394abbae907e94b1f2fd2e2de6c4f201a5b9704573243ca8eb16db8cdb7c**

2021-12-04T19:51:56.895Z	[34mINFO[0m	Detected OS: alpine
2021-12-04T19:51:56.895Z	[34mINFO[0m	Detecting Alpine vulnerabilities...
2021-12-04T19:51:56.901Z	[34mINFO[0m	Number of language-specific files: 0
#### tccr.io/truecharts/alpine:v3.14.2@sha256:4095394abbae907e94b1f2fd2e2de6c4f201a5b9704573243ca8eb16db8cdb7c (alpine 3.14.2)
    
**alpine**

      
| Package         |    Vulnerability   |   Severity  |  Installed Version | Fixed Version |                   Links                   |
|:----------------|:------------------:|:-----------:|:------------------:|:-------------:|-----------------------------------------|
| busybox         |    CVE-2021-42378   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42378">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42378</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42379   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42379">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42379</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42380   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42380">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42380</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42381   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42381">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42381</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42382   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42382">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42382</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42383   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42384   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42384">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42384</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42385   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42385">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42385</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42386   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42386">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42386</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42374   |   MEDIUM  |  1.33.1-r3 | 1.33.1-r4 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42374">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42374</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| busybox         |    CVE-2021-42375   |   MEDIUM  |  1.33.1-r3 | 1.33.1-r5 | <details><summary>Click to expand!</summary><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42378   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42378">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42378</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42379   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42379">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42379</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42380   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42380">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42380</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42381   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42381">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42381</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42382   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42382">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42382</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42383   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42384   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42384">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42384</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42385   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42385">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42385</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42386   |   HIGH  |  1.33.1-r3 | 1.33.1-r6 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42386">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42386</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42374   |   MEDIUM  |  1.33.1-r3 | 1.33.1-r4 | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42374">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-42374</a><br><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |
| ssl_client         |    CVE-2021-42375   |   MEDIUM  |  1.33.1-r3 | 1.33.1-r5 | <details><summary>Click to expand!</summary><a href="https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/">https://jfrog.com/blog/unboxing-busybox-14-new-vulnerabilities-uncovered-by-claroty-and-jfrog/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/6T2TURBYYJGBMQTTN2DSOAIQGP7WCPGV/</a><br><a href="https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/">https://lists.fedoraproject.org/archives/list/package-announce@lists.fedoraproject.org/message/UQXGOGWBIYWOIVXJVRKHZR34UMEHQBXS/</a><br></details>  |

**Container: tccr.io/truecharts/podgrab:v1.0.0@sha256:069fb1ef81d47a37137da2cfd249423c8dc330086c2a2e1271c5895f9f8cae9f**

2021-12-04T19:52:00.409Z	[34mINFO[0m	Detected OS: alpine
2021-12-04T19:52:00.409Z	[33mWARN[0m	This OS version is not on the EOL list: alpine 3.15
2021-12-04T19:52:00.409Z	[34mINFO[0m	Detecting Alpine vulnerabilities...
2021-12-04T19:52:00.410Z	[34mINFO[0m	Number of language-specific files: 1
2021-12-04T19:52:00.410Z	[34mINFO[0m	Detecting gobinary vulnerabilities...
2021-12-04T19:52:00.411Z	[33mWARN[0m	This OS version is no longer supported by the distribution: alpine 3.15.0
2021-12-04T19:52:00.411Z	[33mWARN[0m	The vulnerability detection may be insufficient because security updates are not provided
#### tccr.io/truecharts/podgrab:v1.0.0@sha256:069fb1ef81d47a37137da2cfd249423c8dc330086c2a2e1271c5895f9f8cae9f (alpine 3.15.0)
    
**alpine**

      
| No Vulnerabilities found         |
|:---------------------------------|

      
**gobinary**

      
| Package         |    Vulnerability   |   Severity  |  Installed Version | Fixed Version |                   Links                   |
|:----------------|:------------------:|:-----------:|:------------------:|:-------------:|-----------------------------------------|
| github.com/satori/go.uuid         |    GO-2020-0018   |   UNKNOWN  |  v1.2.0 | v1.2.1-0.20181016170032-d91630c85102 | <details><summary>Click to expand!</summary></details>  |
| golang.org/x/crypto         |    CVE-2020-29652   |   HIGH  |  v0.0.0-20200820211705-5c72a883971a | v0.0.0-20201216223049-8b5274cf687f | <details><summary>Click to expand!</summary><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-29652">https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-29652</a><br><a href="https://go-review.googlesource.com/c/crypto/+/278852">https://go-review.googlesource.com/c/crypto/+/278852</a><br><a href="https://groups.google.com/g/golang-announce/c/ouZIlBimOsE?pli=1">https://groups.google.com/g/golang-announce/c/ouZIlBimOsE?pli=1</a><br><a href="https://linux.oracle.com/cve/CVE-2020-29652.html">https://linux.oracle.com/cve/CVE-2020-29652.html</a><br><a href="https://linux.oracle.com/errata/ELSA-2021-1796.html">https://linux.oracle.com/errata/ELSA-2021-1796.html</a><br><a href="https://lists.apache.org/thread.html/r68032132c0399c29d6cdc7bd44918535da54060a10a12b1591328bff@%3Cnotifications.skywalking.apache.org%3E">https://lists.apache.org/thread.html/r68032132c0399c29d6cdc7bd44918535da54060a10a12b1591328bff@%3Cnotifications.skywalking.apache.org%3E</a><br><a href="https://nvd.nist.gov/vuln/detail/CVE-2020-29652">https://nvd.nist.gov/vuln/detail/CVE-2020-29652</a><br></details>  |
