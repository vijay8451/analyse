# Robottelo CRUD Test Analysis Report (By CaseComponent)

**Repository:** https://github.com/SatelliteQE/robottelo  
**Analysis Date:** December 1, 2025  
**Focus:** Tests Directory - CRUD Operations (API/CLI/UI)  
**Component Classification:** Based on `:CaseComponent:` metadata in test files

---

## Executive Summary

This report presents a comprehensive analysis of CRUD (Create, Read, Update, Delete) tests in the Robottelo test suite, which exercises The Foreman/Satellite automation testing. Tests are categorized by their **CaseComponent** metadata, which is extracted from test docstrings (test-level, class-level, or module-level).

### Total CRUD Tests by Type

| Test Type | Total CRUD Tests |
|-----------|------------------|
| **API**   | 1,200            |
| **CLI**   | 1,072            |
| **UI**    | 730              |
| **TOTAL** | **3,002**        |

### Unique Components Tested

**54 unique CaseComponents** identified across the test suite

---

## Detailed CRUD Test Analysis by CaseComponent

### API Tests (1,200 Total)

| CaseComponent | Create | Read | Update | Delete | Full CRUD | Total |
|---------------|--------|------|--------|--------|-----------|-------|
| **ContentViews** | 58 | 45 | 43 | 8 | 21 | **175** |
| **UsersRoles** | 77 | 40 | 23 | 8 | 4 | **152** |
| **Hosts** | 49 | 31 | 35 | 3 | 14 | **132** |
| **Repositories** | 46 | 38 | 21 | 10 | 5 | **120** |
| **SyncPlans** | 34 | 27 | 8 | 7 | 0 | **76** |
| **Puppet** | 14 | 15 | 18 | 2 | 2 | **51** |
| **ComputeResources** | 17 | 9 | 6 | 1 | 5 | **38** |
| **ActivationKeys** | 20 | 8 | 6 | 3 | 0 | **37** |
| **OrganizationsandLocations** | 18 | 5 | 9 | 1 | 3 | **36** |
| **HostGroup** | 11 | 12 | 8 | 0 | 4 | **35** |
| **Provisioning** | 20 | 5 | 6 | 0 | 2 | **33** |
| **HostCollections** | 19 | 4 | 8 | 1 | 0 | **32** |
| **Networking** | 12 | 4 | 4 | 3 | 0 | **23** |
| **Capsule** | 0 | 1 | 2 | 0 | 19 | **22** |
| **Search** | 13 | 3 | 6 | 0 | 0 | **22** |
| **ContentCredentials** | 11 | 1 | 5 | 1 | 1 | **19** |
| **Reporting** | 6 | 5 | 0 | 0 | 8 | **19** |
| **ErrataManagement** | 3 | 5 | 2 | 1 | 5 | **16** |
| **ProvisioningTemplates** | 4 | 0 | 1 | 3 | 8 | **16** |
| **Ansible** | 1 | 8 | 2 | 2 | 1 | **14** |
| **Settings** | 1 | 1 | 11 | 0 | 1 | **14** |
| **Registration** | 5 | 1 | 3 | 1 | 1 | **11** |
| **SubscriptionManagement** | 4 | 2 | 1 | 2 | 2 | **11** |
| **API** | 0 | 8 | 0 | 2 | 0 | **10** |
| **LifecycleEnvironments** | 1 | 0 | 0 | 0 | 9 | **10** |
| **HTTPProxy** | 3 | 2 | 2 | 0 | 2 | **9** |
| **HooksandWebhooks** | 6 | 0 | 2 | 0 | 1 | **9** |
| **ForemanProxy** | 4 | 1 | 2 | 1 | 0 | **8** |
| **Pulp** | 2 | 2 | 2 | 0 | 0 | **6** |
| **RemoteExecution** | 0 | 2 | 2 | 0 | 2 | **6** |
| **TemplatesPlugin** | 0 | 3 | 2 | 0 | 1 | **6** |
| **AuditLog** | 2 | 0 | 1 | 1 | 1 | **5** |
| **DiscoveryImage** | 2 | 0 | 2 | 1 | 0 | **5** |
| **RHCloud** | 1 | 2 | 1 | 0 | 1 | **5** |
| **DiscoveryPlugin** | 2 | 0 | 0 | 0 | 2 | **4** |
| **AlternateContentSources** | 0 | 0 | 0 | 0 | 2 | **2** |
| **Conversionsappliance** | 0 | 2 | 0 | 0 | 0 | **2** |
| **Parameters** | 1 | 0 | 1 | 0 | 0 | **2** |
| **SCAPPlugin** | 0 | 0 | 0 | 0 | 2 | **2** |
| **Authentication** | 0 | 0 | 0 | 0 | 1 | **1** |
| **Dashboard** | 0 | 0 | 0 | 0 | 1 | **1** |
| **ImageMode** | 0 | 1 | 0 | 0 | 0 | **1** |
| **Notifications** | 0 | 1 | 0 | 0 | 0 | **1** |
| **TasksPlugin** | 0 | 1 | 0 | 0 | 0 | **1** |

