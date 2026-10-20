using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Login
{
    
    public partial class Form1 : Form
    {
        public struct UsuarioSenha
        {
            public string Usuario;
            public var Senha = null;
            public UsuarioSenha() { }
        }
        }
        

        public Form1()
        {
            InitializeComponent();
        }

        private void Criar_Click(object sender, EventArgs e)
        {
          Criar_conta criar_Conta = new Criar_conta();
            criar_Conta.Show();
            this.Hide();

        }

        private void Cancelar_Click(object sender, EventArgs e)
        {
            Application.Exit();
        }

        private void Iniciar_Click(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {
            Usuario = textBox1.Text;

        }
    }
}
