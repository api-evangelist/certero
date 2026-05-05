---
title: "The Role of Good Data in Software Audits"
url: "https://www.certero.com/blog/good-data-software-audits/"
date: "Fri, 14 Nov 2025 11:26:54 +0000"
author: "Daniel Whitefield"
feed_url: "https://www.certero.com/blog/feed/"
---
<h2 class="wp-block-heading"></h2>



<p>Software audits are back on the rise as vendors seek to regain lost revenues.</p>



<p>Now is the time to prepare your company for its next audit, with <a href="https://www.microsoft.com/en-gb" rel="nofollow noopener" target="_blank">Microsoft</a>, <a href="https://www.oracle.com/index.html" rel="nofollow noopener" target="_blank">Oracle</a>, <a href="https://www.sap.com/uk/index.html" rel="nofollow noopener" target="_blank">SAP</a>, and <a href="https://www.ibm.com/uk-en/" rel="nofollow noopener" target="_blank">IBM </a>being the most likely auditors.</p>



<p>This article is part of a series, focused on the factors that can cause organizations problems when on the receiving end of an audit and what you can do now to make sure your business is protected from any potential financial risk and how you can ensure the disruptive impact of the audit process itself is minimized.</p>



<p>This first article looks at the role of having ‘good data’ at your disposal; the power of fundamental network discovery and inventory and how asset data can be enriched to help transform and automate some complex but essential elements of the SAM process.</p>



<p>We’ll begin by looking at the common issues that prevent good data and the scenarios that introduce fundamental risk:</p>



<div class="wp-block-spacer" style="height: 20px;"></div>



<h3 class="wp-block-heading">Risk 1: Data Silos</h3>



<p>If you still have to rely on more than one ITAM/SAM solution to provide visibility of IT hardware and software across your estate, then there is still the fundamental challenge of not having a ‘single source of the truth’ where all your IT asset data is in one place. Manually collating information from different sources is hugely time consuming, prone to errors and almost immediately out of date by the time it’s transformed into any meaningful insight. This of course, makes the license reconciliation processes flawed before it begins, as manipulation of data has to be done manually, outside of a mature SAM solution.</p>



<div class="wp-block-spacer" style="height: 20px;"></div>



<h3 class="wp-block-heading">Risk 2: Inaccurate discovery and inventory</h3>



<p>The old adage ‘if you can’t measure it you can’t manage it’ has never been truer than with your IT assets. </p>



<p>If you do not have an accurate and up-to-date picture of all your IT hardware and software, how will you know what software you have installed and need licenses for? You need to be sure that the inventory does not have gaps – common reasons for this could be:</p>



<p>Legacy discovery / inventory tools are in use, or hardware asset management tools that were never designed to capture the depth and detail required for SAM (think Microsoft SCCM or Service Desk inventory tools designed to capture Configuration Items but not designed to capture detail on software etc.)</p>



<p>SAM tools that alarmingly lack the ability to actively&nbsp;<em>discover</em>&nbsp;the estate – leading to blind-spots where the IT estate changes and you simply don’t know what you don’t know. (Bear in mind that in an audit, the software vendor will understand the limitations of your toolsets and will use a robust solution to discover all traces of installed software).</p>



<p>Policy decisions, such as not wishing to allow inventory agents on Servers – home to the most costly and potentially risky software assets. In these scenarios agentless ITAM/SAM solutions are available, the best offer a combination of both agent and agentless inventory for total coverage.</p>



<p>Remote devices – with the unprecedented recent shift to working from home, your ITAM/SAM capability needs to still keep sight, security and control over any corporately owned and operated devices, no matter what or where they are.</p>



<p>Disparate Ownership of Desktop and Datacenter Vendors and SAM – Traditional structures in IT have led to different teams managing the operation and cost / control of vendors like Microsoft, Oracle, IBM and SAP. The business needs and challenges are surely different, but the fundamental governance of controlling expenditure and strategy with these vendors should all fall under a robust SAM governance, and now solutions and services exist to unify the management of all software and all vendors, from desktop to data center.</p>



<h3 class="wp-block-heading">Risk 3: No control over software downloads</h3>



<p>With most volume licensing agreements now allowing for easy and fast download of all a vendor’s software titles, you can very quickly find yourself in the position of not knowing what is where. Additionally, some vendor’s software, such as Oracle, will install with options switched on or management packs enabled that you may not be aware of. Subsequent use of these, whether accidental or deliberate, will mean you have to pay for them. When the audit comes around, this will quickly become apparent and the true-up invoice will shortly follow.</p>



<p>To prevent this situation from occurring in the first place, to discover what software is installed, most software asset management (SAM) tools require the installation of an agent on a device. However, this means you need to know that the device actually exists in the first place. Many SAM tools take a feed from Microsoft Active Directory (AD) and accept this as the definitive list of devices on which to install their agent.</p>



<div class="wp-block-spacer" style="height: 20px;"></div>



<h3 class="wp-block-heading">Risk 4: AD alone is not the answer</h3>



<p>The fact is, Microsoft AD is not comprehensive. For example, it does not pick up things like Linux/UNIX boxes, DMZ, Macs or anything in a workgroup or other domain. So, in such instances, you will not have a complete view of everything. For most organizations, we estimate that this leaves around 20% or so of your IT assets where the software will not be being properly inventoried, because its host device has not had an agent installed in the first place.</p>



