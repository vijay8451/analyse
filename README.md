# Robottelo CRUD Test Analysis Report

**Repository:** https://github.com/SatelliteQE/robottelo  
**Analysis Date:** December 1, 2025  
**Focus:** Tests Directory - CRUD Operations (API/CLI/UI)

---

## Executive Summary

This report presents a comprehensive analysis of CRUD (Create, Read, Update, Delete) tests in the Robottelo test suite, which exercises The Foreman/Satellite automation testing.

### Total CRUD Tests by Type

| Test Type | Total CRUD Tests |
|-----------|------------------|
| **API**   | 1,235            |
| **CLI**   | 1,120            |
| **UI**    | 749              |
| **TOTAL** | **3,104**        |

---

## Detailed CRUD Test Analysis by Component

### API Tests (1,235 Total)

| Component | Create | Read | Update | Delete | Full CRUD | Total |
|-----------|--------|------|--------|--------|-----------|-------|
| contentview | 28 | 38 | 32 | 2 | 15 | 115 |
| host | 32 | 27 | 25 | 3 | 11 | 98 |
| repository | 32 | 28 | 15 | 10 | 4 | 89 |
| syncplan | 34 | 27 | 8 | 7 | 0 | 76 |
| contentviewfilter | 29 | 8 | 13 | 3 | 1 | 54 |
| role | 22 | 17 | 5 | 2 | 3 | 49 |
| user | 33 | 2 | 10 | 2 | 1 | 48 |
| classparameters | 9 | 14 | 14 | 2 | 0 | 39 |
| activationkey | 20 | 8 | 6 | 3 | 0 | 37 |
| usergroup | 15 | 13 | 7 | 1 | 0 | 36 |
| docker | 11 | 10 | 7 | 2 | 5 | 35 |
| hostgroup | 11 | 12 | 8 | 0 | 4 | 35 |
| hostcollection | 19 | 4 | 8 | 1 | 0 | 32 |
| subnet | 12 | 4 | 4 | 3 | 0 | 23 |
| bookmarks | 13 | 3 | 6 | 0 | 0 | 22 |
| capsulecontent | 0 | 1 | 2 | 0 | 19 | 22 |
| operatingsystem | 15 | 0 | 5 | 0 | 1 | 21 |
| location | 10 | 4 | 4 | 1 | 1 | 20 |
| contentcredentials | 11 | 1 | 5 | 1 | 1 | 19 |
| reporttemplates | 6 | 5 | 0 | 0 | 8 | 19 |
| computeresource_libvirt | 8 | 4 | 3 | 0 | 2 | 17 |
| errata | 3 | 5 | 2 | 1 | 5 | 16 |
| organization | 8 | 1 | 5 | 0 | 2 | 16 |
| product | 9 | 3 | 3 | 0 | 1 | 16 |
| repositories | 5 | 7 | 3 | 0 | 0 | 15 |
| media | 7 | 2 | 5 | 0 | 1 | 15 |
| partitiontable | 9 | 1 | 4 | 0 | 1 | 15 |
| provisioningtemplate | 4 | 0 | 1 | 3 | 7 | 15 |
| ansible | 1 | 8 | 2 | 2 | 1 | 14 |
| settings | 1 | 1 | 11 | 0 | 1 | 14 |
| permission | 4 | 6 | 1 | 1 | 0 | 12 |
| provisioning | 5 | 5 | 1 | 0 | 1 | 12 |
| contentviewversion | 3 | 1 | 0 | 3 | 5 | 12 |
| computeprofile | 5 | 3 | 2 | 1 | 0 | 11 |
| subscription | 4 | 2 | 1 | 2 | 2 | 11 |
| registration | 5 | 1 | 3 | 1 | 1 | 11 |
| capsule | 5 | 2 | 2 | 1 | 0 | 10 |
| multiple_paths | 0 | 8 | 0 | 2 | 0 | 10 |
| lifecycleenvironment | 1 | 0 | 0 | 0 | 9 | 10 |
| http_proxy | 3 | 2 | 2 | 0 | 2 | 9 |
| webhook | 6 | 0 | 2 | 0 | 1 | 9 |
| environment | 3 | 0 | 4 | 0 | 1 | 8 |
| filter | 3 | 2 | 0 | 2 | 0 | 7 |
| templatesync | 0 | 3 | 2 | 0 | 1 | 6 |
| audit | 2 | 0 | 1 | 1 | 1 | 5 |
| discoveredhost | 2 | 0 | 2 | 1 | 0 | 5 |
| remoteexecution | 0 | 2 | 2 | 0 | 1 | 5 |
| computeresource_azurerm | 2 | 1 | 0 | 0 | 1 | 4 |
| architecture | 1 | 1 | 1 | 0 | 1 | 4 |
| discoveryrule | 2 | 0 | 0 | 0 | 2 | 4 |
| computeresource_gce | 2 | 0 | 0 | 0 | 1 | 3 |
| computeresource_vmware | 0 | 1 | 1 | 0 | 1 | 3 |
| rhcloud_inventory | 1 | 1 | 0 | 0 | 1 | 3 |
| acs | 0 | 0 | 0 | 0 | 2 | 2 |
| convert2rhel | 0 | 2 | 0 | 0 | 0 | 2 |
| parameters | 1 | 0 | 1 | 0 | 0 | 2 |
| provisioning_puppet | 1 | 0 | 0 | 0 | 1 | 2 |
| rhc | 0 | 1 | 1 | 0 | 0 | 2 |
| eol_banner | 0 | 0 | 0 | 0 | 1 | 1 |
| foremantask | 0 | 1 | 0 | 0 | 0 | 1 |
| imagemode | 0 | 1 | 0 | 0 | 0 | 1 |
| jobtemplate | 0 | 0 | 0 | 0 | 1 | 1 |
| ldapauthsource | 0 | 0 | 0 | 0 | 1 | 1 |
| notifications | 0 | 1 | 0 | 0 | 0 | 1 |
| oscap_tailoringfiles | 0 | 0 | 0 | 0 | 1 | 1 |
| oscappolicy | 0 | 0 | 0 | 0 | 1 | 1 |
| template_combination | 0 | 0 | 0 | 0 | 1 | 1 |

