**[linkedin-private-api](../README.md)**

> [Globals](../globals.md) / ["src/repositories/search.repository"](../modules/_src_repositories_search_repository_.md) / SearchRepository

# Class: SearchRepository

## Hierarchy

- **SearchRepository**

## Index

### Constructors

- [constructor](_src_repositories_search_repository_.searchrepository.md#constructor)

### Properties

- [client](_src_repositories_search_repository_.searchrepository.md#client)

### Methods

- [searchCompanies](_src_repositories_search_repository_.searchrepository.md#searchcompanies)
- [searchConnectionsOf](_src_repositories_search_repository_.searchrepository.md#searchconnectionsof)
- [searchJobs](_src_repositories_search_repository_.searchrepository.md#searchjobs)
- [searchOwnConnections](_src_repositories_search_repository_.searchrepository.md#searchownconnections)
- [searchPeople](_src_repositories_search_repository_.searchrepository.md#searchpeople)

## Constructors

### constructor

\+ **new SearchRepository**(`__namedParameters`: { client: [Client](_src_core_client_.client.md) }): [SearchRepository](_src_repositories_search_repository_.searchrepository.md)

_Defined in [src/repositories/search.repository.ts:24](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L24)_

#### Parameters:

| Name                | Type                                              |
| ------------------- | ------------------------------------------------- |
| `__namedParameters` | { client: [Client](_src_core_client_.client.md) } |

**Returns:** [SearchRepository](_src_repositories_search_repository_.searchrepository.md)

## Properties

### client

• **client**: [Client](_src_core_client_.client.md)

_Defined in [src/repositories/search.repository.ts:24](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L24)_

## Methods

### searchCompanies

▸ **searchCompanies**(`__namedParameters?`: { keywords: undefined \| string ; limit: number = 10; skip: number = 0 }): [CompanySearchScroller](_src_scrollers_company_search_scroller_.companysearchscroller.md)

_Defined in [src/repositories/search.repository.ts:50](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L50)_

#### Parameters:

| Name                | Type                                                                     | Default value |
| ------------------- | ------------------------------------------------------------------------ | ------------- |
| `__namedParameters` | { keywords: undefined \| string ; limit: number = 10; skip: number = 0 } | {}            |

**Returns:** [CompanySearchScroller](_src_scrollers_company_search_scroller_.companysearchscroller.md)

---

### searchConnectionsOf

▸ **searchConnectionsOf**(`__namedParameters`: { filters: Omit<PeopleSearchFilters, \"network\" \| \"connectionOf\"\> ; keywords: undefined \| string ; limit: number = 10; profileId: string ; skip: number = 0 }): [PeopleSearchScroller](_src_scrollers_people_search_scroller_.peoplesearchscroller.md)

_Defined in [src/repositories/search.repository.ts:87](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L87)_

#### Parameters:

| Name                | Type                                                                                                                                                                |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `__namedParameters` | { filters: Omit<PeopleSearchFilters, \"network\" \| \"connectionOf\"\> ; keywords: undefined \| string ; limit: number = 10; profileId: string ; skip: number = 0 } |

**Returns:** [PeopleSearchScroller](_src_scrollers_people_search_scroller_.peoplesearchscroller.md)

---

### searchJobs

▸ **searchJobs**(`__namedParameters?`: { filters: JobSearchFilters ; keywords: undefined \| string ; limit: number = 10; skip: number = 0 }): [JobSearchScroller](_src_scrollers_job_search_scroller_.jobsearchscroller.md)

_Defined in [src/repositories/search.repository.ts:109](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L109)_

#### Parameters:

| Name                | Type                                                                                                 | Default value |
| ------------------- | ---------------------------------------------------------------------------------------------------- | ------------- |
| `__namedParameters` | { filters: JobSearchFilters ; keywords: undefined \| string ; limit: number = 10; skip: number = 0 } | {}            |

**Returns:** [JobSearchScroller](_src_scrollers_job_search_scroller_.jobsearchscroller.md)

---

### searchOwnConnections

▸ **searchOwnConnections**(`__namedParameters?`: { filters: Omit<PeopleSearchFilters, \"network\"\> ; keywords: undefined \| string ; limit: number = 10; skip: number = 0 }): [PeopleSearchScroller](_src_scrollers_people_search_scroller_.peoplesearchscroller.md)

_Defined in [src/repositories/search.repository.ts:67](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L67)_

#### Parameters:

| Name                | Type                                                                                                                        | Default value |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------- | ------------- |
| `__namedParameters` | { filters: Omit<PeopleSearchFilters, \"network\"\> ; keywords: undefined \| string ; limit: number = 10; skip: number = 0 } | {}            |

**Returns:** [PeopleSearchScroller](_src_scrollers_people_search_scroller_.peoplesearchscroller.md)

---

### searchPeople

▸ **searchPeople**(`__namedParameters?`: { filters: PeopleSearchFilters ; keywords: undefined \| string ; limit: number = 10; skip: number = 0 }): [PeopleSearchScroller](_src_scrollers_people_search_scroller_.peoplesearchscroller.md)

_Defined in [src/repositories/search.repository.ts:30](https://github.com/eilonmore/linkedin-private-api/blob/84c9c15/src/repositories/search.repository.ts#L30)_

#### Parameters:

| Name                | Type                                                                                                    | Default value |
| ------------------- | ------------------------------------------------------------------------------------------------------- | ------------- |
| `__namedParameters` | { filters: PeopleSearchFilters ; keywords: undefined \| string ; limit: number = 10; skip: number = 0 } | {}            |

**Returns:** [PeopleSearchScroller](_src_scrollers_people_search_scroller_.peoplesearchscroller.md)