---

### CLI Tests (1,072 Total)

| CaseComponent | Create | Read | Update | Delete | Full CRUD | Total |
|---------------|--------|------|--------|--------|-----------|-------|
| **ContentViews** | 43 | 55 | 17 | 16 | 37 | **168** |
| **Repositories** | 22 | 49 | 14 | 9 | 10 | **104** |
| **Hosts** | 19 | 31 | 14 | 9 | 26 | **99** |
| **ActivationKeys** | 11 | 19 | 14 | 7 | 15 | **66** |
| **SCAPPlugin** | 14 | 21 | 6 | 8 | 1 | **50** |
| **OrganizationsandLocations** | 7 | 19 | 5 | 14 | 2 | **47** |
| **UsersRoles** | 9 | 18 | 5 | 9 | 5 | **46** |
| **ContentCredentials** | 5 | 15 | 13 | 3 | 0 | **36** |
| **InterSatelliteSync** | 4 | 25 | 1 | 1 | 5 | **36** |
| **Puppet** | 6 | 14 | 9 | 4 | 2 | **35** |
| **Settings** | 0 | 15 | 19 | 0 | 0 | **34** |
| **DiscoveryPlugin** | 12 | 9 | 6 | 3 | 1 | **31** |
| **RemoteExecution** | 4 | 12 | 3 | 4 | 7 | **30** |
| **SyncPlans** | 6 | 17 | 3 | 1 | 0 | **27** |
| **Authentication** | 6 | 13 | 2 | 2 | 3 | **26** |
| **ComputeResources** | 10 | 3 | 3 | 0 | 9 | **25** |
| **Networking** | 8 | 2 | 5 | 6 | 2 | **23** |
| **ErrataManagement** | 5 | 14 | 1 | 0 | 2 | **22** |
| **Reporting** | 3 | 6 | 4 | 1 | 4 | **18** |
| **HostGroup** | 3 | 5 | 4 | 2 | 1 | **15** |
| **Provisioning** | 3 | 7 | 2 | 2 | 1 | **15** |
| **SubscriptionManagement** | 2 | 7 | 1 | 3 | 0 | **13** |
| **Registration** | 6 | 3 | 1 | 1 | 1 | **12** |
| **HostCollections** | 3 | 5 | 2 | 0 | 1 | **11** |
| **ProvisioningTemplates** | 3 | 3 | 1 | 1 | 1 | **9** |
| **Capsule** | 0 | 0 | 1 | 0 | 6 | **7** |
| **LifecycleEnvironments** | 0 | 0 | 0 | 0 | 7 | **7** |
| **AlternateContentSources** | 3 | 0 | 1 | 0 | 2 | **6** |
| **DiscoveryImage** | 0 | 3 | 2 | 1 | 0 | **6** |
| **RHCloud** | 1 | 2 | 1 | 0 | 2 | **6** |
| **Fact** | 0 | 4 | 0 | 0 | 1 | **5** |
| **HTTPProxy** | 2 | 2 | 0 | 0 | 1 | **5** |
| **HooksandWebhooks** | 0 | 2 | 2 | 0 | 1 | **5** |
| **Logging** | 1 | 4 | 0 | 0 | 0 | **5** |
| **TemplatesPlugin** | 0 | 2 | 2 | 1 | 0 | **5** |
| **ContainerImageManagement** | 0 | 1 | 0 | 0 | 3 | **4** |
| **Hammer** | 0 | 2 | 0 | 1 | 0 | **3** |
| **Insights** | 0 | 0 | 0 | 0 | 2 | **2** |
| **Leappintegration** | 0 | 1 | 0 | 1 | 0 | **2** |
| **Parameters** | 0 | 1 | 0 | 1 | 0 | **2** |
| **BootdiskPlugin** | 0 | 0 | 0 | 0 | 1 | **1** |
| **ForemanProxy** | 0 | 0 | 0 | 1 | 0 | **1** |
| **ImageMode** | 0 | 1 | 0 | 0 | 0 | **1** |
| **katello** | 0 | 1 | 0 | 0 | 0 | **1** |

