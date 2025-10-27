# HR-Consulting-and-Strategy
Professional portfolio for Ayomide Ibitoye, ACIPM, Strategic HR Leader &amp; Operational Consultant. Showcases HR trajectory and pivot to high-value consultancy. Services focus on: Operational Efficiency (change management, streamlining) and High-Performance Frameworks (retention, culture).
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayomide Ibitoye - HR & Operational Consultant</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Custom font and base styles */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f9fb;
        }
        /* Style for the fixed header */
        .header-fixed {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1);
        }
        /* Custom card background for the main content */
        .content-card {
            background-color: #ffffff;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -4px rgba(0, 0, 0, 0.05);
        }
        /* Style for the client logos container */
        .client-logos {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 1.5rem; /* 6 in Tailwind */
        }
        @media (min-width: 768px) {
            .client-logos {
                grid-template-columns: repeat(4, 1fr);
            }
        }
    </style>
</head>
<body>

    <!-- Header & Navigation -->
    <header class="header-fixed bg-white sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <div class="text-xl font-extrabold text-navy-800">
                <span class="text-blue-600">Ayomide Ibitoye</span> | Consultant
            </div>
            <nav class="hidden md:flex space-x-6 text-gray-600 font-medium">
                <a href="#summary" class="hover:text-blue-600 transition duration-150">Summary</a>
                <a href="#consultancy" class="hover:text-blue-600 transition duration-150">Services</a>
                <a href="#clients" class="hover:text-blue-600 transition duration-150">Clients</a>
                <a href="#trajectory" class="hover:text-blue-600 transition duration-150">Trajectory</a>
                <a href="#impact" class="hover:text-blue-600 transition duration-150">Impact</a>
                <a href="#contact" class="px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition duration-150">Contact</a>
            </nav>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 pb-16">

        <!-- 1. Hero Section (Summary) -->
        <section id="summary" class="content-card rounded-xl p-8 md:p-12 mb-12 border-t-4 border-blue-500">
            <div class="md:flex items-center">
                <div class="md:w-3/4">
                    <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-800 mb-4">
                        The People and Performance Architect
                    </h1>
                    <p class="text-lg text-gray-600 leading-relaxed mb-6">
                        I am an innovative and results-driven **Strategic HR Leader and Operational Consultant** with over four years of proven success. I specialize in aligning talent strategy with operational efficiency, helping businesses streamline processes, manage critical change (like ERP adoption), and drive high-impact performance and retention.
                    </p>
                    <a href="#consultancy" class="inline-flex items-center px-6 py-3 bg-blue-600 text-white font-semibold rounded-lg hover:bg-blue-700 transition duration-200">
                        Explore Consulting Services
                        <i data-lucide="arrow-right" class="w-5 h-5 ml-2"></i>
                    </a>
                </div>
                <div class="hidden md:block md:w-1/4 flex justify-center items-center mt-6 md:mt-0">
                     <!-- Placeholder for Professional Headshot or Icon -->
                    <div class="w-32 h-32 bg-blue-100 rounded-full flex items-center justify-center text-blue-600">
                         <i data-lucide="briefcase" class="w-16 h-16"></i>
                    </div>
                </div>
            </div>
        </section>

        <!-- 2. Consultancy Focus (Services) -->
        <section id="consultancy" class="mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-blue-500 pb-2">2. Consultancy Focus: Operational Strategy & Employees</h2>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Pillar 1: Operational Efficiency & Change Management -->
                <div class="content-card rounded-xl p-6">
                    <i data-lucide="zap" class="w-8 h-8 text-blue-600 mb-3"></i>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Pillar 1: Operational Efficiency & Change Management</h3>
                    <p class="text-gray-600 mb-4">I streamline core HR and business processes, ensuring your organization is agile and ready for growth or systemic changes (like ERP adoption).</p>
                    <ul class="space-y-2 text-gray-700">
                        <li class="flex items-start"><i data-lucide="check-circle" class="w-5 h-5 text-green-500 mr-2 mt-1"></i> **Process Streamlining:** Cut friction to reduce request resolution time by 70%.</li>
                        <li class="flex items-start"><i data-lucide="check-circle" class="w-5 h-5 text-green-500 mr-2 mt-1"></i> **Organizational Scaling:** Strategic talent roadmaps for 5x expansion goals.</li>
                        <li class="flex items-start"><i data-lucide="check-circle" class="w-5 h-5 text-green-500 mr-2 mt-1"></i> **Change Readiness:** Talent and protocol planning for successful ERP/system adoption.</li>
                    </ul>
                </div>

                <!-- Pillar 2: High-Performance Frameworks & Culture -->
                <div class="content-card rounded-xl p-6">
                    <i data-lucide="users" class="w-8 h-8 text-blue-600 mb-3"></i>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Pillar 2: High-Performance Frameworks & Culture</h3>
                    <p class="text-gray-600 mb-4">I translate objectives into measurable programs that foster commitment, boost retention, and drive a high-performing culture.</p>
                    <ul class="space-y-2 text-gray-700">
                        <li class="flex items-start"><i data-lucide="check-circle" class="w-5 h-5 text-green-500 mr-2 mt-1"></i> **Performance Design:** Building frameworks that improved employee satisfaction and engagement.</li>
                        <li class="flex items-start"><i data-lucide="check-circle" class="w-5 h-5 text-green-500 mr-2 mt-1"></i> **Engagement Strategy:** Programs resulting in a **30% rise in morale** and **45% jump in satisfaction**.</li>
                        <li class="flex items-start"><i data-lucide="check-circle" class="w-5 h-5 text-green-500 mr-2 mt-1"></i> **Retention Strategy:** Feedback-driven benefits and compensation review for stability.</li>
                    </ul>
                </div>
            </div>
        </section>
        
        <!-- 3. Client Partners -->
        <section id="clients" class="content-card rounded-xl p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-blue-500 pb-2">3. Strategic Client Partners</h2>
            <p class="text-gray-600 mb-8">I partner with organizations across various industries (Tech, Digital Media, Fintech) to drive measurable results. Below are examples of recent collaboration sectors.</p>

            <div class="client-logos">
                <!-- Mock Client 1 -->
                <div class="p-4 bg-gray-50 rounded-lg flex flex-col items-center justify-center h-24 border border-gray-200">
                    <i data-lucide="code" class="w-6 h-6 text-gray-500 mb-1"></i>
                    <span class="text-sm font-semibold text-gray-700">TechCo Solutions</span>
                </div>
                <!-- Mock Client 2 -->
                <div class="p-4 bg-gray-50 rounded-lg flex flex-col items-center justify-center h-24 border border-gray-200">
                    <i data-lucide="trending-up" class="w-6 h-6 text-gray-500 mb-1"></i>
                    <span class="text-sm font-semibold text-gray-700">Growth Financials</span>
                </div>
                <!-- Mock Client 3 -->
                <div class="p-4 bg-gray-50 rounded-lg flex flex-col items-center justify-center h-24 border border-gray-200">
                    <i data-lucide="monitor" class="w-6 h-6 text-gray-500 mb-1"></i>
                    <span class="text-sm font-semibold text-gray-700">Digital Media Hub</span>
                </div>
                <!-- Mock Client 4 -->
                <div class="p-4 bg-gray-50 rounded-lg flex flex-col items-center justify-center h-24 border border-gray-200">
                    <i data-lucide="factory" class="w-6 h-6 text-gray-500 mb-1"></i>
                    <span class="text-sm font-semibold text-gray-700">Global Logistics</span>
                </div>
            </div>
            <div class="mt-8 text-center">
                 <p class="text-base text-gray-600">The full list of engagements, strategic focus, and outcomes is maintained in my detailed client portfolio document.</p>
            </div>
        </section>


        <!-- 4. Professional Trajectory (The HR Foundation) -->
        <section id="trajectory" class="content-card rounded-xl p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-blue-500 pb-2">4. Professional Trajectory: The HR Foundation</h2>
            <p class="text-gray-600 mb-6">A proven history in diverse sectors, focusing on strategic achievements that prepared me for advisory roles.</p>

            <div class="space-y-6">
                <!-- Role 1: Slice Tech Limited -->
                <div class="border-l-4 border-blue-500 pl-4">
                    <p class="text-lg font-semibold text-gray-800">Human Resource Manager | Slice Tech Limited</p>
                    <p class="text-sm text-gray-500 mb-2">February 2025 - Present</p>
                    <ul class="list-disc list-inside text-gray-700 space-y-1">
                        <li>Provided strategic analysis on quarterly turnover rates to inform retention strategies for a planned **5x organizational expansion**.</li>
                        <li>Advised on change management and talent protocols required for potential **ERP system implementation**.</li>
                    </ul>
                </div>

                <!-- Role 2: Beauty and Fragrance International -->
                <div class="border-l-4 border-blue-500 pl-4">
                    <p class="text-lg font-semibold text-gray-800">Human Resource Officer | Beauty and Fragrance International</p>
                    <p class="text-sm text-gray-500 mb-2">June 2023 - Present</p>
                    <ul class="list-disc list-inside text-gray-700 space-y-1">
                        <li>Led an employee engagement program that resulted in a **20% increase in workforce satisfaction and customer service metrics**.</li>
                        <li>Centralized L&D budgets, **reducing costs** while ensuring alignment with strategic business goals.</li>
                    </ul>
                </div>

                <!-- Role 3: Lagos State Signage and Advertisement Agency -->
                <div class="border-l-4 border-blue-500 pl-4">
                    <p class="text-lg font-semibold text-gray-800">Asst. Human Resource Manager | Lagos State Signage and Advertisement Agency</p>
                    <p class="text-sm text-gray-500 mb-2">April 2021 - May 2023</p>
                    <ul class="list-disc list-inside text-gray-700 space-y-1">
                        <li>Designed and rolled out a **revamped performance management framework**, improving employee satisfaction and engagement.</li>
                        <li>Aligned HR policies with labor regulations, ensuring **compliance across all organizational units**.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 5. Measurable Impact (Case Studies) -->
        <section id="impact" class="mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-blue-500 pb-2">5. Measurable Impact: Case Studies</h2>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Case Study A -->
                <div class="content-card rounded-xl p-6 border-t-4 border-yellow-500">
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Case Study A: Streamlining HR Operations</h3>
                    <p class="text-sm font-medium text-gray-500 mb-4">Focus: Operational Efficiency & Employee Support</p>
                    <p class="text-gray-700">
                        **Action:** Audited and restructured the HR support mechanism, implementing clear SLAs and a digital tracking system.
                        <br><br>
                        **Result:** Achieved a **70% reduction in wait time for employee request resolution**, leading to higher productivity and immediate employee trust.
                    </p>
                </div>

                <!-- Case Study B -->
                <div class="content-card rounded-xl p-6 border-t-4 border-yellow-500">
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Case Study B: Culture, Engagement & Retention</h3>
                    <p class="text-sm font-medium text-gray-500 mb-4">Focus: Performance Frameworks & Workforce Stability</p>
                    <p class="text-gray-700">
                        **Action:** Designed comprehensive recognition, continuous feedback, and benefits review programs.
                        <br><br>
                        **Result:** Delivered a **30% increase in employee morale** and a **45% jump in overall satisfaction**, directly boosting retention rates and creating a stable, high-performing culture.
                    </p>
                </div>
            </div>
        </section>

        <!-- 6. Contact Section -->
        <section id="contact" class="content-card rounded-xl p-8 bg-blue-500 text-white text-center">
            <h2 class="text-3xl font-bold mb-4">Ready to Architect Your Performance?</h2>
            <p class="text-lg mb-6">
                Let's discuss how my experience in strategic HR can translate into measurable operational improvements for your business.
            </p>
            <div class="flex flex-col sm:flex-row justify-center space-y-3 sm:space-y-0 sm:space-x-6">
                <a href="mailto:ayomibitoye@gmail.com" class="flex items-center justify-center px-6 py-3 bg-white text-blue-600 font-semibold rounded-lg hover:bg-gray-100 transition duration-200">
                    <i data-lucide="mail" class="w-5 h-5 mr-2"></i> Email Me
                </a>
                <a href="https://www.linkedin.com/in/ayomideibitoyeacipm" target="_blank" class="flex items-center justify-center px-6 py-3 bg-blue-700 text-white font-semibold rounded-lg hover:bg-blue-800 transition duration-200">
                    <i data-lucide="linkedin" class="w-5 h-5 mr-2"></i> Connect on LinkedIn
                </a>
            </div>
        </section>

    </main>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();
    </script>
</body>
</html>