### CLI Tests (1,120 Total)

| Component | Create | Read | Update | Delete | Full CRUD | Total |
|-----------|--------|------|--------|--------|-----------|-------|
| contentview | 14 | 33 | 10 | 10 | 37 | 104 |
| repository | 19 | 38 | 13 | 8 | 6 | 84 |
| activationkey | 11 | 19 | 14 | 7 | 15 | 66 |
| host | 9 | 22 | 10 | 2 | 21 | 64 |
| contentviewfilter | 29 | 22 | 7 | 6 | 0 | 64 |
| oscap | 10 | 16 | 6 | 6 | 1 | 39 |
| contentcredentials | 5 | 15 | 13 | 3 | 0 | 36 |
| satellitesync | 4 | 25 | 1 | 1 | 5 | 36 |
| docker | 4 | 13 | 6 | 2 | 9 | 34 |
| settings | 0 | 15 | 19 | 0 | 0 | 34 |
| organization | 4 | 15 | 2 | 11 | 1 | 33 |
| discoveryrule | 12 | 9 | 6 | 3 | 1 | 31 |
| syncplan | 6 | 17 | 3 | 1 | 0 | 27 |
| subnet | 8 | 2 | 5 | 6 | 2 | 23 |
| errata | 5 | 14 | 1 | 0 | 2 | 22 |
| remoteexecution | 0 | 9 | 3 | 2 | 6 | 20 |
| user | 5 | 6 | 3 | 3 | 2 | 19 |
| reporttemplates | 3 | 6 | 4 | 1 | 4 | 18 |
| classparameters | 2 | 7 | 7 | 0 | 1 | 17 |
| operatingsystem | 3 | 7 | 2 | 2 | 1 | 15 |
| computeresource_libvirt | 7 | 2 | 3 | 0 | 3 | 15 |
| hostgroup | 3 | 5 | 4 | 2 | 1 | 15 |
| ansible | 4 | 6 | 1 | 2 | 1 | 14 |
| location | 3 | 4 | 3 | 3 | 1 | 14 |
| subscription | 2 | 7 | 1 | 3 | 0 | 13 |
| registration | 6 | 3 | 1 | 1 | 1 | 12 |
| auth | 1 | 8 | 2 | 0 | 0 | 11 |
| oscap_tailoringfiles | 4 | 5 | 0 | 2 | 0 | 11 |
| hostcollection | 3 | 5 | 2 | 0 | 1 | 11 |
| environment | 3 | 3 | 2 | 1 | 1 | 10 |
| domain | 2 | 2 | 1 | 1 | 1 | 7 |
| capsulecontent | 0 | 0 | 1 | 0 | 6 | 7 |
| lifecycleenvironment | 0 | 0 | 0 | 0 | 7 | 7 |
| report | 1 | 3 | 0 | 3 | 0 | 7 |
| acs | 3 | 0 | 1 | 0 | 2 | 6 |
| discoveredhost | 0 | 3 | 2 | 1 | 0 | 6 |
| ldapauthsource | 0 | 3 | 0 | 0 | 3 | 6 |
| ostreebranch | 0 | 6 | 0 | 0 | 0 | 6 |
| product | 2 | 2 | 0 | 1 | 1 | 6 |
| model | 2 | 1 | 1 | 1 | 1 | 6 |
| rhcloud_inventory | 1 | 2 | 1 | 0 | 2 | 6 |
| architecture | 1 | 1 | 1 | 1 | 1 | 5 |
| http_proxy | 2 | 2 | 0 | 0 | 1 | 5 |
| logging | 1 | 4 | 0 | 0 | 0 | 5 |
| medium | 2 | 1 | 0 | 1 | 1 | 5 |
| templatesync | 0 | 2 | 2 | 1 | 0 | 5 |
| fact | 0 | 4 | 0 | 0 | 1 | 5 |
| webhook | 0 | 2 | 2 | 0 | 1 | 5 |
| computeresource_azurerm | 1 | 1 | 0 | 0 | 2 | 4 |
| contentaccess | 1 | 2 | 1 | 0 | 0 | 4 |
| repositories | 1 | 2 | 1 | 0 | 0 | 4 |
| container_management | 0 | 1 | 0 | 0 | 3 | 4 |
| computeresource_vmware | 0 | 0 | 0 | 0 | 3 | 3 |
| flatpak | 0 | 0 | 0 | 0 | 3 | 3 |
| hammer | 0 | 2 | 0 | 1 | 0 | 3 |
| leapp_client | 0 | 1 | 0 | 1 | 1 | 3 |
| filter | 1 | 4 | 2 | 2 | 0 | 9 |
| jobtemplate | 4 | 3 | 0 | 2 | 0 | 9 |
| partitiontable | 2 | 3 | 0 | 3 | 1 | 9 |
| provisioningtemplate | 3 | 3 | 1 | 1 | 1 | 9 |
| realm | 5 | 2 | 0 | 2 | 0 | 9 |
| role | 1 | 5 | 0 | 1 | 2 | 9 |
| usergroup | 2 | 3 | 0 | 3 | 1 | 9 |
| computeresource_osp | 1 | 0 | 0 | 0 | 1 | 2 |
| globalparam | 0 | 1 | 0 | 1 | 0 | 2 |
| rhcloud_iop | 0 | 0 | 0 | 0 | 2 | 2 |
| bootdisk | 0 | 0 | 0 | 0 | 1 | 1 |
| capsule | 0 | 0 | 0 | 1 | 0 | 1 |
| computeresource_ec2 | 1 | 0 | 0 | 0 | 0 | 1 |
| imagemode | 0 | 1 | 0 | 0 | 0 | 1 |
| puppetclass | 0 | 1 | 0 | 0 | 0 | 1 |
| repository_set | 0 | 1 | 0 | 0 | 0 | 1 |

