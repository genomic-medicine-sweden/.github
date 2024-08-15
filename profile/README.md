<img src="https://github.com/genomic-medicine-sweden/.github/assets/64251477/a0cd0967-a161-42c7-b98d-87d1d55d0ba4" alt="GMS logo" width="150"/>

# Genomic Medicine Sweden 
## About
[Genomic Medicine Sweden](https://genomicmedicine.se/en/) (GMS) was founded in 2018 with the aim of translating innovation in genomics into clinical practice and implementing a sustainable infrastructure for precision medicine in Sweden. GMS receives national funding from the Swedish Innovation Agency, Vinnova, as well as co-funding from the seven regions with university hospitals and the seven Swedish universities medical faculties. We bring together clinicians, researchers, industry, and patient organizations within a single organization with the goals of implementing precision medicine in healthcare and conducting cutting-edge research and development.

Further information is available at the [GMS website](https://genomicmedicine.se/en/about-us/).

## GMS GitHub
This GitHub organisation is the shared resources used by all participating developers within the Genomic Medicine Sweden realm. Here we have code for analytic tools, technical documentation and other resources open for all our members. All code in the GMS organisation is public and collaboration is encouraged.

<details>
<summary><h2>Developer guidelines</h2></summary>

### Who can add new code/repos
All members of GMS are free to use the GMS GitHub organisation to add new code, technical documentaion or anothe shared resources. We do ask that you as a developer adhead to the guidlines found below. If you are unsure about how to set things up, feel free to reach out to one of the [owners of the GitHub organisation](https://github.com/orgs/genomic-medicine-sweden/people?query=role%3Aowner).
  
### Creating new repositories
Since the repositories at the GMS GitHub is for all members, it is important that all new repos are created with verbose information about the intent of the repository and how the content should be used. A good reference for creating excellent technical documentation can be found in the various nf-core GitHub repositories, e.g. [Sarek](https://github.com/nf-core/sarek).

### Branch protection
New repositories should be created with branch protection at least for the main branch. This should include that all commits to the main branch goes through pull-requests, and that they require review from the Code Owners.

### Code Owners
All repositories should have a maintained [Code Owners file](https://docs.github.com/en/enterprise-server@3.10/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners). The Code Owners can be individuals, but a preferred way is to set up a develop team and have them all be maintainers and Code Owners of a given repo. An example of this is the [@jasen-devs team](https://github.com/orgs/genomic-medicine-sweden/teams/jasen-devs) and the [JASEN Code Owners](https://github.com/genomic-medicine-sweden/jasen/blob/master/.github/CODEOWNERS).

The developers team should be maintained to ensure that there are active developers for each GMS repository. This will ensure that it is easy to get a hold of a developer if there are questions or if there a bugs/errors which need to be adressed. 

### Versioning
All tools developed in the GMS GitHub should be versioned and regular [releases](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository) (with verbose release notes) should be created. This help users to deploy stable version of the tools.

Versioning of releases is enocuraged to follow [Semantic Versioning](https://semver.org/). 

### Action workflows
For now the GMS GitHub only have access to 2000 minutes for GitHub actions per month. Once the are used up there are no additional resources for this. Due to this we encourage developers to be considerate in which automations are set up.

One should also be aware that github actions in repositories which have no commits in the last 60 days will be deactivated. This is a feature of GitHub and there is no possibility to turn this off. A work around is to use the keep-alive action which adds a keep alive ocmmit every 59 days: https://github.com/marketplace/actions/keepalive-workflow 

### Non-used repositories
If there are repos which are no longer maintained, they should be archived. Reach out to one of the [owners of the GitHub organisation](https://github.com/orgs/genomic-medicine-sweden/people?query=role%3Aowner) if you have such a repo.

</details>
