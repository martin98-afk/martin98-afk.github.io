<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>可视化编程流程算法开发工具</title>
    <!-- 引入 Bootstrap CSS (使用 CDN) -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* 自定义 CSS */
        body {
            padding-top: 20px;
            padding-bottom: 40px;
        }
        .main-title {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .section-title {
            border-bottom: 2px solid #dee2e6;
            padding-bottom: 0.5rem;
            margin-top: 2rem;
            margin-bottom: 1rem;
        }
        .feature-icon {
            width: 3rem;
            height: 3rem;
        }
        .img-fluid {
            margin: 10px 0; /* 图片上下留白 */
        }
        .badge {
            margin: 2px; /* 标签间距 */
        }
        .table th, .table td {
            vertical-align: middle; /* 表格内容垂直居中 */
        }
        footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #e5e5e5;
        }
    </style>
</head>
<body>

    <div class="container">
        <header class="d-flex flex-column align-items-center mb-4">
            <!-- Logo -->
            <img src="images/logo2.png" alt="Logo" class="img-fluid mb-3" style="max-width: 50%; height: auto;">
            <!-- Title -->
            <h1 class="main-title text-center">可视化编程流程算法开发工具</h1>
            <!-- Language Links -->
            <div>
                <a href="#zh" class="text-decoration-none me-3">🇨🇳 中文</a>
                <a href="#en" class="text-decoration-none">🇬🇧 English</a>
            </div>
            <!-- Badges -->
            <div class="mt-2">
                <span class="badge bg-primary">Python 3.8+</span>
                <span class="badge bg-warning text-dark">NodeGraphQt v0.3+</span>
                <span class="badge bg-success">qfluentwidgets v1.0+</span>
            </div>
        </header>

        <main>
            <!-- Description -->
            <p class="lead">
                一个基于 <strong>NodeGraphQt</strong> 和 <strong>qfluentwidgets</strong> 的现代化低代码可视化编程平台，支持拖拽式组件编排、异步执行、文件操作、循环控制，并可将工作流一键导出为独立可运行项目，实现从开发到部署的无缝衔接。
            </p>

            <!-- Screenshots Section -->
            <h2 class="section-title">📷 工作流管理界面示意图</h2>
            <img src="images/工作流管理示意图.gif" class="img-fluid" alt="工作流管理示意图">

            <h2 class="section-title">🎉 工作流示意图</h2>
            <img src="images/工作流示意图.gif" class="img-fluid" alt="工作流示意图 1">
            <img src="images/工作流示意图2.gif" class="img-fluid" alt="工作流示意图 2">

            <h2 class="section-title">📦 模型运行效果</h2>
            <img src="images/模型运行效果.gif" class="img-fluid" alt="模型运行效果">

            <h2 class="section-title">节点调试模式效果</h2>
            <img src="images/组件调试模式示意图.gif" class="img-fluid" alt="组件调试模式示意图">

            <h2 class="section-title">复杂组件控件示意图</h2>
            <img src="images/复杂组件控件示意图.png" class="img-fluid" alt="复杂组件控件示意图">

            <h2 class="section-title">循环控制流逻辑示意图</h2>
            <img src="images/循环控制示意图.png" class="img-fluid" alt="循环控制示意图">

            <h2 class="section-title">循环节点运行效果</h2>
            <img src="images/循环节点执行示意图.gif" class="img-fluid" alt="循环节点执行示意图">

            <h2 class="section-title">全局变量使用示意图</h2>
            <img src="images/全局变量使用示意图.gif" class="img-fluid" alt="全局变量使用示意图">

            <h2 class="section-title">分支节点执行效果图</h2>
            <img src="images/分支执行效果示意图.gif" class="img-fluid" alt="分支执行效果示意图">

            <h2 class="section-title">代码编辑运行组件示意图</h2>
            <img src="images/代码编辑执行效果示意图.gif" class="img-fluid" alt="代码编辑执行效果示意图">

            <h2 class="section-title">📦 子图导出示意图</h2>
            <img src="images/项目导出示意图.gif" class="img-fluid" alt="项目导出示意图">

            <h2 class="section-title">📷 组件开发示意图</h2>
            <img src="images/组件开发示意图.gif" class="img-fluid" alt="组件开发示意图">

            <h2 class="section-title">导出项目管理示意图</h2>
            <img src="images/导出项目管理示意图.png" class="img-fluid" alt="导出项目管理示意图">

            <h2 class="section-title">项目服务日志示意图</h2>
            <img src="images/项目服务日志示意图.png" class="img-fluid" alt="项目服务日志示意图">

            <h2 class="section-title">📦 运行环境管理示意图</h2>
            <img src="images/运行环境管理示意图.png" class="img-fluid" alt="运行环境管理示意图">

            <!-- Features Section -->
            <h2 class="section-title">🌟 主要特性</h2>
            <div class="row">
                <div class="col-md-6">
                    <h4>🎨 现代化 UI 界面</h4>
                    <ul>
                        <li><strong>Fluent Design 风格</strong> - 基于 qfluentwidgets 的现代化界面</li>
                        <li><strong>深色主题</strong> - 护眼的深色主题设计</li>
                        <li><strong>响应式布局</strong> - 适配不同屏幕尺寸</li>
                    </ul>

                    <h4>🧩 可视化编程</h4>
                    <ul>
                        <li><strong>拖拽式组件</strong> - 从组件面板拖拽到画布创建节点</li>
                        <li><strong>连线数据流</strong> - 通过连线建立节点间的数据依赖</li>
                        <li><strong>Backdrop 分组</strong> - 使用 Backdrop 节点对相关组件进行视觉分组</li>
                        <li><strong>右键菜单</strong> - 完整的上下文菜单操作</li>
                    </ul>

                    <h4>⚡ 异步执行引擎</h4>
                    <ul>
                        <li><strong>非阻塞执行</strong> - 使用 QThreadPool 实现异步执行，避免界面卡死</li>
                        <li><strong>状态可视化</strong> - 节点状态通过颜色实时显示（运行中/成功/失败/未运行）</li>
                        <li><strong>拓扑排序</strong> - 自动检测依赖关系，按正确顺序执行节点</li>
                    </ul>

                    <h4>✅ 动态代码组件</h4>
                    <ul>
                        <li><strong>自由编程</strong>：在节点内直接编写完整 Python 组件逻辑（含 `run` 方法及辅助函数）</li>
                        <li><strong>动态端口</strong>：通过属性表单自由增删输入/输出端口，支持为输入端口绑定<strong>全局变量默认值</strong></li>
                        <li><strong>无缝集成</strong>：复用全局变量、表达式系统、依赖自动安装、独立日志、状态可视化等全部核心能力</li>
                        <li><strong>安全执行</strong>：代码在独立子进程运行，支持超时控制、错误捕获与重试</li>
                        <li><strong>开发友好</strong>：专业级代码编辑器（深色主题、语法高亮、智能补全、折叠、错误提示）</li>
                    </ul>
                </div>
                <div class="col-md-6">
                    <h4>🔁 高级控制流支持 ✨（新增）</h4>
                    <ul>
                        <li><strong>条件分支（Conditional Branch）</strong> - 根据表达式动态启用/禁用分支，实现 `if/else` 逻辑</li>
                        <li><strong>迭代执行（Iterate）</strong> - 遍历列表/数组，对每个元素执行子流程</li>
                        <li><strong>循环控制（Loop）</strong> - 支持固定次数或条件驱动的迭代循环</li>
                        <li><strong>动态禁用</strong> - 未激活分支及其<strong>整个下游子图自动跳过</strong>，提升执行效率</li>
                        <li><strong>表达式驱动</strong> - 分支条件、循环次数等均支持 `$...$` 动态表达式</li>
                    </ul>

                    <h4>🌐 全局变量与表达式系统 ✨</h4>
                    <ul>
                        <li><strong>结构化全局变量</strong> - 支持环境变量（env）、自定义变量（custom）、节点输出（node_vars）三类作用域，环境变量在组件执行时实时注入</li>
                        <li><strong>动态表达式引擎</strong> - 使用 `$表达式$` 语法在参数中引用和组合变量（如 `$env_user_id$`、`$custom_threshold * 2$`）</li>
                        <li><strong>实时求值</strong> - 执行前自动解析表达式，支持嵌套结构（列表/字典）中的动态值</li>
                        <li><strong>安全沙箱</strong> - 基于 `asteval` 的安全执行环境，禁止危险操作，使用 `contextmanager` 实现组件间环境变量隔离</li>
                        <li><strong>属性面板集成</strong> - 在组件属性中可直接选择全局变量或输入表达式</li>
                    </ul>

                    <h4>📦 模型导出与独立部署 ✨</h4>
                    <ul>
                        <li><strong>子图导出</strong> - 选中任意节点组合，一键导出为独立项目</li>
                        <li><strong>训练/推理分离</strong> - 仅导出推理流程，自动打包训练好的模型文件</li>
                        <li><strong>自包含运行</strong> - 生成完整可执行项目，无需主程序即可运行</li>
                        <li><strong>跨环境部署</strong> - 自动生成工具包要求，支持服务器、Docker、命令行等无 GUI 环境</li>
                    </ul>
                </div>
            </div>

            <!-- Quick Start Section -->
            <h2 class="section-title">🚀 快速开始</h2>
            <h4>环境要求</h4>
            <ul>
                <li>Python 3.8+</li>
                <li>PyQt5 或 PySide2</li>
            </ul>

            <h4>安装依赖</h4>
            <pre class="bg-light p-2 border"><code>pip install -r requirements.txt</code></pre>

            <h4>运行应用</h4>
            <pre class="bg-light p-2 border"><code>python main.py</code></pre>

            <h4>pyinstaller打包应用</h4>
            <pre class="bg-light p-2 border"><code>pyinstaller --onedir --windowed --add-data "app;app" --add-data "icons;icons" -i icons/logo3.png main.py</code></pre>

            <!-- Component Development Section -->
            <h2 class="section-title">🧪 组件开发</h2>
            <h3>创建新组件</h3>
            <ol>
                <li><strong>在 <code>components/</code> 目录下创建组件文件</strong></li>
                <pre class="bg-light p-2 border"><code># components/data/my_component.py