---

### UI Tests (730 Total)

| CaseComponent | Create | Read | Update | Delete | Full CRUD | Total |
|---------------|--------|------|--------|--------|-----------|-------|
| **ContentViews** | 54 | 28 | 13 | 5 | 30 | **130** |
| **Hosts** | 39 | 34 | 14 | 7 | 21 | **115** |
| **Repositories** | 18 | 23 | 5 | 6 | 5 | **57** |
| **ActivationKeys** | 18 | 15 | 4 | 5 | 9 | **51** |
| **ContentCredentials** | 13 | 13 | 8 | 0 | 1 | **35** |
| **UsersRoles** | 16 | 8 | 4 | 2 | 3 | **33** |
| **Authentication** | 13 | 11 | 4 | 2 | 3 | **33** |
| **ErrataManagement** | 9 | 8 | 3 | 0 | 3 | **23** |
| **ComputeResources** | 5 | 2 | 0 | 2 | 14 | **23** |
| **Settings** | 3 | 5 | 10 | 1 | 2 | **21** |
| **OrganizationsandLocations** | 6 | 5 | 5 | 0 | 3 | **19** |
| **Puppet** | 3 | 5 | 4 | 0 | 5 | **17** |
| **RHCloud** | 1 | 5 | 5 | 1 | 2 | **14** |
| **HostGroup** | 4 | 3 | 2 | 1 | 3 | **13** |
| **HTTPProxy** | 4 | 3 | 1 | 1 | 3 | **12** |
| **AuditLog** | 5 | 2 | 1 | 2 | 1 | **11** |
| **DiscoveryImage** | 2 | 5 | 3 | 1 | 0 | **11** |
| **Registration** | 5 | 2 | 1 | 0 | 3 | **11** |
| **Dashboard** | 4 | 4 | 0 | 0 | 2 | **10** |
| **SyncPlans** | 3 | 3 | 0 | 2 | 2 | **10** |
| **RemoteExecution** | 2 | 5 | 1 | 0 | 1 | **9** |
| **HostCollections** | 2 | 0 | 0 | 2 | 4 | **8** |
| **Search** | 4 | 0 | 1 | 1 | 2 | **8** |
| **DiscoveryPlugin** | 2 | 1 | 0 | 2 | 2 | **7** |
| **SCAPPlugin** | 2 | 1 | 0 | 0 | 4 | **7** |
| **LifecycleEnvironments** | 0 | 0 | 0 | 0 | 6 | **6** |
| **Reporting** | 2 | 0 | 0 | 1 | 3 | **6** |
| **SubscriptionManagement** | 3 | 0 | 2 | 0 | 1 | **6** |
| **Capsule** | 0 | 1 | 1 | 0 | 2 | **4** |
| **Insights** | 0 | 0 | 0 | 0 | 3 | **3** |
| **TemplatesPlugin** | 1 | 1 | 1 | 0 | 0 | **3** |
| **AlternateContentSources** | 1 | 0 | 0 | 0 | 1 | **2** |
| **Branding** | 0 | 2 | 0 | 0 | 0 | **2** |
| **ImageMode** | 0 | 1 | 0 | 0 | 1 | **2** |
| **Provisioning** | 1 | 0 | 0 | 0 | 1 | **2** |
| **ProvisioningTemplates** | 0 | 1 | 0 | 0 | 1 | **2** |
| **ContainerImageManagement** | 0 | 1 | 0 | 0 | 0 | **1** |
| **HooksandWebhooks** | 0 | 0 | 0 | 0 | 1 | **1** |
| **Leappintegration** | 0 | 1 | 0 | 0 | 0 | **1** |
| **Networking** | 0 | 0 | 0 | 0 | 1 | **1** |

---

## Top Components by Total CRUD Tests (All Test Types Combined)

| Rank | CaseComponent | API | CLI | UI | **Total** |
|------|---------------|-----|-----|-------|-----------|
| 1 | **ContentViews** | 175 | 168 | 130 | **473** |
| 2 | **Hosts** | 132 | 99 | 115 | **346** |
| 3 | **Repositories** | 120 | 104 | 57 | **281** |
| 4 | **UsersRoles** | 152 | 46 | 33 | **231** |
| 5 | **ActivationKeys** | 37 | 66 | 51 | **154** |
| 6 | **Puppet** | 51 | 35 | 17 | **103** |
| 7 | **SyncPlans** | 76 | 27 | 10 | **113** |
| 8 | **OrganizationsandLocations** | 36 | 47 | 19 | **102** |
| 9 | **ContentCredentials** | 19 | 36 | 35 | **90** |
| 10 | **ComputeResources** | 38 | 25 | 23 | **86** |

