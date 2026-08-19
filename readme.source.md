```aura width=800 height=200
<div style={{
  display: 'flex',
  flexDirection: 'column',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #0f0b1e 0%, #1a1330 100%)',
  borderRadius: '16px',
  padding: '32px',
  color: '#e6e1f5',
  fontFamily: 'Inter',
}}>
  <div style={{ display: 'flex', alignItems: 'center', gap: '20px' }}>
    <img src="https://github.com/sad-gpt.png" width={72} height={72} style={{ borderRadius: '50%', border: '3px solid #a78bfa' }} />
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <div style={{ fontSize: '30px', fontWeight: 700, color: '#f3f0fc' }}>Harshmeet Bath</div>
      <div style={{ fontSize: '16px', color: '#9d8fc4' }}>CS Undergrad</div>
    </div>
  </div>
  <div style={{ display: 'flex', gap: '10px', marginTop: '18px', flexWrap: 'wrap' }}>
    {['React', 'TypeScript', 'Next.js', 'Java', 'Node.js'].map(t => (
      <div style={{
        display: 'flex',
        padding: '6px 14px',
        background: 'rgba(167, 139, 250, 0.15)',
        border: '1px solid rgba(167, 139, 250, 0.4)',
        borderRadius: '999px',
        fontSize: '13px',
        color: '#c4b5fd',
      }}>{t}</div>
    ))}
  </div>
</div>
```

```aura width=800 height=250
<div style={{
  display: 'flex',
  flexDirection: 'column',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #0f0b1e 0%, #1a1330 100%)',
  borderRadius: '16px',
  padding: '28px',
}}>
  <div style={{ display: 'flex', fontSize: '12px', letterSpacing: '2px', color: '#6e6390', marginBottom: '18px' }}>TECH STACK</div>

  <div style={{ display: 'flex', flexDirection: 'column', gap: '14px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: '12px' }}>
      <div style={{ display: 'flex', fontSize: '12px', color: '#c4b5fd', width: '120px' }}>LANGUAGES</div>
      <div style={{ display: 'flex', gap: '8px', flexWrap: 'wrap' }}>
        {['TypeScript', 'JavaScript', 'Java', 'Python', 'SQL'].map(t => (
          <div style={{ display: 'flex', padding: '5px 12px', background: 'rgba(167,139,250,0.1)', borderRadius: '999px', fontSize: '13px', color: '#e6e1f5' }}>{t}</div>
        ))}
      </div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '12px' }}>
      <div style={{ display: 'flex', fontSize: '12px', color: '#c4b5fd', width: '120px' }}>BACKEND</div>
      <div style={{ display: 'flex', gap: '8px', flexWrap: 'wrap' }}>
        {['Bun', 'Hono', 'Node.js', 'Express.js', 'Socket.IO'].map(t => (
          <div style={{ display: 'flex', padding: '5px 12px', background: 'rgba(167,139,250,0.1)', borderRadius: '999px', fontSize: '13px', color: '#e6e1f5' }}>{t}</div>
        ))}
      </div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '12px' }}>
      <div style={{ display: 'flex', fontSize: '12px', color: '#c4b5fd', width: '120px' }}>DATABASES</div>
      <div style={{ display: 'flex', gap: '8px', flexWrap: 'wrap' }}>
        {['PostgreSQL', 'MongoDB', 'Redis', 'Drizzle ORM', 'Prisma', 'Supabase'].map(t => (
          <div style={{ display: 'flex', padding: '5px 12px', background: 'rgba(167,139,250,0.1)', borderRadius: '999px', fontSize: '13px', color: '#e6e1f5' }}>{t}</div>
        ))}
      </div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', gap: '12px' }}>
      <div style={{ display: 'flex', fontSize: '12px', color: '#c4b5fd', width: '120px' }}>MOBILE / DEVOPS</div>
      <div style={{ display: 'flex', gap: '8px', flexWrap: 'wrap' }}>
        {['React Native', 'Expo', 'Docker', 'Vercel', 'Railway'].map(t => (
          <div style={{ display: 'flex', padding: '5px 12px', background: 'rgba(167,139,250,0.1)', borderRadius: '999px', fontSize: '13px', color: '#e6e1f5' }}>{t}</div>
        ))}
      </div>
    </div>
  </div>
</div>
```

