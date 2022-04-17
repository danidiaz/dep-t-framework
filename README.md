# dep-t-framework

Calling this a "framework" is something of a stretch. 

- **dep-t** The main package. Basic utilities for dependency injection using records-of-functions.
- **dep-t-advice** Arity-generic function decorators, also function invocation helpers.
- **dep-t-dynamic** Dependency injection environments with dynamic fields. 
- **dep-t-value** Helpers for handling resource files.

## Hackage versions

    build-depends:
        dep-t ^>= 0.6.2.0,
        dep-t-advice ^>= 0.6.1.1,
        dep-t-dynamic ^>= 0.1.0.2,
        dep-t-value ^>= 0.1.0.0,

## Modules

Modules you might want to import in your program logic:

- [Control.Monad.Dep.Class](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Control-Monad-Dep-Class.html) [(If you choose to use `DepT`.)](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Env.html#g:9)
- [Dep.Has](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Has.html)
- [Dep.Resource](https://hackage.haskell.org/package/dep-t-value-0.1.0.0/docs/Dep-Resource.html)
- [Dep.Value](https://hackage.haskell.org/package/dep-t-value-0.1.0.0/docs/Dep-Value.html)

Modules you might want to import when building the dependency injection environment:

- [Control.Monad.Dep](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Control-Monad-Dep.html) [(If you choose to use `DepT`.)](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Env.html#g:9)
- [Dep.Env](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Env.html)
- [Dep.Tagged](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Tagged.html)
- [Dep.Advice](https://hackage.haskell.org/package/dep-t-advice-0.6.1.0/docs/Dep-Advice.html) [(If you choose to use `DepT`.)](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Env.html#g:9)
- [Dep.Advice.Basic](https://hackage.haskell.org/package/dep-t-advice-0.6.1.0/docs/Dep-Advice-Basic.html) [(If you choose to use `DepT`.)](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Env.html#g:9)
- [Dep.SimpleAdvice](https://hackage.haskell.org/package/dep-t-advice-0.6.1.0/docs/Dep-SimpleAdvice.html)
- [Dep.SimpleAdvice.Basic](https://hackage.haskell.org/package/dep-t-advice-0.6.1.0/docs/Dep-SimpleAdvice-Basic.html)
- [Dep.Dynamic](https://hackage.haskell.org/package/dep-t-dynamic-0.1.0.2/docs/Dep-Dynamic.html)
- [Dep.Checked](https://hackage.haskell.org/package/dep-t-dynamic-0.1.0.2/docs/Dep-Checked.html) [(If you choose to use `DepT`.)](https://hackage.haskell.org/package/dep-t-0.6.2.0/docs/Dep-Env.html#g:9)
- [Dep.SimpleChecked](https://hackage.haskell.org/package/dep-t-dynamic-0.1.0.2/docs/Dep-SimpleChecked.html)
- [Dep.Loader](https://hackage.haskell.org/package/dep-t-value-0.1.0.0/docs/Dep-Loader.html)
- [Dep.Value.Cached](https://hackage.haskell.org/package/dep-t-value-0.1.0.0/docs/Dep-Value-Cached.html)
- [Dep.Value.JSON](https://hackage.haskell.org/package/dep-t-value-0.1.0.0/docs/Dep-Value-JSON.html)
- [Dep.Value.Text](https://hackage.haskell.org/package/dep-t-value-0.1.0.0/docs/Dep-Value-Text.html)