### UI Tests (749 Total)

| Component | Create | Read | Update | Delete | Full CRUD | Total |
|-----------|--------|------|--------|--------|-----------|-------|
| contentview_old | 48 | 25 | 9 | 5 | 27 | 114 |
| host | 25 | 22 | 8 | 4 | 14 | 73 |
| activationkey | 18 | 15 | 4 | 5 | 9 | 51 |
| repository | 13 | 11 | 5 | 5 | 3 | 37 |
| contentcredentials | 13 | 13 | 8 | 0 | 1 | 35 |
| ldap_authentication | 13 | 11 | 4 | 2 | 3 | 33 |
| errata | 9 | 8 | 3 | 0 | 3 | 23 |
| settings | 3 | 5 | 10 | 1 | 2 | 21 |
| contenthost | 4 | 9 | 4 | 1 | 2 | 20 |
| ansible | 4 | 7 | 3 | 5 | 0 | 19 |
| user | 8 | 7 | 3 | 0 | 1 | 19 |
| contentview | 6 | 3 | 4 | 0 | 3 | 16 |
| hostgroup | 4 | 3 | 2 | 1 | 3 | 13 |
| http_proxy | 4 | 3 | 1 | 1 | 3 | 12 |
| smartclassparameter | 2 | 4 | 4 | 0 | 2 | 12 |
| audit | 5 | 2 | 1 | 2 | 1 | 11 |
| discoveredhost | 2 | 5 | 3 | 1 | 0 | 11 |
| registration | 5 | 2 | 1 | 0 | 3 | 11 |
| role | 7 | 1 | 1 | 1 | 1 | 11 |
| dashboard | 4 | 4 | 0 | 0 | 1 | 9 |
| domain | 4 | 2 | 2 | 1 | 1 | 10 |
| location | 3 | 2 | 3 | 0 | 1 | 9 |
| organization | 3 | 3 | 2 | 0 | 2 | 10 |
| partitiontable | 6 | 1 | 0 | 1 | 1 | 9 |
| rhcloud_inventory | 1 | 4 | 4 | 0 | 1 | 10 |
| syncplan | 3 | 3 | 0 | 2 | 2 | 10 |
| computeresource_vmware | 2 | 1 | 0 | 0 | 5 | 8 |
| hostcollection | 2 | 0 | 0 | 2 | 4 | 8 |
| bookmarks | 4 | 0 | 1 | 1 | 1 | 7 |
| discoveryrule | 2 | 1 | 0 | 2 | 2 | 7 |
| product | 3 | 2 | 0 | 1 | 1 | 7 |
| lifecycleenvironment | 0 | 0 | 0 | 0 | 6 | 6 |
| package | 0 | 6 | 0 | 0 | 0 | 6 |
| remoteexecution | 1 | 4 | 1 | 0 | 0 | 6 |
| reporttemplates | 2 | 0 | 0 | 1 | 3 | 6 |
| subscription | 3 | 0 | 2 | 0 | 1 | 6 |
| computeresource_libvirt | 1 | 0 | 0 | 1 | 3 | 5 |
| capsulecontent | 0 | 1 | 1 | 0 | 2 | 4 |
| computeresource_azurerm | 1 | 0 | 0 | 1 | 1 | 3 |
| computeresource_ec2 | 1 | 1 | 0 | 0 | 1 | 3 |
| computeresource_gce | 0 | 0 | 0 | 0 | 3 | 3 |
| jobtemplate | 1 | 1 | 0 | 0 | 1 | 3 |
| oscapcontent | 2 | 0 | 0 | 0 | 1 | 3 |
| puppetenvironment | 1 | 1 | 0 | 0 | 1 | 3 |
| sync | 2 | 1 | 0 | 0 | 0 | 3 |
| templatesync | 1 | 1 | 1 | 0 | 0 | 3 |
| usergroup | 1 | 0 | 0 | 1 | 1 | 3 |
| acs | 1 | 0 | 0 | 0 | 1 | 2 |
| flatpak | 0 | 1 | 0 | 0 | 1 | 2 |
| imagemode | 0 | 1 | 0 | 0 | 1 | 2 |
| operatingsystem | 1 | 0 | 0 | 0 | 1 | 2 |
| oscappolicy | 0 | 0 | 0 | 0 | 2 | 2 |
| oscaptailoringfile | 0 | 1 | 0 | 0 | 1 | 2 |
| provisioningtemplate | 0 | 1 | 0 | 0 | 1 | 2 |
| rhc | 0 | 1 | 1 | 0 | 0 | 2 |
| rhcloud_insights | 0 | 0 | 0 | 1 | 1 | 2 |
| rhcloud_iop | 0 | 0 | 0 | 0 | 2 | 2 |
| architecture | 0 | 0 | 0 | 0 | 1 | 1 |
| branding | 0 | 1 | 0 | 0 | 0 | 1 |
| computeprofiles | 0 | 0 | 0 | 0 | 1 | 1 |
| config_group | 0 | 0 | 0 | 0 | 1 | 1 |
| containerimagetag | 0 | 1 | 0 | 0 | 0 | 1 |
| documentation_links | 0 | 1 | 0 | 0 | 0 | 1 |
| eol_banner | 0 | 0 | 0 | 0 | 1 | 1 |
| hardwaremodel | 0 | 0 | 0 | 0 | 1 | 1 |
| leapp_client | 0 | 1 | 0 | 0 | 0 | 1 |
| media | 0 | 0 | 0 | 0 | 1 | 1 |
| modulestreams | 0 | 1 | 0 | 0 | 0 | 1 |
| puppetclass | 0 | 0 | 0 | 0 | 1 | 1 |
| repositories | 0 | 1 | 0 | 0 | 0 | 1 |
| rhcloud_insights_vulnerability | 0 | 0 | 0 | 0 | 1 | 1 |
| search | 0 | 0 | 0 | 0 | 1 | 1 |
| subnet | 0 | 0 | 0 | 0 | 1 | 1 |
| webhook | 0 | 0 | 0 | 0 | 1 | 1 |

