# Microsoft-Defender---Mitigating-Security-Recommendations

# What does the Secure Score represent in Defender?
- The higher the secure score, the more secure your environment is.

# Azure security benchmark
- It is an initiative that's defined in the Azure policy service
- Initatives are a group of policies. They are usually created with a common cause.
- The security posture of your resources are compared against the Azure Security Benchmark.
- The recommendations come from the initiatives (group of policies) in the Azure Security Benchmark

# How to view where the policies apply?
- Environment settings > select subscription > Security policy
- Admins can view the amount of policies applied within the initiatives

# Recommendations
- Defender will provide recommendations on what should be done to be compliant
- It would give you controls and best practices to implement.
- The recommendations will provide instructions on how to mitigate

# Regulatory Compliance
- This tells you how compliant your resources are compared to the Azure Security Benchmark.
- Other security standards can be applied like ISO 27001, PCI DSS, and more.


# Continous Recommendations
- As soon as an admin deploys a resource in a subscription that is linked to Microsoft Defender, Defender will immediately check for vulnerabiltiies and provide recommendations

# Enable Enhanced Security
- If admins want to use Just-in-Time access (JIT), then admins must have enhanced security in place
- Enhanced Security has more security features


# Vulnerability Assessments
- From Microsoft Defender, admins can deploy vulnerability assessments onto virtual machines 
- Qualys scanner, an external party, can be installed via an extension and perform a vulnerability assessment 
- An extension to the Azure Virtual Machine will be installed when admins opt to deploy the vulnerability assessment solution
- Scanning begins immediately from Qualys when the extension is installed
