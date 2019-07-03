---
layout: full-width
title: Continuous Monitoring Strategy
permalink: /conmon-strategy/
body-class: wiki

---

<div class="wiki-main-wrapper">
<p>Within the FedRAMP Security Assessment Framework, once an authorization has been granted, the CSP’s security posture is monitored according to the assessment and authorization process. Monitoring security controls is part of the overall risk management framework for information security and the CPS is required to maintain a security authorization that meets the FedRAMP requirements.</p>

<p>Traditionally, this process has been referred to as “Continuous Monitoring” as noted in the National Institute of Standards and Technology Special Publication (NIST SP) 800-137 Information Security Continuous Monitoring for Federal Information Systems and Organizations. Other NIST documents such as NIST SP 800-37, Revision 1 refer to “ongoing assessment of security controls.” It is important to note that both the terms “Continuous Monitoring” and “Ongoing Security Assessments” mean essentially the same thing and should be interpreted as such.</p>

<p>Performing ongoing security assessments determines whether the set of deployed security controls in a cloud information system remains effective in light of new exploits and attacks, and planned and unplanned changes that occur in the system and its environment over time. To maintain an authorization that meets the FedRAMP requirements, the CSP must monitor their security controls, assess them on a regular basis, and demonstrate that the security posture of their service offering is continuously acceptable.</p>

<p>Ongoing assessment of security controls results in greater control over the security posture of the CSP system and enables timely risk-management decisions. Security-related information collected through continuous monitoring is used to make recurring updates to the security assessment package. Ongoing due diligence and review of security controls enables the security authorization package to remain current which allows agencies to make informed risk management decisions as they use cloud services.</p>


<p>The below information provides CSPs with guidance and instructions on how to implement their continuous monitoring program. Certain deliverables and artifacts related to continuous monitoring that FedRAMP requires from CSPs are discussed below as well.</p>

<p><strong>Contents </strong></p>
<ol>
	<li><a href="#conmon-process">Continuous Monitoring Process</a></li>
<li><a href="">Continuous Monitoring Roles & Responsibilities</a>
<ul>
<li><a href="">2.1 Agency Authorizing Official (AO) </a></li>
<li><a href="">2.2 FedRAMP Joint Authorization Board (JAB) </a></li>
<li><a href="">2.3 FedRAMP Program Management Office (PMO) </a></li>
<li><a href="">2.4 Department Of Homeland Security (DHS)</a></li>
<li><a href="">2.5 Third Party Assessment Organization (3PAO)</a></li></ul></li>
<li><a href="">Continuous Monitoring Process Areas</a>
<ul>
<li><a href="">3.1 Operational Visibility</a></li>
<li><a href="">3.2 Change Control</a></li>
<li><a href="">3.3 Incident Response</a></li></ul></li>
<li><a href="">Control Frequencies</a></li>
<li><a href="">Monthly Reporting Summary</a></li>
<li><a href="">JAB P-ATO Continuous Monitoring Analysis</a></li>
<li><a href="">Continuous Monitoring Performance Management </a></li>
</ol>


<div id="conmon-process"><h2>Continuous Monitoring Process </h2>
	<hr>
<p>The FedRAMP continuous monitoring program is based on the continuous monitoring process described in <em>NIST SP 800-137, Information Security Continuous Monitoring for Federal Information Systems and Organization</em>. The goal is to provide: (i) operational visibility; (ii) managed change control; and (iii) attendance to incident response duties. For more information on incident response, review the FedRAMP <em>Incident Communications Procedure</em>.</p>
					
<p>The effectiveness of a CSP’s continuous monitoring capability supports ongoing authorization and reauthorization decisions. Security-related information collected during continuous monitoring is used to make updates to the security authorization package. Updated documents provide evidence that FedRAMP baseline security controls continue to safeguard the system as originally planned.	</p>

