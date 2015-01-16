{{{
  "title": "Cloud Platform – Release Notes: January 30, 2013",
  "date": "1-31-2013",
  "author": "Richard Seroter",
  "attachments": [],
  "related-products" : [],
  "preview" : "",
  "contentIsHTML": true
}}}

<p><strong>New Features (2)</strong>
</p>
<hr />
<ul>
  <li><strong>Configure a complete reseller experience in the Tier 3 Control Portal.</strong> This release marks the end of an effort to deliver an offering for resellers who plan to create a private label experience based on the Tier 3 cloud. Customers who
    sign up for the reseller program can configure unique values for the "support" email address, knowledge base location, feature request mailbox, legal information, privacy policy, and more. In addition, customers have the option of customizing email
    notifications related to everything from "welcome" messages to billing notices.</li>
  <li><strong>Cross data center firewall policies now available for customer self-service.</strong>The ability to connect globally distributed data centers via firewall policies was previously available only to Tier 3 system administrators. For more information
    on creating these firewall policies, see the KB article <a href="http://help.tier3.com/entries/22603797-creating-cross-data-center-firewall-policies">Creating Cross Data Center Firewall Policies</a>.</li>
</ul>
<p>&nbsp;</p>
<p><strong>Minor Defects Fixed or Enhancements Added (5)</strong>
</p>
<hr />
<ul>
  <li><strong>Server, Group, and Network APIs extended to be cross-data center aware.</strong> The <a href="http://help.tier3.com/forums/20578872-server">API for Tier 3 Servers</a>, <a href="http://help.tier3.com/forums/20568588-group">API for Tier 3 Groups</a>,
    and <a href="http://help.tier3.com/forums/20587856-network">API for Tier 3 Networking</a> now support each global Tier 3 data center and any sub-accounts of the active account.</li>
  <li><strong>Improved experience for choosing data center for new servers.</strong> Previously, when Tier 3 users created servers, they had to select the target data center twice. First via the breadcrumb at the top, and then in the "create server" form
    itself. Now, the "create server" form doesn't ask the user for the target data center, but rather uses the data center context set by the breadcrumb at the top of the page.</li>
  <li><strong>Resizing Linux storage drives results in the volume being automatically extended in the virtual machine.</strong> Now when you expand a (non-operating system) drive in a Linux virtual machine via the Control Portal, the system automatically
    expands the volume within the virtual machine itself without any manual intervention.</li>
  <li><strong>Improved logging of billing details associated with software installation.</strong> Tier 3 supports the installation of many commercial software packages into cloud servers. The installation process has been improved to capture more details
    about the software that gets installed. This improves transparency in our billing procedures while making it easier to add more commercial software to our catalog.</li>
  <li><strong>Username is decoupled from email address.</strong>Previously, a user's email address was also their unique username. This could cause issues if the same person existed in multiple accounts. Now, users can specify a globally unique username while
    reusing whatever email address they wish.</li>
</ul>