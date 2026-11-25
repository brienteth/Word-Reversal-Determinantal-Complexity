# Word-Reversal Symmetry, Darboux Block Obstructions, and a General `codim(Sing) + 2` Determinantal Complexity Bound for Degree-`n >= 4` Hypersurfaces

**Author:** BrientH

## Repository Contents

1. **`word_reversal_determinantal_complexity.tex`**: Complete LaTeX manuscript containing:
   - **Theorem 6.1**: Free associative algebra Word-Reversal Identity `$(\Phi(P)K)^T = -\Phi(\rho(P))K$`, necessary and sufficient annihilation conditions (`$\Phi(P^-)K = 0$`), exact dimensions `$\dim \mathcal{A}_k^\pm = (s^k \pm s^{\lceil k/2 \rceil})/2$`, and the Darboux block structure of `$\mathcal{L}_K$`.
   - **Proposition 6.2 & Theorem 6.3**: LTI Control Theory infinite Hankel matrix collapse (`$\operatorname{rank}(H_\infty) = 0$`), palindromic ABP width bound (`$w \ge \operatorname{codim}\operatorname{Sing}(V(F)) + 1$`), and non-homogeneous ABP Darboux-Hessian rank bound (`$\operatorname{rank}\operatorname{Hess}(F)(\xi) \le 2r \le w - d_z$`).
   - **Theorem 6.5**: Unconditional lower bound `$\operatorname{dc}_{\mathbb{C}}(F) \ge \operatorname{codim}_{\mathbb{C}^N}(\operatorname{Sing}(V(F))) + 2$` for all homogeneous polynomials `$F$` of degree `$n \ge 4$` satisfying `$\operatorname{codim}\operatorname{Sing}(V(F)) \ge 5$` and `$\operatorname{codim}\operatorname{Sing}_2(V(F)) > \operatorname{codim}\operatorname{Sing}(V(F))$`.
   - **Theorem 1.2, Proposition 2.3, Theorem 3.1, Proposition 4.1, Lemma 5.1 & Appendix A**: Self-contained application to `$\operatorname{dc}_{\mathbb{C}}(\operatorname{perm}_4) \ge 10$` with the normative `$16 \times 8$` slice matrix `$M_{L_8}$`.
2. **`exact_mod_rref.c`**: Standalone pure-`uint64_t` modular CSR row-echelon rank engine over `$\mathbb{F}_p$` (`$p \le 65535$`) with zero floating-point operations.
3. **`verify_codim_sing_perm4.py`**: Exact verification script certifying `$\operatorname{codim}_{\mathbb{C}^{16}}(\operatorname{Sing}(V(\operatorname{perm}_4))) = 8$` on `$L_8$` modulo `$p_1 = 32749$` and `$p_2 = 65521$`, along with the `$L_9$` negative control.
4. **`.zenodo.json`**: Zenodo automated publication metadata.