---

## Key Findings

### 1. **Component Coverage Analysis**

- **54 unique CaseComponents** tested across the suite
- **Top 3 most tested components:**
  1. ContentViews (473 tests)
  2. Hosts (346 tests)
  3. Repositories (281 tests)

### 2. **CRUD Operation Distribution**

#### API Tests (1,200 total)
- **Create:** 46.3% of tests
- **Read:** 26.8% of tests
- **Update:** 17.9% of tests
- **Delete:** 5.4% of tests
- **Full CRUD:** 11.7% of tests

#### CLI Tests (1,072 total)
- **Create:** 23.6% of tests
- **Read:** 40.2% of tests
- **Update:** 16.1% of tests
- **Delete:** 8.5% of tests
- **Full CRUD:** 18.8% of tests

#### UI Tests (730 total)
- **Create:** 39.9% of tests
- **Read:** 29.3% of tests
- **Update:** 14.1% of tests
- **Delete:** 6.8% of tests
- **Full CRUD:** 22.2% of tests

### 3. **Test Interface Comparison**

- **API:** Strongest in total test count (1,200), heavy focus on Create operations
- **CLI:** Most balanced distribution, highest percentage of Full CRUD tests (18.8%)
- **UI:** Smallest test count but highest percentage of Full CRUD tests (22.2%)

### 4. **Coverage Gaps Identified**

**Components with minimal Delete operation coverage:**
- ContentViews: 8 API, 16 CLI, 5 UI delete tests
- Hosts: 3 API, 9 CLI, 7 UI delete tests
- Repositories: 10 API, 9 CLI, 6 UI delete tests

**Components tested in only one interface:**
- **katello** (CLI only - 1 test)
- **Branding** (UI only - 2 tests)
- **Conversionsappliance** (API only - 2 tests)

---

## Component Classification Methodology

Tests were classified using the `:CaseComponent:` metadata found in test docstrings following this hierarchy:

1. **Test-level docstring** - CaseComponent specified in individual test function docstring
2. **Class-level docstring** - CaseComponent specified in test class docstring (for grouped tests)
3. **Module-level docstring** - CaseComponent specified at the file level

This ensures accurate component classification based on the actual test metadata rather than file naming conventions.

---

## Recommendations

### 1. **Increase Delete Operation Coverage**
Delete operations are consistently underrepresented across all test types (5-9% of total tests). Recommend adding comprehensive deletion tests for:
- ContentViews
- Hosts
- Repositories
- All major components with < 10% delete coverage

### 2. **Balance UI Test Coverage**
UI tests (730) lag significantly behind API (1,200) and CLI (1,072) tests. Consider expanding UI test coverage for:
- Settings (21 UI vs 14 API, 34 CLI)
- SyncPlans (10 UI vs 76 API, 27 CLI)
- Puppet (17 UI vs 51 API, 35 CLI)

### 3. **Expand Full CRUD Tests**
While CLI and UI have good Full CRUD coverage (18.8% and 22.2%), API tests could benefit from more end-to-end lifecycle tests (currently 11.7%)

### 4. **Address Single-Interface Components**
Components tested in only one interface should be evaluated for cross-interface test coverage needs

### 5. **Standardize CaseComponent Metadata**
Some test files are missing CaseComponent metadata (4 files identified). Ensure all test files include proper component classification

---

## Files Generated

1. **robottelo_crud_by_casecomponent_detailed.json** - Complete detailed results with all test names and file mappings
2. **robottelo_crud_by_casecomponent_summary.csv** - Summary statistics in CSV format for easy analysis
3. **ROBOTTELO_CRUD_ANALYSIS_REPORT.md** - This comprehensive report

---

## Analysis Details

- **Total test files analyzed:** 230 files (72 API + 81 CLI + 77 UI)
- **Tests with CaseComponent metadata:** 3,002 CRUD tests
- **Component extraction method:** AST parsing with regex fallback
- **Metadata hierarchy:** Test-level → Class-level → Module-level

---

*Analysis completed on December 1, 2025*  
*Robottelo Repository: https://github.com/SatelliteQE/robottelo*  
*Classification based on :CaseComponent: metadata*
