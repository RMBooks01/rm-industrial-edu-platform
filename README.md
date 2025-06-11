
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { CalendarDays, Wrench, Building2, Rocket, Users, Factory } from "lucide-react";

export default function IndustrialLiteracyWebsite() {
  return (
    <div className="p-6 space-y-12 max-w-5xl mx-auto">
      <header className="text-center space-y-2">
        <h1 className="text-4xl font-bold text-blue-700">RM Books and Beyond</h1>
        <p className="text-xl text-gray-700">
          Industrial Literacy Programme for Grade 8–11 Female Learners
        </p>
      </header>

      <section className="space-y-4">
        <h2 className="text-2xl font-semibold text-gray-800">About the Programme</h2>
        <p>
          Our Industrial Literacy Programme bridges the gender gap in Manufacturing and Infrastructure Development. Through mentorship, hands-on projects, and 4IR exposure, female learners will gain the skills to lead in industries traditionally dominated by men.
        </p>
      </section>

      <section className="grid grid-cols-1 md:grid-cols-2 gap-6">
        <Card>
          <CardContent className="p-4">
            <h3 className="text-xl font-bold mb-2">Objectives</h3>
            <ul className="list-disc list-inside space-y-1">
              <li>Introduce girls to technical aspects of Manufacturing & Infrastructure.</li>
              <li>Teach foundational 4IR tools (e.g., automation, digital design).</li>
              <li>Provide entrepreneurial & small business training.</li>
              <li>Offer career mentorship & industrial exposure.</li>
              <li>Develop a self-sustaining model through partnerships.</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <h3 className="text-xl font-bold mb-2">Target Audience</h3>
            <p>Grade 8–11 female learners from urban & peri-urban schools in the Free State.</p>
            <p className="mt-2">Focus on schools with existing interest in technical literacy but limited access to industrial pathways.</p>
          </CardContent>
        </Card>
      </section>

      <section className="grid grid-cols-1 md:grid-cols-2 gap-6">
        <Card>
          <CardContent className="p-4">
            <div className="flex items-center space-x-2 mb-2">
              <Factory className="text-blue-600" />
              <h3 className="text-xl font-bold">Focus: Manufacturing</h3>
            </div>
            <ul className="list-disc list-inside space-y-1">
              <li>Production processes, raw materials, and safety</li>
              <li>3D printing, digital design software</li>
              <li>Assembly line simulations & cost estimation</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <div className="flex items-center space-x-2 mb-2">
              <Building2 className="text-green-600" />
              <h3 className="text-xl font-bold">Focus: Infrastructure Development</h3>
            </div>
            <ul className="list-disc list-inside space-y-1">
              <li>Basics of construction & civil engineering</li>
              <li>Blueprints, planning, budgeting</li>
              <li>Sustainability & smart infrastructure</li>
            </ul>
          </CardContent>
        </Card>
      </section>

      <section className="space-y-4">
        <div className="flex items-center space-x-2">
          <CalendarDays className="text-purple-600" />
          <h2 className="text-2xl font-semibold">Programme Structure</h2>
        </div>
        <p><strong>Duration:</strong> 12 months</p>
        <p><strong>Sessions:</strong> Twice weekly (Tuesdays & Thursdays), plus one exposure Saturday per month</p>
        <div>
          <h3 className="font-bold">Modules</h3>
          <ul className="list-disc list-inside space-y-1">
            <li>Intro to Manufacturing & Infrastructure Development</li>
            <li>Women in Industry: Career Exploration & Guest Talks</li>
            <li>4IR Tools in Manufacturing & Infrastructure</li>
            <li>Financial Literacy & Small Business Development</li>
            <li>Business Ideation & Prototyping</li>
            <li>Capstone: Industrial Project & Business Pitch</li>
          </ul>
        </div>
      </section>

      <footer className="text-center text-sm text-gray-500 mt-10">
        © 2025 RM Books and Beyond. Empowering future industry leaders.
      </footer>
    </div>
  );
}
