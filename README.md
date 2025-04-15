# AArch32 ISA XML for A-profile Architecture (2025-03)

## Release Date 2025-05-30

## Introduction

This is the *2025-03* release of the
AArch32 ISA XML for A-profile Architecture.

The [Proprietary
Notice](ISA_AArch32_xml_A_profile-2025-03/xhtml/notice.html) gives
details of the terms and conditions under which this package is
provided.

If you have comments on the content of this package, create a ticket at
<https://support.developer.arm.com>. As part of the ticket, include:

- The title, \"AArch32 ISA XML for A-profile Architecture\".
- The version, \"2025-03\".
- The section name to which your comments refer.
- A concise explanation of your comments.

## Product Status

The information relating to the 2024 Extensions is at Alpha quality.
Alpha quality means that most major features of the specification are
described in this release, but some features and details might be
missing. The information relating to the rest of the A-profile
Architecture is at Beta quality. Beta quality means that all major
features of the specification are described, but some details might be
missing.

### Change history

Many simple clarifications and corrections are present, but are too
small to be listed here. Some minor formatting changes are suppressed
and not highlighted in the diff output.

### Known issues

All issues identified in the below list will be fixed in a future
release.

- In VAND (immediate) and VORN (immediate), the I16 and I32 type
  specifiers in the assembly syntax will be corrected.
- There is a mismatch between the encoding for VMOVL and some other
  instructions and the conditions defined for the groups they appear in.
  The encoding is correct. The group conditions for affected
  instructions will be clarified.
- The setting of FPEXC.DEX and FPEXC.TFV bits for an invalid FPSCR.Len
  and FPSCR.Stride, for an allocated CP10 or CP11 instruction is missing
  from pseudocode.

### Upcoming Changes

The details of the architecture are presented in pseudocode in
Architecture Specification Language (ASL). Arm is defining a new version
of the Architecture Specification Language, ASL1, to improve and expand
the capabilities of the language. Please see
https://developer.arm.com/Architectures/Architecture%20Specification%20Language
for details on this language. Arm will be publishing an equivalent
release in ASL1 format later in 2025.

### Intention and quality statements for all ArmARM architecture releases

The intention and scope of the **Architecture releases** is to describe
changes from the existing architecture to the next release. The quality
of the architecture releases refers to the accuracy and completeness of
the changes described in the specifications.

The intention and scope of the **XML releases** is to describe the
content and behavior of the registers, system registers, instructions,
pseudocode and features of the architecture in full, for human readers
in a way that enables correct information for the current or any
previous release can be deduced. The quality of the XML releases refers
to the accuracy and completeness of the content to a human reader.

The intention and scope of the **JSON releases** is to describe aspects
of the XML releases in a structured, machine readable format. The
content of the architectural content will be approximately equivalent to
the corresponding XML release. However there are some aspects of the
architecture which cannot yet be represented in a machine readable
format.

The intention and scope of the **Schema** for the JSON releases is to
describe the syntax and format of the json files used in the json
releases. The schema is still under development and is subject to
change.