class Component(BaseComponent):
    name = ""
    category = ""
    description = ""
    requirements = ""
    inputs = [
    ]
    outputs = [
    ]
    properties = {
    }

    def run(self, params, inputs=None):
        """
        params: 节点属性（来自UI）
        inputs: 上游输入（key=输入端口名）
        return: 输出数据（key=输出端口名）
        """
        # 在这里编写你的组件逻辑
        input_data = inputs.get("input_data") if inputs else None
        param1 = params.get("param1", "default_value")
        # 处理逻辑
        result = f"处理结果: {input_data} + {param1}"
        return {
            "output_data": result
        }
</code></pre>
                <li><strong>自动加载</strong> - 组件会自动被扫描并添加到组件面板</li>
                <li><strong>自动依赖安装</strong> - 当运行工作流时，如果该组件因缺少依赖包而执行失败，系统会根据 <code>requirements</code> 字段自动安装所需包，然后重试执行。</li>
            </ol>

            <h3>组件端口参数支持</h3>
            <div class="table-responsive">
                <table class="table table-striped">
                    <thead>
                        <tr>
                            <th>类型</th>
                            <th>说明</th>
                            <th>示例</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>TEXT</td><td>文本输入</td><td>字符串参数</td></tr>
                        <tr><td>LONGTEXT</td><td>长文本输入</td><td>字符串参数</td></tr>
                        <tr><td>INT</td><td>整数输入</td><td>数值参数</td></tr>
                        <tr><td>FLOAT</td><td>浮点数输入</td><td>小数参数</td></tr>
                        <tr><td>BOOL</td><td>布尔输入</td><td>开关选项</td></tr>
                        <tr><td>CSV</td><td>csv列表数据</td><td>预定义选项</td></tr>
                        <tr><td>JSON</td><td>json结构数据</td><td>不定长度数据列表信息</td></tr>
                        <tr><td>EXCEL</td><td>excel列表数据</td><td>指定范围的数值</td></tr>
                        <tr><td>FILE</td><td>文本数据</td><td>指定范围的数值</td></tr>
                        <tr><td>UPLOAD</td><td>上传文档</td><td>指定范围的数值</td></tr>
                        <tr><td>SKLEARNMODEL</td><td>sklearn模型</td><td>指定范围的数值</td></tr>
                        <tr><td>TORCHMODEL</td><td>torch模型</td><td>指定范围的数值</td></tr>
                        <tr><td>IMAGE</td><td>图片数据</td><td>指定范围的数值</td></tr>
                    </tbody>
                </table>
            </div>

            <h3>组件属性参数支持</h3>
            <div class="table-responsive">
                <table class="table table-striped">
                    <thead>
                        <tr>
                            <th>类型</th>
                            <th>说明</th>
                            <th>示例</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>TEXT</td><td>文本输入</td><td>字符串参数</td></tr>
                        <tr><td>LONGTEXT</td><td>长文本输入</td><td>字符串参数</td></tr>
                        <tr><td>INT</td><td>整数输入</td><td>数值参数</td></tr>
                        <tr><td>FLOAT</td><td>浮点数输入</td><td>小数参数</td></tr>
                        <tr><td>BOOL</td><td>布尔输入</td><td>开关选项</td></tr>
                        <tr><td>CHOICE</td><td>下拉选择</td><td>预定义选项</td></tr>
                        <tr><td>DYNAMICFORM</td><td>动态表单</td><td>不定长度数据列表信息</td></tr>
                        <tr><td>RANGE</td><td>数值范围</td><td>指定范围的数值</td></tr>
                    </tbody>
                </table>
            </div>

            <!-- Canvas Usage Guide Section -->
            <h2 class="section-title">🎮 画布使用指南</h2>
            <h3>基本操作</h3>
            <ol>
                <li><strong>创建节点</strong> - 从左侧组件面板拖拽组件到画布</li>
                <li><strong>连接节点</strong> - 从输出端口拖拽到输入端口</li>
                <li><strong>运行节点</strong> - 右键点击节点选择"运行此节点"</li>
                <li><strong>查看日志</strong> - 右键点击节点选择"查看节点日志"</li>
            </ol>

            <h3>高级功能</h3>
            <ol>
                <li><strong>循环执行</strong> - 使用循环控制器节点配合 Backdrop 实现循环</li>
                <li><strong>文件操作</strong> - 在属性面板中点击文件选择按钮</li>
                <li><strong>工作流管理</strong> - 使用左上角按钮保存/加载工作流</li>
                <li><strong>节点分组</strong> - 选中多个节点右键创建 Backdrop</li>
                <li><strong>依赖管理</strong> - 组件运行失败时，系统会根据其 <code>requirements</code> 尝试自动安装。</li>
            </ol>

            <h3>快捷键</h3>
            <ul>
                <li><code>Ctrl+R</code> - 运行工作流</li>
                <li><code>Ctrl+S</code> - 保存工作流</li>
                <li><code>Ctrl+O</code> - 加载工作流</li>
                <li><code>Ctrl+A</code> - 全选节点</li>
                <li><code>Del</code> - 删除选中节点</li>
            </ul>

            <!-- Canvas Development Notes Section -->
            <h2 class="section-title">🛠️ 画布开发说明</h2>
            <h3>节点状态管理</h3>
            <ul>
                <li><strong>未运行</strong> - 灰色框</li>
                <li><strong>运行中</strong> - 蓝色框</li>
                <li><strong>执行成功</strong> - 绿色框</li>
                <li><strong>执行失败</strong> - 红色框</li>
            </ul>

            <h3>连接线状态管理</h3>
            <ul>
                <li><strong>未运行</strong> - 黄色线</li>
                <li><strong>运行中输入连接</strong> - 蓝色线</li>
                <li><strong>运行中输出连接</strong> - 绿色线</li>
            </ul>

            <h3>日志系统</h3>
            <ul>
                <li>每个节点独立存储日志</li>
                <li>自动添加时间戳</li>
                <li>支持 Loguru 日志库，组件内部使用 <code>self.logger</code> 记录日志</li>
                <li>组件内部 <code>print()</code> 输出自动捕获</li>
            </ul>

            <h3>数据流</h3>
            <ul>
                <li>输入端口自动获取上游节点输出</li>
                <li>输出端口数据按端口名称存储</li>
                <li>支持多输入多输出</li>
            </ul>

            <!-- Model Export Section -->
            <h2 class="section-title">📥 模型导出（独立部署）</h2>
            <h3>核心价值</h3>
            <p><strong>将画布上的任意子图导出为可独立运行的项目</strong>，无需依赖主程序即可部署到任何 Python 环境！</p>

            <h3>使用场景</h3>
            <ul>
                <li><strong>训练/推理分离</strong>：只导出推理部分，打包训练好的模型文件</li>
                <li><strong>模型分享</strong>：将完整工作流打包分享给同事</li>
                <li><strong>生产部署</strong>：直接部署到服务器或 Docker 容器</li>
                <li><strong>离线运行</strong>：在无 GUI 环境中执行工作流</li>
            </ul>

            <h3>导出功能特点</h3>
            <ul>
                <li>✅ <strong>智能依赖分析</strong> - 自动识别并复制所需组件代码</li>
                <li>✅ <strong>文件路径重写</strong> - 模型文件、数据文件自动复制到项目目录并重写为相对路径</li>
                <li>✅ <strong>列选择支持</strong> - CSV 列选择配置完整保留</li>
                <li>✅ <strong>环境隔离</strong> - 自动生成 <code>requirements.txt</code>，确保依赖一致性</li>
                <li>✅ <strong>即开即用</strong> - 包含完整运行脚本，无需额外配置</li>
            </ul>

            <h3>导出步骤</h3>
            <ol>
                <li><strong>选择节点</strong> - 在画布上选中要导出的节点（可多选）</li>
                <li><strong>点击导出</strong> - 点击左上角 <strong>"导出模型"</strong> 按钮（📤 图标）</li>
                <li><strong>选择目录</strong> - 选择导出目录，系统自动生成项目文件夹</li>
                <li><strong>运行项目</strong> - 进入导出目录，执行以下命令：</li>
            </ol>
            <pre class="bg-light p-2 border"><code># 安装依赖