```aura width=800 height=100
<div style={{
  display: 'flex',
  alignItems: 'center',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #0f0b1e 0%, #1a1330 100%)',
  borderRadius: '16px',
  padding: '24px 28px',
}}>
  <div style={{ display: 'flex', fontSize: '15px', color: '#e6e1f5', lineHeight: 1.6 }}>
    <span style={{ color: '#a78bfa', fontWeight: 700, marginRight: '8px' }}>Currently working on:</span>
    Laazo — an anonymous dating app for university students.
  </div>
</div>
```

```aura width=800 height=470
<div style={{
  display: 'flex',
  flexDirection: 'column',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #0f0b1e 0%, #1a1330 100%)',
  borderRadius: '16px',
  padding: '32px',
}}>
  <div style={{ display: 'flex', fontSize: '22px', fontWeight: 700, color: '#f3f0fc', marginBottom: '6px' }}>Key Projects</div>
  <div style={{ display: 'flex', width: '100%', height: '1px', background: '#2a2140', marginBottom: '20px' }}></div>

  <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
    <div style={{ display: 'flex', fontSize: '18px' }}>🎭</div>
    <div style={{ display: 'flex', fontSize: '17px', fontWeight: 600, color: '#f3f0fc' }}>Laazo — College Social & Dating Platform</div>
  </div>
  <div style={{ display: 'flex', gap: '8px', marginTop: '10px', marginBottom: '10px', flexWrap: 'wrap' }}>
    {['TypeScript', 'Bun', 'Hono', 'PostgreSQL', 'Drizzle ORM', 'React Native', 'Socket.IO'].map(t => (
      <div style={{ display: 'flex', padding: '4px 10px', background: 'rgba(167,139,250,0.1)', borderRadius: '6px', fontSize: '12px', color: '#c4b5fd', fontFamily: 'monospace' }}>{t}</div>
    ))}
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '6px', fontSize: '14px', color: '#d3cbe8', marginBottom: '24px' }}>
    <div style={{ display: 'flex' }}>• Founded and led development of a real-time social platform from MVP to production, owning architecture and infra end-to-end.</div>
    <div style={{ display: 'flex' }}>• Migrated Socket.IO's event contract from JSON to Protobuf with zero-downtime rollout across live clients.</div>
    <div style={{ display: 'flex' }}>• Merged REST and realtime services into one process, halving hosting cost with no latency regression.</div>
  </div>

  <div style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
    <div style={{ display: 'flex', fontSize: '18px' }}>⚡</div>
    <div style={{ display: 'flex', fontSize: '17px', fontWeight: 600, color: '#f3f0fc' }}>High-Concurrency Movie Ticket Booking System</div>
  </div>
  <div style={{ display: 'flex', gap: '8px', marginTop: '10px', marginBottom: '10px', flexWrap: 'wrap' }}>
    {['Node.js', 'Express.js', 'PostgreSQL', 'Prisma', 'Redis', 'BullMQ', 'Docker', 'k6'].map(t => (
      <div style={{ display: 'flex', padding: '4px 10px', background: 'rgba(167,139,250,0.1)', borderRadius: '6px', fontSize: '12px', color: '#c4b5fd', fontFamily: 'monospace' }}>{t}</div>
    ))}
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '6px', fontSize: '14px', color: '#d3cbe8' }}>
    <div style={{ display: 'flex' }}>• Built transactional booking workflows with row-level locking, ensuring ACID guarantees under concurrent reservations.</div>
    <div style={{ display: 'flex' }}>• Implemented Redis-based seat holds with TTL expiration to prevent double-booking and release abandoned reservations.</div>
    <div style={{ display: 'flex' }}>• Load-tested with k6, orchestrated background jobs via BullMQ, containerized with Docker for reproducible environments.</div>
  </div>
</div>
```
