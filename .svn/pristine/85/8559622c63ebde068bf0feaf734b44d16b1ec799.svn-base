<template>
    <div class="dashboard-container web-font">
        <div class="dashboard-header">
            <el-select
                v-model="value"
                placeholder="请选择"
            >
                <el-option
                    v-for="item in options"
                    :key="item.value"
                    :label="item.label"
                    :value="item.value"
                >
                </el-option>
            </el-select>
            <span>| 山东省更高水平现代化指标评估体系（非真实数据）</span>
            <div class="buttonBox">
                <el-button
                    type="primary"
                    icon="el-icon-plus"
                    style="font-size:16px;height:40px;margin-right:20px;"
                >新增指标</el-button>
                <el-button
                    type="primary"
                    icon="el-icon-download"
                    style="font-size:16px;height:40px;background:#FF933A;border-color:#FF933A"
                >下载</el-button>
            </div>

        </div>
        <div class="dashboard-footer">
            <el-table
                :data="tableData"
                style="width: 100%"
                height="100%"
                :header-cell-style="{background: '#E4E8F3',color: '#021938'}"
                :row-class-name="tableRowClassName"
            >
                <el-table-column
                    prop="number"
                    label="序号"
                    width="120"
                    align="center"
                >
                </el-table-column>
                <el-table-column
                    prop="Level1"
                    label="一级指标"
                    width="120"
                    align="center"
                >
                </el-table-column>
                <el-table-column
                    prop="number1"
                    label="序号"
                    align="center"
                >
                </el-table-column>
                <el-table-column
                    prop="Level2"
                    label="二级指标"
                    align="center"
                >
                </el-table-column>
                <el-table-column
                    prop="number2"
                    label="序号"
                    align="center"
                >
                </el-table-column>
                <el-table-column
                    prop="Level3"
                    label="三级指标"
                    align="center"
                >
                </el-table-column>
                <el-table-column
                    prop="state"
                    label="状态"
                    align="center"
                >
                </el-table-column>
            </el-table>
        </div>
    </div>
</template>

<script>
import { mapGetters } from "vuex";

export default {
    name: "Dashboard",
    computed: {
        ...mapGetters(["name"]),
    },
    data() {
        return {
            options: [
                /*  {
                    value: "选项1",
                    label: "全省指标",
                }, */
            ],
            value: "全省指标",
            tableData: [
                {
                    number: "A",
                    Level1: "智能观测",
                    number1: "A1",
                    Level2: "综合气象观测能力",
                    number2: "A11",
                    Level3: "气象观测自动化率",
                    state: "停用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "A12",
                    Level3: "观测装备业务可用性",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "A13",
                    Level3: "实时气象数据传输能力",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "A14",
                    Level3: "气象数据质控能力",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "A2",
                    Level2: "综合气象观测稳定运行能力",
                    number2: "A21",
                    Level3: "综合气象装备运行监控率",
                    state: "待审核",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "A22",
                    Level3: "自动气象站计量检定（核查）率",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "A23",
                    Level3: "故障维修时限",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "A24",
                    Level3: "装备供应完成率",
                    state: "停用",
                },
                {
                    number: "B",
                    Level1: "智能预报",
                    number1: "B1",
                    Level2: "气象预报准确率",
                    number2: "B11",
                    Level3: "24小时晴雨预报准确率",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "B12",
                    Level3: "24小时暴雨预报准确率",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "B13",
                    Level3: "24小时气温预报准确率",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "B14",
                    Level3: "24小时台风路径预报误差",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "B15",
                    Level3: "10天晴雨预报准确率",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "B16",
                    Level3: "月降水预测准确率",
                    state: "在用",
                },
                {
                    number: "",
                    Level1: "",
                    number1: "",
                    Level2: "",
                    number2: "B17",
                    Level3: "月气温预测准确率",
                    state: "在用",
                },
            ],
        };
    },
    methods: {
        tableRowClassName({ row, rowIndex }) {
            if (rowIndex % 2 == 1) {
                return "warning-row";
            }
        },
    },
};
</script>

<style lang="scss" scoped>
.dashboard {
    &-container {
        margin: 15px;
        height: calc(100% - 30px);
    }
    &-header {
        width: 100%;
        height: 64px;
        line-height: 64px;
        background: #ffffff;
        display: flex;
        justify-content: space-between;
        border: 1px solid rgba(210, 216, 234, 1);
        border-radius: 8px;
        ::v-deep.el-input__inner {
            margin: 12px;
            width: 128px;
            font-size: 16px;
        }
        ::v-deep.el-input__suffix {
            right: 16px;
            top: -2px;
        }
        span {
            flex: 1;
            padding-left: 50px;
        }
        .buttonBox {
            margin-right: 20px;
        }
    }
    &-footer {
        margin: 20px 10px;
        height: calc(100% - 84px);
        overflow: auto;
        ::v-deep.el-table {
            border: 1px solid #ccc;
            
        }
        ::v-deep.el-table .warning-row {
            background: rgba(245, 246, 250, 0.5);
        }
    }
}
</style>