pip install -r requirements.txt

# 运行模型
python run.py
</code></pre>

            <h3>导出项目结构</h3>
            <pre class="bg-light p-2 border"><code>model_xxxxxxxx/
├── model.workflow.json    # 工作流定义（包含节点配置、连接关系、列选择等）
├── preject_spec.json      # 项目输入输出定义信息
├── preview.png            # 项目导出时画布节点预览图
├── REAMDME.md             # 项目信息展示
├── requirements.txt       # 自动分析的依赖包列表
├── run.py                 # 一键运行脚本
├── api_server.py          # 一键微服务脚本
├── scan_components.py     # 组件扫描器
├── runner/                # 执行器模块
│   ├── component_executor.py
│   └── workflow_runner.py # 工作流执行引擎
├── components/            # 组件代码（保持原始目录结构）
│   ├── base.py           # 组件基类
│   └── your_components/  # 你的组件文件
└── inputs/                # 输入文件（模型文件、数据文件等）
</code></pre>

            <!-- Future Plans Section -->
            <h2 class="section-title">下一步计划</h2>
            <ul>
                <li>~~1. <strong>增加“调试模式”</strong>~~</li>
                <li>~~2. <strong>变量系统 & 表达式引擎</strong>~~</li>
                <li>3. <strong>支持远程执行</strong>
                    <ul>
                        <li>将工作流提交到 <strong>远程服务器 / Kubernetes / Ray</strong></li>
                        <li>本地只做编排，执行在集群</li>
                        <li>适合大模型、大数据场景</li>
                    </ul>
                </li>
                <li>4. <strong>并行执行</strong>
                    <ul>
                        <li>问题：串行执行，无法利用多核</li>
                        <li>优化：
                            <ul>
                                <li>无依赖的节点 并行执行</li>
                                <li>支持 GPU 资源调度（如 PyTorch 模型分配到不同 GPU）</li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>

            <!-- Feature Implementation Status Section -->
            <h2 class="section-title">功能实现情况</h2>
            <ul>
                <li>[x] 组件管理</li>
                <li>[x] 组件开发</li>
                <li>[ ] 支持组件类型
                    <ul>
                        <li>[x] 基本组件</li>
                        <li>[x] 多输入组件</li>
                        <li>[x] backdrop节点集成</li>
                        <li>[x] 输入输出节点集成</li>
                        <li>[ ] circle节点集成</li>
                    </ul>
                </li>
                <li>[x] 组件依赖自动管理 (requirements)</li>
                <li>[x] 逻辑控制预制组件
                    <ul>
                        <li>[x] 逻辑判断</li>
                        <li>[x] 条件分支</li>
                        <li>[x] 循环</li>
                        <li>[x] 迭代</li>
                    </ul>
                </li>
                <li>[x] 组件调试</li>
                <li>[x] 组件参数
                    <ul>
                        <li>[x] CSV 参数
                            <ul>
                                <li>[x] CSV 参数信息预览</li>
                                <li>[x] CSV 参数列选择</li>
                                <li>[x] CSV 数据预览</li>
                                <li>[ ] CSV 数据分析</li>
                            </ul>
                        </li>
                        <li>[x] EXCEL 参数</li>
                        <li>[x] SKLEARN 参数</li>
                        <li>[x] Torch 参数</li>
                        <li>[x] NUMPY 参数</li>
                        <li>[x] IMAGE 参数</li>
                        <li>[x] JSON 参数</li>
                        <li>[x] TEXT 参数
                            <ul>
                                <li>[x] 文本数据预览</li>
                            </ul>
                        </li>
                        <li>[x] FILE 参数</li>
                    </ul>
                </li>
                <li>[x] 组件输入端口校验</li>
                <li>[x] 组件运行
                    <ul>
                        <li>[x] 组件运行颜色状态更新</li>
                        <li>[x] 组件运行连线状态更新</li>
                    </ul>
                </li>
                <li>[x] 组件日志
                    <ul>
                        <li>[x] 实时日志读取保存</li>
                        <li>[ ] 组件日志持久化存储</li>
                    </ul>
                </li>
                <li>[x] 输出节点预览</li>
                <li>[x] 输出节点变量下载</li>
                <li>[x] 组件分组</li>
                <li>[x] 组件预览
                    <ul>
                        <li>[x] 节点拖拽预览</li>
                    </ul>
                </li>
                <li>[x] 模型管理
                    <ul>
                        <li>[x] 模型画布预览图</li>
                    </ul>
                </li>
                <li>[x] 模型运行
                    <ul>
                        <li>[x] 运行环境切换</li>
                        <li>[x] 三种运行模式</li>
                        <li>[x] 全局变量系统</li>
                    </ul>
                </li>
                <li>[x] 画布导出
                    <ul>
                        <li>[x] 模型画布保存</li>
                        <li>[x] 模型输出结果保存</li>
                        <li>[x] 画布预览图保存</li>
                    </ul>
                </li>
                <li>[x] 画布导入
                    <ul>
                        <li>[x] 模型画布导入</li>
                        <li>[x] 模型输出结果导入</li>
                    </ul>
                </li>
                <li>[x] 模型导出
                    <ul>
                        <li>[x] 导出独立模型项目</li>
                        <li>[x] 项目预览图保存</li>
                        <li>[x] 自动检测依赖包</li>
                        <li>[x] 导出项目可运行性检测</li>
                        <li>[x] 自动包装API接口</li>
                        <li>[ ] 自动生成API文档</li>
                        <li>[x] API 输入输出节点定义</li>
                    </ul>
                </li>
                <li>[ ] 导出项目编辑</li>
                <li>[x] 模型运行环境控制
                    <ul>
                        <li>[x] 安装包安装、强制重装、更新、卸载</li>
                        <li>[x] 组件安装包同步</li>
                        <li>[x] 多运行环境管理</li>
                        <li>[x] 运行环境切换</li>
                        <li>[x] 工具包列表信息</li>
                        <li>[x] 安装实时日志</li>
                    </ul>
                </li>
                <li>[x] 工具配置</li>
            </ul>

        </main>

        <footer class="text-center text-muted">
            <p>&copy; 2025 你的名字. Licensed under <a href="LICENSE" target="_blank">GPLv3</a>.</p>
            <p>Powered by <a href="https://github.com/jchanvfx/NodeGraphQt" target="_blank">NodeGraphQt</a>, <a href="https://github.com/zhiyiYo/PyQt-Fluent-Widgets" target="_blank">qfluentwidgets</a>, and <a href="https://github.com/Delgan/loguru" target="_blank">Loguru</a>.</p>
        </footer>
    </div>

    <!-- 引入 Bootstrap JS (使用 CDN) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
