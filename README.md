# FastExpressionCompiler

## Summary

Fast ExpressionTree compiler to delegate

More than 10 times faster than `Expression.Compiler`.

Intially developed and used in DryIoc v2 (no closure support). 
Then closure support is added into upcoming DryIoc v3 branch. 

Additionally the version with hoisted closure support was contributed by me to ExpressionToCodeLib project. 

__Main idea is to evolve and test the compiler separately targeting more projects.__

## Current state / to-do

- no projects,  just sources from [DryIoc] and [ExpressionToCodeLib]
- not tests except some integrated in above projects
- FastExpressionCompiler is a newer version, __but__ without support
for hoisted expression with closure `Expression<Func<T>> e = () => blah`. Only hand composed expressions are supported. 
- Benchmark for perf comparison vs `Expression.Compile`

__Everything is up-for-grabs__
