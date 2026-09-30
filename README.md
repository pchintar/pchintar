# Approved Pull Requests

A curated list of my merged contributions across 5 open-source projects.

## Apache Arrow
- [perf(arrow-ord): Avoid full index materialization for small-limit lexsorts](https://github.com/apache/arrow-rs/pull/9991)
- [fix(ipc): handle duplicate projection indices in IPC reader](https://github.com/apache/arrow-rs/pull/9952)
- [fix(parquet): avoid panic on ColumnIndex length mismatch](https://github.com/apache/arrow-rs/pull/9833)
- [fix(ipc): correct skip_field handling for V4 Union](https://github.com/apache/arrow-rs/pull/9829)
- [fix(ipc): replace wildcard in skip_field with explicit DataType handling](https://github.com/apache/arrow-rs/pull/9822)
- [fix(ipc): reader misalignment when skipping ListView / LargeListView columns](https://github.com/apache/arrow-rs/pull/9806)
- [fix(ipc): Avoid panic on malformed compressed buffer prefix](https://github.com/apache/arrow-rs/pull/9802)
- [parquet: fix panic in DeltaByteArrayDecoder on invalid prefix lengths](https://github.com/apache/arrow-rs/pull/9797)
- [feat(ipc): Remove per-message flush in IPC writer hot path](https://github.com/apache/arrow-rs/pull/9763)

## Apache DataFusion
- [fix: Coerce aggregate FILTER predicates to boolean](https://github.com/apache/datafusion/pull/22774)
- [fix: Enable sliding window execution for covar_pop, covar_samp, and corr](https://github.com/apache/datafusion/pull/22764)
- [fix: Preserve integer values in round() for large Int64 and UInt64 inputs](https://github.com/apache/datafusion/pull/22697)

## Apple's FoundationDB
- [Reduce arena allocations when materializing RocksDB range read results](https://github.com/apple/foundationdb/pull/13273)
- [perf(fdbclient): reduce arena allocations in MutationRef deep-copy constructors](https://github.com/apple/foundationdb/pull/13270)

## Apple's MLX
- [Handle invalid dimensions in SinusoidalPositionalEncoding](https://github.com/ml-explore/mlx/pull/3615)
- [Correct p-norm computation in triplet_loss](https://github.com/ml-explore/mlx/pull/3613)

## Apache Spark
- [Fix API inconsistency for 4-argument regexp_replace](https://github.com/apache/spark/commit/463d8043978f39260e2494f3daae56ca4ea6422d)
