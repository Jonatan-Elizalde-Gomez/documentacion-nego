Usar JSDoc asegura que el código sea fácil de entender y mantener. Ejemplo:

```typescript
/**
 * Componente que muestra el perfil del usuario.
 * @param {Object} props - Propiedades del componente.
 * @param {string} props.userId - ID del usuario.
 * @returns {JSX.Element} - Componente de perfil de usuario.
 */
const UserProfile = ({ userId }: { userId: string }): JSX.Element => {
  // Lógica del componente
};
export default UserProfile;
