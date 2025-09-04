<img src="repozilla_logo.png" alt="Repozilla Logo" width="256" height="256">

**Repozilla**

A robust repository library for MongoDB with scoped access, full CRUD, audit trails, versioning, aggregation, and deep search — backed by 40+ test cases including edge cases and OWASP scenarios. SQL Server and other databases coming soon.

---

**Overview**

Repozilla is a fully implemented, production-ready repository library designed for MongoDB-backed collections. It provides a clean abstraction for data access while enforcing scoped visibility and semantic versioning.

**Core Features**

- CRUD operations with soft delete, restore, rollback, and upgrade support  
- Scoped querying using access context, predicates, filters, and dynamic search  
- Aggregation pipelines for advanced data shaping  
- Audit trail and versioning with upgrade previews and rollback  
- Upgrade path validation and historical inspection  
- 40+ test cases covering edge scenarios, OWASP threats, and nested data  
- Modular architecture built on `Jamun.Model.Dto.Repository`  
- Semantic versioning and compatibility matrix powered by [VersionSurgeon](https://github.com/AmitDua/VersionSurgeon)

**Deep Search Highlights**

- Native pagination, multi-field sorting, and projections  
- Predicate-based filtering with LINQ-style expressions  
- Dynamic filters via `QueryFilter`  
- Nested array support with `$elemMatch`, `$in`, and `$all`  
- Scoped access enforcement for multi-tenant and role-based data isolation

---

Currently optimized for MongoDB, Repozilla is built with cross-database support in mind. SQL Server and other providers are on the roadmap, making it a future-proof solution for multi-database environments.
