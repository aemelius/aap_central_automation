# What is this repository?
This repo maps the layout described in [https://www.redhat.com/en/blog/creating-ansible-controller-config-code-pipeline] and contains the generic logic to manage organization-wide configuration as code in Ansible Automation Platform (AAP).

# What else is needed to implement an organization-wide configuration-as-code solution?

A project pointing to this repo needs to be created in Ansible Automation Platform. In the referenced article[^1], the project is named **controller_automator**.

This repo, and the **controller_automator** AAP project pointing to it, can be used to manage the configuration of an arbitrary number of organizations; for each of them, a dedicated additional repository and a dedicated set of AAP objects will need to be created. An example layout for such a repo, and further information, can be found here: [https://github.com/aemelius/aap_org01_cac.git](https://github.com/aemelius/aap_org01_cac.git).

This repo does not include any automation to create the **controller_automator** project in AAP.

[^1]: https://www.redhat.com/en/blog/creating-ansible-controller-config-code-pipeline
[^2]: https://github.com/aemelius/aap_org01_cac.git
