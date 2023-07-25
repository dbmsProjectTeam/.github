<h2 align='center'>Composable Database Management based on Velox</h2>
<h4>Contributors: LIU XINYU, LONG QIYU, LU HAOZHENG, YOU CHENGLEI, ZHAO ZEYU</h4>

## Instructions
The project contains 3 parts - Velox, Calcite and Front-End.

#### Velox

For compile and run Velox, please see [velox configuration](https://github.com/dbmsProjectTeam/ComposableDBMS_Velox/tree/dev)

#### Calcite

For compile and run Calcite, please see [Calcite configuration](https://github.com/dbmsProjectTeam/ComposableDBMS_Calcite)

#### Front-End

For run the front-end interface, please see [SqlEditer configuration](https://github.com/dbmsProjectTeam/SqlEditor)


Hand Written Test Sqls are in [TestSqls](./TestSqls/test.sql), just copy and paste into Sql Editor without semicolons.

TPCH Sqls are in [TPCH Sqls](https://github.com/dbmsProjectTeam/ComposableDBMS_Calcite/tree/main/data/queries), they are embedded into Sql Editor already.

Credits Claim:

For Velox, all contents of the file [VeloxIn10MinDemo.cpp](https://github.com/dbmsProjectTeam/ComposableDBMS_Velox/blob/dev/velox/exec/tests/VeloxIn10MinDemo.cpp) is written by ourselves. Parts of the file [PlanBuilder.h](https://github.com/dbmsProjectTeam/ComposableDBMS_Velox/blob/dev/velox/exec/tests/utils/PlanBuilder.h) are modified by ourselves.

For Calcite, all of the codes are written by ourselves.

For SqlEditor, all [componets](https://github.com/dbmsProjectTeam/SqlEditor/tree/main/src/components) are achieved by ourselves.
