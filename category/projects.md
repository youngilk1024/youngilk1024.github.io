---
layout: page
title: Projects
sidebar_link: true
---
<span style="font-size:150%">`Ongoing projects`</span><br>

<p class="message">  
    <b> Execution integrity for Low‑end IoT devices (EILID) @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    (In submission)
    Atop CASU, we have designed and implemented the control-flow integrity (CFI) technique to thwart runtime attacks.
    With instrumentation techniques at compile-time and a shadow stack securely supported by CASU hardware,
    we achieved backward-edge and function-level forward-edge CFI.
    It is implemented on the Basys 3 board (synthesized with openMSP430) and its overhead is also analyzed.
  </span>
</p>

<p class="message">  
    <b> Network attestation (aka Swarm attestation) @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    (In submission)
    The project aims to deal with multiple provers (remote embedded devices) with minimum latency and TOCTOU (Time-of-check to Time-of-use) window.
    It achieves constant-time attestation in each prover using CASU and RATA.
    Theoretically, they entirely remove TOCTOU windows (the inter-device TOCTOU and the time interval between two successive attestations).
    We have measured the attestation time (on Basys 3) and emulated network nodes using OMNeT++.
  </span>
</p>

<p class="message">  
    <b> Alternative approach for Transparency of IoT ecosystems @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    (In submission)
    Instead of continuous broadcasts from IoT devices, Discovery-Based PAISA (DB-PAISA) enables a user-initiated approach.
    IoT devices only send their information when they receive requests from nearby users.
    It removes unnecessary runtime/traffic overheads incurred by PAISA when no users are around.
  </span>
</p>

<p class="message">  
    <b> CloakCam -- Privacy from birth: privacy-preserving photo capturing @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    With the advance of smart devices with cameras, concerns about being captured by others have arisen and this is likely getting more critical.
    In this project, we aim to provide a privacy-preserving photo-capturing service leveraging confidential computing.
    Faces are blurred by default by CloakCam and unblurred explicitly requested by users.
  </span>
</p>

<p class="message">  
    <b> Privacy-enhanced architecture in Cellular network @ <i>UC Irvine with KAIST</i></b><br>
  <span style="font-size:80%">
    It has been widely reported that mobile operators have been selling user's information for their lucrative purpose.
    However, the adversary models including the mobile carriers have been overlooked.
    In this project, we aim to enhance user privacy even from the network operators' perspective and we formally verify the privacy properties we suggest using Tamarin.
  </span>
</p>

<p class="message">  
    <b> Interruptible root-of-trust (RoT) in RISC-V @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    The goal of the project is to construct a remote attestation architecture atomically on RISC-V.
    To realize this, we lower priority of the RoT computation and enable critical interrupts to be triggered with the Physical Protection Unit.
  </span>
</p>


<span style="font-size:150%">`Previous projects`</span><br>

<p class="message">  
    <b>Active root-of-trust with Secure update @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    Compared to prior research papers that work in `passive' (they operate upon receiving a request from server - verifier),
    CASU [ICCAD'22] is a hybrid (hw/sw) `active' root-of-trust architecture on low-tier embedded devices (e.g. MSP430).
    It fundamentally frustrates software modification by assuring software immutability with the support of authenticated updates.
  </span>
</p>

<p class="message">  
    <b>Toward Transparency of IoT device presence @ <i>UC Irvine</i></b><br>
    <span style="font-size:80%">
    PAISA [CCS'23] is a privacy-agile root-of-trust architecture for IoT devices.
    It offers a compliant-based approach for transparency of IoT devices' presence to users in their vicinity.
    In PAISA, IoT devices broadcast timely and secure announcements about their presence and capabilities to all nearby users.
    Its prototype is implemented and evaluated on Cortex M33-based NXP LPC55S69 board (IoT device) and Google Pixel 6 Android phone (user).
  </span>
</p>

<p class="message">  
    <b>Development of a firmware on mobile SoC @ <i>LGE</i></b><br>
  <span style="font-size:80%">
    In mobile devices, power consumption, stability, and performance are the most important components. Especially,
    hardware and firmware should be sophisticatedly designed to minimize power consumption. In this project, we
    developped a firmware including peripheral drivers, power management drivers, and inter-communicate drivers, and
    analyszed unintended power leakage in various scenarios.
  </span>
</p>

<p class="message">  
    <b>Research on automotive systems security @ <i>LGE</i></b><br>
  <span style="font-size:80%">
    In recent years, a large amount of electronic vehicles have been demanding for enviroment and deployed 
    all around the world. Accordingly, many works have studied to improve security in automotive systems
    as there were little to no security features originally. In this project, we developped a secure update
    system (PoC) based on <a href="https://uptane.github.io/">Uptane</a> project. Also, we developped a firewall
    with the security requirements from OEM. Lastly, we developped a digital key archietecture (PoC) proposed by Car
    Connectivity Consortium.
  </span>
</p>