<p>As defined by NIST, the process for continuous monitoring includes the following initiatives:</p>
<ul>
<li><strong>Define</strong> a continuous monitoring strategy based on risk tolerance that maintains clear visibility into assets and awareness of vulnerabilities and utilizes up-to-date threat information.</li>
<li><strong>Establishz</strong> measures, metrics, and status monitoring and control assessments frequencies that make known organizational security status and detect changes to information system infrastructure and environments of operation, and status of security control effectiveness in a manner that supports continued operation within acceptable risk tolerances.</li>
<li><strong>Implement</strong> a continuous monitoring program to collect the data required for the defined measures and report on findings; automate collection, analysis, and reporting of data where possible.</li>
<li><strong>Analyze</strong> the data gathered and <strong>Report</strong> findings accompanied by recommendations. It may become necessary to collect additional information to clarify or supplement existing monitoring data.</li>
<li><strong>Respond</strong> to assessment findings by making decisions to either mitigate technical, management, and operational vulnerabilities, or accept the risk; or transfer it to another authority.</li>
<li><strong>Review</strong> and <strong>Update</strong> the monitoring program, revising the continuous monitoring strategy and maturing measurement capabilities to increase visibility into assets and awareness of vulnerabilities; further enhance data-driven control of the security of an organization’s information infrastructure; and increase organizational flexibility.</li>
</ul>
<p class="caption"><strong>Figure 1. NIST Special Publication 800-137 Continuous Monitoring Process 
</strong></p>
<div class="image-wrapper">
<img title="Continuous Monitoring Process" alt="Continuous Monitoring Process" src="{{site.baseurl}}/assets/img/conmon-fig1.png">
</div>
<p>Security control assessments performed periodically validate whether stated security controls are implemented correctly, operating as intended, and meet FedRAMP baseline security controls. Security status reporting provides federal officials with information necessary to make risk-based decisions and provides assurance to existing customer agencies regarding the security posture of the system. </p>
</div>
<div id="conmon-roles"><h2>Continuous Monitoring Roles and Responsibilities</h2>  
<hr>
<h3>Agency Authorizing Official (AO)</h3> 
<p>Agency AOs and their teams oversee the CSP’s continuous monitoring activities on behalf of their Agency. They must review all security artifacts provided by the CSP, 3PAO, or FedRAMP to ensure the CSP’s security posture remains sufficient for their Agency’s use of the system.</p>

<p>Agency AOs should ensure their Agency is monitoring the Plan of Action & Milestones (POA&M) and reporting artifacts (such as vulnerability scan reports), as well as any significant changes associated with the CSP’s service offering. AOs should use this information to make risk-based decisions about ongoing authorization of the system for that Agency.</p>

<p>For FedRAMP Agency ATOs, the Agency AO should consult the FedRAMP Guide for Multi-Agency Continuous Monitoring, which can be found at <a href="http://fedramp.gov">http://fedramp.gov</a>.</p>

