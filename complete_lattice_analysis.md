# Complete Lattice Analysis: All Groups and Properties

## The Lattice (Containment Order)

```
                         Π = ∏ᵢ ℤ/2ⁱℤ
                              │
                           K + Ḡ
                          ╱     ╲
                         K       Ḡ
                          ╲     ╱
                             G
                             │
                             0
```

---

## Part I: Properties of Base Groups

### Legend
- ✓ = Yes
- ✗ = No
- P = Partial / Some elements
- ? = Unknown / Unclear

### Table 1: Structural Properties

| Group | Torsion | Torsion-Free | Mixed | Bounded Torsion | Countable | Cardinality |
|-------|---------|--------------|-------|-----------------|-----------|-------------|
| **G** = ⊕ᵢ ℤ/2ⁱ | ✓ | ✗ | ✗ | ✗ (unbounded) | ✓ | ℵ₀ |
| **K** = Ext(ℚ/ℤ,G) | ✗ | ✗ | ✓ | ✗ | ✗ | 2^ℵ₀ |
| **Ḡ** = torsion(Π) | ✓ | ✗ | ✗ | P (each elt bounded) | ✗ | 2^ℵ₀ |
| **K+Ḡ** | ✗ | ✗ | ✓ | ✗ | ✗ | 2^ℵ₀ |
| **Π** = ∏ᵢ ℤ/2ⁱ | ✗ | ✗ | ✓ | ✗ | ✗ | 2^ℵ₀ |

### Table 2: Homological Properties

| Group | Divisible | Reduced | Cotorsion | Pure-Injective | Injective | Projective |
|-------|-----------|---------|-----------|----------------|-----------|------------|
| **G** | ✗ | ✓ | ✗ | ✗ | ✗ | ✗ |
| **K** | ✗ | ✓ | ✓ | ✗ | ✗ | ✗ |
| **Ḡ** | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ |
| **K+Ḡ** | ✗ | ✓ | ? | ✗ | ✗ | ✗ |
| **Π** | ✗ | ✓ | ✓ | ✓ | ✗ | ✗ |

### Table 3: Completeness Properties

| Group | Z-adically Complete | 2-adically Complete | Torsion-Complete | Algebraically Compact |
|-------|---------------------|---------------------|------------------|----------------------|
| **G** | ✗ | ✗ | ✗ | ✗ |
| **K** | ✗ | ✗ | ✗ | ✗ |
| **Ḡ** | ✓ | ✓ | ✓ | ✓ |
| **K+Ḡ** | ✗ | ✗ | ✗ | ✗ |
| **Π** | ✓ | ✓ | N/A (mixed) | ✓ |

### Table 4: Special Structural Properties

| Group | Direct Sum of Cyclics | Torsion Part | Torsion-Free Rank | Adjusted Cotorsion |
|-------|----------------------|--------------|-------------------|-------------------|
| **G** | ✓ | G | 0 | N/A |
| **K** | ✗ | G | uncountable | ✓ |
| **Ḡ** | ✗ | Ḡ | 0 | N/A (torsion) |
| **K+Ḡ** | ✗ | Ḡ | uncountable | ✗ |
| **Π** | ✗ | Ḡ | uncountable | ✗ |

---

## Part II: Properties of All Quotients

### Table 5: Quotients by G

| Quotient | Torsion | Torsion-Free | Divisible | Reduced | Cotorsion | Pure-Inj | Countable |
|----------|---------|--------------|-----------|---------|-----------|----------|-----------|
| **K/G** | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ | ✗ |
| **Ḡ/G** | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✗ |
| **(K+Ḡ)/G** | ✗ | ✗ | ✗ | ✓ | ? | ✗ | ✗ |
| **Π/G** | ✗ | ✗ | ✗ | ✓ | ? | ✗ | ✗ |

### Additional info for K/G:
- K/G ≅ Ext(ℚ, G) ≅ lim¹ G
- ℚ-vector space of dimension 2^ℵ₀
- Isomorphic to ⊕_{2^ℵ₀} ℚ

### Table 6: Quotients by K

| Quotient | Torsion | Torsion-Free | Divisible | Reduced | Cotorsion | Pure-Inj |
|----------|---------|--------------|-----------|---------|-----------|----------|
| **(K+Ḡ)/K** ≅ Ḡ/G | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ |
| **Π/K** | ✗ | ✗ | ✗ | ✓ | ? | ✗ |

### Table 7: Quotients by Ḡ

| Quotient | Torsion | Torsion-Free | Divisible | Reduced | Cotorsion | Pure-Inj |
|----------|---------|--------------|-----------|---------|-----------|----------|
| **(K+Ḡ)/Ḡ** ≅ K/G | ✗ | ✓ | ✓ | ✗ | ✓ | ✗ |
| **Π/Ḡ** | ✗ | ✓ | ✗ | ✓ | ? | ✗ |

### Table 8: Quotients by K+Ḡ

| Quotient | Torsion | Torsion-Free | Divisible | Reduced | Cotorsion | Pure-Inj |
|----------|---------|--------------|-----------|---------|-----------|----------|
| **Π/(K+Ḡ)** | ✗ | ✓ | ✗ | ✓ | ? | ✗ |

---

## Part III: Complete Quotient Matrix

Every possible A/B where B ⊆ A:

| A \ B | 0 | G | K | Ḡ | K+Ḡ | Π |
|-------|---|---|---|---|------|---|
| **G** | G | 0 | — | — | — | — |
| **K** | K | K/G | 0 | — | — | — |
| **Ḡ** | Ḡ | Ḡ/G | — | 0 | — | — |
| **K+Ḡ** | K+Ḡ | (K+Ḡ)/G | Ḡ/G | K/G | 0 | — |
| **Π** | Π | Π/G | Π/K | Π/Ḡ | Π/(K+Ḡ) | 0 |

(— means not applicable since B ⊄ A)

---

## Part IV: Detailed Property Tables for Each Quotient

### K/G = Ext(ℚ, G)

| Property | Value | Reason |
|----------|-------|--------|
| Torsion | None | torsion(K) = G, so K/G is torsion-free |
| Torsion-free | ✓ | See above |
| Divisible | ✓ | Ext(ℚ, −) is always divisible |
| Reduced | ✗ | Divisible ≠ 0 implies not reduced |
| Cotorsion | ✓ | Divisible groups are cotorsion |
| Pure-injective | ✗ | Not algebraically compact |
| Injective | ✓ | Divisible abelian groups are injective |
| Bounded | ✗ | Infinite |
| Countable | ✗ | Cardinality 2^ℵ₀ |
| ℚ-vector space | ✓ | Torsion-free divisible |
| Dimension | 2^ℵ₀ | Uncountable |

### Ḡ/G

| Property | Value | Reason |
|----------|-------|--------|
| Torsion | ✓ (all) | Ḡ is torsion, G is torsion |
| Torsion-free | ✗ | All torsion |
| Divisible | ✗ | Not every element divisible |
| Reduced | ✓ | No divisible subgroups |
| Cotorsion | ✓ | Quotient of cotorsion is cotorsion |
| Pure-injective | ✓ | Quotient of pure-inj by pure subgroup |
| Injective | ✗ | Not divisible |
| Bounded | ✗ | Unbounded orders |
| Countable | ✗ | Cardinality 2^ℵ₀ |

### Π/Ḡ

| Property | Value | Reason |
|----------|-------|--------|
| Torsion | None | Ḡ = torsion(Π) |
| Torsion-free | ✓ | Quotient by torsion subgroup |
| Divisible | ✗ | (1,1,1,...) not 2-divisible mod Ḡ |
| Reduced | ✓ | No divisible subgroups |
| Cotorsion | ? | Unknown |
| Pure-injective | ✗ | Not algebraically compact |
| Injective | ✗ | Not divisible |
| Countable | ✗ | Cardinality 2^ℵ₀ |

### Π/(K+Ḡ)

| Property | Value | Reason |
|----------|-------|--------|
| Torsion | None | (K+Ḡ) contains all torsion of K+Ḡ |
| Torsion-free | ✓ | Quotient mod Ḡ then mod divisible |
| Divisible | ✗ | K/G was the divisible part |
| Reduced | ✓ | Quotient by maximal divisible subgp |
| Cotorsion | ? | Unknown |
| Pure-injective | ✗ | Not algebraically compact |
| Injective | ✗ | Not divisible |
| Countable | ✗ | Cardinality 2^ℵ₀ |

---

## Part V: Intersection and Join Structure

### Table 9: Intersections (Meets in Lattice)

| A ∩ B | G | K | Ḡ | K+Ḡ | Π |
|-------|---|---|---|------|---|
| **G** | G | G | G | G | G |
| **K** | G | K | G | K | K |
| **Ḡ** | G | G | Ḡ | Ḡ | Ḡ |
| **K+Ḡ** | G | K | Ḡ | K+Ḡ | K+Ḡ |
| **Π** | G | K | Ḡ | K+Ḡ | Π |

### Table 10: Sums/Joins (Joins in Lattice)

| A + B | G | K | Ḡ | K+Ḡ | Π |
|-------|---|---|---|------|---|
| **G** | G | K | Ḡ | K+Ḡ | Π |
| **K** | K | K | K+Ḡ | K+Ḡ | Π |
| **Ḡ** | Ḡ | K+Ḡ | Ḡ | K+Ḡ | Π |
| **K+Ḡ** | K+Ḡ | K+Ḡ | K+Ḡ | K+Ḡ | Π |
| **Π** | Π | Π | Π | Π | Π |

---

## Part VI: Ulm Invariants

| Group | u₀ | u₁ | u₂ | ... | Length |
|-------|----|----|----|----|--------|
| **G** | ℵ₀ | 0 | 0 | 0 | 1 |
| **torsion(K)** = G | ℵ₀ | 0 | 0 | 0 | 1 |
| **Ḡ** | 2^ℵ₀ | 2^ℵ₀ | 2^ℵ₀ | ... | ω |
| **torsion(K+Ḡ)** = Ḡ | 2^ℵ₀ | 2^ℵ₀ | 2^ℵ₀ | ... | ω |
| **torsion(Π)** = Ḡ | 2^ℵ₀ | 2^ℵ₀ | 2^ℵ₀ | ... | ω |

---

## Part VII: Key Relationships Summary

1. **K ∩ Ḡ = G** (cotorsion hull and pure-injective envelope intersect at original group)

2. **K/G ⊕ Ḡ/G ≅ (K+Ḡ)/G** (direct sum since K/G is torsion-free, Ḡ/G is torsion)

3. **K/G ⊆ Π/Ḡ** but K/G ⊊ Π/Ḡ (K/G is the divisible part)

4. **Π/(K+Ḡ) = (Π/Ḡ)/(K/G)** (reduced quotient)