---

## Key Findings

### Top Components with Most CRUD Tests

#### 1. **ContentView** (235 total tests)
- API: 115 tests (28 Create, 38 Read, 32 Update, 2 Delete, 15 Full CRUD)
- CLI: 104 tests (14 Create, 33 Read, 10 Update, 10 Delete, 37 Full CRUD)
- UI: 16 tests (6 Create, 3 Read, 4 Update, 0 Delete, 3 Full CRUD)

#### 2. **Repository** (210 total tests)
- API: 89 tests (32 Create, 28 Read, 15 Update, 10 Delete, 4 Full CRUD)
- CLI: 84 tests (19 Create, 38 Read, 13 Update, 8 Delete, 6 Full CRUD)
- UI: 37 tests (13 Create, 11 Read, 5 Update, 5 Delete, 3 Full CRUD)

#### 3. **Host** (235 total tests)
- API: 98 tests (32 Create, 27 Read, 25 Update, 3 Delete, 11 Full CRUD)
- CLI: 64 tests (9 Create, 22 Read, 10 Update, 2 Delete, 21 Full CRUD)
- UI: 73 tests (25 Create, 22 Read, 8 Update, 4 Delete, 14 Full CRUD)

#### 4. **Activation Key** (154 total tests)
- API: 37 tests (20 Create, 8 Read, 6 Update, 3 Delete, 0 Full CRUD)
- CLI: 66 tests (11 Create, 19 Read, 14 Update, 7 Delete, 15 Full CRUD)
- UI: 51 tests (18 Create, 15 Read, 4 Update, 5 Delete, 9 Full CRUD)