<h3>FedRAMP Joint Authorization Board (JAB</h3>
<p>While each Agency AO maintains the final approval authority for the use of a system by that Agency, the FedRAMP JAB acts as focal point for continuous monitoring activities of systems with a P-ATO. The JAB:</p>
<ul>
<li>Reviews continuous monitoring and security artifacts on a regular basis;</li>
<li>Authorizes, denies, monitors, suspends, and revokes a system’s P-ATO as appropriate;</li>
<li>Authorizes or denies significant change and deviation requests; and</li>
<li>Ensures the FedRAMP PMO is providing artifacts to leveraging Agencies in a timely manner.</li>
</ul>

<h3>FedRAMP Program Management Office (PMO)  </h3> 
<p>The FedRAMP PMO acts as the liaison for the JAB for ensuring CSPs with a JAB P-ATO strictly adhere to their established Continuous Monitoring Plan. The FedRAMP PMO:</p>
<ul>
<li>Receives continuous monitoring and significant change artifacts on behalf of the JAB;M</li>
<li>Performs initial analysis of artifacts, such as ensuring scanner output files match POA&M submissions;</li>
<li>Facilitates JAB review of artifacts; and</li>
<li>Ensures artifacts are made available to all leveraging agencies.</li>
</ul>

<h3>Department Of Homeland Security (DHS)  </h3> 
<p>The FedRAMP Policy Memo released by OMB defines the DHS FedRAMP responsibilities as follows:
Assist government-wide and agency-specific efforts to provide adequate, risk-based, and cost- effective cybersecurity;</p>
<ul>
<li>Coordinate cyber security operations and incident response and provide appropriate assistance;</li>
<li>Develop continuous monitoring standards for ongoing cybersecurity of Federal information systems to include real-time monitoring and continuously verified operating configurations; and</li>
<li>Develop guidance on agency implementation of the Trusted Internet Connection (TIC) program for cloud services.</li>
</ul>

<p>The FedRAMP PMO works with DHS to incorporate DHS’s guidance into the FedRAMP program guidance and documents. </p>

<h3>Third Party Assessment Organization (3PAO)   </h3>
<p>3PAOs, or agency assessors, are responsible for independently verifying and validating the control implementation and test results for CSPs in the continuous monitoring phase of the FedRAMP process. Specifically, 3PAOs are responsible for:</p>
<ul>
<li>Assessing a defined subset of the security controls annually;</li>
<li>Submitting the assessment report to the AO one year after the CSP’s authorization date and each year thereafter;</li>
<li>Performing announced penetration testing;</li>
<li>Performing annual scans of web applications, databases, and operating systems; and</li>
<li>Assessing changed controls on an ad hoc basis as requested by the AOs for any changes made to the system by the CSP.</li>
</ul>

<p>In order to be effective in this role, 3PAOs are responsible for ensuring that the chain of custody is maintained for any 3PAO-authored documentation. 3PAOs must also be able to vouch for the veracity and integrity of data provided by the CSP for inclusion in 3PAO-authored documentation. As an example:</p>
<ul>
<li>If scans are performed by the CSP, the 3PAO must either be on site and observe the CSP performing the scans or be able to monitor or verify the results of the scans through other means documented and approved by the AO.</li>
<li>Documentation provided to the CSP must be placed in a format that either the CSP cannot alter or that allows the 3PAO to verify the integrity of the document.</li>
</ul>
</div>
<div id="conmon-process-areas">
<h2>Continuous Monitoring Process Areas </h2>
<hr>
<h3>Operational Visibility  </h3>
<p>The CSP must demonstrate the efficacy of its continuous monitoring program through the evidence it provides. The CSP and its 3PAO must provide evidentiary information to AOs at least monthly, annually, every three years, and on an as-needed basis after an authorization is granted. These deliverables allow each AO to evaluate the risk posture of the CSP’s service offering.</p>

<p>Table 1 below identifies the deliverables required as part of continuous monitoring activities. These deliverables include providing evidence, such as providing monthly vulnerability scans of CSPs operating systems/infrastructure, databases, and web applications.</p>

<p>As part of the continuous monitoring process, CSPs are required to have a 3PAO perform an assessment on an annual basis for a subset of the overall controls implemented on the system. During the annual assessment, the controls listed in Table 2 are tested along with an additional number of controls selected by the AO. The AO has the option to vary the total number of controls tested to meet the desired level of effort for testing. The AO selects the additional controls for testing based on the following criteria in Table 1.</p>
<p class="caption"><strong>Table 1. Control Selection Criteria</strong></p>
<table>
<tbody>
<tr>
<th colspan="2">
CRITERIA
</th>
<th>
DESCRIPTION</th>
</tr>
<tr>
<td>1.</td>
<td><strong>Conditions from previous assessment</strong></td>
<td>Any conditions made by the AO in the authorization letter or during a previous assessment. This includes the resolution of vulnerabilities within designated time-frames and implementations of new capabilities.</td>
</tr>
<tr>
<td>2.</td>
<td><strong>Weakness identified since the last assessment</strong></td>
<td>Any area where the system has known vulnerabilities or enhanced risk related to specific controls, such as an actual or suspected intrusion , compromise, malware event, loss of date, or denial of service (DoS) attack.</td>
</tr>
<tr>
<td>3.</td>
<td><strong>Known or suspected testing/continuous monitoring failure</strong></td>
<td>Any area where the cloud system demonstrated a weakness or vulnerability in continuous monitoring or testing related to specific security controls, such as controls related to patch management, configuration management, or vulnerability scanning.</td>
</tr>
<tr>
<td>4.</td>
<td><strong>Control implementation that has changed since last assessment</strong></td>
<td>Any control implementation that has changed since the last assessment must be independently assessed, even if it does not rise to the threshold of <em>significant change</em></td>
</tr>
<tr>
<td>5.</td>
<td><strong>Newly discovered vulnerability, zero-day attack, or exploit</strong></td>
<td>Any control that is potentially affected by newly discovered vulnerabilities or zero-day exploits, such as the Heartbleed vulnerability</td>
</tr>
<tr>
<td>6.</td>
<td><strong>Recommendation of Authorizing Official or Organization</strong></td>
<td>Based on direct knowledge and use of a cloud system, authorizing officials or organizations can require the CSP to test additional controls based on unique mission concerns or based on the CSP's performance since their last assessment.</td>
</tr>
</tbody>
</table>
<h3>Change Control   </h3>
<p>Systems are dynamic, and FedRAMP anticipates all systems are in a constant state of change. Configuration management and change control processes help maintain a secure baseline configuration of the CSP’s architecture. Routine day-to-day changes are managed through the CSP’s change management process described in their Configuration Management Plan.</p>

<p>Before a planned change takes place, the CSP must perform a Security Impact Analysis, which must be a standard part of a CSP’s change control process as described in the CSP’s Configuration Management Plan. If the analysis concludes the change will adversely affect the integrity of the system’s authorization, the CSP must treat it as a significant change, which requires AO coordination and 3PAO involvement.</p>

<p>There are many factors that could result in making it difficult to establish specific thresholds for a significant change determination. For this reason, FedRAMP recommends the CSP involve the AO’s team in discussions related to future changes to the system as a best practice.</p>

<p>For a significant change, the CSP must complete the FedRAMP Significant Change Request Form and provide it to the AO for their analysis a minimum of 30 days before implementing a significant change. The AO might require more time based on the impact of the change, so the CSPs must work closely with the AO to understand how much time is needed in advance of significant changes. The form must include the CSP’s rationale for making the change.</p>

<p>The FedRAMP Significant Change Request Form can be found at http://fedramp.gov. Submission instructions are on the form.</p>

<p>The CSP’s 3PAO must provide a Security Assessment Plan (SAP) to FedRAMP, which the 3PAO will later use to assess the system following implementation of the significant change.</p>

<p>The AO must approve the assessment scope for the significant change SAP. The 3PAO should exercise best judgement to recommend the scope of the significant change assessment; and coordinate the final scope with the AO. Typically, if the significant change involves a new control implementation, the 3PAO must test the new control for the entire system. If the significant change is a new technology, the 3PAO must test its integration into existing controls.</p>

<p>If any anticipated change adds residual risk, or creates other risk exposure that the AO finds unacceptable, the system’s authorization could be revoked. For this reason, it is imperative the CSP seeks AO approval before making the change. The goal is for the CSP to make planned changes in a controlled manner so that the security posture of the system is not diminished.</p>

<p>After approval and implementation of the significant change, the CSP’s 3PAO must perform an assessment and submit a Security Assessment Report (SAR) to the AO in accordance with the SAP and within the timeframe agreed between the CSP and the AO. Additionally, the CSP must submit updated documentation pertaining to the newly implemented changes.</p>

<h3>Incident Response   </h3>
<p>FedRAMP requires the CSP to demonstrate they are able to adequately respond to security incidents. As part of the FedRAMP authorization process, the CSP is required to submit and maintain an incident response plan, which the AO approves. The CSP is also required to follow the incident response and reporting guidance contained in the FedRAMP Incident Communications Procedure.</p>

<p>At the government’s discretion, FedRAMP or individual Agency AOs may direct the CSP to treat certain critical vulnerabilities as incidents, such as "zero day" vulnerabilities (e.g., Heartbleed). CSPs must take immediate action to fully resolve the vulnerability if possible, or at least implement mitigating factors. The FedRAMP PMO may request immediate reporting on these items. FedRAMP may request immediate reporting on these critical vulnerabilities, both for JAB P-ATO and FedRAMP Agency ATO systems. The CSP must continue to track critical vulnerabilities in the system’s POA&M even when they are providing special reporting to FedRAMP.</p>
</div>
<div id="control-frequencies">
<h2>Control Frequencies  </h2>
<hr>
<p>Security controls have different frequencies for performance and review, and some controls require review more often than others. Table 2 summarizes the minimally required frequencies needed for each continuous monitoring activity. Some activities require the CSP to submit a deliverable to FedRAMP. Note the CSP is required to submit deliverables listed in Table 2 if they have full or shared responsibility for the listed control; however, the CSP is not responsible for deliverables related to fully inherited controls. For example, if a Software as a Service (SaaS) system fully inherits physical and environmental protection controls from a separately-authorized underlying Infrastructure as a Service (IaaS) system, no deliverables are required from the CSP with the SaaS system inheriting those controls.</p>

<p>Other continuous monitoring activities do not require a deliverable, and are reviewed by the 3PAO during security assessments. The CSP must demonstrate to the 3PAO that ongoing continuous monitoring capabilities are in place, and are consistently occurring as represented in the System Security Plan (SSP). For example, if a CSP has indicated in their SSP that they monitor unsuccessful login attempts on an ongoing basis, the 3PAO may ask to see log files, along with the CSP’s analysis of the log files, for random dates over the course of a prior authorization period (e.g., bi-annual, annual).</p>

<p>In Table 2, refer to the “Description” column for information about what is required and when it is required to be submitted. A checkmark in either the CSP Authored Deliverable column or 3PAO Authored Deliverable column of Table 2 indicates that a deliverable is required.</p>

<p>The AO may ask the CSP for a security artifact at any point in time, especially if they have concerns about the security posture of the system. For example, if a CSP indicates in their SSP that they actively monitor information system connections, the AO may ask the CSP to provide log file snippets for a particular connection at any point in time. If the AO learns that an entity that connects to the CSP’s system has been compromised by an unauthorized user, the AO coordinates with the CSP to check in on the interconnection monitoring of the system. The CSP should anticipate that aside from scheduled continuous monitoring deliverables, and 3PAO assessments, the AO may request certain system artifacts on an ad hoc basis at any time.</p>
<p>CSPs are required to submit a schedule of activities to the AO within 15 days from the date of their authorization and annually thereafter. This schedule assists CSPs in managing continuous monitoring activities.</p>

<p><strong>Note:</strong> For controls that do not have a check in either the CSP authored deliverable or 3PAO authored deliverable columns in Table 2, the CSP is required to provide evidence of compliance minimally during annual assessment and upon request.</p>
</div>
<div id="monthly-reporting-summary">
<h2>Monthly Reporting Summary </h2>
<hr>
<p>As described in the FedRAMP requirements, CSPs must provide monthly reports of all vulnerability scanning to authorizing officials for review and track these vulnerabilities within the POA&Ms. These deliverables are really a subset of the evidence required at time of authorization. In this vein, the analysis of these scan results should be performed in the same manner they were for time of authorization. In particular, this means the CSP must:</p>
<ul>
<li>Document all inventory, late or deviated scan findings, and non-scan related findings in the POA&M (including low findings);</li>
<li>Track each unique vulnerability as an individual POA&M item; and,</li>
<li>Submit and receive AO approval for each deviation request or change to scan findings (e.g. risk adjustments, false positives, and operational requirements).</li>
</ul>

<p>On a monthly basis, the AO monitors these deliverables to ensure the CSP maintains an appropriate risk posture, which typically means the risk posture stays at the level of authorization or improves. As stated in their authorization letter, the CSP is required to maintain a continuous monitoring program. FedRAMP’s review and analysis of the CSP’s continuous monitoring deliverables results in a continuous authorization decision by the AO every month. request.</p>
</div>
<div id="jab-conmon-monitoring-analysis">
<h2>JAB P-ATO Continuous Monitoring Analysis </h2>
<p>This section provides Agency AOs and CSPs with key aspects of FedRAMP’s analysis of continuous monitoring deliverables for those systems with a JAB P-ATO:</p>
<ul>
<li>FedRAMP reviews summary information if provided by the CSP. This enables the CSP to provide context and manage FedRAMP’s expectations, especially related to issues and overdue vulnerability mitigation.</li>
<li>FedRAMP correlates scan data with current and past submissions, as well as the summary information, to ensure the CSP provided information that accurately reflects the system’s risk posture.</li>
<li>FedRAMP evaluates trending data to understand the overall effectiveness of a CSP’s continuous monitoring program over time.</li>
<li>FedRAMP focuses on late POA&M items. A pattern of late items, or excessively late items can reflect a CSP’s inability to meet FedRAMP requirements. Late items, as well as trends of late items, are always identified to leveraging agencies.</li>
<li>FedRAMP evaluates deviation requests and unique items for each system on a case-by-case basis. Below are some common circumstances that arise:
	<ul>
<li>FedRAMPwillnotentertainrequestsfordateadjustments.Therequiredtimeframefor resolution is always based on the severity of the vulnerability and date of discovery.</li>
<li>FedRAMP will typically only evaluate risk reduction deviations when submitted in a timely manner. A risk reduction submitted just before a vulnerability becomes late will be viewed as an attempt to avoid the late status and receives additional scrutiny.</li>
<li>A vendor dependency exists when the CSP must rely on a downstream vendor to resolve a vulnerability, such as a patch for a commercial off-the-shelf (COTS) product, but the vendor has not yet made the fix available. Risks are only considered vendor dependencies when remediating vulnerabilities within a product or service is not allowed by the vendor (e.g. it would void the warranty), or would impede the intended function of the system.
<ul>
<li>All vendor dependencies at a high risk level must be mitigated to a moderate level through compensating controls within 30 days.</li>
<li>To avoid being cited as a late item, vendor dependencies at the low and moderate level require the CSP to be in contact with their vendor at least every 30 days to continuously ensure the CSP knows as soon as a patch becomes available. FedRAMP evaluates the last vendor check-in date relative to the POA&M submission date.</li>
<li>The CSP should provide evidence of vendor interaction regarding any fixes to the open vulnerabilities with their monthly deliverables.</li>
<li>Vendor dependencies do not require a deviation request.</li>
</ul>
</li>
	</ul>
</li>
<li>Operational requirements exist only for vulnerabilities where the ability to remediate a vulnerability does not exist, remediating a vulnerability is not supported if the vulnerability is vendor dependent, or where the only means of remediating the vulnerability would impair the intended function of the system.</li>
<li>Deviation requests for risk adjustments, false positives, and operational requirements require AO approval. The CSP must submit the FedRAMP Deviation Request Form to FedRAMP with all appropriate supporting information. The CSP should upload the form to the continuous monitoring container in OMB MAX, then send an email notification to their FedRAMP POC or info@fedramp.gov, and include a link to the container location in the email notification. The FedRAMP Deviation Request Form can be found on http://fedramp.gov under Templates.</li>
<li>FedRAMP evaluates continuous monitoring issues against the FedRAMP Continuous Monitoring Performance Management Guide to determine if any escalation action is necessary. If so, the escalation action is cited, and the status reported monthly until resolved.</li>
</ul>
<p>Each month, the FedRAMP PMO performs the above analysis and provides a Monthly Reporting Summary to the JAB for each system operating with a P-ATO. This summary highlights key considerations for JAB and each leveraging Agency’s AO. An example of the Monthly Reporting Summary appears in Figure 2 below. In this template you can see:</p>
<ul>
<li>System Status</li>
<li>Overview</li>
<li>Unique Scanning Summary § Raw Scanning Summary</li>
<li>Open POA&M Summary </li>
<li>Items of Note</li>
<li>Considerations for Review</li>
<li>Additional Information</li>
<li>Requested Deviation Details</li>
</ul>

<p class="caption"><strong>Figure 2. FedRAMP Continuous Monitoring Report Example </strong></p>
<div class="image-wrapper">
<img src="{{site.baseurl}}/assets/img/conmon-example.png" title="FedRAMP Continuous Monitoring Report Example" alt="FedRAMP Continuous Monitoring Report Example">
</div>
</div>
<div id="conmon-performance-mgmt">
<h2>Continuous Monitoring Performance Management  </h2>
<hr>
<p>Failure to adhere to FedRAMP’s ConMon requirements for a P-ATO may result in escalation actions by the FedRAMP PMO and JAB. FedRAMP provides <a href="{{site.baseurl}}/conmon-performance-mgmt/">ConMon Performance Management</a> guidance that details the processes that FedRAMP and the JAB use to maintain appropriate ConMon performance for CSPs with JAB P-ATOs. CSPs with Agency ATOs also must maintain compliance with FedRAMP ConMon requirements outlined in the ATO letter. FedRAMP recommends Agencies create guides and/or use <a href="{{site.baseurl}}/conmon-performance-mgmt/">FedRAMP’s Continuous Monitoring Performance Management guidelines</a> when maintaining FedRAMP Agency ATOs. </p>
</div></div>
