# Ivan Mykhavko

PHP/Laravel backend engineer. Into perf tuning, clean architecture, and the dusty corners of PHP internals.

Senior Backend Engineer, Lviv, Ukraine. Four and a half years on the backend of a B2B auto-parts marketplace: a 257k-SKU catalog at 750+ orders on a weekday.

**LLM output, measured** - my AI filter-translation pipeline returned 9.5% of rows in the wrong language on its first pass; validating structured output in code rather than in the prompt brought all 1,067 active values to zero wrong-language rows. A three-round review of a colleague's separate product-translation pipeline found an unbounded response schema dropping 22 of every 2,000 translations.

**Laravel core** - one fix merged into 13.x, [#57196](https://github.com/laravel/framework/pull/57196): MySQL grammar was dropping `ORDER BY` and `LIMIT` from a `DELETE` with a join.

**Packages**
- [`tegos/laravel-telescope-flusher`](https://packagist.org/packages/tegos/laravel-telescope-flusher) - `telescope:flush`, because `telescope:clear` takes 9,025 s where this takes 1.21 s.
- [`@tegos/spindle`](https://www.npmjs.com/package/@tegos/spindle) - zero-dependency TypeScript 360 viewer.

**Writing** - [dev.to/@tegos](https://dev.to/tegos), 37 articles, mostly about whatever broke that month.

[![Why PHP](https://img.shields.io/badge/Why_PHP-in_2026-7A86E8?style=flat-square&labelColor=18181b)](https://whyphp.dev)
[![Dev.to](https://img.shields.io/badge/dev.to-%40tegos-0A0A0A?style=flat-square&logo=dev.to&logoColor=white)](https://dev.to/tegos)
[![Codeboards](https://img.shields.io/badge/codeboards-tegos-6366f1?style=flat-square&labelColor=18181b)](https://codeboards.io/tegos)

---

[![Stack](https://skillicons.dev/icons?i=php,laravel,mysql,redis,docker,git&theme=dark)](https://skillicons.dev)

## Projects

<a href="https://github.com/tegos/laravel-telescope-flusher"><img src="https://tegos-github-readme-stats.vercel.app/api/pin/?username=tegos&repo=laravel-telescope-flusher&hide_border=true&theme=github_dark" /></a>
<a href="https://github.com/tegos/laravel-hierarchical-data"><img src="https://tegos-github-readme-stats.vercel.app/api/pin/?username=tegos&repo=laravel-hierarchical-data&hide_border=true&theme=github_dark" /></a>
<a href="https://github.com/tegos/laravel-action-and-service-guideline"><img src="https://tegos-github-readme-stats.vercel.app/api/pin/?username=tegos&repo=laravel-action-and-service-guideline&hide_border=true&theme=github_dark" /></a>
<a href="https://github.com/tegos/cad-3d-viewer"><img src="https://tegos-github-readme-stats.vercel.app/api/pin/?username=tegos&repo=cad-3d-viewer&hide_border=true&theme=github_dark" /></a>

## Writing

<!-- BLOG-POST-LIST:START -->
- [Why I Avoid PHP Traits (And What I Use Instead)](https://dev.to/tegos/why-i-avoid-php-traits-and-what-i-use-instead-1288)
- [Laravel Actions and Services](https://dev.to/tegos/laravel-actions-and-services-360d)
- [PHP 8.5 Pipe Operator (|>) – Is It Worth Using?](https://dev.to/tegos/php-85-pipe-operator-is-it-worth-using-4gig)
- [Pessimistic & Optimistic Locking in Laravel](https://dev.to/tegos/pessimistic-optimistic-locking-in-laravel-23dk)
- [Composer Update Is Not Safe Anymore](https://dev.to/tegos/composer-update-is-not-safe-anymore-2bcf)
<!-- BLOG-POST-LIST:END -->

## Stats

<p align="left">
  <img height="170" src="https://tegos-github-readme-stats.vercel.app/api?username=tegos&show_icons=true&hide_border=true&theme=github_dark&count_private=true&include_all_commits=true" />&nbsp;&nbsp;
  <img height="170" src="https://tegos-github-readme-stats.vercel.app/api/top-langs/?username=tegos&layout=compact&hide_border=true&theme=github_dark&hide=html,css,blade,C%23,Jupyter%20Notebook&langs_count=6&exclude_repo=burger-reborn" />
</p>