<p>Also for AD, keeping it up-to-date is a major and ongoing task when the organization has regular leavers and new starters. For a larger organization with many thousands of AD Objects spread regionally or even globally, the chances of it being up-to-date are slim. This means that your AD listing will give you both an incomplete and inaccurate view of your IT assets and so your subsequent software inventory will be similarly inaccurate and incomplete.</p>



<div class="wp-block-spacer" style="height: 20px;"></div>



<h3 class="wp-block-heading">Risk 5: SaaS &amp; Cloud</h3>



<p>Okay, so you pay for these assets as you go and there’s no audit ‘risk’ of being found under-licensed, but the risk of over-spending is huge and controlling it is at the forefront of SAM governance. You should think of having visibility of SaaS and Cloud proliferation and usage as being as fundamental as having robust inventory – it needs to be present, within your SAM solution and business intelligence needs to be available whenever needed to right-size expenditure and maintain governance within IT. See <a href="https://www.certero.com/saas/">SaaS &amp; Cloud Asset Management</a> for more information.</p>



<div class="wp-block-spacer" style="height: 20px;"></div>



<h3 class="wp-block-heading">Risk 6: Evidence Needs to be Accepted by the Vendor When Audited</h3>



<p>Whereas the general rule of thumb with SAM is that when defending during an audit, you need to provide the required evidence of your stated license position to satisfy the vendor and there are no automatically ‘pre-approved’ solutions or outputs, there are some exceptions when it comes to the data center.</p>



<p>A good example is with Oracle, who are extremely thorough in their audit process and usually deploy their own LMS (Oracle’s Licence Management Services) or GLAS (Global Licensing and Advisory Services) scripts to discover traces of Oracle in use. The output of these scripts goes directly to Oracle and they respond with their interpretation of the findings.</p>



<p>It’s well worth noting if using Oracle that solutions such as <a href="https://www.certero.com/itam/"><strong>Certero for Oracle</strong></a> are formally verified by Oracle LMS / GLAS, so that the output of the solution is accepted within an audit scenario. This not only saves all of the time and disruption that would be caused by running additional scripts but also importantly puts the information retrieved in your hands.</p>



<p>Meaning your SAM team or trusted SAM partner can interpret the information and you have full visibility to question anything you don’t agree with, with insight of the interpretation of your contract. This is where the combination of the detail from the solution and the deep knowledge of an expert licensing consultant can be extremely beneficial to negotiations.</p>



<div class="wp-block-spacer" style="height: 20px;"></div>



<h3 class="wp-block-heading">Overcoming the challenges to ensure Good Data</h3>



<p>What is required to overcome this problem? How can you ensure an accurate and up-to-date&nbsp;<a href="https://www.certero.com/sam/">inventory</a>&nbsp;of all your IT assets?</p>



<p>The answer is a multi-layered approach that utilizes sources like your AD listing and cross-references it against robust independent scans of your IT environment, using multiple inventory methods and connectors to gain full and detailed coverage. This should be dynamically updating automatically as the estate changes. This of course sounds complex because it is complex, and traditionally most of a SAM manager’s time is spent unraveling all this information from different sources to make sense of it.</p>



<p>So, to address these problems, you must first address the use of ‘legacy’ toolsets and whether they’re really fit for purpose now. Progressive enterprises are finding that instead of bending the use of an old ITAM solution to manage SAM in this painfully complex way, it’s now far easier to simply upgrade to a modern single platform for ITAM &amp; SAM, providing everything you need in one place along with a significant upgrade in the quality, integrity and availability of IT asset data for any purpose.</p>



<p>A modern single platform eliminates the disparate data source problem by default, and instead offers one ‘single source of the truth’ with one single data source for all IT assets to be transformed into meaningful information and Business Intelligence through a single UI and UX.</p>



<p>With data consolidated, it then becomes possible to enrich data in automated ways, making it even more valuable. A great example of this is the addition of intelligence from a Software Recognition Service – full automation of the complex process of identifying and categorizing discovered software into meaningful, licensable products.</p>



<p>This saves time whilst removing potential human error when determining how discovered software needs to be managed commercially, and if so, what the correct licensing metrics are according to vendors’ many licensing rules. The SAM reconciliation can therefore become dynamic – with the automated reconciliation of licensing rules against your entitlement rights within the SAM solution.</p>



<p>The result is a constant and live view of license compliance and any exposure in real financial terms – dynamically updating as the IT estate fluctuates and evolves…. A far cry from static, point-in-time reports painstakingly derived with heavy use of caffeine and Excel.</p>



<p>The value of this central view of all IT assets and added intelligence is also far greater than just SAM, adding to IT’s ability to measure, report and digitally transform. But also, in an audit scenario it means that the information required is already present by default, so understanding and maintaining license compliance is far easier and when a vendor calls, you know exactly where you are in terms of potential risk and what actions are required for mitigation.</p>



<p>Find out more about how&nbsp;<a href="https://www.certero.com/sam/">Certero for Enterprise SAM</a>&nbsp;can help overcome the challenges with inaccurate inventory and discovery or if you would like help with&nbsp;<a href="https://www.certero.com/itam/audit-management/">Vendor Audit Response</a>.</p>
<p>The post <a href="https://www.certero.com/blog/good-data-software-audits/" rel="nofollow">The Role of Good Data in Software Audits</a> appeared first on <a href="https://www.certero.com" rel="nofollow">Certero</a>.</p>
