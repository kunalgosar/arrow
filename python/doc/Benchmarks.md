<!---
  Licensed to the Apache Software Foundation (ASF) under one
  or more contributor license agreements.  See the NOTICE file
  distributed with this work for additional information
  regarding copyright ownership.  The ASF licenses this file
  to you under the Apache License, Version 2.0 (the
  "License"); you may not use this file except in compliance
  with the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing,
  software distributed under the License is distributed on an
  "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
  KIND, either express or implied.  See the License for the
  specific language governing permissions and limitations
  under the License.
-->
## Benchmark Requirements

The benchmarks are run using [asv][1] which is also their only requirement.

## Running the benchmarks

To run the benchmarks, call `asv run --python=same`. You cannot use the
plain `asv run` command at the moment as asv cannot handle python packages
in subdirectories of a repository.

[1]: https://asv.readthedocs.org/
