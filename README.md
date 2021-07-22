# ploigos-example-oscap-content
Example OSCAP Content, Profiles and Tailoring definitions.

**WARNING** Not intended for production use but rather used to work around CVE and Compliance
errors when using the reference app and as reference for how to use tailing files when running
Ploigos.

# creation

Created with [SCAP Workbench](https://www.open-scap.org/tools/scap-workbench/).

# tailoring files

## xccdf_com.ploigos_profile_default_cve_ploigos_reference_apps-tailoring.xml

Tailoring file for CVE Vulnerability scans.

## xccdf_com.ploigos_profile_standard_compliance_ploigos_reference_apps-tailoring.xml

Tailoring file for Compliance scans.

## xccdf_com.redhat.ploigos_profile_example_ubi8-tailoring-xccdf.xml

**DEPRECATED** This one was replaced by [xccdf_com.ploigos_profile_standard_compliance_ploigos_reference_apps-tailoring.xml](./xccdf_com.ploigos_profile_standard_compliance_ploigos_reference_apps-tailoring.xml) and will eventually be
deleted.
