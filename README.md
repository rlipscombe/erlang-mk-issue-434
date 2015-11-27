# erlang-mk-issue-434

I've got a multiple application project that uses erlydtl. It fails with:

```
 DTL    index.dtl
{"init terminating in do_boot",{{case_clause,{error,[{"templates/index.dtl",[{none,erlydtl_beam_compiler,{write_file,enoent}}]}],[]}},[{erl_eval,expr,3,[]}]}}
```

This is a minimal, complete and verifiable example. Just run `make`.