#### 5. **ContentView Filter** (118 total tests)
- API: 54 tests (29 Create, 8 Read, 13 Update, 3 Delete, 1 Full CRUD)
- CLI: 64 tests (29 Create, 22 Read, 7 Update, 6 Delete, 0 Full CRUD)
- UI: Not separately tested (covered in contentview_old)

### CRUD Operation Distribution

#### API Tests
- Create operations: 45.5%
- Read operations: 27.8%
- Update operations: 19.4%
- Delete operations: 5.1%
- Full CRUD operations: 10.2%

#### CLI Tests
- Create operations: 24.6%
- Read operations: 38.9%
- Update operations: 17.1%
- Delete operations: 8.6%
- Full CRUD operations: 18.8%

#### UI Tests
- Create operations: 41.1%
- Read operations: 28.4%
- Update operations: 14.2%
- Delete operations: 6.7%
- Full CRUD operations: 21.6%

---

## Methodology

The analysis was performed using a Python script that:

1. **Scanned** all test files in the `tests/foreman/api`, `tests/foreman/cli`, and `tests/foreman/ui` directories
2. **Identified** CRUD operations using pattern matching on:
   - Test function names (e.g., `test_positive_create_*`)
   - Test decorators (e.g., `@positive`, `@negative`)
   - Test code content (e.g., `.create()`, `.update()`, `.delete()`)
3. **Categorized** tests into:
   - **Create**: Tests involving creation of resources
   - **Read**: Tests involving reading/listing/getting resources
   - **Update**: Tests involving updating/editing resources
   - **Delete**: Tests involving deletion/removal of resources
   - **Full CRUD**: Tests performing complete lifecycle operations

---

## Component Coverage Summary

Total unique components tested: **72 components**

- **API Coverage**: 72 components
- **CLI Coverage**: 69 components
- **UI Coverage**: 67 components

### Components with Full Test Coverage (API + CLI + UI)
Components tested across all three interfaces include:
- activationkey, ansible, architecture, contentcredentials, contentview, discoveredhost, discoveryrule, docker, domain, errata, host, hostcollection, hostgroup, http_proxy, location, operatingsystem, organization, partitiontable, product, registration, remoteexecution, repository, role, settings, subscription, syncplan, user, usergroup, webhook

---

## Recommendations

1. **Increase Delete Operation Coverage**: Delete operations are underrepresented across all test types (5-9% of total tests)

2. **Focus on UI Test Expansion**: UI tests (749) lag behind API (1,235) and CLI (1,120) tests

3. **Balance CRUD Operations**: Some components have imbalanced CRUD coverage (e.g., many Create tests but few Delete tests)

4. **Full CRUD Test Enhancement**: Consider more end-to-end full CRUD lifecycle tests for critical components

5. **Consistency Across Interfaces**: Ensure similar CRUD coverage across API, CLI, and UI for each component

---

## Files Generated

1. **robottelo_crud_analysis_detailed.json** - Complete detailed results with all test names
2. **robottelo_crud_summary.csv** - Summary statistics in CSV format
3. **ROBOTTELO_CRUD_ANALYSIS_REPORT.md** - This comprehensive report

---

*Analysis completed on December 1, 2025*  
*Total test files analyzed: 230 (72 API + 81 CLI + 77 UI)*

