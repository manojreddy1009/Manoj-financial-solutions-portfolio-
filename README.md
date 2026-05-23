# Manoj-financial-solutions-portfolio-
export default function ManojFinancialSolutionsPortfolio() { return ( <div className="min-h-screen bg-white text-gray-800 font-sans"> {/* Navbar */} <nav className="fixed top-0 left-0 w-full bg-white/90 backdrop-blur-md shadow-sm z-50"> <div className="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center"> <h1 className="text-2xl font-bold tracking-wide text-gray-800"> Manoj Financial Solutions </h1> <div className="hidden md:flex gap-8 text-sm font-medium"> <a href="#home" className="hover:text-blue-500">Home</a> <a href="#about" className="hover:text-blue-500">About</a> <a href="#services" className="hover:text-blue-500">Services</a> <a href="#partners" className="hover:text-blue-500">Partners</a> <a href="#contact" className="hover:text-blue-500">Contact</a> </div> </div> </nav>

{/* Hero Section */}
  <section
    id="home"
    className="pt-32 pb-20 bg-gradient-to-br from-gray-100 to-blue-50"
  >
    <div className="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h2 className="text-5xl md:text-6xl font-bold leading-tight mb-6">
          Protecting Families.
          <span className="text-blue-500"> Securing Futures.</span>
        </h2>
        <p className="text-lg text-gray-600 mb-8 leading-relaxed">
          Professional Insurance & Financial Advisor helping families with
          trusted insurance solutions, financial planning, and future
          protection.
        </p>

        <div className="flex flex-wrap gap-4">
          <a
            href="tel:8186081009"
            className="px-6 py-3 bg-blue-500 text-white rounded-2xl shadow-lg hover:scale-105 transition"
          >
            Contact Now
          </a>

          <a
            href="https://wa.me/918186081009"
            className="px-6 py-3 border border-gray-300 rounded-2xl hover:bg-gray-100 transition"
          >
            WhatsApp
          </a>
        </div>
      </div>

      <div className="flex justify-center">
        <div className="bg-white rounded-[40px] shadow-2xl p-4 w-[320px]">
          <img
            src="/mnt/data/1000716572.jpg"
            alt="Dongala Manoj Reddy"
            className="rounded-[30px] object-cover"
          />
        </div>
      </div>
    </div>
  </section>

  {/* About */}
  <section id="about" className="py-20 bg-white">
    <div className="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
      <div>
        <img
          src="/mnt/data/1000739457.webp"
          alt="Logo"
          className="w-72 mx-auto"
        />
      </div>

      <div>
        <h3 className="text-4xl font-bold mb-6">About Me</h3>
        <p className="text-gray-600 leading-relaxed text-lg mb-4">
          I am Dongala Manoj Reddy, founder of Manoj Financial Solutions.
          My mission is to help families stay financially protected through
          trusted insurance and investment solutions.
        </p>

        <p className="text-gray-600 leading-relaxed text-lg">
          Insurance is not just a policy — it is peace of mind for your
          family’s future. I believe in honest guidance, long-term support,
          and helping people make better financial decisions.
        </p>
      </div>
    </div>
  </section>

  {/* Services */}
  <section id="services" className="py-20 bg-gray-50">
    <div className="max-w-7xl mx-auto px-6 text-center">
      <h3 className="text-4xl font-bold mb-14">Services</h3>

      <div className="grid md:grid-cols-3 gap-8">
        {[
          'Health Insurance',
          'Life Insurance',
          'Term Plans',
          'Savings Plans',
          'Child Future Plans',
          'Investment Planning',
        ].map((service, index) => (
          <div
            key={index}
            className="bg-white rounded-3xl p-8 shadow-lg hover:-translate-y-2 transition"
          >
            <div className="text-5xl mb-4">🛡️</div>
            <h4 className="text-2xl font-semibold mb-3">{service}</h4>
            <p className="text-gray-600">
              Trusted financial guidance and protection plans designed for
              individuals and families.
            </p>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Partners */}
  <section id="partners" className="py-20 bg-white">
    <div className="max-w-6xl mx-auto px-6 text-center">
      <h3 className="text-4xl font-bold mb-12">Insurance Partners</h3>

      <div className="grid md:grid-cols-2 gap-8">
        <div className="bg-gray-50 rounded-3xl p-10 shadow-md">
          <h4 className="text-3xl font-bold mb-4 text-blue-500">
            TATA AIA
          </h4>
          <p className="text-gray-600 text-lg">
            Trusted insurance solutions with strong financial protection and
            customer support.
          </p>
        </div>

        <div className="bg-gray-50 rounded-3xl p-10 shadow-md">
          <h4 className="text-3xl font-bold mb-4 text-blue-500">
            Aditya Birla Health Insurance
          </h4>
          <p className="text-gray-600 text-lg">
            Reliable health insurance plans designed to support families
            during medical emergencies.
          </p>
        </div>
      </div>
    </div>
  </section>

  {/* Why Choose Us */}
  <section className="py-20 bg-gradient-to-r from-blue-50 to-gray-100">
    <div className="max-w-6xl mx-auto px-6 text-center">
      <h3 className="text-4xl font-bold mb-14">Why Choose Us</h3>

      <div className="grid md:grid-cols-3 gap-8 text-left">
        {[
          'Trusted Guidance',
          'Quick Claim Assistance',
          'Family Protection Focus',
          'Personalized Financial Planning',
          'Long-Term Support',
          'Professional Service',
        ].map((item, index) => (
          <div
            key={index}
            className="bg-white rounded-3xl p-8 shadow-md"
          >
            <h4 className="text-2xl font-semibold mb-4">{item}</h4>
            <p className="text-gray-600">
              Dedicated support and financial solutions tailored to your
              future goals.
            </p>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Testimonials */}
  <section className="py-20 bg-white">
    <div className="max-w-6xl mx-auto px-6 text-center">
      <h3 className="text-4xl font-bold mb-14">Client Testimonials</h3>

      <div className="grid md:grid-cols-3 gap-8">
        {[
          'Very professional and supportive during claim process.',
          'Best guidance for health insurance and future planning.',
          'Trusted advisor who genuinely cares about families.',
        ].map((review, index) => (
          <div
            key={index}
            className="bg-gray-50 rounded-3xl p-8 shadow-lg"
          >
            <p className="text-gray-600 italic text-lg">“{review}”</p>
          </div>
        ))}
      </div>
    </div>
  </section>

  {/* Contact */}
  <section id="contact" className="py-20 bg-gray-900 text-white">
    <div className="max-w-5xl mx-auto px-6 text-center">
      <h3 className="text-4xl font-bold mb-6">Contact Me</h3>
      <p className="text-gray-300 mb-12 text-lg">
        Let’s secure your family’s future together.
      </p>

      <div className="grid md:grid-cols-2 gap-8 text-left">
        <div className="bg-white/10 backdrop-blur-md rounded-3xl p-8">
          <h4 className="text-2xl font-semibold mb-6">Contact Details</h4>

          <div className="space-y-4 text-gray-200 text-lg">
            <p>📞 8186081009</p>
            <p>📧 manoj.insurance.advisor.help@gmail.com</p>
            <p>📷 @manoj_financial_solutions</p>
          </div>
        </div>

        <div className="bg-white/10 backdrop-blur-md rounded-3xl p-8">
          <h4 className="text-2xl font-semibold mb-6">
            Free Consultation
          </h4>

          <form className="space-y-4">
            <input
              type="text"
              placeholder="Your Name"
              className="w-full p-4 rounded-2xl bg-white/20 border border-white/20 placeholder:text-gray-300"
            />

            <input
              type="tel"
              placeholder="Phone Number"
              className="w-full p-4 rounded-2xl bg-white/20 border border-white/20 placeholder:text-gray-300"
            />

            <textarea
              rows="4"
              placeholder="Your Message"
              className="w-full p-4 rounded-2xl bg-white/20 border border-white/20 placeholder:text-gray-300"
            ></textarea>

            <button
              type="submit"
              className="w-full bg-blue-500 hover:bg-blue-600 transition py-4 rounded-2xl font-semibold"
            >
              Send Inquiry
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  {/* Footer */}
  <footer className="bg-black text-gray-400 text-center py-6 text-sm">
    © 2026 Manoj Financial Solutions. All Rights Reserved.
  </footer>

  {/* Floating WhatsApp */}
  <a
    href="https://wa.me/918186081009"
    className="fixed bottom-6 right-6 bg-green-500 text-white px-5 py-4 rounded-full shadow-2xl text-lg hover:scale-110 transition"
  >
    WhatsApp
  </a>
</div>

); }
