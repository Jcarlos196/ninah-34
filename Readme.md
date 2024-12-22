ninah-34
import React from 'react';
import { FaFacebook, FaTwitter, FaInstagram } from 'react-icons/fa';
import './Footer.css';

const Footer = () => {
  return (
    <footer className="footer">
      <div className="footer-content">
        <h2 className="footer-title">Meu Aplicativo</h2>
        <p className="footer-description">Obrigado por visitar nosso aplicativo. Esperamos que você tenha uma ótima experiência!</p>
        <div className="social-media">
          <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" className="social-icon">
            <FaFacebook />
          </a>
          <a href="https://twitter.com" target="_blank" rel="noopener noreferrer" className="social-icon">
            <FaTwitter />
          </a>
          <a href="https://instagram.com" target="_blank" rel="noopener noreferrer" className="social-icon">
            <FaInstagram />
          </a>
        </div>
      </div>
      <div className="footer-bottom">
        <p>&copy; 2024 Meu Aplicativo. Todos os direitos reservados.</p>
      </div>
    </footer>
  );
};

export default Footer;